# Read: Class 05
## Why does this topic matter?
- This topic matters because learning about the command line interface and virtualization will be important tools for cybersecurity personnel.
- There will be situations where a graphical user interface will be unavailable or you need to remotely access a computer.
- Knowing how to use the CLI will enable individuals to do these things and much more.
## Readings: Installing Virtualbox with Linux Terminal
### 1.Explain the terms “shell”, “terminal”, “cli”, and “command prompt”. Why are these still used today, when we have graphical interfaces?
- the terms such as shell, terminal, cli, and command prompt are all synonyms that developers use.
- All those terms basically refer to a text-based interface that allows users to interact with the operating system by typing commands such as ls to list the directory or cd to change directory.
- It's a way to control and manage the system using text commands instead of a GUI.
### 2.What are the commands to change directories, list the file’s contents and rename/move files?
- The command to change directories is cd.
- The command to list file's contents is ls.
- The command to rename/move files is mv.
### 3.What are relative and absolute paths? What is special about starting with a ~ (tilde) or a ‘/’ character in the path?
- The relative path means that you will navigate based on your current working directory. so if you are in a directory called test1 with many subdirectories such as test1-1, test1-2, and test1-3 you can navigate simply by using cd and the name of the directory
    example: pwd
             ~/home/test1
             ls
             test1-1 test1-2 test1-3
             cd test1-2
             pwd
             ~/home/test1/test1-2
- The absolute path means that you can navigate anywhere because you will start from the root directory with either the / or ~.
    example: pwd
             ~/home/test1/test1-2
             cd ~/home
             pwd
             ~/home
### 4.Explain what Linux is, using anything except English.
- Linux es un sistema operativo de código abierto basado en el kernel de Linux. Fue desarrollado por Linus Torvalds en 1991.
- Linux se utiliza en una amplia variedad de dispositivos, desde servidores y supercomputadoras hasta dispositivos móviles y electrodomésticos. Es conocido por su estabilidad, seguridad y flexibilidad. Además, Linux es el núcleo de muchos sistemas operativos basados en Linux, como Ubuntu, Fedora y Debian.
### Things I want to know more about
- I would like to know more command lines. I understand we are just getting started with the linux command line, but I am eager to learn about commands that allow me to backup files, download database software, and load modules to the linux kernel.
