# Crunchy's Useful Electronics & Programming Links & References (CUEPLAR) 
####(Edit date: 20240109 15:58)
<hr /> 

Just a personal list of links to online reference books for current projects. Public because not everybody knows where to find this stuff at the beginning and Google can be no help some days! There's a little order to this list, but it is still very much a "no particular order" kind of beast.

If you find any links have changed, broken or otherwise gone AWOL, open an issue, preferrably with a new link if you can find one.

- ## Electronics
  1. [Electronics Tutorials](https://www.electronics-tutorials.ws/): Great general electronics site.
  2. [Operational Amplifiers and Linear Integrated Circuits - Theory and Application (Fiore)](https://eng.libretexts.org/Bookshelves/Electrical_Engineering/Electronics/Operational_Amplifiers_and_Linear_Integrated_Circuits_-_Theory_and_Application_(Fiore)): A free, open book on Libre Texts on all matters of operational amplifier design

- ## Programming
  - ### Javascript
    1. [Eloquent Javascript](https://eloquentjavascript.net/): Javascript breaks my brain like C/C++ never did, but I work through this a bit at a time. Maybe one day I'll be able to JS the shit out of things.
  - ### Arduino
    1. [Arduino Reference](https://www.arduino.cc/reference/en/): The go-to source for Arduino flavoured C
    2. [Adafruit Learning System](https://learn.adafruit.com/): I don't yet Python, but I'm maintaining this info-repo for everybody, and maybe, one day I might have a project where I'll need this. Adafruit are awesome!
    3. PlatformIO Docs](https://docs.platformio.org/en/latest/): Still coding in ArduinoIDE? Level up, dudes!
    4. [Wokwi](https://wokwi.com/): Emulate your sketchs and simulate their supporting circuits without ever breaking out a breadboard or steaming up a soldering iron! It doesn't do everything, but it's not bad for a free app. It has a subscription layer, too, with a few more features. Even supports officially supported Arduino libraries and has a growing range of microcontroller sims. Runs in the browser and in VS Code as an extension.
    5. [Using ATmega 328p chips standalone from UNO board](https://wolles-elektronikkiste.de/en/using-the-atmega328p-standalone)<br />
        a. [And my PlatformIO template for standalone 328P chips using an UNO as an ISP](https://github.com/crunchysteve/Standalone328PU)
  - ### C++
    1. [Learn C++ in 31 Hours (FreeCodeCamp)](https://www.youtube.com/watch?v=8jLOx1hD3_o): I've been doing this over January, to elevate my Arduino C to more general C++
    2. [wxWidgets](https://siytek.com/macos-gui-cpp/#:~:text=%E2%80%93-,https%3A//www.wxwidgets.org/,-So%E2%80%A6%20how) is a phenomenal C++, x-platform, GUI, application framework
       that allows you to code a gui app in the commandline, write once, run on many. They're now even working on Android and iOS frameworks. You can literally take their demo
       app, add interface widgets as per the documentation, add your own C++ functional code to run when fields are filled and buttons are pressed, then compile it for Windows, Mac
       and Linux, on your choice of platform. My Mac can build for Windows and Linux, as well as for Mac. Your PC can build for Mac and Linix as well as for Windows. (eg: I'm a
       bicycle nut, I literally have plans for yet another bicycle gearing calculator.)
    [](3.)

- ## General Pages and Apps
  1.  [Joplin Notes](https://joplinapp.org/): Probably the BEST and totally FOSS note-keeping app I have ever found. Evernote users feel right at home here, blows Apple Notes out of the freakin' water. I wish I'd had this in high school 45 years ago! I'd have gotten that programming degree and had my own startup. (I'm ND and this has made my life less chaotic!)
  2.  [PlatformIO](https://platformio.org/): Still coding in ArduinoIDE? Level up, dudes! Seriously!  Do I have to nag?

- ## Ideas & Weird Sh**
  1.  I write often about how the internet needs to be truly peer-to-peer at the user level. I think about it a LOT, in fact. Obsessively, according to my wife and friends. It has recently occurred to me that by mashing together wikipedia and github, using github as the CRDT, offline-first database infrastructure, as well as for version control, every human can have a profile, humans can connect directly with humans, every human can have an "opinion" but the opinions based on data or expertise will post with more weight and upvotes from experts in the field will have more weight, such that truth will float. Read this article for the details...
      https://www.shinyhappyrainbows.com/2024/01/p2p-standards-there-are-many-therefore.html
  And this article has the backend basics
      https://betterprogramming.pub/how-to-use-git-as-an-offline-first-database-dca7f9604142
      The great thing about git as a peer to peer backend is that you have version control and traceability on any post. Proof-of-work is inherently built-in and more compact than, say Ethereum. You only have the snapshots of the posts you're reading or maintaining, not an entire, global blockchain. A user frontend could have a setting to limit the number of vesions retrieved, or edits by specific people. Enourmous space savings. You don't need to hold the whole sky, just what is relevant.

<hr />
There is more to come. This is going to take a while to build, lots of web crawling, lots of organising my Joplin notes. If you have any sites you'd like for consideration in this list, open an issue with the link in the body and your idea of which section you'd like it included in.
