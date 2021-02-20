# ESP32FTPServer
Simple FTP Server for Espressif ESP32
Based on the work from https://github.com/MollySophia/ESP32_FTPServer_SD (which again is based on https://github.com/robo8080/ESP32_FTPServer_SD) 

Modified to better support subdirectories
Changes proposed by RP6conrad :
As the files on the SD do have a timestamp, it is possible to transfer also this timestamp with the file with FTP
I made a small parser that convert the timestamp to the right format, and ad some changes to FTP commands "LIST" and "MLSD"
