# Kata 7

This repository contains a small program to run that simply opens a window. However, the goal of this Kata 7 is to learn how to **generate a distributable app with JPackage and the Maven plugins.**

When downloading this code, it is necessary to know how to use Maven to compile, generate a .jar and install the plugins. In addition, you must also use a command like the following in order to have an app to distribute with all the dependencies through an installer.

`'jpackage --input . --name kata7 --main-jar kata7-1.0.0.jar --main-class software.ulpgc.kata7.Main --type msi'`


> **Note:** Possibly the app will need to be installed and we can check in the program files folder that we have our app ready to use.
