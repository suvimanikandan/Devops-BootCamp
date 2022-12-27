🖊️Chapter 11:TextEditors    
👉Text editors (rather than word processing programs) are used quite often in Linux, for tasks such as creating or modifying system configuration files, writing scripts, developing source code, etc.       
👉nano is an easy-to-use text-based editor that utilizes on-screen prompts.         
👉gedit is a graphical editor, very similar to Notepad in Windows.           
👉The vi editor is available on all Linux systems and is very widely used. Graphical extension versions of vi are widely available as well.      
👉emacs is available on all Linux systems as a popular alternative to vi. emacs can support both a graphical user interface and a text mode interface.                   
👉To access the vi tutorial, type vimtutor at a command line window.          
👉To access the emacs tutorial type Ctl-h and then t from within emacs.         
👉vi has three modes: Command, Insert, and Line. emacs has only one, but requires use of special keys, such as Control and Escape.            
👉Both editors use various combinations of keystrokes to accomplish tasks. The learning curve to master these can be long, but once mastered using either editor is extremely efficient.       

🖋️Chapter 12:File Permissions      
👉Linux is a multi-user system.     
👉To find the currently logged on users, you can use the who command.     
👉To find the current user ID, you can use the whoami command.     
👉The root account has full access to the system. It is never sensible to grant full root access to a user.     
👉You can assign root privileges to regular user accounts on a temporary basis using the sudo command.     
👉The shell program (bash) uses multiple startup files to create the user environment. Each file affects the interactive environment in a different way. /etc/profile provides the global settings.     
👉Advantages of startup files include that they customize the user's prompt, set the user's terminal type, set the command-line shortcuts and aliases, and set the default text editor, etc.      
👉An environment variable is a character string that contains data used by one or more applications. The built-in shell variables can be customized to suit your requirements.    
👉The history command recalls a list of previous commands, which can be edited and recycled.    
👉In Linux, various keyboard shortcuts can be used at the command prompt instead of long actual commands.    
👉You can customize commands by creating aliases. Adding an alias to ~/.bashrc will make it available for other shells.   
👉File permissions can be changed by typing chmod permissions filename.     
👉File ownership is changed by typing chown owner filename.     
👉File group ownership is changed by typing chgrp group filename.      
