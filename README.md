#BEGIN INTRO

This is a user modification project using the Paradox Game Crusader Kings 2, which will try to capture the universe presented in Jagex's MMORPG, Old School Runescape.
Two days ago, that is 2019-07-08, I had no idea how to start a user modification and have now moved my project to GitHub which I admittedly do not know how to use, but that's all in the learning process I assume.


It is my hope that eventually someone with more experience in user modification could contact me and help me and contribute in realizing my project so it can eventually be enjoyed by everybody.

#END INTRO  


#INSTALLATION INSTRUCTION

THIS USER-MODIFICATION PROJECT IS CURRENTLY HOSTED AT: https://github.com/justwillem/mod/

1. Download the mod, hit the green button on the right named 'Clone or download', download ZIP and you will get the file 'mod-master.zip' in your download folder.
2. Extract the contents of 'mod-master.zip' to your paradox mod folder. Usually placed in: C:\Users\me\Documents\Paradox Interactive\Crusader Kings II\mod
Note: Only the folder and .mod file is necessary for playtesting.
3. Open ck2game.exe, open the mod tab and check 'WorldOfGielinor'.
4. Enjoy.


#ModMethod

This mod could not be written if it weren't for ParadoxUsername and GitHub username: JonStryker, as the foundation of my work comes from his guide on how to make a Total Conversion Mod.
        You can find that guide here: https://forum.paradoxplaza.com/forum/index.php?threads/guide-to-total-conversion-map-modding-clans-of-ireland.801599/


#Installed programs that are very nice to have:

I am writing this assuming you are using Windows 10, as I don't really know how to use Linux or MacOS.

To edit this mod, we must make use of programs other than the mod, and Crusaderkings2. The following programs is just a summary, if you want to look at a specific aspect of this mod, I will say which program is required.

Photoshop, I use photoshop CS6, if you are student you may have a student's copy connected to your school e-mail. If not, you can purchase it here: https://www.adobe.com/creativecloud/plans.html?single_app=photoshop&promoid=695P7SPW&mv=other
Though, if you don't have access to a copy, I would recommend you find some other software, as I would personally never willingly support corporate Adobe monetarily :D.

      Nvidia's DDS file plugin for Photoshop: https://developer.nvidia.com/nvidia-texture-tools-adobe-photoshop#downloads
      I assume there are ways to generate .DDS files on other programs, but you have to do your own research on that :) .

Excel, since I am a student I have access to Office 365, chances are if you are a student or work for a company that needs a lot of IT services you have access to this too. I am simply not going to link a way to purchase Excel as I also have moral qualms about giving more than the bare minimum financial support to Microsoft. In any case you can also use OpenOffice Calc, though I think you need to download the entirety of OpenOffice to get to that point (So it's not unlike Microsoft Office).

A text editor like Notepad++, though I use the program Atom in conjunction with GitHub, since that is the environment I have decided to commit to.


#.BMP Files, .DDS Files and photoshop

The Files that concern the visual aspect of the mod are found in the map directory (mod\WorldOfGielinor\map)
These files are modifications of the 'Vanilla' files found in the original game file directories (in the file map)
This mod uses a custom resolution for the map of 2560 x 4096. This is different from the vanilla resolution which is 3072 x 2048 . Apparently any resolution would world as long as it is divisible by 64. Do note that trees.bmp should be 1/8 of the resolution of everything else. Everything written here is heavily based on JonStrykers guide so I would recommend his explanation.
You can open provinces.psd in the mod\ directory, this is what I used to make most of the .bmp files.
I don't have a very good knowledge on how to make .DDS files, but you can download the aforementioned NVidia plugin which will give an option on the photoshop filter tab, you will generate a .DDS file. You do this to generate images for the \map\terrain files, as well as world_normal_height. But I haven't figured this out :D



#Map Filler Tool

I am currently using JonStryker's 'map filler tool'. You can download it here: https://forum.paradoxplaza.com/forum/index.php?threads/tutorial-tool-how-to-fill-a-custom-map.697082/

To use CK2Tools-v20, you need to have Java 7 installed, but I found that the latest version of Java will work just as fine.

You can download that here: https://java.com/en/download/

One of the files in CK2Tools-v20 is called 'config.properties' if you open this in a text based editor, you need to change the moddirectory to CK2 mod folder, that is, in line one you should have written: moddirectory=C:\\Users\\me\\Documents\\Paradox Interactive\\Crusader Kings II\\mod\\WorldOfGielinor
And in line 2, you need to have the correct directory to your standard ck2 game, for example: intalldir=C:\\Program Files (x86)\\Steam\\steamapps\\common\\Crusader Kings II
