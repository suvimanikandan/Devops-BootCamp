linux file system    
->hierarchial tree structure   
->1 root folder   
windows file system  
->multiple root folders  

linux file system overview  
1)multiple users on computer  
2)each user has it own space   
3)each user can have own configuration 
4)Programs installed system wide,are available for all users on that computer  

π/bin-binaries   
->executable for most essential user command  
binary ->computer readable format  
->exefccute command in binary format  

π->root users home directory is at /root  

πsystem binaries ->
->system relevant command  
->super user permission access  
->essential system binaries program that would use(need super user privilege)  

π/lib  ->library  
->essential shared libraries that executable from /bin or /sbin use  

π/usr ->user  
->this was used for user home directories  

π/usr/local  
->programs that you install on computer  
->third party application like docker ,minibuke ,java   
->program installed here,will be available for all user in computer  

π/opt ->optional  
->third party programs you install  

π/usr/local->programs which split its components             π/opt Programs,which not split its component  

π/boot  -booting   
->contain files required for booting
->read only folders  

π/etc et cetera  
->place where configuration for system wide application is stored  
->originally for etc. meaning   
->emerged to main configuration location    

π/dev -devices  
->location of device files-like keyboard ,hard drive,webcam etc.,  
->apps and drivers will accesss this not user  

π/var - variable   
->contains files to which the system writes data during the course of its operations  

π/var/log-contained  log files           π/var/cache ->contains cached data from application programs   

π/tmp-temprorary   
->temporary resources required for some process kept here temporarily   

π/media-removable media   
->contains sub directories  ,where removable media devices inserted into the computer are mounted   
ex:when you insserted a CD a directory will automatically be created and you can access the contents of CD inside the directory    


π/mnt:  temporary mount points   
->historically sys admins mounted temporary file system there   
