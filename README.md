[Live Demo](https://magnusware.vercel.app/index.html)

Partial credit goes to the [original source](https://github.com/stefanhaustein/quake2-playn-port) creators.

Welcome to the worlds first FULL VERSION of Quake II running on the web! This, unlike every other port, runs the PC files, and isn't an emulation of Quake II for the N64. This PROJECT is STRICTLY for educational purposes. I left my goofy Xbox name in the repo title to make this more difficult to find.

This project was first started by Stefan Haustein and worked for a little while until at some point in time it broke. 

[INITIAL CONTACT](https://groups.google.com/g/quake2-gwt-port/c/bfQMfbMc41k)

February 2021, I fixed the audio, file fetching, and zip API. After I'd made those changes, I wasn't able to figure out how to make a full port. 12/21/2022 @ 12pm I had an itch. Ended up going down a rabbit hole of outdated software to simply get the files in order. Finally got it to run and have been "perfecting" it since.

**MUST I RESTATE THIS AGAIN, THIS PROJECT IS FOR EDUCATIONAL PURPOSES ONLY!**

Big changes made:
- Created ```E635C924D74AFB6527B814C542FC5B1C.cache.html```
- Created ```PlayNQuake.nocache.js```
- Created ```PlayNQuake.js``` (correcting audio issues, setting initial spawn map, enabling save and load states, etc.)
- Reformatted ```index.html```
- Changed game from ```.EXE``` to ```.ZIP```
  - Compresses better, runs faster, don't need 20+ year old software
- Added Quake 2 game assets.
- Edited config file to better suit web app usage

*Here are some other things I would like to add to this project (whenever i can find time🗿):*
- [ ] Fix lighting
- [ ] Add ```.pak1``` & ```.pak2```
- [ ] Multiplayer support
- [ ] Migrate from ```FileSystem JS API``` to ```BrowserFS```
