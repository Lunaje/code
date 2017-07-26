## Monitor Progress of File Descriptors of Another ProcessOriginally published: 2014-05-19 11:16:47 
Last updated: 2014-05-30 01:10:53 
Author: Alfe  
 
This tool (inspired by azat@stackoverflow, see http://stackoverflow.com/a/16082562/1281485) allows to watch the progress of the file descriptors of another process.  This can be used, for example, if you transfer a file to another host and the transferring program does not show any progress indication itself.  Instead of waiting blindly until the routine is done, with this tool you can use Linux's proc file system to monitor the progress of the other process while it walks through the file.