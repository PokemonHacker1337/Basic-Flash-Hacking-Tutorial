# Basic-Flash-Hacking-Tutorial

So, you want to try to hack or crack Flash games? Let me start by welcoming you then. If you are interested in this, you may want to join the [Flash Game Archive Discord server](https://discord.com/invite/h5PW6NqUvA) as any and all contributions would be appreciated. There are some people who are willing to give you a hand if needed. 

Here are the requirements/essentials:

A copy of [ffDec](https://github.com/jindrapetrik/jpexs-decompiler/releases) (more formally known as JPEXS). Works on Windows, Mac OS and Linux. 

[Flash Player Projector](https://www.adobe.com/support/flashplayer/debug_downloads.html). Supports Windows, Mac OS (64 bit) and Linux. Technically optional, but if you want to actually test the games, this is required.

Basic programming understanding. I do not expect you to learn all about ActionScript, as it is essentially a dead language, replaced with more modern languages like Python, HTML5, TypeScript, etc. However, if you happen to know JavaScript, it's very functionally similar. You are very likely to recognize a lot of what is used. 

Any SWF that you'd like to use. You are on your own for this one, but you can find some from Google by searching \*insert game name here* swf. If not, you'll likely be able to get one from Flash Game Archive if you ask around. I will share premade SWFs for tutorial purposes (WIP). 

Note: Flash games with obfuscation and encryption are out of the scope of this tutorial, as I don't know that much about working with them in general.


The first thing I would recommend doing is getting comfortable with the program. There are quite a few options, which can be intimidating for first time users. We'll explore some of the more useful ones together. 

![alt text](https://cdn.discordapp.com/attachments/912722328411070515/926077900699099156/unknown.png)

The open button allows you to open SWF files saved to your system.

The save button saves the SWF as it is, overwriting the previous one.

Save as... allows you to save the SWF, allowing you to save the file under a new name, which is useful if you would still like a copy of the old file.

Reload will discard all of the changes that you've made since your last save. This is useful in case you make a mistake and need to revert to your last save quickly.

The Run button will launch the Flash game so you may test it. Make sure you configure the path for the Flash projector (see below). 

Debug will launch the game using the content debugger, allowing you to get debugging information if needed. 

Stop will close the game. This isn't all that useful as clicking the X button on the projector will do the same thing. However, if for some reason, the program does not respond to you clicking X, this will close the game, in the event that the projector hangs entirely. 

![alt text](https://cdn.discordapp.com/attachments/912722328411070515/926081899682730034/unknown.png)

Text search allows you to search through the files for text. You can specify for it to be in ActionScript, P-Code, or regular text. 

![alt text](https://cdn.discordapp.com/attachments/912722328411070515/926086783677124648/unknown.png)

You can get to the above menu through the Settings → Advanced Settings option on the top. At a minimum, you should have the path set for the regular projector. The content debugger is optional, but if you need to do debugging, I would strongly recommend picking that up and configuring the path as well. Additionally, you can also change the theme of the program in the Interface menu, but I personally feel that the default one is fine

Once you are comfortable with the program, try opening a Flash game with it. I will use Super Mario 63 as an example, as it is one of my favorite games made in Flash. 

![alt text](https://cdn.discordapp.com/attachments/912722328411070515/926090847232065617/unknown.png)

A lot of these are very obvious. Texts has, well, the text used in the game. Sounds has all the audio related files in the game, like background music and sound effects. I'm sure you can figure the rest of this out. 

With all of this being said, where do we start? I would recommend starting by just opening the files and exploring. Unless you change stuff randomly, you aren't going to break anything by doing this. Eventually, I'll make a tutorial explaining specific games and how to make changes to them. 
