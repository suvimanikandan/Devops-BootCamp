🖋️Chapter 8:finding linux documentation   
👉The main sources of Linux documentation are the man pages, GNU info, the help options and command, and a rich variety of online documentation sources.     
👉The man utility searches, formats, and displays man pages.    
👉The man pages provide in-depth documentation about programs and other topics about the system, including configuration files, system calls, library routines, and the kernel.    
👉The GNU Info System was created by the GNU project as its standard documentation. It is robust and is accessible via command line, web, and graphical tools using info.     
👉Short descriptions for commands are usually displayed with the -h or --help argument.   
👉You can type help at the command line to display a synopsis of built-in commands.   
👉There are many other help resources both on your system and on the Internet.     

🖋️Chapter 9:Process   
👉Processes are used to perform various tasks on the system.   
👉Processes can be single-threaded or multi-threaded.    
👉Processes can be of different types, such as interactive and non-interactive.    
👉Every process has a unique identifier (PID) to enable the operating system to keep track of it.
👉The nice value, or niceness, can be used to set priority.    
👉ps provides information about the currently running processes.   
👉You can use top to get constant real-time updates about overall system performance, as well as information about the processes running on the system.    
👉Load average indicates the amount of utilization the system is under at particular times.    
👉Linux supports background and foreground processing for a job.  
👉at executes any non-interactive command at a specified time.    
👉cron is used to schedule tasks that need to be performed at regular intervals.     

🖋️Chapter10:file Operations    
👉The filesystem tree starts at what is often called the root directory (or trunk, or /).    
👉The  Filesystem Hierarchy Standard (FHS) provides Linux developers and system administrators a standard directory structure for the filesystem.    
👉Partitions help to segregate files according to usage, ownership, and type.    
👉Filesystems can be mounted anywhere on the main filesystem tree at a mount point. Automatic filesystem mounting can be set up by editing /etc/fstab.    
👉NFS (Network File System) is a useful method for sharing files and data through the network systems.     
👉Filesystems like /proc are called pseudo filesystems because they exist only in memory.     
👉/root (slash-root) is the home directory for the root user.        
👉/var may be put in its own filesystem so that growth can be contained and not fatally affect the system.    
👉/boot contains the basic files needed to boot the system.   
👉patch is a very useful tool in Linux. Many modifications to source code and configuration files are distributed with patch files, as they contain the deltas or changes to go from an old version of a file to the new version of a file.   
👉File extensions in Linux do not necessarily mean that a file is of a certain type.   
👉cp is used to copy files on the local machine, while rsync can also be used to copy files from one machine to another, as well as synchronize contents.     
👉gzip, bzip2, xz and zip are used to compress files.     
👉tar allows you to create or extract files from an archive file, often called a tarball. You can optionally compress while creating the archive, and decompress while extracting its contents.    
👉dd can be used to make large exact copies, even of entire disk partitions, efficiently.    
