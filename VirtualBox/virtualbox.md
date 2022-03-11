# VirtualBox Documentation

Created by [itsaghin](https://github.com/itsaghin) 

## GoTo:
- [About](#virtualbox-about)
- [Resizing Virtual Drive](#resizing-virtual-drive)

## About
This is a custom documentation file with things that helped me while working with [Oracle VirtualBox](https://www.virtualbox.org/). The point of this document is to help people with some common problems and to be a quick reminder for some common tasks. If you need a deeper dive into some parts of VirtualBox I strongly recommend lookin at the [Official VirtualBox User Manual](https://www.virtualbox.org/manual/UserManual.html).

##  Resizing Virtual Drive

### Ubuntu
- **From VirtualBox**

<span style="color:red">Important!</span> Make sure you **Power Off** your VM

1. *File > Virtual Media Manager > Select {machineVDI}.vdi*
2. *Set Size attribute to whatever value you need*
3. *Apply*

- **On your VM**

1. *Start partition manager <code>gparted</code> (Install using command <code>sudo apt install gparted</code>)



