# last class topics 

* script installtion 
* erros on package manager 
* help on linux 
* linux service 
* alias
* tmux 
* wget 
* find 

# script installtion 

* some hacking tools are develped by some people and those poeple makw it open-sourse, that means we can get those script those script/programs from github
* so we can download and use it for tihs purpose git have a feature called **clone** 
* syntax 
    * git clone < link of the script from githube>
* scrpipt modules 
    * script are made wtih scripting laguage(programming)
        * python,bash,go ruby 
* example 
    * pip instal term
    * for requirments file pip install -r requirments.txt
    * go install <modulename>
    * gem install <modulename>


* **man(manual) this will give the whole manual and instaraction of tools or commands example man awk or man mkdir**

# linux proccesses and service 

* as we interact wtih linux , we create numbered instance of running programs called **processes**

* to get processes
    * ps [optionals]
* more commands 
    * ps => for running on my shell 
    * ps -A => view all running process
    * ps -u username => view user process

* pid -process id 

* to stop process 
    * kill[optional]
* more on kill 
    * kill -19 pid => to stop process 
    * kill -18 pid => to resume the process we stopped 
    * kill -9 pid => to stop a process immedately 
    * there are 31 options.

# foreground / background

* thus far we have run commands at prompt and waited for them to complete.we call this running in the **foreground** 

* use **&** oprators to run programs in the **background** or press ^z 

# null device 

* /dev/null- redirects output to nowwhere 
* if you wants to ignore out you can send it to the null device
* on shell output there are 2 things 
    * STDERR = 2
    * STDOUT = 1 
* to redirect the erros from a commands results we do 
    * command 2 >filename
* to redirect the errors free output 
    * command 1> filename
*mso if we redirect our command output to /dev/null we will get error free results 
    * command 2> /dev/null

# alias 

* used to give name to some bunch of command 
* example
    * ls -la 
        * alias rex='ls -la'


# tmux 

* tmux is used to calssify uor terminal works 
* to create config file type 
    * nano.tmuxxconf
    * type this

# wegt 

* is a tools to dawnload file website/servers
* syntax 
    * wegt[options] [links]

# find 

* on treminal if you want to search for file/folders/mudic/video we can use find command.
* it very essntial tools
* syntax 
    * find[search path]

* more commands 
    * find /-name 
    * find /home-perm777
    * find-type | find-type d

                            end