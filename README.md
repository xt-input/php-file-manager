# php-file-manager
Simple file manager script to manipulate with files on the remote server. Just upload this script to some server and open it in the web browser.

Available function:
- List directory
- Open subfolders recursively
- Create new folder
- Delete file/folder recursively
- Change permissions of file/folder recursively (with ability to specify permissions for files and directories separately)
- Unpack ZIP archives to some folder

The main magic of it is that all the operations are made by php functions, which means server is doing them. So everything is much faster than doing it classicaly via FTP.

Useful for website administrators, which needs to move their projects to different servers.
