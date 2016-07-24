#sdelete

.Description

Securely delete files and folders for Unix systems 

Uses shred for secure file deleting. 
You can find more information about shred at http://linux.about.com/library/cmd/blcmdl1_shred.htm

Can recursively delete folders.

You can check that your system have shred app by running this command:

$ man shred

If you don't have shred already installed, you can install it (on some system, for example on Debian/Ubuntu) using:

$ sudo apt-get install shred

.Install

Just make it executable using:
$ chmod +x sdelete

.Usage

$ sdelete dir|file [dir2|file2] [dir3|file3]
Where:
    dir  - directory name for delete
    file - file to delete


