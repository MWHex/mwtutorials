# Converting .MP3 to .SPS

Swift stole this tutorial from Soundbarrier and made it into a Github page. Original tutorial at: [https://eatsleepsexdierepeat.blogspot.com/2023/01/sps-to-mp3-nfsmw12.html](https://eatsleepsexdierepeat.blogspot.com/2023/01/sps-to-mp3-nfsmw12.html)

How to convert whatever MP3 you want into SPS files so the game can recognise and play it. Use this tutorial together with [Adding New Songs](https://mwhex.github.io/mwtutorials/tutorials/mw12_addingnewsongs) or just replace some existing songs you don’t want.

## Stuff you need to download:

[EALayer3 Tool](https://drive.google.com/file/d/1LBqbYStbpoYWBiy-LrqHciqZjGL0lwbw/)  
[EA Sound eXchange tool](https://drive.google.com/file/d/15lIvI2D6p1Wt98XbD3M7u53M4h40uKqH/)

## Extract:

*   Open **sx\_6.00.00.7z**
    
*   Go inside the sx folder
    
*   Extract the contents to **C:\\Windows\\System32**
    

## Set up:

*   Open up CMD (Command line) as admin
    
*   Select "Yes" if prompted
    
*   Once CMD opens up, type the following command:
    
*   cd \<Directory\>
    

\<Directory\> is where your file(s) are stored

Example: cd C:\\Users\\hello\\Documents\\Songs

## Convert:

After the cd command, type the following command:

sx -sndplayer -fileformatversion1 -ealayer3_int -vbr100 **\<input\>** -=**\<output\>**

**\<input\>** is the file you want to convert to .SPS (Supports .WAV and .MP3 only)

**\<output\>** is the file it will be named after conversion

Example: sx -sndplayer -fileformatversion1 -ealayer3\_int -vbr100 **Song.mp3** -=**Songname**

The new .SPS should appear in the same folder opened with the cd command

## Test:

*   Make a copy of the .SPS
    
*   Open and extract **ealayer3-0.7.0-win32.zip** in the same directory as the file
    
*   Drag the converted .SPS file into ealayer3.exe
    

If it works, it should appear as a new file with the same name as the copy of the .SPS

## Use:

Convert the .SPS files to .MP3 files located in **Need for Speed(TM) Most Wanted\\UI\\SONGS** one by one

Listen to each and choose which you want to be removed

## Song list

Taken from [hrjohn's site](https://hrj.leibur.eu/PUBLIC/UPLOADED/New%20folder)

| ID | SPS filename | Length | Song |
| --- | --- | --- | --- |
| 89 39 00 00 | 14729 | 0:38 | NFSHP2010 menu theme |
| 8A 39 00 00 | 14730 | 0:38 | NFSHP2010 menu theme |
| DA 79 00 00 | 31194 | 3:45 | NFSHP2010 Pursuit theme |
| 16 C7 01 00 | 116502 | 5:31 | NFSHP2010 Pursuit theme |
| 17 C7 01 00 | 116503 | 5:29 | NFSHP2010 Pursuit theme |
| 18 C7 01 00 | 116504 | 6:04 | NFSHP2010 Pursuit theme |
| 19 C7 01 00 | 116505 | 6:12 | NFSHP2010 Pursuit theme |
| 1A C7 01 00 | 116506 | 5:08 | NFSHP2010 Pursuit theme |
| 99 DC 05 00 | 384153 | 0:44 | \*unknown\* |
| EB E1 14 00 | 1368555 | 6:10 | MW2012 instrumental |
| ED E1 14 00 | 1368557 | 5:56 | MW2012 instrumental |
| EF E1 14 00 | 1368559 | 4:37 | MW2012 instrumental |
| F1 E1 14 00 | 1368561 | 3:48 | MW2012 instrumental |
| 7A 06 1C 00 | 1836666 | 4:24 | Dead Sara - Weatherman |
| 18 9E 1F 00 | 2072088 | 4:12 | Poliça - Violent Games |
| 19 9E 1F 00 | 2072089 | 4:19 | Dead Sara - Weatherman |
| 1A 9E 1F 00 | 2072090 | 3:15 | Riverboat Gamblers - Blue ghosts |
| 1B 9E 1F 00 | 2072091 | 3:37 | Above & Beyond - Anjunabeach |
| 1C 9E 1F 00 | 2072092 | 3:03 | The Vaccines - Bad Mood |
| 1D 9E 1F 00 | 2072093 | 3:20 | The Who - Baba O'Riley |
| 1E 9E 1F 00 | 2072094 | 2:33 | Icona Pop - I Love it |
| 1F 9E 1F 00 | 2072095 | 4:49 | Deadmau5 - Channel 42 |
| 20 9E 1F 00 | 2072096 | 3:13 | Mutemath - Allies |
| 21 9E 1F 00 | 2072097 | 2:34 | Asherel - Shake the dust |
| 22 9E 1F 00 | 2072098 | 4:52 | Silent code - East star |
| 23 9E 1F 00 | 2072099 | 4:18 | Bassnectar - Empathy |
| 24 9E 1F 00 | 2072100 | 5:29 | Calvin Harris - We'll be coming back |
| 25 9E 1F 00 | 2072101 | 2:59 | C&D - The Chase |
| 26 9E 1F 00 | 2072102 | 3:05 | Flux Pavilion - Double Edge |
| 27 9E 1F 00 | 2072103 | 3:35 | Dispatch - Circles around the sun |
| 28 9E 1F 00 | 2072104 | 2:55 | Dizzee Rascal - Bonkers |
| 29 9E 1F 00 | 2072105 | 3:10 | Foreign Beggars - Contact |
| 2A 9E 1F 00 | 2072106 | 4:31 | Beware of Darkness - Howl |
| 2B 9E 1F 00 | 2072107 | 2:57 | Heaven's Basement - I Am Electric |
| 2C 9E 1F 00 | 2072108 | 2:48 | The Joy Formidable - Little Blimp |
| 2D 9E 1F 00 | 2072109 | 4:01 | Nero - Won't you be there |
| 2E 9E 1F 00 | 2072110 | 4:56 | RuN RIOT - A Light Goes Off |
| 2F 9E 1F 00 | 2072111 | 3:44 | Last Dinosaurs - Zoom |
| 30 9E 1F 00 | 2072112 | 5:49 | Popeska - Now or Never |
| 31 9E 1F 00 | 2072113 | 3:10 | Madeon - The City |
| 32 9E 1F 00 | 2072114 | 5:06 | The Maccabees - Unknow |
| 33 9E 1F 00 | 2072115 | 2:30 | Lower than Atlantis - Love Someone Else |
| 34 9E 1F 00 | 2072116 | 3:38 | Rudimental - Feel the Love |
| 35 9E 1F 00 | 2072117 | 4:24 | Silent Code - Night Train |
| 36 9E 1F 00 | 2072118 | 3:17 | Crosses - Telepathy |
| 37 9E 1F 00 | 2072119 | 5:30 | Skrillex - Breakin' a sweat |
| 38 9E 1F 00 | 2072120 | 4:23 | X Ambassadors - Unconsolable |
| 39 9E 1F 00 | 2072121 | 4:28 | Strange Talk - Cast away |
| 3A 9E 1F 00 | 2072122 | 4:26 | The chemical brothers - Galvanize |
| 3B 9E 1F 00 | 2072123 | 3:33 | The Who - Won't Get Fooled Again |
| 3C 9E 1F 00 | 2072124 | 3:35 | We are the ocean - The Road |
| 3D 9E 1F 00 | 2072125 | 2:26 | Green Day - Stop when red lights flash |
| 3E 9E 1F 00 | 2072126 | 4:59 | Muse - Butterflies and hurricanes |
| 3F 9E 1F 00 | 2072127 | 4:17 | Silent Code - Spell bound |
| 40 9E 1F 00 | 2072128 | 2:47 | DJ Fresh - The power |
| 41 9E 1F 00 | 2072129 | 3:02 | Band of Skulls - You're Not Pretty But You Got It Goin' On |
| 42 9E 1F 00 | 2072130 | 3:28 | Crosses - Telepathy |
| 43 9E 1F 00 | 2072131 | 4:17 | Muse - Butterflies and hurricanes(intro ver) |
