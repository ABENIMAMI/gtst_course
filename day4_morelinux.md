#  linux file hierarchy

* linux have a special file system file appear under the "localdisk C"
* linux system file appear the root dirctory(/)

# /(root)

* every single file and dirctory starts from the root dirctory 
* the only root user has the right to write under this dirctory
* /root is the root users home dirctory,which is not the same as /

# bin - binary executable 

* essential command binaries that need to be avalible in single-user mode 
example cat,ls,cp,pwd 

# /boot - boot loader file 

* kernel initrd, vmlinux,grup file are located under /boot 
example * initrd.img-2.6.32-24-generic  
        * vmlinuz-2.6.32-24-generic

# /dev - essential device file 

* these include terminal device,usb,or any device attached to system 
example /dev/ttv1,/dev/usbmon0

# /etc - etstera device file 

* contains configrtaions file required by all progerams. this also contains startup and shutdown shell script used to start/stop individual programs.
example /etc/resolv.conf,/etc/lograte.conf

# /home - home dircotry

* home dircotry for all user to store their personal file 
example /home/abeni

# /lib - libraries esstinal for the binaries in /bin and /sbin 

* libraries filename are either id* or lib*,do*
example id-2.11.1.so,libncurses.so.5.7

# /media mount ponit for removeble media such as CD-ROM 

* temporary mount dirctory for removable device.
example /media/floppy for floppy drivers 

# /mnt - temporary mounted file 

* temporary mount dirctory where sysadmins can mount filesystem.


# /opt  - optinal application softwere packeges

* contanis add on application from indivudual vendors. add-on applications shuould be installed under either /opt/ or /opt/sub-dirctory.

# /sbin - esstinal system binaries 

* just like /bin , /sbin also contians binary executables. the linux commands located under this dirctory are used typiacally by system administrator for sytem maintenance purpose.

# /temp - temporary file 

* dirctory that contains temporary file created by system and users. 
* file under this dirctory are deleted when system is rebooted.

# /usr - user utilities 


*  contains bainary ,libraries ,documentations and sourse-code fore second level program 
* /usr/bin contians binary file system administretores. if you cant find system binary under/sbin, look under /usr/sbin. example atd,caron,sshd



# text editors 

* programs that user for text processing 
* linux comand line text editors
     * vim
     * nano
     * emacs 
     * neovim

* linux graphical text editors
    * sublime 
    * vscode
    * gedit
    * pulma

# vim 


* the vim editors is 
    * a very power full 
    * but at the same time it is cryptic
    * it is hard to learn, spicaliy for windows user 

* it have to modes 
    * command modes => were you can do commands 
    * input mode => were you can write 

* inside commands modes you can 
    * save => :w 
    * force and quite => :q
    * force quit and save => :wq 
    * undo 
    * executive bash commands 

# linux user management 

* on computer system person who uses the computer is called "user" 
    * every user have group 
    * user have thier own file and applications 
    * those user have power/privilge 
    * on linux their is two kind users 
        * root id=0 
        * normal user id=1-999
* sudo = superuser do, user to pass permission 
* the root user have the power denied to do everyting on linux 
* creating users 
    * on linux to create user,you can use those commands 
        * useradd => simple 
        * adduser => detail
* useradd commands 
    * sudo useradd username
* adduser commands 
    * sudo adduser username

* the user file stored inside /etc/passpwd
* the user password a stored inside /etc/shadows

# tip

* adduser => by defult bash or bin/bash
* useradd => bin/sh 
    