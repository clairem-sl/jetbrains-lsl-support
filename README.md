LSL support for IntelliJ and other JetBrains IDEs
=================================================

The LSL.xml file will allow the LSL (Linden Script Language) support in all IDE of the JetBrains range :

Supported IDEs
--------------

Ce fichier permet de supporter le langage LSL dans les IDE de la gamme Jetbrains :

* IntelliJ
* PyCharn
* WebStorm
* PhpStorm
* ReSharper
* ReSharper C++
* Rider
* CLion
* RubyMine
* AppCode
* GoLand

What does it provide ?
----------------------

Once enabled, the LSL support will be applied to all files with extension .lsl or .LSL that you 
will open in your IDE. It will give you :


* Syntax highligh
* Keywords and function autocompletion

Installation
------------

Following process describes the installation for the IntelliJ IDE.
You have to adapt it, replacing "IntelliJ" by the name of your IDE.

Download LSL.xml

Go to the IDE folder of your personal folder.
Where is this folder depends of your OS and how your IDE was installed.
For example, on Ubuntu system, that will be something like :

```
/home/aglaia/.IntelliJIdea2018.1
```

Go now in the subfolder config.
Here you may find a folder called "filetypes".
If filetypes folder doesn't exist, create it.
The put in this folder the LSL.xml file.

The file should now be located at something like :

```
/home/aglaia/.IntelliJIdea2018.1/config/filetypes/LSL.xml
```

If your IDE is running : restart it.

Your should now have the LSL support for all files with extension .lsl or .LSL !

For any question, please contact me in Second Life. Usename : aglaia
