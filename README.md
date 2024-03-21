# Open Source Yoot Tower

Welcome to the Open Source Yoot Tower repo! 

Yoot Saito just sent me (Don Hopkins -- don@donhopkins.com) a code drop of Yoot Tower for archival and academic study, and to make a modern open source version that runs in the browser!

So I’ve started the process of documenting and publishing the public open source version of Yoot Tower on GitHub:

https://github.com/SimHacker/YootTower

## Call for Collaboration

Anybody want to help, or know somebody who does, please? ;) You can get in touch with me at don@donhopkins.com and check out the repo.

There’s a lot of stuff, so I am going over the files, sorting out which versions there are, and trying to date and classify them. 

Boy am I jazzed!!! It’s as cool as I imagined, even more! 

## Micropolis Core (Open Source SimCity for the browser, using WebAssembly)

I’ve been getting a head start on porting Yoot Tower to the browser by working on renovating the existing open source C++ version of SimCity / Micrcopolis run in the browser too. 

Both projects will share the same modern tech stack and web interface (Emscripten, Embind, WebAssembly, TypeScript/JavaScript, SvelteKit, Node, Canvas/WebGL/HTML/CSS, etc), so they'll eventually plug together with multiple Yoot Towers embedded into your live Micropolis city!

https://github.com/SimHacker/MicropolisCore

Maybe somebody can even fix the bug in the Windows version that Clint Basinger (LGR) kept getting zapped by in his in-depth review of Yoot Tower:

## LGR: Yoot Tower: The Sequel to SimTower

https://www.youtube.com/watch?v=CqNECXCd9iU

## Next Steps

I examined the timestamps in the files in the Yoot Tower code drop, and organized the sources and releases by date, translating the Japanese directory names. 

The file names and function and variable names are all in English, but there are lots of Japanese comments, and some user visible Japanese strings that will need to be translated. 

I'll continue comparing and analyzing the different versions to figure out how they changed over time and what to use for the open source version. 

It includes the old Maxis SimTower code, some Japanese Windows versions, and versions for the GameBoy Advance SP and Nintendo DS. 

The most recent version is the Nintendo DS version. It has some interesting additions and changes, but I presume a lot of that stuff is Nintendo's property and branding, like Mario and other characters we can't use in the open source version. 

We have to remove / fictionalize / rename / rewrite / redraw any trademarked content for the open source version, but we can archive the original sources for academic research purposes.

Jeff Braun told me happened with Maxis and Godzilla, so I want to be careful to avoid stomping on anybody’s property:

"Maxis was sued by Toho. We never referred to the name Godzilla, our monster on the box cover was a T-Rex looking character, but... a few magazine reviews called the monster, Godzilla. That was all it took. Toho called it "confusion in the marketplace". We paid $50k for Godzilla to go away. In all honesty, Toho liked Maxis, they said $50k was the minimum they take for Godzilla infringement. I doubt you will need to worry about Toho, as long as there are no magazine reviews that call the monster Godzilla."

I guess the lesson is to always make sure to give your monsters a unique name, and don’t leave that up to the user’s imagination. 

Thanks for your attention and any advice or collaboration you can contribute! 

-Don (don@donhopkins.com)

## Directories of code drop:

- The_Tower
  - Windows sources.
  - 1993-02-01 .. 2005-07-05

- The_TowerSP
  - GameBoy Advance SP sources.
  - 2004-08-03 .. 2005-04-07

- The_TowerDS
  - Nintendo DS sources.
  - 2008-05-26 .. 2009-08-01

- The_TowerⅡ
  - Windows releases, no sources.
  - 1999-01-19 .. 1999-11-09

## Sources:

- 1993-02-01 .. 1996-09-22	./The_Tower/Old NT Backup 2/95ntback2/tow_EX2/Maxis-ST-code
  - Original Maxis SimTower sources.
  - Old short upper case file names.

- 1993-07-20 .. 1995-09-07	./The_Tower/Tower 秋ヤンバージョン Final Data/SOURCE/WIN/TOWER/SRC1_2 🇯🇵🌐🇺🇸 Tower Autumn Version Final Data
  - Old short upper case file names.

- 1994-04-02 .. 1997-02-04	./The_Tower/Old NT Backup 1/95ntback2/tow_EX2/tower 8-22 working version stuff/SRC_CD
  - Old short upper case file names.

- 1994-08-14 .. 1996-03-18	./The_Tower/Old NT Backup 1/95ntback2/tow_EX2/tower 8-22 working version stuff/Demo95
  - Old short upper case file names.

- 1994-08-14 .. 1996-09-29	./The_Tower/Old NT Backup 1/95ntback2/tow_EX2/tower 8-22 working version stuff/Src_cde
  - Old short upper case file names.

- 1994-08-14 .. 1996-10-09	./The_Tower/Old NT Backup 1/95ntback2/tow_EX2/tower 8-22 working version stuff/SRC1_295
  - Old short upper case file names.

- 1997-05-23 .. 1997-05-23	./The_Tower/Old NT Backup 1/95ntback2/tow_EX2/Src_cd2
  - Old short upper case file names.

- 2004-08-03 .. 2004-08-03	./The_TowerSP/The Tower SP 2004.05.25版　マスター ソース・ドキュメント・マスターROM/TowerSP040525/TowerSP_J_040525/beta/tower 🇯🇵🌐🇺🇸 The Tower SP 2004.05.25 version Master Source Documents & Master ROM
  - Newer long mixed case file names.
  - GameBoy Advance SP.

- 2005-07-05 .. 2005-07-05  ./The_Tower/Towerマスター 2005,7,5/tower 🇯🇵🌐🇺🇸 Tower Master 2005,7,5
  - Newer long mixed case file names.

- 2005-04-07 .. 2005-04-07	./The_TowerSP/The Tower SP 2005.02.25版　マスター　(製品版)ソース・ドキュメント・マスターROM/TowerSP050225/TowerSP_J_050225/overseas/tower 🇯🇵🌐🇺🇸 The Tower SP 2005.02.25 version Master (Final Version) Source Documents & Master ROM 
  - Almost identical to above but for a few added psd and other files.

- 2008-05-26 .. 2009-08-01	./The_TowerDS/The Tower DS クラシック 全バックアップデータ 2009,9,7/TowerDS_NAND/tower 🇯🇵🌐🇺🇸 The Tower DS Classic Full Backup Data 2009,9,7
  - Nintendo specific additions and modifications.

## Releases:

- The_TowerⅡ/99121自由の女神 マスター2版　ハイブリット CD-ROM GM No2 🇯🇵🌐🇺🇸 99121 Statue of Liberty Master 2 version Hybrid CD-ROM GM No2
  - 1999-01-19

- The_TowerⅡ/99226 1400 京都駅ビル ハイブリット CD-ROM GM no.2 🇯🇵🌐🇺🇸 99226 1400 Kyoto Station Building Hybrid CD-ROM GM no.2
  - 1999-02-26

- The_TowerⅡ/120 1700 自由の女神 windows版　マスター2 本体+movieデータをMacinToshに移すデータ「readme」は変更 219ガメラスターター Windows版をMacに移す 🇯🇵🌐🇺🇸 120 1700 Statue of Liberty Windows version Master 2 Body + movie data to transfer to Macintosh "readme" is to be changed. Move Windows version of Gamera Starter to Mac
  - 1999-02-16

- The_TowerⅡ/Macintoshiに移すガメラ東都オプションデータ 🇯🇵🌐🇺🇸 Transfer to Macintosh Gamera Eastern Capital Option Data
  - 1999-02-26

- The_TowerⅡ/Tower2 9935版 🇯🇵🌐🇺🇸 Tower2 version 9935
  - 1999-02-26

- The_TowerⅡ/TowerⅡ 駅ビル　window’s Mac ハイブリッド　d-STATION 🇯🇵🌐🇺🇸 Tower II Station Building Windows Mac Hybrid d-STATION
  - 1999-02-26

- The_TowerⅡ/TowerⅡfor Windows GM プログラミング・ソース　なにわ　ビル王　伝説　1999年　8月17日 🇯🇵🌐🇺🇸 Tower II for Windows GM Programming Source Naniwa Building King Legend August 17, 1999
  - 1999-03-04

- The_TowerⅡ/990308 yoot Tower Windows
  - 1999-03-09

- The_TowerⅡ/99817 なにわビル王伝説　ハイブリットCD-ROM 1000 GM no.2 🇯🇵🌐🇺🇸 99817 Naniwa Building King Legend Hybrid CD-ROM 1000 GM no.2
  - 1999-08-17

- The_TowerⅡ/99817なにわビル王伝説 Windows版　GM マッキントッシュで焼くために使用した 🇯🇵🌐🇺🇸 99817 Naniwa Building King Legend Windows version GM Used for burning on Macintosh. Transfer Gamera Eastern Capital Option Data to Macintosh
  - 1999-08-17

- The_TowerⅡ/99119 The　Tower2　クリスマスストーリー　ハイブリット CD-ROM. GM no.2 🇯🇵🌐🇺🇸 99119 The Tower 2 Christmas Story Hybrid CD-ROM. GM no.2
  - 1999-11-09

## Introduction

This Open Source Yoot Tower repo encompasses the evolution and development of the "SimTower" game, created by Yoot Saito and later developed into "Yoot Tower" in the US and "The Tower II" in Japan. Published by Maxis, the game, initially released as "SimTower: The Vertical Empire" (or "The Tower" in Japan), is a construction and management simulation game for Windows and Macintosh System 7, developed by OPeNBooK and published in November 1994. It involves building and managing a tower, placing various facilities to achieve a five-star rating while dealing with random events like terrorist acts.

The Tower II introduced the ``Tower Kit`` an optional software allowing players to add new maps and stages, enhancing gameplay with new features. It also included a crossover element between redevelopment and a love story, set in New York. The game links to the movie "Gamera 3," featuring battles between Gamera and Gyaos in Tokyo, and offers a final showdown in Kyoto. Additionally, it offers a special package with maps related to the movie and various towerkit maps, enhancing the gaming experience.

Discussions on Hacker News reflect the game's impact and its innovative approach to game design, including its start as an elevator simulator and its influence on the gaming community. Yoot Saito, the game's creator, also worked on other projects like "Mario Motors" and expressed interest in open-source development. His relationship with key figures in the gaming industry, such as Satoru Iwata and Shigeru Miyamoto, is highlighted, showcasing the game's significance in the industry and pop culture.

## Description

Maxis published SimTower by Yoot Saito, which later developed and published as Yoot Tower in the US and The Tower II in Japan, along with many plug-ins using Tower Kit.

https://en.wikipedia.org/wiki/SimTower

SimTower: The Vertical Empire (known as The Tower in Japan) is a construction and management simulation video game developed by OPeNBooK and published by Maxis for the Microsoft Windows and [Macintosh System 7 operating systems in November 1994. In Japan, it was published by OPeNBook that same year and was later released for the Sega Saturn and 3DO in 1996. The game allows players to build and manage a tower and decide what facilities to place in it, in order to ultimately build a five-star tower. Random events take place during play, such as terrorist acts that the player must respond to immediately.

https://web.archive.org/web/20000521002924fw_/http://www.openbook9003.co.jp/tower2/towerkit/whats_tk.html
***

## What's Tower Kit?

Tower Kit is optional software for The Tower II. In The Tower II, you can select the stage where you want to start the game using the concept of a "map." The Tower II package comes with three maps: "Shinjuku Subcenter," "Hawaii Diamond Head," and "Kegon Falls," and the "Tower Kit" adds these maps. By installing this tower kit, a new stage game will begin. Tower kits don't just add more stages. Each map has new features, allowing you to play a completely new game.

>Please try the "Tower Kit" which allows for infinite variations.

A love story between you, the person in charge of the Liberty Island redevelopment project, and two men and women who are your subordinates. Your work will have a subtle influence on the course of your love life. The Tower II is the first attempt at a crossover between redevelopment and love, set in New York. What is the ending...?

```
Analog radio wave output has stopped working properly. It appears that jamming waves are being emitted.''
With this report, the incident began. What is the purpose of radio interference?
Who is the culprit? When this mystery is solved, surprising facts await you.
With the official cooperation of Tokyo Tower,
you will be captivated by the precision of Tokyo Tower and its illuminations.
	

Gyaos appears in Shibuya, Tokyo. Gamera also flies in after this. 
A huge battle ensues as people crowd in on the weekend.
Gamera narrowly defeats Gyaos, but the people and the city are severely damaged, 
leaving only Shibuya in ruins.
Ayana Hirasaka is a girl who is coldly watching the growing debate.
Ayana lost her parents in the battle between Gamera and Gyaos. That girl, 
Ayana, held her unwavering determination in her heart.

_"I will not forgive Gamera."_
```

Make the most of the city of Osaka with your own building! ! Introducing the tower kit CD “Naniwa Building King Legend” full of Naniwa items! ! The "final item" that appears on the top floor can change seven times depending on how the building is constructed. It's up to you what will jump out. It's also fun to try out Kansai-style buildings. Arrangements are free, such as ``Kuidaore Building`` ``"Akindo Building`` and ``Owarai Building`` here we go! Build original buildings and dye the city of Osaka your own color! !
	
You are the main character of a small forest. Set in a small, deserted town, your role is to give dreams to children and animals and develop the town. Now, quickly find Santa items and acquire mysterious powers! Towerkit's first heartwarming fantasy. Full of mini-games and characters that color the game.

https://web.archive.org/web/20000229064305fw_/http://www.openbook9003.co.jp/tower2/index.html

Special limited pack to commemorate the release of the movie “Gamera 3”

The new map "Kyoto Station Building", where the contents of the movie "Gamera 3" are developed in the game, and The Tower II itself are now in one package. There are 4 maps included: `Shinjuku` `Hawaii` `Kegon Falls` and `Kyoto Station Building` Enjoy the world of The Tower II with this great value package that is a must-have for Gamera enthusiasts.

<Attached map>

**1. Shinjuku**

**2. Hawaii**	

**3. Kegon Falls**	

**4. kyoto station**



***
# Links to various programs and videos

## The Tower II Special Gamera Pack

＜Towerkit CD ``Kyoto Station Building + The Tower II body (including Kegon Falls)＞

A 2-disc set of hybrid CD-ROMs that operate on both Macintosh and Windows98/95, standard price 11,800 yen. Great value!

Comes with a special original screensaver and wallpaper collection. Released on March 13, 1999. Standard price: 11,800 yen (excluding tax)
***

### Go to the homepage of the movie “Gamera 3: Awakening of Iris” :

https://web.archive.org/web/20000301085848/http://www.gamera.gr.jp/

***
### Gamera 3: Revenge of Iris:


https://en.wikipedia.org/wiki/Gamera_3:_Revenge_of_Iris

***
### Gyaos Destroys Tokyo Tower - Gamera: Guardian of the Universe (British Dub):

https://www.youtube.com/watch?v=yDdFASPfxt8

***
### Gamera 3: Revenge Of Iris (2000) - Full Movie:

https://www.youtube.com/watch?v=vy7G6lrXuoc


***
### SimTower / The Tower / Yoot Tower / All Games:

https://archive.org/details/the-tower-games


***

# Versions & installation instructions for Windows

***
## SimTower 1.1b installed in DOSBOX with Windows 3.11

```
SimTower 1.1b to run on modern Windows 
1. download winevdm from github 
2. place all files from here to winevdm folder
3. run SIMTOWER.EXE with otvdmw.exe)
```

***
## The Tower 1.2j + DOSBOX with Japanese Windows 3.11

```
The Tower 1.2j to run on modern Windows 
1. download winevdm from github 
2. place all files from here to winevdm folder
3. run TOWER.EXE with otvdmw.exe)
```
***
## The Tower Sega Saturn?

The Tower Sega Saturn - SimTower based on latest 1.3J cd version + 4 maps, 
max floors reduced from 100 to 80 and population for Tower rating from 15k to 8500,
office and housekeeping room population reduced from 6 to 5, 14 new movie theater videos

***
## The Tower 3DO

The Tower 3DO - same as Sega Saturn version but very slow and laggy because of weaker 3do clockspeed, playable speed only on emulator with 500% overclocking, got no videos with magnifying glass to reduce lags, videos is watchable with binoculars icon, option to build restaurants is text only compare to Saturn version where you can see picture of what type you build, got no ending video, you just kicked into title screen after Tower rating

***
## The Tower: Bonus Edition PS1

The Tower: Bonus Edition PS1 - last version of SimTower, upgraded Saturn/3DO version, 5 maps, got different intro video and different world map, hotels and suites colors changed from brown and pink to blue and green, new videos in tower vision, 31 movie theater videos, 2 ending videos - first is just for tower rating and second for getting tower rating on all 4 maps, exclusive 3d mode where you can walk in your tower at midnight and catch thief, Statue of Liberty bonus map - 5 stars is max no tower rating

***
## Yoot Tower English version
Yoot Tower English version, 3 maps Windows The Tower 2 Japanese version with all 5 towerkit maps, applocale emulator

***
## Tower SP GBA
Tower SP GBA - based on 1.2J version, mini version with only 2 maps, max floors is 50 for office building and 35 for commercial building, 4 stars max and population for Tower rating is 2000

***
## The Tower DS
The Tower DS - sequel to GBA version with annoying touch control gimmick, you can clean rooms and catch thieves/dogs only with touchscreen, service elevators for workers returned, you can manually set check in and check out time for hotel rooms, 4 maps, got Mario Tower minigame available in menu only at 1 star rating if you got low cash, first 3 maps is short and more like tutorials and real Tower is only last map, there is 2 versions of last tower map on building screen, only difference is lobby size, left - default lobby, right - big lobby

### [Minna no NC] The Tower DS - Trailer

https://www.youtube.com/watch?v=mJtV4ZIXpR0

### The Tower DS - Nintendo DS Gameplay

https://www.youtube.com/watch?v=2DQGVU-vm-k

***
# Yoot Tower Playlists

## Video's

### Youtube
https://www.youtube.com/playlist?list=PL-_dl5TFEwyfPnzPDnVl7z2voYrfvQ7Aq

### Reddit: All games in one place + all longplays
https://www.reddit.com/r/SimTower/comments/14kgohl/all_games_in_one_place_all_longplays/

### The Tower opening (Japanese):

https://www.youtube.com/watch?v=W6On3weQvjU&t=2s

### The Tower - Bonus Edition :: HD Enhanced FMV (PlayStation):

https://www.youtube.com/watch?v=BPXY_YgyWrM

### The Tower BONUS edition:

https://www.youtube.com/watch?v=9MwnPMjT7Ik

### LGR - SimTower - PC Game Review:

https://www.youtube.com/watch?v=_4ToEDrhxo0

### LGR - Yoot Tower: The Sequel to SimTower:

https://www.youtube.com/watch?v=CqNECXCd9iU

### Yoot Tower Part 1 - Full Gameplay Walkthrough Longplay No Commentary:

https://www.youtube.com/watch?v=3wap-Ga6vG0

### Yoot Tower - 4h pure Gameplay no commentary:

https://www.youtube.com/watch?v=3H3hAPE3rJU


***

# About Yoot Saito
Yoot Saito: The original impetus was the SimCity event held around 1993 at the "Simulation & Gaming Society" event. I met Mr. Will Wright, who had just released Simcity. When I showed him The Tower under development in the event waiting room, he was so impressed that he recommended it to Jeff, the founder of MAXIS, the publisher of Simcity. I remember jumping up and down when I heard that there was something going on. Even after 15 years, I don't think I've ever experienced news comparable to this.

***

# The Open Source SimTower Clone

https://www.reddit.com/r/SimTower/comments/18r2s7f/would_anyone_like_to_develop_an_open_source/

**Reddit: I would love a opensource version/clone of simtower/yoottower but it seems all the ones i found are abandoned**

https://www.reddit.com/r/SimTower/comments/oc6glc/i_would_love_a_opensource_versionclone_of/

**Reddit: What would you like to see in a Yoot Tower sequel?**

https://www.reddit.com/r/SimTower/comments/jlufze/what_would_you_like_to_see_in_a_yoot_tower_sequel/

***

# Article about Yoot

https://www.destructoid.com/yoot-saito-worked-on-mario-motors-a-canceled-ds-game-about-building-engines/

Yoot Saito worked on Mario Motors, a canceled DS game about building engines
Posted 21 April 2018 by Jordan Devore

He also explained what it’ll take for a new Seaman to happen

In a talk about game design philosophy at Reboot Develop 2018, SimTower, Seaman, and Odama creator Yoot Saito revealed that he once worked on an unusual Nintendo DS game codenamed Mario Motors.

Saito told some heartwarming stories about his friendship with Nintendo’s Satoru Iwata and Shigeru Miyamoto, some of which he has shared before in detail. Back in the early 2000s, the three would have get-togethers in which they would “chat over tea casually” and talk about ideas for games.

“During one meeting, Iwata-san asked me a question: ‘Saito-san, what have you been interested in lately?’ I immediately understood what he was getting at, so I answered ‘sculpting chunk.’ Miyamoto-san said ‘huh?!'” (To help explain to the audience what he was referring to, Saito talked a bit about how things like watches, camera frames, and MacBooks are made. Sculpting objects out of metal chunks spoke to him and it was an idea he “really wanted” to make into a game.)

“This kind of sculpting is really appealing to a middle-aged guy like me,” Saito said.

“I explained this crazy idea to them and they really listened to me very carefully in complete silence, and finally said ‘that sounds interesting, let’s give it a try.'”

The concept eventually morphed into Mario Motors, “a game where you created engines.”

Saito summed it up as “shaving and sculpting out of a chunk of metal to make a cylinder [which then] decides the ability of your engines.” For part of the game he wanted to teach players how acceleration works in an interesting way and thought about having them blow into the DS microphone. “I scrapped this idea because this would cause children to get out of breath,” he explained.

Reflecting back on his meetings with Iwata and Miyamoto, Saito said “I really understand just how much they respected each other, and how they formed the two wheels that pulled Nintendo’s game business forward. They paid attention to me because they were always hungry for something new.”

As for why Mario Motors never moved ahead, Saito said “I can’t tell you why, but please guess.”

He didn’t have any formal announcements to make during the talk, but it seems as if he’s still interested in a SimTower-style game (he asked the entire audience to come up mid-presentation and look at a basic prototype on his iPad) as well as Seaman. For the latter, Saito would want it on mobile “without any endings for years” and that would require a sophisticated and nuanced AI engine that talks back to players. “Until that engine is done, I’m not going to create a sequel to Seaman, but I am working on that.”

https://www.destructoid.com/yoot-saito-on-iwata-canned-seaman-3ds-game/

Yoot Saito on Iwata, canned Seaman 3DS game
Posted 15 July 2015 by Steven Hansen


***

# Some words from Yoot

Canned fish

We’ve covered Seaman frequently throughout the years on Destructoid with overflowing hearts. And it’s under tragic circumstances that we get confirmation: Seaman 3DS was a planned project that fell through.

Original Seaman developer Yoot Saito wrote a blog post, translated over at Neogaf, reflecting on his relationship with the late Satoru Iwata.

I first met Iwata-san back in 1996, so it was a time before you would typically see him in a suit. It was at HAL in Kofu. I remember that he always carried around a Mac (PowerBook), which was quite rare in the games industry. I think that formed a bit of connection between us—a feeling that we shared the same interests. It was around the year after that when I saw him with a G3 PowerBook, which even I had hesitated to buy, and I remember thinking, ‘this guy really loves Macs.’

It wasn’t until a bit later that I got a chance to work with him. It was around the time when Seaman was taking the world by storm and I was really busy working on planning for the sequel and taking interviews and such.

Iwata-san got in touch and asked if we could meet, and he even came all the way out to the apartment I was renting in Tokyo to see me.

As anyone who has met him probably understands, Iwata-san always has this aura about him that makes you feel happy and at ease. When you’re around him, you just feel good, even if you’re talking about work. That day, Iwata-san wasn’t in his typical casual garb, but had donned a blazer that he didn’t look quite comfortable in. He handed me his business card and awkwardly said, ‘this is what I’m up to these days.’ I looked at the card and he had a title that named him as part of the Office of the President. He said that he had distanced himself from HAL (the company at which he got his start in the games industry) and was now helping out at Nintendo (HAL was under the umbrella of Nintendo).

‘I’ve been given a special assignment to go out and get new types of games that haven’t been on Nintendo platforms before.’ That’s the reason Iwata-san gave me for why he wanted to meet that day. He told me that Seaman was the kind of thing he was looking for. Thinking about it now, his role at this time was probably given to him as preparation for taking over management of Nintendo down the road, but it didn’t look like that was on his mind at all at the time.

It’s worth reading in full for the interesting tidbits, such as Saito’s confirmation that his suggestion led to the Wii controller’s speaker, or Saito and Iwata’s experimentation with StreetPass sort of technology back in the Game Boy days. I was so bright eyed over the sincerity and passion of this nostalgia I almost forgot how Saito’s blog post had to end.

When Iwata-san came to ask me to create Seaman for the 3DS, I like to think he was in the same frame of mind as when he first came to visit me at my apartment back in 1999. I did start working on the project, but things got really complicated and I eventually let go of it. Unfortunately that brought an end to our relationship, where I could just casually visit him in Kyoto and have fun exchanging new ideas. I felt like we needed some time before we could go back to the kind of creativity-filled relationship.

It was early last summer that I first heard about him taking some time off to recover from an unfortunate illness. I distinctly remember it, because I was actually sharing a taxi at the time with two super famous people: Yuji Horii-san of Dragon Quest fame and Takafumi Horie, otherwise known as Horiemon.

Iwata-san, when I later saw you appear before the press, I was really happy to see that you had recovered, but it looks like the gods aren’t that lenient… Tezuka-san (from Nintendo) suggested that I make an appointment to see you, but I couldn’t find the nerve to do so. Now, after all my hesitation, I’ve learned that we truly passed each other by, and I’ll never be able to see you again. I wish I had a StreetPass feature that could connect with heaven. I would run out and buy a DS with that feature right now just so I could send you my thanks. Yeah, I know that sounds a bit too convenient for me. When I left the Seaman project, I sent you a book and a letter. Whether you actually read them or not has been on my mind ever since. Also, I’m really sorry for being late with Odama, causing it to completely miss the window for it to be a success. There’s so much more I want to tell you, but I really don’t know what to do with myself after hearing about your sudden departure in the news.

Life is always just a succession of regrets.

Iwata-san, thank you for everything. I don’t typically look up to a lot of people, but I really respected you. I would always be thinking from afar just how amazing of a person you are.

岩田さん、ありがとうございました。そして、さようなら。[Yoot]


# More News articles

## Hacker News: Railroad Tycoon:

https://news.ycombinator.com/item?id=13898241
https://www.filfre.net/2017/03/railroad-tycoon/

# Words from the Gamers themselves (Shocking)

***
Somewhat of a competitor, but any Sim Tower fans here? I was obsessed with everything Sim* but especially loved Sim Tower. Maxis was an amazing gaming company and actually my first entry into Macs. My friends dad had a Macintosh II, then classic, then LC, and I would spend hours playing games on them
 -nodesocket on March 17, 2017

***

Interestingly, SimTower was published by Maxis but developed by OpenBook (later Vivarium), the Japanese developer that would later make Seaman for the Dreamcast.
 -xxr on March 17, 2017

***

Yoot Saito just presented a classic game postmortem of "Seaman" at the recent GDC.

http://schedule.gdconf.com/session/classic-game-postmortem-seaman

Unfortunately I wasn't there to see it, but I saw him talk earlier about Seaman at GDC 2000, and it was fascinating to learn how he was able to pull off such an unprecedented original design, even supporting speech recognition on the Dreamcast!

Announcement: Yoot Saito is coming to GDC 2017 to present a Classic Game Postmortem of Seaman!

http://www.gdconf.com/news/yoot-saito-coming-gdc-2017-present-classic-game-postmortem-seaman/

"Yutaka "Yoot" Saito, the talented game designer known for his idiosyncratic approach to game development, will be delivering a Classic Game Postmortem on his remarkable Dreamcast game 'Seaman' at GDC 2017! Saito's game development career took off in the early '90s when he created the game that was published by Maxis as 'SimTower', but it was after he founded his own studio Vivarium that he really came into his own. Under the Vivarium banner, Saito developed the groundbreaking virtual pet game 'Seaman' (lending his own face to the titular Seaman), its striking sequel 'Seaman 2', the pinball strategy game 'Odama', and the airport baggage management puzzle game 'Aero Porter'. Now, Saito is coming to GDC 2017 to speak at length about his work creating 'Seaman', a game that left an indelible mark on the fabric of both the game industry and pop culture at large. Don't miss it!"

I just found the video of his GDC 2017 talk: Classic Game Postmortem: 'Seaman'!

http://www.gdcvault.com/play/1024327/Classic-Game-Postmortem-Seaman

And here's a review and summary of his talk.

http://www.seganerds.com/2017/03/02/yoot-saito-gives-gdc-presentation-on-seaman-development/

Hacker News: When SimCity Got Serious: Story of Maxis Business Simulations and SimRefinery (obscuritory.com)

https://news.ycombinator.com/item?id=23236132

https://obscuritory.com/sim/when-simcity-got-serious/

 -DonHopkins on March 18, 2017

***

I loved SimAnt and SimTower as a kid. I spent days playing those games, as well as SimCity.
 -griffinkelly on May 19, 2020

***

SimEarth really taught me the importance of critical mass. You could peter out if you didn’t marshal your resources to reach the next stage of the game.

Oxygen Not Included is my simulation game of choice atm. It really punishes you if you don’t realize how quickly you’ll deplete some finite resource.
 -milesvp on May 19, 2020

***


Interestingly, SimTower was not developed by Maxis but by the Japanese OPeNBooK, and was originally released in Japan as "The Tower". Maxis then published it in US as part of the Sim series.

OPenBooK went on to develop Yoot Tower ("The Tower II" in Japan), a sequel to the original game, in 1998.

Looking at their Wikipedia page ( https://en.wikipedia.org/wiki/Vivarium_Inc. ), seems Seaman and Seaman 2 were also theirs - interesting.

Hacker News: List of Special Elevator Modes

https://news.ycombinator.com/item?id=27776830

https://elevation.fandom.com/wiki/List_of_elevator_special_modes
 -AnssiH on May 19, 2020

***

If you love elevators try out SimTower, it's all about micromanaging them!
 -pram on July 9, 2021

***


SimTower started as elevator simulator, and was then turned into a game.

Also, this is a great talk if you want to know more about elevators: 

Elevator Hacking: From the Pit to the Penthouse:

https://www.youtube.com/watch?v=ZUvGfuLlZus

Hacker News: Elevator Saga: An elevator programming game (2015)

https://news.ycombinator.com/item?id=27487111

https://play.elevatorsaga.com/
 -ben_bai on July 9, 2021

***

As aidenn0 said, this sounds like SimTower and its sequel Yoot Tower. There's a section of the manual called "A Message From Yoot Saito, Creator of Sim Tower" that describes how he started creating it because he was curious about elevator programming. https://archive.org/details/SimTower_-_Manual_-_PC/page/n7/mode/2up
 -SaberTail on June 12, 2021

***

Maybe Sim Tower? The game was pretty boring, but building and managing elevators to keep people happy was a fun challenge.
 -aidenn0 on June 12, 2021

***

Sim Tower and Sim Ant were both great network-building games. They seemed boring until you really delved into the details. Maxis was really genius up until EA bought them. Here's a pretty cool project they did that never came to light...

https://www.gamesradar.com/simrefinery-the-lost-oil-plant-game-from-maxis-is-now-playable-in-your-browser/

Hacker News: The Story of Maxis Software (1999):

https://news.ycombinator.com/item?id=30141278

https://web.archive.org/web/19991012021220/http://gamespot.com/features/maxis/index.html

 -noduerme on June 13, 2021
***

Here are some old Sims design documents:

https://donhopkins.com/home/__/TheSims

https://donhopkins.com/home/__/TheSimsDesignDocuments

This one describes Maxis's philosophy of Sim game design:

https://donhopkins.com/home/__/TheSimsDesignDocuments/MaxisSimRules.pdf

MAXIS SIM GAME REQUIREMENTS

SUMMARY

The Maxis marketing department recently studied customer expectations of Maxis Sim games. The study revealed seven descriptions of what the Maxis Sim player thought a Sim game should be. While the “Seven Points of Sim” descriptions reflect customer expectations, they are not all necessarily the ingredients for a Sim game. To understand why Sim players perceive Sim games the way they do, we can look at the key factors that make a game a “Sim”.

REQUIREMENTS FOR A MAXIS SIM GAME

Dilemma

Players must always grapple with difficult decisions. In SimCity, pollution may be a problem, but there might be a strong industrial demand. In SimTower, condo-dwellers will need elevators heading down, while office workers will need elevators heading up.

Crisis

Crisis can also mean disasters. Players occasionally need to abandon long term strategy in favor of short-term success. If a fire is burning in SimCity or SimTower, players might need to destroy all their creations in the surrounding area.

Budgeting

The amount of funding a player has acts as both a limiting factor and a kind of score. Every action by the player costs money - even mistakes - and there are no refunds. “Cheats” to gain more money are the most popular cheats.

Aesthetics

Artwork is important for players to admire their creations. Also, the ability to place buildings, zones, crops, etc. in various places that may not have relevance to the Sim, fakes players into believing that their city or tower designs are “better” than other’s. Finally, aesthetics are a form of reward for the player. In SimTower, an aesthetic reward for reaching the 100th floor is the ability to place a cathedral. This is akin to “winning”.

Change in Rules over Time

Rule changes cause players to change their playing strategy. In SimCity, demand for Industry is high at first, but then swings to Commerce. In SimTower, the placement of condos is important at first, but nearly irrelevant after the 3rd Star.

Visual/Graphical Feedback

A Simulator is nothing but formulae operating on a data set. The player’s main interpretation of the change in data is graphical, in the form of tall buildings in SimCity, and long elevator lines in SimTower. An example failure in graphical feedback is Outpost from Sierra, where player feedback is in the form of numbers in a dialog box.

Cause & Effect are not Immediately Apparent

Because of the interleaving data sets in the simulators, players may not initially understand why certain actions have unexpected effects. One of the compelling reasons to play is to discover and understand various causes and effects.

Players are allowed to destroy their Creations

Who says there is no violence in Sim games? A favorite activity of the Sim player is to save a “masterpiece” copy of their creation, then unleash disaster after disaster, and bulldoze like crazy.

Hacker News: So You Think You Can Program an Elevator

https://news.ycombinator.com/item?id=10889075

https://github.com/mshang/python-elevator-challenge/blob/master/README.md
 -DonHopkins on Jan 31, 2022

***

This makes me want a hackable version of SimTower.
 -logn on Jan 13, 2016

***

I have a pet theory that Sim Tower came out of someone playing around with elevator algorithms for fun and then turning that into a game.
 -prutschman on Jan 13, 2016

***

Not a theory, reality. https://en.wikipedia.org/wiki/SimTower#Gameplay
 -cridenour on Jan 13, 2016

***
Awesome, my favorite game when I was younger.

Hacker News: Elevator Dispatch Algorithms:

https://news.ycombinator.com/item?id=4347568

http://www.smartplanet.com/blog/pure-genius/intelligent-elevators-answer-vertical-challenges/8191

- Jcsnv on Jan 13, 2016

***

So how long before they can predict the future to be at the right place at the right time every time?

It's certainly how interesting how critical a good setup can be to get a large skyscraper to actually work well. If they take too long to get to the people waiting then they need to leave or get to work. The old game SimTower is actually a pretty decent simulation of this kind of effect (if not still overly simplified).

 -simcop2387 on Aug 6, 2012

***

SimTower was /actually/ just built around an elevator simulator. "You guessed right," she said. "Sim Tower was built around a real elevator simulation program we bought from a Japanese guy." 

http://www.gamasutra.com/view/feature/2150/the_designers_notebook_the_.php

Hacker News: The SimCity Planning Commission Handbook:

https://news.ycombinator.com/item?id=10168016

http://archive.vg/blog/retro-book-look-the-simcity-planning-commission-handbook-publ-1990


 -Tiktaalik on Sept 4, 2015

***
SimCity and Cities: Skylines are still half stuck in 1950s era car oriented urban planning so they're not totally representative of the real world and modern urban planning. In these games public transportation options are limited, walkable public spaces such as pedestrian only streets and squares are not possible, and bike lanes do not exist. Additionally zoning is either residential, commercial or industrial, so there's no concept of mixed-use zoning (ie. commercial on the bottom of a building, residential on top) which you see everywhere.

I'd love to see a smaller scale game that really focuses on these details. SimCity 4 and other games went in the other direction, building systems around how a metropolitan region of multiple cities would interact.

 -rmserror on Aug 7, 2012

***

SimTower sort of did this, within the context of a single skyscraper. I'm not sure if it is on GOG or anywhere else legitimate these days - odds are it might not be a simple matter to run on modern Windows, unless you want to spin up an XP VM.

I spent way too many hours playing SimTower as a kid. It was pretty fun, especially if you took advantage of the infinite money cheat involving building a specific type of room in one certain place on the bottom of the level... Not bad for a game that was built around an elevator simulator 

The Designer's Notebook: The Perils of Bottom-up Game Design:

https://web.archive.org/web/20130510184845/http://www.gamasutra.com/view/feature/130563/the_designers_notebook_the_.php

 -douche on Sept 4, 2015

***


I've very much enjoyed playing SimTower, and I still have a legitimate exe of it sitting around. But the game is a Win16 game, and my latest experience running it in WINE was crap (it became very easy to completely lock up X). Possibly it might make more sense running in Windows 3.1 in dosbox.

Incidentally, this is a motivation for why I'm playing a bit with statically recompiling x86-16 code to run on x86-32.

 -jcranmer on Sept 4, 2015

***

It's actually available on iPad under it's Japanese release name:

https://itunes.apple.com/us/app/yoot-tower/id379197311?mt=8

 -mosheroperandi on Sept 4, 2015

***
Yoot Tower was actually the sequel to SimTower, not the Japanese name for it.

Hacker News: Elevator Expert on How to Move 10k People Up a 118-Floor Skyscraper

https://news.ycombinator.com/item?id=39064171

https://www.youtube.com/watch?v=dK6XZvIt22w

 -amyjess on Sept 4, 2015

***

If I remember the story correctly, the creator of Sim Tower wondered the same, and discovered that the algorithms governing that were closely-guarded secrets. So he developed Sim Tower.

https://en.wikipedia.org/wiki/SimTower

 -robertlagrant 23 days ago

***


So, somewhat related. Is there a way to play Sim Tower nowadays? I regret that I never got that last star, and think about it once or twice a year.

 -jvanderbot 23 days ago

***

Try https://infinitemac.org/

Pick a System Software/Mac OS version (you probably want something like 7.5), then choose the SimTower disc from the CD-ROMs drawer at the bottom of the screen.
 -brirec 23 days ago

***

This has blown my mind, thank you.
...but:

The emulator encountered an error:

Could not load disk chunk /CD-ROM/aHR0cHM6Ly9hcmNoaXZlLm9yZy9kb3dubG9hZC9TaW1Ub3dlck1hY09TL1NJTVRPV0VSLmJpbiNNT0RFMS8yMzUy/172097536-172228608.chunk#1313: HTTP status 500: ()

-4gotunameagain 22 days ago

***


There is a pretty cool PICO-8 remake:

https://www.lexaloffle.com/bbs/?tid=46087
 -duck 18 days ago

***

> algorithms governing that were closely-guarded secrets

Do many lifts have fancy algorithms in practice? I don't think I've ever had one go backwards to pick up a nearby floor, for example.

I suppose optimising where the lift loiters while empty is something I wouldn't really notice happening.

 -adhesive_wombat 22 days ago

***

> algorithms governing that were closely-guarded secrets

[citation needed]

I am not sure how you derived that conclusion from the article. The passage seems to imply little else than a company spokesman declined to divulge proprietary information to some random dude who cold-called them.

 -NoZebra120vClip 22 days ago

***


> I am not sure how you derived that conclusion from the article.

I didn't. I was saying I was trying to remember the story.
 
 -robertlagrant 22 days ago

***

I know Yoot Saito (creator of SimTower) from my time at Maxis, so I just gave him a cold call out of the blue and asked. ;) I caught him drinking Jack Daniels in a Japanese bar, but he had some time to chat.

He said he once did a big interview with BBC about SimTower (which would be worth looking up and watching if you can find it), and had a friend who worked in the elevator industry, who told him generally about how elevators worked, but much of it was secret and proprietary, so he had to come up with how they worked in the game himself, based on the general ideas he learned and his own experience and imagination.

He also said he's interested in releasing the original source code of SimTower as free open source software, like I did with the original SimCity Classic source code, so I volunteered to help him and find other people who could help. Anybody interested? ;)

 -DonHopkins 22 days ago


-END
