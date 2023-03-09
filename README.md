# 🥤 Afurbly
Afurbly is a software for developers to create installers/setups, for their programs and games. Besides being lightweight, fast, free and open-source, Afurbly requires no programming and has dozens of user languages from around the world.
Afurbly uses the LubryZT understanding, created by SwankyNoob, which allows the user's program/game files to be compressed and stored within Afurbly itself, and will be protected, encrypted and stored until the user runs the installer.

# 📖 LICENSE
Afurbly is under the CC-NC-ND license. It is open-source, but has many restrictions and does not accept contributions.

# 🍸 REQUIRES NWJS
For the operation of Afurbly, NWjs is required, to download and read the NWjs documentation, go to nwjs.io!

# ☂️ HOW TO USE
It's pretty simple to use Afurbly. You are required to edit 2 files, and there is another optional file. You must edit the following files:
AppName.afurbly and terms.afurbly
The file "AppName.afurbly" must be edited with the name of your program. You must only put the name of your program and nothing else. The file "terms.afurbly" you must put the terms of your program, editing this file is also mandatory, otherwise Afurbly will not work. There is a file you can create (it is not created automatically), the file "bg.afurbly" can be created by you (optionally) to add a background image instead of the black screen (which comes as default). If you want to add a background image, you must create the file "bg.afurbly" and simply add the URL/link of the image, and nothing else.
Another file that is needed is the file "main.zip". This file is nothing more than the files of your program. You must compress your program into a .ZIP file and rename it "main.zip". After renaming, move this file to the Afurbly folder and you are done. After completing all these steps you must rename the file "Afurbly.exe" to the name of your program, for example "Setup_MyProgram.exe". After renaming, you must run this file (.EXE) and complete all steps (by clicking "Next"). After finishing all steps and completing the installation of your own program, you can now distribute the installer as you wish, and you are done! Remember, the "main.zip" file and the files you have to edit must be in the Afurbly folder, in the subfolder called "engine". You must distribute the entire "Afurbly" folder with the "engine" subfolder and the "Setup.exe" file. You can rename the "Afurbly" folder as you like, and you can (we recommend) compress it to distribute, the name of the .ZIP is of your choice as well.
Here is how it should look like:
MyProgram.zip
> Setup.exe
> engine > main.zip, setup_myprogram.exe, locales, AppNams.afurbly, terms.afurbly, bg.afurbly...
-------------------
Note that when you finish everything, and run your installer, the file "main.zip" that you created, will no longer exist. This is because your program files are moved into Afurbly, and are encrypted, stored, compressed and hidden, thanks to SwankyNoob's LubryZT technology.

---> ALL RIGHTS RESERVED, SWANKYNOOB INC. | ESTABLISHED AND MANAGED BY Wesley YAN Soares Brehmer
