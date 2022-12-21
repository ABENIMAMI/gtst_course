# today class 


* futher on user management
* linux file wonership + permissions 
* software installation 
* script installation 
* packege installation common errors


# some advanced user commands 

* to change password of user 
    * sudo passwd user id 
* to change user id 
    * sudo usermod -u new_id username
* to delete user 
    * sudo userdel -r username


# sudores file 


* the sudoers file is a file linux and unix administration use to allocate system rights to system user 
* the user you created dosent have power to sudo as the orginal one.

# linux file permission 

* every file on linux have their own 
    * owner 
    * permissions
* there is 5 main parts on the listing 
    * permission 
    * owners 
    * dates 
    * size 
    * filename

# ownership 

* ownership is the owner of the file 
* this have 2 kinds 
    * user 
    * group

* to change the owner of file you can use the command
    * chown user:group filename 

# permission 

* there are 3 type of permissions 
    * read(r)
    * write(w)
    * excutive(x)
    * the folder and file are differ with the "d" and on the beginning of the permissions
# CHMOD commands 

* this commands helps to change file permission.
* those file permissions are read.write & execute.
* each of the permissions have a number represntation
    * read => 4-r
    * write => 2-w
    * executive => 1-x 
* syntax 
    * chmod<parameter>file name

# package installtion on linux 

* on linux to install softwere you use pakage managers.
ex: apt,pacman,pkg
* ehile will use debian package manager 

# advanced package tool/apt/

* apt is a free-softwere user intrface that works with an online server to handele the installition and removal of softwere on debian and debian based linux disturbutions.used for online and offline purpose.
* syntax
    * sudo apt update 
    * sudo apt search <softwerename>
    * sudo apt install <softwerename>
    * sudo apt remove 
    * sudo apt upgrade
    * sudo apt purge 

# package dependencies 

* a softwere can be bulit based on another program called "module"
* so , aprogram to work proprely,the dependencies have to be insatlled secucssfully
* those pakage manage install the softwere+dependcies

# Dpkg/debian packeg manage/


* dpkg is an offilne package managing programs
* package on debian have extension "deb"
* syntax
    * sudo dpkg -i <packagename>
    * sudo dpkg -r <pakagename>
    * sudo dpkg -p <pakagename>

                ** end of to day **