# Practical 1
## Linux Commomd Line - File Operations, Navigations, Permission.

### Commond Line Interface of making flow of 
  * **NIMS** 
     * **CSE**
        * Data.SH
        * **D1**
           * Data.txt
# OPERATIONS.
````bash
/~> cd Desktop
/Desktop> mkdir NIMS
/Desktop> cd NIMS
/NIMS> mkdir CSE
/NIMS> cd CSE
/CSE> touch Data.sh
/CSE> mkdir D1
/CSE> cd D1
/D1> touch Data.txt
/D1> echo Hii>Data.txt
/D1>cat Data.txt
    Hii (OUTPUT)
/D1> echo Sir>>Data.txt
/D1>cat Data.txt
    Hii
    Sir (OUTPUT)

````
# NEVIGATION:
````bash
/D1> cd ../../..
/Desktop> cd NIMS/CSE/D1
/D1> cd ..
/CSE> mv Data.sh D1
/CSE> cd D1
/D1> ls
     Data.sh Data.txt
````
# Permission:

````bash
/~> cd Desktop
/Desktop> touch script.sh
/Desktop> vim script.sh

## inside vim
## Enter I to Insert
## echo Hello World --- To write inside the sh file
## click esc --- To exit Insert mode
## enter :wq --- to exit vim

/Desktop> chmod +x script.sh
/Desktop> sh script.sh
## To see what the content was written in sh file
           Hello World (OUTPUT)
/Desktop> cat script.sh
## To see entire thing written inside the sh file
           echo Hello World

````

