# E1. Exercise 4. Operating System structure

## Introduction

We can divide operating system in following parts:
- Kernel
- Memory manager
- Input/Output manager
- Filesystem manager

## Contents

Let's analyze operating system behaviour on each module. We will be using linux comands to see what's going on on a linux OS.

## Delivery

### Kernel

1. **Where does the kernel reside in disk?** Write down the command with the output and tell exactly where it is the kernel.


2. **How can we show the actual kernel version that it is loaded on our system**? Please show command output


3. **How can we show the detected hardware done by the kernel?** Please show command output.


4. **How can we show the modules (drivers) actually in use?** Which module it is being used for video graphics card?



### Memory manager

1. **What is the 'cache' memory that shows the command 'free -m'?** Show also the command output


2. **What is the 'swap' memory that shows the command 'free -m'?**


3. **How does the memory manager handle an out-of-memory problem?**


4. **How can we show the actual 'out of memory score' of a Gimp instance that it is running?**



### Input/Output manager

1. **How can we list all the interrupts that it is aware our Operating System?** Show also command output


2. **In multiprocessor systems, how does the operating system distribute interrupts by default?** How can we change the default behaviour?


3. **How does an operating system control a device that has no interrupts?** Explain the process 


4. **What will happen if two applications want to send data through network device at the same time?**



### Filesystem manager

1. **Which is the typical linux folder structure? ** Describe what it is and the use of each folder.
- bin:  
- boot:  
- dev:  
- etc:  
- home:
- lib:  
- lib64:
- lost+found:
- media:
- mnt:
- opt:
- proc:
- root:
- run:
- sbin:
- srv:
- sys:
- tmp:
- usr:
- var:

2. **How can we:?**
- Move a file that resides in /usr/local/src/file.md to the folder /opt:
- Copy a file that resides in /usr/local/src/file.md to the folder /opt:
- Move a file in /usr/file.md to /usr/local if we are currently in path /usr/local:
- Create the file .gitignore using command 'touch' and then try to list it (ls). What happens?
