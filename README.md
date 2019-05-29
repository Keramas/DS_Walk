# DS_Walk
Python tool for enumerating directories and files on web servers that contain a publicly readable .ds_store file.

Uses the 'python-dsstore' .ds_store file parser tool created by gehxelt. (https://github.com/gehaxelt/Python-dsstore)

## Tool Description
DS_Walk enumerates all possible files and directories on a web server where a .ds_store file can be publicly accessed and downloaded. The tool will traverse all directories until no further .ds_store files are found in subsequent directories.

![alt text](https://media.giphy.com/media/i1RDKNhLddmi4/giphy.gif)
