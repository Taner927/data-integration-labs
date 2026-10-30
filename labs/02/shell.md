# Task for Data Intzegration

## 1) Which shell? Which shell runs in your terminal, and which version is it?
- ### ```echo $0``` finds the name:
- Name : /usr/bin/bash

- ### ```bash --version``` or ```zsh --version``` finds its version
- version : GNU bash, version 5.3.15(2)-release (x86_64-pc-cygwin)

## 2) Where am I? Which absolute path does your shell print for your home directory and for your downloads folder?

- for this, use ```pwd```
- /c/Users/taner for my dictionary
- /c/Users/taner/Downloads for my Download file

>[!Note]
*```pwd``` nutze ich um den pfadnamen vom dictionary herauszufinden.*
*cd Downloads bringt mich in den downloads ordner.*
*dann nochmal pwd zeigt mir den  pfadnamen für den dowenlaods ordner.*
*um zurückzugehen einfach cd wieder schreiben.*

## 3) Where do commands come from? How many directories are in your PATH, and which one is searched first? Where are curl, python3 and git installed? 

- number of directories in path: 21
- used code:```echo $PATH | tr ":" "\n```
- python3 ist in : /c/Users/taner/AppData/Local/Microsoft/WindowsApps/python3
- curl ist in : /ucrt64/bin/curl
- git ist in : /ucrt64/bin/git

## 4) How full is your disk? How much space is left on it, and how much space do your downloads take up?

- for that, use df -h
- result: available 370G and used: 106G
- Download file has : 1.4G used.
- How: du -sh Download
>[!Note]
* du - sh und dann der name des ordners von dem du gb benutzt haben willst*

