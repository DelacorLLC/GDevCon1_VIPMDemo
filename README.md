# GDevCon1_VIPMDemo
Repository for CML DQMH demo presented at GDevCon1 and covered in the CLA Summit in Krakow in 2019. 
You can find more details here: 
http://delacor.com/how-to-organize-your-large-labview-project-using-libraries/

## Purpose
Show how different reusable modules/libraries can reside in different repositories and even be in different LabVIEW versions.

The code in the top-level code calls the VIPM packaged version of all the other submodules.
The source code in all of the submodules has to be in the same version, or the dependencies can be in earlier versions.
When you package code with VIPM, VIPM mass compiles the code when it installs it and gets it to the latest version.
For example, we continue to develop DQMH in LabVIEW 2014, but anyone can install it in LabVIEW 2014 or later. 


## Cloning this repository
When cloning this repository make sure you select to clone recursively, this video shows you how to do it with SourceTree:
https://youtu.be/Lg6Bey-Y2KE
This repository relies in other repositories.

## Code in LabVIEW 2014

## Dependencies
* DQMH 4.2 installed via VIPM
* Right click on the CML.vipc file and select "Apply Configuration" this will install all the dependencies via JKI VIPM

