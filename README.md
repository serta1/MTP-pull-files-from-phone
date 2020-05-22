# MTP-pull-files-from-phone
code of the original author: https://github.com/Bassman2/MediaDevices
In order ti save files form the phone in given directory on pc.


MediaDevice Dll file taken from the nuget package mediadevices.1.8.0.nupkg
by changing the .nupkg to .zip and  saving the .xml and .dll locally into the same directory as 
the main phoneImg.cs script.
![Screenshot](readme1.PNG)

In order to run c sharp on my pc because I didn't want to install Visual Studio
For compiling the cs file to an exe  using I downloaded https://www.mono-project.com/download/stable/
Afterwards I opend the mono exe and typed 
used cd to get to the folder with the cs file and the rest.
then:
 csc phoneImg.cs /r:MediaDevices.dll
 
 The resulting exe needs to be together with the dll and xml file.
It will copy the files according to the cs file destinations.

Connect yout mobile phone and tap on data connection on it's screen.
The execute the exe.
