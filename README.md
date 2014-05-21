#### This is a WIP list that I've made a few weeks ago for HaxeFlixel and didn't have time to complete. Maybe someone can use it as it is. Updates may follow. ```Entry's Name ([Author](Author's link))](Entry's link):``` is the markdown template I use for entries, this is why you have this guy (): all over the document.


```
title: "External Libraries and Services"
```

# Introduction
When you are building your game you want to have the ability to extend its capabilites beyond what HaxeFlixel/OpenFL supports. This requires you to interact with many external libraries and services, which may only allow you to do so through their [API](http://www.techterms.com/definition/api)'s or [RTE](http://www.techterms.com/definition/rte)'s. 

It may seem like a scary task at first, but luckily, there's a good chance some good people (such as [Johann Martinache](https://github.com/shoebox), [Sergey Miryanov](https://github.com/sergey-miryanov) and [Emiliano Angelini](https://github.com/emibap)) did most of the work for you; writing code that allows you to use these libraries and services within your own project at (relative) ease. 

Some of these resources are already written in Haxe, so frequently it's just a matter of [using Haxelib](http://haxeflixel.com/documentation/using-haxelib/) with the quite comfortable [list of available libraries to install](http://lib.haxe.org/), but some of them are written in a variety of languages, which makes it a bit more complicated to deal with, so let us start with those:

# Non-Haxe libraries and services

## How does it work?

### OpenFL native extensions


### JAVA

### AS3 (Action-Script)

#### Convert AS3 to Haxe

#### Use Haxe with AS3 


### C++

## Native Targets 

### Android
[Barcode ([Barak Shohat](http://www.bazzisoft.com/index.php))](https://github.com/bazzisoft-openfl-extensions/barcode):This extension provides real-time barcode scanning functionality for iOS and Android, directly from the device's camera. In Android, it uses the Google/ZXing Barcode Scanner app as a service. This app must be installed separately for barcode scanning to work. The extension provides an indication if it's not installed when attempting to scan.

[CameraMic ([Josu Igoa](https://github.com/josuigoa))](https://github.com/josuigoa/CameraMic):

[Device ID (hopewise)](https://github.com/hopewise/HardDiskSerialNumberExtension):


[ ([]())](https://github.com/ipsilondev/getimagext):

[HypSystem([Johann Martinache ```at``` [HyperFiction](https://github.com/hyperfiction)](https://github.com/shoebox))](https://github.com/hyperfiction/HypSystem): 

[ ([]())]():https://github.com/shoebox/HyperTouch

[Image Saver([Emiliano Angelini](https://github.com/emibap))](https://github.com/emibap/imageSaver): 

[Interop ([Barak Shohat](http://www.bazzisoft.com/index.php))](https://github.com/bazzisoft-openfl-extensions/interop): Launch your iOS/Android app via a URL with parameters. This extension provides functionality for launching other apps via a URL, and detecting when this app is launched by a URL with a custom scheme. This can be useful for integrating with 3rd party apps or integrating to & from a website.

[Mail Sender([Emiliano Angelini](https://github.com/emibap))](https://github.com/emibap/mailSender): 

[Mobile Display ([Barak Shohat](http://www.bazzisoft.com/index.php))](https://github.com/bazzisoft-openfl-extensions/mobiledisplay): Manage the mobile display & detect virtual keyboard appearance. This extension provides functionality for managing the display of mobile devices. Currently this includes:
- Keeping the screen on indefinitely.
- Detecting and triggering events when the virtual keyboard pops up & down.
- Simulating a soft keyboard display element for non-mobile devices.

[ ([]())]():

### iOS
[Barcode ([Barak Shohat](http://www.bazzisoft.com/index.php))](https://github.com/bazzisoft-openfl-extensions/barcode): This extension provides real-time barcode scanning functionality for iOS and Android, directly from the device's camera. In iOS, it uses the ZBarSDK (http://zbar.sourceforge.net/iphone/) and the scanner is integrated as a view inside the app.

[CameraMic ([Josu Igoa](https://github.com/josuigoa))](https://github.com/josuigoa/CameraMic):

https://github.com/ipsilondev/getimagext

[HypSystem([Johann Martinache ```with``` [HyperFiction](https://github.com/hyperfiction)](https://github.com/shoebox))](https://github.com/hyperfiction/HypSystem): 

[ ([]())]():https://github.com/shoebox/HyperTouch

[Image Saver([Emiliano Angelini](https://github.com/emibap))](https://github.com/emibap/imageSaver): 

[Interop ([Barak Shohat](http://www.bazzisoft.com/index.php))](https://github.com/bazzisoft-openfl-extensions/interop): Launch your iOS/Android app via a URL with parameters. This extension provides functionality for launching other apps via a URL, and detecting when this app is launched by a URL with a custom scheme. This can be useful for integrating with 3rd party apps or integrating to & from a website.


[Mail Sender([Emiliano Angelini](https://github.com/emibap))](https://github.com/emibap/mailSender): 

[Mobile Display ([Barak Shohat](http://www.bazzisoft.com/index.php))](https://github.com/bazzisoft-openfl-extensions/mobiledisplay): Manage the mobile display & detect virtual keyboard appearance. This extension provides functionality for managing the display of mobile devices. Currently this includes:
- Keeping the screen on indefinitely.
- Detecting and triggering events when the virtual keyboard pops up & down.
- Simulating a soft keyboard display element for non-mobile devices.
https://github.com/bazzisoft-openfl-extensions


### Small Devices
https://github.com/AlexHaxe/hxL8: is a command line application to talk to the L8 smartlight via USB

### OUYA

### Windows
[Hard Disk SN (hopewise)](https://github.com/hopewise/HardDiskSerialNumberExtension):

[OpenFL Kinect ([Chris Porter](https://github.com/chrisporter))](https://github.com/chrisporter/OpenFlKinect): Based on Windows SDK, so Windows only.


## Platform API
There are many different services 


### App Store
[Hxgk-Flixel ([Anthony Prestia](http://anthonyprestia.com/))](https://github.com/prestia/hxgk-flixel): A modified hxgk that adds Game Center support to HaxeFlixel projects. The options for integrating Game Center into HaxeFlixel projects are not great. The original HxGK project seems to have largely disappeared from the Internet and NMEX, while full of great features, is an absolute pain to get running in its current state. This project should, hopefully, make basic Game Center integration (leaderboards and achievements) much simpler.

[ ([]())](https://github.com/openfl/gamecenter):

[ ([]())](https://github.com/openfl/iap): Provides an access to in-app purchases (iOS) and in-app billing (android) for OpenFL projects, using a common API.


### Facebook

[ ([]())]():
#### Windows and Flash


#### Mobile (Android + iOS)
[HypFacebook](https://github.com/hyperfiction/HypFacebook)


[ ([]())]:

### Google Play
[ ([]())]:https://github.com/openfl/iap: Provides an access to in-app purchases (iOS) and in-app billing (android) for OpenFL projects, using a common API.

### Kaltura
Kaltura’s open source platform includes hundreds of REST-based application programming interfaces (APIs) providing programmable access to every core service of the platform. With full access to our API*, you can independently extend every feature and functionality of the Kaltura Platform. This means you’ll be able to seamlessly integrate Kaltura’s various solutions, services, and widgets to create a unified experience within your chosen environments - be it a known CMS, or custom in-house application.
[KalturaHaxe [Jean-Baptiste Richardet](http://www.knowledge-players.com)] (https://github.com/Knowledge-Players/KalturHaxe):

### Ouya Market
Ouya is a 99$ game-console that is based on custom Android OS, Tegra 3, and a native controller (with support to other mainstream controllers). The console have a relatively small game market,     

	
[ ([Jushoa Granick '''at''' OpenFL](https://github.com/jgranick))](https://github.com/openfl/openfl-ouya):

### Steam Store
Steam, the giant game store that is beloved anywhere but the lairs of pure evil, so it seems. Every game maker wants to be greenlighted into steam, and many would sell their grandmothers' cats to be featured on it for a day. Still, even when you are lucky enough to get in, you still need to integrate Steam's unique C++ based API into your game.   
[ ([]())](https://github.com/dukope/SteamWrap):

### Twitter
#### PC and Flash

#### Android
Sadly there isn't a 

#### iOS
[Twixel ([Anthony Prestia](http://anthonyprestia.com/))](https://github.com/prestia/twixel) (HaxeFlixel):An openfl extension that adds the ability to use Tweet Sheets from within iOS applications. Includes a sample HaxeFlixel project. This extension currently supports multiple accounts, basic tweets, and fancy iOS-style URL appends. I will likely add image support in the future. This extension also uses the newer iOS Social framework and can potentially support Facebook in the future. Most of the existing Haxe extensions use the deprecated Twitter framework. 


[ ([]())]


### Game Portals (Web)

#### Armor Games (Flash)

#### Kongregate (Flash, HTML5, Unity) 

#### NewGrounds (Flash)


## Services API
### AdMob
#### PC and Flash
[ ([]())]():
#### Mobile (Android + iOS)
[Admob Openfl ([Michał Korman '''based on'''](https://github.com/mkorman9) [NMEX](https://github.com/watsnow/nmex))]([https://github.com/mkorman9/admob-openfl):

### ChartBoost 
[RueChartBoost ([WalterTorres](https://github.com/WalterTorres))](https://github.com/WalterTorres/RueChartboost): 

### DDAnalytics
[DDAnalytics ([Double-Duck](http://www.doubleduck.co/)](https://github.com/doubleduck/DDAnalytics):

[DDGameAnalytics ([Double-Duck](http://www.doubleduck.co/)](https://github.com/doubleduck/DDAnalytics):

[ ([]())]()


### Flurry
#### PC and Flash
#### Mobile (Android + iOS)

### Game Analytics
#### PC and Flash
[Game Analytics Haxe ([Nicolò Pretto](http://npretto.com/))](https://github.com/lordkryss/gameanalytics-haxe):

#### Mobile (Android + iOS)

### FGL (Flash)
#### In-site
FGL (Flash-Game-License) is the front runner of Flash (and recently, Android, Unity, HTML5) games sponsorships. 
[FGL Game Tracker ([Boyan Ololoevich](https://github.com/as3boyan))](https://github.com/as3boyan/FGL.GameTracker.hx)
#### FGL ADS 
[Openfl FGLads preloader ([Ben Lowry](https://github.com/benlowry?tab=repositories))](https://github.com/benlowry/openfl-fglads-preloader)(OpenFL):A preloader wrapper for the FGLAds service for OpenFL. Contains rich customization to include your own game, developer and sponsor branding.

### Google Analytics v.3
#### Cross Platform
[GA ([fbricker](https://github.com/fbricker))](https://github.com/fbricker/haxe-ga)

#### PC and Flash
[Rocket Haxe Goggle Analytics([Rocketship Games]())](http://code.google.com/p/rockethaxe/source/browse/#git%2Fcom%2Frocketshipgames%2Fhaxe%2Fanalytics): An Haxe library and only a small but very important part of a nice open-source project. 

#### Mobile (Android + iOS)
[GAnalytics ([Emiliano Angelini](https://github.com/emibap))](https://github.com/emibap/GAnalytics): 

https://github.com/hyperfiction/HypGA

### Keen.io
#### PC and Flash
#### Mobile (Android + iOS)

### Localitics
#### PC and Flash
#### Mobile (Android + iOS)

### Mochi - "It's dead, Jim"

### Nuggeta
#### PC and Flash
#### Mobile (Android + iOS)
[ ([]())]()
### Playtomic
An Open source incarnation of the once popular and the now dead service for Flash Games. 

[Playtomic Haxe API([Playtomic](http://playtomic.org/))](https://github.com/playtomic/gameapi-haxe): 

### Startapp
#### PC and Flash
#### Mobile (Android + iOS)




# Haxe Libraries and services
## 3D
### OpenFL support
### Angel 3D
[ ([]())]()
### Away 3D (Cross Platform)
[Away 3D Core OpenFL ([Away3D](http://www.away3d.com/))](https://github.com/away3d/away3d-core-openfl)
[Away 3D Core OpenFL Exampls](https://github.com/away3d/away3d-examples-openfl)

### Stage 3D 
### H3D (Flash)
[ ([]())]()https://github.com/ncannasse/h3d
### Native 3D
[ ([]())]()https://github.com/matrix3d/native3d

## AI
[ ([]())]()
## Animation
### Keyframes Animation
#### Skeleton Animation
##### Dragon Bones
##### Skeletoraxe
##### Spine
##### Spriter

#### Tween Libraries

##### Actuate
##### Atomic Motion
https://github.com/TomByrne/AtomicMotion

##### Tween Chain
https://github.com/doubleduck/TweenChain
##### Tween Cube
##### TweenX 

### Frame-by-Frame Animation



[ ([]())]():
## Audio
### Synthesis
[Mofl ([Brad Harms](https://github.com/bradharms))](https://github.com/bradharms/mofl): Library for realtime music synthesis using Haxe and OpenFL.


## Bug Report
## Coding 
## Compiling 
## Controls
[Gamepad Haxe ([Adam Harte](http://www.adamharte.com/))](https://github.com/AdamHarte/Gamepad-Haxe):
[ ([]())]():
## Debug

[Game Console ([TiagoLr](https://github.com/ProG4mr))](https://github.com/ProG4mr/gameconsole)

## Text

[ ([]())]():


### Fonts
#### Bitmap Fonts
#### TTF 
### 

### Localization
[ ([]())]():CastleDB
[FireTongue ([Lars Doucet](http://www.fortressofdoors.com/))](https://github.com/larsiusprime/firetongue):

## Formats 
### GIF
[Haxe Gif ([]())](https://github.com/fbricker/haxe-gif)
### PSD (Photoshop)
[Haxe PSD Parser ([Ed Ryzhov](https://plus.google.com/113967380781631212562/posts))](https://github.com/ryzed/haxe-psd-parser)
### MD (Markdown)
[ ([]())](https://github.com/dpeek/haxe-markdown):

### SVG
[ ([]())]():
### XML
[ ([]())]():https://github.com/TomByrne/xml-tools

[ ([]())]():
## FX
## Levels
### Isometric 
[Openfl Isolib ([]())](https://github.com/ianharrigan/openflisolib): an haxe port of AS3isolib.

### Auto Generation
[ ([]())]()https://github.com/lordkryss/tilemapgen:
[ ([]())](https://github.com/julsam/dungeon-builder):It's an Haxe port of the Dungeon builder written in python by Steve Wallace. It builds a dungeon procedurally generated with rooms, corridors, and doors. 

### Editors
[OpenFL Tiled Flixel ([Christopher Kaster](http://kasoki.de/))](https://github.com/kasoki/openfl-tiled-flixel) (HaxeFlixel):Experimental glue to use openfl-tiled with HaxeFlixel.

[OpenFL Tiled([Christopher Kaster](http://kasoki.de/))](https://github.com/kasoki/openfl-tiled):openfl-tiled is a library, which gives openfl developers the ability to use the TILED Map Editor.

[ ([]())]():

[Haxe GLEED2D ([Pekka Heikkinen](https://github.com/volvis))]():https://github.com/volvis/Haxe-GLEED2D

[ ([]())]():

## Lighting
### Geometry Based
[HxDynaLight ([PSvils](https://github.com/PDeveloper))](https://github.com/PDeveloper/hxDynaLight):A geometry based dynamic lighting engine.

### Bitmaps Based

### Shaders Based

## Network
### Multiplayer 
[socket.io-openfl-client ([Dmitriy Kapustin](gemioli.com))](https://github.com/dimanux/socket.io-openfl-client): Socket.io OpenFL client extension. Tested with HaXe 3.x, OpenFL 1.3.0, nodejs 0.10.26 (or dotcloud) on platforms: Flash 11, HTML5, Windows, Android, iOS, Blackberry (not tested).

[HaxeNet ([ohmnivore](ohmnivore.elementfx.com/))](https://github.com/Ohmnivore/HaxeNet): Haxe bindings for ENet, a UDP implementation written in C. With these wrappers, you should be able to release online multiplayer games for Haxe's C++ target.

### XMPP
### JSON-RPC 
[ ([]())](https://github.com/druppy/jsonhx)(JS, Flash?): Haxe lib to handle JsonRPC, and handling calles async using promhx. I try to use this for the structure of the SMD file.

[ ([]())]()
## Particles

## Physics
### Collisions
[HxCollision([Sven Bergström](http://underscorediscovery.com/))](https://github.com/underscorediscovery/hxcollision): This is a port of Separating Axis Theorem, for collision detection between shapes. Supports polygons and circles, currently. Includes a simple drawing interface for debugging shapes COLLISION ONLY. No physics here. By design :)
### Nape
Andrey Pissantchev https://github.com/andrey-p
https://github.com/andrey-p/nape-physics-editor


[ ([]())]():
## Resolution
[ ([]())]():

## Script
[ ([]())]():

## Security
### Encode-Decode
### Assets Embeding
https://github.com/ProG4mr/EmbedAssets

## Spritesheets
### Packing
Jarkko Syrjälä https://github.com/jarkkosyrjala https://github.com/jarkkosyrjala/RectanglePacking.hx: OpenFL porf of ActionScript3 utility class to pack smaller rectangles within larger container rectangle efficiently by Ville Koskela.

## Storage
[ ([]())]():
### Loaders
[AkaLoader ([Onat Bas](https://github.com/onatbas))](https://github.com/onatbas/AkaLoader)(OpenFL): This library contains some useful classes - for handling external assets. It's designed for: 
- Loading Assets without using openfl.Assets class. This allows you to use assets without embedding them.
- Use external assets from web or local storage.
- Downloading/Saving assets from web.
- Reusing assets from pre-downloaded content without needing to connect to internet.
- Cross-Platform asset management system with very simple load/unload calls.
- Simplified, id based, delivering of assets.


[ ([]())]():

### Saves


## UI
There are many different attempts to create a proper UI support for Haxe. HaxeFlixel have its own such UI implementation which works well, but that should not stop you from locating different libraries that may better suit your needs:
### [StableX UI ([Alexander Kuzmenko](https://github.com/RealyUniqueName))](https://github.com/RealyUniqueName/StablexUI):
### [Haxe UI ([Ian Harrigan](https://github.com/ianharrigan))](http://haxeui.org/):
### [Guise ([TomByrne](http://www.tbyrne.org/))](https://github.com/TomByrne/Guise):

## Update And Deployment
[ ([]())]():

## Video
[Jaris Player ([Jefferson González](https://github.com/jgmdev))](https://github.com/jegoyalu/jarisplayer):
Jaris is a video (FLV, MP4) and audio (MP3) player developed in Haxe that can be used freely on any site.


# Haxe Game Engines (other than HaxeFlixel)
## HaxPunk
[ ([]())]():
## Milkshake
(https://github.com/Milkshake-Inc/Milkshake)
## Sexual Engine 
https://github.com/seleb/SexualTengine
[ ([]())]():
#HaxeFlixel unoffical addons
https://github.com/madhoe/flixel-plus: flixel-plus is a library that contains additional classes for HaxeFlixel. The core class, FlxPlus, contains simple, helper functions to make life easier.

# HaxeFlixel/OpenFL/Haxe Games' Sources
There is a growing number of free games sources written with HaxeFlixel/OpenFL/Haxe available online for you to learn from. So far no one has made a proper list of them, so, let us change that shall we? There is one big caveat though: the vast majority of such games is outdated, so there's a good chance you will not be able to run it right out the box. However, that's really O.K because tinkering with the code is what makes you learn, eventually. 

## Androgynous Humanoid Murder Mansion (HaxeFlixel)
[ ([a merry bunch of people]())](https://github.com/seleb/GameJam2014-AndrogynousHumanoidMurderMansion):
## Barricade
[ ([]())](https://github.com/AdamHarte/Barricade):




## Conquering Curiosity (HaxeFlixel)
[Concquering Curiousity ([Tim I Hely with a bunch of people](http://www.tims-world.com/))](https://github.com/SeiferTim/ConqueringCuriosity): You are Dr Henry Jekyll - and someone has broken into your laboratory and stolen your secret serum! Now the whole town is in chaos as violent animals, doused in the dangerous potion, are out to get you. You must switch to and from your alter-ego, the dangerous, ill-hearted Mr Hyde to find clues and apprehend the villain!

## Falling  
## Flappybalt (HaxeFlixel)

## Flappy Bird Haxe (HaxeFlixel)
[FlappyBirdHaxe ([Denis Sheremetov](https://github.com/mrjazz))](https://github.com/mrjazz/FlappyBirdHaxe) (HaxeFlixel): FlappyBird game implemented with HaxeFlixel.

## Fluyo
[ ([]())]():

## FlxMine (HaxeFlixel)
[FlxMine ([Benjamin Sinkula](http://gamejolt.com/profile/bsinky/21178/))](https://github.com/bsinky/FlxMine) (HaxeFlixel): This is a simple Minesweeper clone in Haxe, using the library HaxeFlixel.


## Gourdgeous
## HaxeFlixel GUM (HaxeFlixel)
https://github.com/SeiferTim/HaxeFlixel-GUM

## Haxe Boat (HaxeFlixel)
[HaxeBoat ([Vinícius K. Daros](http://uspgamedev.org/))](https://github.com/vkdaros/HaxeBoat) (HaxeFlixel):Boat vs Submarines game implemented in HaxeFlixel.

## Haxe Platformer

[ ([]())]():
## HaXe Runner
[HaXeRunner ([William Thompson](https://github.com/williamthompsonj))](https://github.com/williamthompsonj/HaXeRunner) (HaxeFlixel): An infinite runner in HaXeFlixel. Originally designed as a tutorial on how to make an infinite runner using HaXeFlixel, this project grew beyond it's original scope. It was used as an entry in the first every Procedural Death Jam put on by OpenGameArt.org on 16 March 2014. Special thanks to my wife and 3-year-old son for play testing the hell out of it and laughing the whole time.

## Haxe Endless Runner
[Haxe Endless Runner ([Jonathan A Dunlap](http://effectivestack.org/))](https://github.com/jadbox/Haxe-Endless-Runner-Game):

## Isometric Game (HaxeFlixel) (OLD)
[Isometric Game([J. Brown](https://github.com/DrMelon))](https://github.com/DrMelon/IsometricGame) (HaxeFlixel): An isometric game thingo! the IsoTilemap.hx is made out of FlxSprites with a z-Ordering. 

## The Lone Tower
## Mega Haxe (HaxeFlixel)
[MegaHaxe ([Florian DORMONT](http://retro-actif.blogspot.com/))](https://github.com/Eiyeron/MegaHaxe) (HaxeFlixel): Megaman prototype + Haxe + Flixel. Just a prototype at the moment, don't expect a finished game.

## Memory Game
[Memory Game ([Alexey Oleynick](https://github.com/AlexeyOleynick))](https://github.com/AlexeyOleynick/MemoryGame): 

## Moon War
## Muton
## Out of Orbit
[ ([]())]():
## Pang Revenge
## Polaterian Ninja X
## Pole Vaultage
## Simple Platformer (HaxeFlixel)
[Simple Platfomer ([Benjamin Sinkula](http://gamejolt.com/profile/bsinky/21178/))](https://github.com/bsinky/platformer):A very basic platformer, written in Haxe using HaxeFlixel. Lots of room for improvement, to be sure, but there's a good foundation here.
## Scourge
###[Scourage Location](https://github.com/Rezmason/Scourge)
### Description
[ ([]())]():


## Super Awesome Game
## Sweat Marathon
[ ([]())]()
## Tea Time!
[ ([]())]():

## TileMap Platformer (HaxeFlixel) (OLD)
[TileMapPlatformer ([J. Brown](https://github.com/DrMelon))](https://github.com/DrMelon/TileMapPlatformer) (HaxeFlixel): No descripition. There are some useful classes though: BinEnemy.hx, MoolahGenerator.hx, HUD.hx,  

[ ([]())]():

## Toast Tapper (HaxeFlixel) (OLD)
[ToastTapper ([J. Brown](https://github.com/DrMelon))](https://github.com/DrMelon/ToastTapper) (HaxeFlixel): It's like Cookie Clicker. But in Haxe, using HaxeFlixel, and targeted for Android.

[ ([]())]():
[ ([]())]():
# Software
## Flash Pro 
[Flash to Haxe Converter ([Dango Itimi](https://github.com/siratama))](https://github.com/siratama/Flash-To-Haxe-Converter): 

https://github.com/imcj/haxecs: 

## HIDE

[ ([]())]():

# The Great Halls of Extension Members (WIP!):
- [Johann Martinache ```with``` [HyperFiction](https://github.com/hyperfiction)](https://github.com/shoebox)
- [Sergey Miryanov](https://github.com/sergey-miryanov)
- [Emiliano Angelini](https://github.com/emibap)
- [Anthony Prestia](http://anthonyprestia.com/)


[ ([]())]():
[ ([]())]():
[ ([]())]():
[ ([]())](): 
[ ([]())]():
[ ([]())]():
[ ([]())]():
[ ([]())]():



# Flixel's Potential Addons
## HaxeFlixel Unofficial Libraries and Classes 
### Libraries
[Flixel-Rpg ([Kevin Resol](https://github.com/kevinresol))](https://github.com/kevinresol/flixel-rpg): an RPG framework based on HaxeFlixel, including a set of essential components to build an RPG such as:
- Item/inventory/equipment system
- Trade system
- AI system
- Stats (attributes) system
- Dialog system
and more (maybe multiplayer in the future).

[HaxeFlixel Godot Parser([Pekka Heikkinen](https://github.com/volvis))](https://github.com/volvis/HaxeFlixel-Godot_Parser): Experimental tools for reading Godot scenes into HaxeFlixel.HaxeFlixel lacks a common IDE for managing objects. Godot, while a fully functional game engine, is at the time of writing still in its infancy. However the IDE offers plenty of attractive tools for content authoring. The idea here is to read in Godot scene files, which can be saved as plain text XML, and recreate the Node2D items in HaxeFlixel.


### Classes
[Flixel-Wrapper ([Kevin Resol](https://github.com/kevinresol))](https://github.com/kevinresol/flixel-wrapper): a simple game wrapper for HaxeFlixel. Contains: 
- ** FlxStateManager.hx **: new, add, switchTo.
- ** FlxTypedStateManager.hx **: new, add, aswitchTo.
- ** IFlxHighScore.hx **: Initial Commit.

[Flixel-Plus ([Malody Hoe](https://twitter.com/maddhoexD))](https://github.com/madhoe/flixel-plus): Flixel-plus is a library that contains additional classes for HaxeFlixel. The core class, FlxPlus, contains simple, helper functions to make life easier. Contains:
- ** FlxPlus.hx**: A static class that contains misc functions: getMusicTime, playPersistingSound,tempChangeTimeScale, sleep, quit, remapValue. 
- ** FlxFadingEmitter.hx **: A FlxEmitterExt that fades out old particles. For now, only works on particles that live forever.
- ** FlxTouchFix.hx **: A plugin class to fix the one-touch-behind bug caused by lime/openfl update.
- ** RatioStageSizeScaleMode.hx **: A ScaleMode that resizes the stage to the window's size,but keeps aspect ratio.Essentially a combination of RatioScaleMode and StageSizeScaleMode.
- ** FlxSplashPlus.hx **: A FlxSplash that fixes centering of logo on mobile, and also includes a handy initDefaults.
- ** FlxRandomStack.hx **: An object that simulates a random stack/bag of values.

flixel-plugins


[Haxeflixel My-Addons ([l0rb](https://github.com/l0rb))](https://github.com/l0rb/haxeflixel-my-addons): some self coded addons for haxeflixel that I use. Contains: MyMute.hx, MyText.hx, MyButton.hx (fixed FlxButtonPlus), MyMessage.hx (A useful text-state), MyPause.hx (A pause button and a sub-state), MySpeed.hx (A button to change game's speed). 


[Minimal game structures using HaxeFlixel ([Vinícius K. Daros] (http://uspgamedev.org))](https://github.com/uspgamedev/haxeflixel): Minimal game structures using HaxeFlixel. Contains:
- Example 01: Explosion.hx, LoseState.hx, PreLoader.hx, Sprite.hx (+anchor), State.hx + StateManager.hx (html5 fix), WinState.hx 
- Example 02: Button.hx.  


## AS3 classes to port

[FlxAchievementSystem ([Tal Datner](http://www.chameneon.com/))](https://github.com/Tal3D/FlxAchievementSystem)(AS3):The FlxAchievementSystem is a class built on Flixel that handles global achievements for individual games. It utilizes flash's shared object (or FlxSave) to save achievement progress.



## HaxeFlixel Templates
There is a great number of repeating game related Classes that every game needs, but right now you need to create from scratch if you use HaxeFlixel, a practice that is not very useful or efficient. This list represent some of them, so in the future these classes can become a part of HaxeFlixel through a templates folder.     
### GUI

