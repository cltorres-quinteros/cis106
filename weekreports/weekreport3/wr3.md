---
Name: Christian Torres
Semester: Fall 2023
Course: CIS 106
---

# Week Report 3

## Summary of presentations

### Introduction to Linux

**What is an operating system?**

* An **operating system** provides all fundamental softwares features of a computer. An OS enables you to use the computer's hardware providing basic tools that make computers useful. The OS's kernel are relayed by the features.

**Aside from a kernel, what other parts make an operating system?**
* **Command-Line Shells** was the de facto way of using computers before the Graphical Interface. CMDs work by typing commands in a shell and in Linux, the entire system can be controlled by the CLI.
* **Graphical User Interfaces** rely on icons, menus, and a mouse pointer for user interaction. Linux relies on a GUI called the X Window System.
* **Utility and productivity programs** are tools like web browsers, document processors, and text editors.
* Lastly, **libraries** are collections of programming functions that can be used in a variety of programs.
 
**What is a Linux distribution?**

* **Linux distribution** is a complete Linux package that consists of the following elements:
  * The use of different versions of the Linux Kernel on different distributions.
  * **Core unix tools** that consists of the GNU tool set, the X Window System, Desktop Environment, etc.
  * **Supplemental software** that includes server applications, user applications and more.
  * **Startup scripts** differentiate different distributions that range from launching dozens of programs at startup to modifying the way desktop environments behave.
  * A number of **installers** are used differently by different distributions and manage software differently. 

**What is Ubuntu?**

* Ubuntu is a **Linux Distribution** that is freely available with both community and professional support. It includes pieces of software such as Libre Office and Firefox.

**Define the following terms: Open Source, Closed source, free software**

* **Open source-** the software may be distributed for a fee or for free and is distributed with the software.
* **Closed source-** software is not distributed with the source code and the user is restricted from modifying the code.
* **Free software-** the software is distributed with the source code and this software can be free or obtained by paying a fee.

**What are the 4 freedoms defined by the free software foundation?**

* **Freedom 0:** using the software for any purpose.
* **Freedom 1:** examine the source code and modify as you see fit.
* **Freedom 2:** redistribute the software.
* **Freedom 3:** redistribute your modified software.

### The Basics of Virtualization
**What is virtualization?**

* **Virtualization** means creating virtual versions of something. Virtualization is often used to create multiple computers in one physical computer.

**List 3 benefits of virtualization**

* The reduced costs due to decreasing the physical hardware needed for a network.
* Allowing a chance to test applications before installing them on a host machine.
* Offers the ability to save the state of a machine and roll it back or forward to the time wanted.

**What is a hypervisor?**

* A **hypervisor** is a software or hardware in charge of creating, managing, and running virtual machines. There are two types of hypervisors with **type 1** running directly on the hardware and **type 2** is an application that runs on top of an operating system.

**What is virtualbox**

* **VirtualBox** is a powerful virtualization product for enterprise and home use. VirtualBox is rich in features and outputs high performance.

### Exploring Desktop Environments
**What is a desktop environment? (Provide 3 examples)**

* A desktop environment is an implementation of the desktop metaphor made of a bundle of programs running on top of a computer operating system.
  * Three examples include GMOME, KDE and MATE.

**List 4 common elements of desktop environments**

* **Desktop Settings** consists of programs that allow you to make configuration changes to the desktop environment.
* **Display manager** allows you to choose between the desktop environment and users.
* **File manager** allows you to perform file maintenance activities graphically.
* **Icons** are picture representations of a file or program.

**What is Ubuntu’s default desktop environments?**

* **GNOME 3** is Ubuntu's default desktop environment. The official GUI for GNOME 3 is called GNOME Shell.
* The **KDE desktop environment** specified the project's organizations and the strong community that supported it.

**What are the official flavors of Ubuntu?**

* **Mate** is an official flavour of Ubuntu and is a desktop environment that has forked application in Spanish.
* The **Cinnamon Desktop Environment** is a free and open-source desktop environment for the X Window System that is considered to be easy to use.

### What is a Shell?
**What is Bash?**

* **Bash** is a necessary component to modern computing that make large-scale IT possible.

**How do you access the Linux CLI?**

* The **Linux CLI** is accessed via the ***terminal emulator*** or the ***linux console.***

**What is a console terminal?**

* **Console Terminals** has a mode called the *Linux console* that emulates the old days of a hard-wired console terminal and is a direct interface of the Linux system.

**What is a terminal emulator?**

* **Terminal Emulator** is a program that allows you to access the Linux CLI.
* Terminal emulators include GNOME terminal, konsole, terminology, and TILIX.

**Provide 3 examples of Linux commands**

* **date**   displays the current date and time
* **cal**    displays a calendar of the current month
* **free**   displays the amount of free memory
* **clear** clears the screen

### Managing Software
**Which command is used for updating ubuntu**

* The command used for updating ubuntu is: 
  * sudo apt update; sudo apt upgrade -y

**Which command is used for installing software. Provide an example.**

* The command for installing software is:
  * sudo apt install package name
* Example: sudo apt install screenfetch -y

**Which command is used for removing software. Provide an example.**

* The command for removing software is:
  * sudo apt remove package name
* Example: sudo apt remove firefox -y

**Which command is used for searching for software. Provide an example.**

* The command for searching software is:
  * apt search "search"
* Example: apt search "web browser"

**Definition of the following terms:**
* **Package-** archives that contain binaries of software, configuration files, and information about dependencies.
* **Library-** reusable code that can be used by more than one function or program.
* **Repository-** a large collection of software available for download.
