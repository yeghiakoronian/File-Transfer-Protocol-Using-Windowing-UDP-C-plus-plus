File-Transfer-Protocol-Using-Windowing-UDP-C-plus-plus
======================================================
This is an implementation of an FTP using UDP and sliding window protocol

Notes:

After opening the clientSide and building it go in the Client Root Debug Folder and create folder called "files" then inside "files" folder create folder "rename" (this is the path where the files will be stored of the client )

After opening the clientSide and building it go in the Client Root Debug Folder and create folder called "files (this is the path where the client will download files from and upload files to)

you can also rename a file if it is a duplicate

PUT = Upload (client's point of view) Get = Download(client's point of view) LIST will list all files in the directory

to make transfer faster decrease the window sizes to 1 , and make drop and error rate 0( I may have hard coded some things to make testing faster)

Have fun