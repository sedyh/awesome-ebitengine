# <img align="right" width="120px" src="https://user-images.githubusercontent.com/19890545/150690287-d7a7a4c0-ce89-4c49-8043-5af0348e615e.png" alt="awesome-ebitengine" title="awesome-ebitengine" /> Awesome Ebitengine

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome Ebitengine frameworks, libraries and software 

[Ebitengine](https://github.com/hajimehoshi/ebiten) is an open source game library for the Go programming language. Ebitengine's simple API allows you to quickly and easily develop 2D games that can be deployed across multiple platforms. Ebitengine is made by [Hajime Hoshi](https://github.com/hajimehoshi).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/sedyh/awesome-ebiten/blob/main/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/sedyh/awesome-ebiten/graphs/contributors); you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!

### Wiki

Please visit our [wiki](../../wiki) for a curated list of the helpful articles and best practices about Ebitengine.

If you have a great article or tutorial, please submit it through issues.


### Contents

- [Frameworks](#frameworks)
- [GUI](#gui)
- [Graphics](#graphics)
- [Physics](#physics)
- [World](#world)
- [Integration](#integration)
- [Input](#input)
- [Games](#games)
- [Demoscenes](#demoscenes)
- [Applications](#applications)

### Frameworks

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Various architectural patterns and approaches to game design*

* [gohan](https://code.rocketnine.space/tslocum/gohan) - Entity Component System framework for Ebitengine.
* [donburi](https://github.com/yohamta/donburi) - Just another Entity Component System library for Ebitengine.
* [mizu](https://github.com/sedyh/mizu) - Entity Component System framework for Ebitengine.
* [goecsengine](https://github.com/x-hgg-x/goecsengine) - A simple game engine using Ebitengine with ECS. 
* [pgfsm](https://github.com/PenguinCabinet/pgfsm) - A state and stack machine framework for Ebitengine.

### GUI

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Libraries for building GUI Applications*

* [ebitenui](https://github.com/ebitenui/ebitenui) - A user interface engine and widget library for Ebitengine.
* [ebiten-imgui](https://github.com/gabstv/ebiten-imgui) - Dear ImGui renderer for Ebitengine.
* [furex](https://github.com/yohamta/furex) - A simple UI framework with a subset of flexbox layout specification.
* [messeji](https://code.rocketnine.space/tslocum/messeji) - Text input and display widgets for Ebitengine.

### Graphics

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Useful libraries for graphics*

* [tetra3d](https://github.com/SolarLune/Tetra3d) - A 3D software renderer written in Go by means of Ebitengine, primarily for video games.
* [etxt](https://github.com/tinne26/etxt) - A library for font management and text rendering in Ebitengine.
* [canvas](https://github.com/eihigh/canvas) - Cairo in Go for Ebitengine.
* [colorgrad](https://github.com/mazznoer/colorgrad) - Go color scales library for data visualization, charts, games, maps, generative art and others.
* [raycaster-go](https://github.com/harbdog/raycaster-go) - Golang raycaster engine using the Ebitengine 2D Game Library.
* [goaseprite](https://github.com/SolarLune/goaseprite) - A JSON loader for Aseprite files for Golang.
* [gween](https://github.com/SolarLune/gween) - A small library to perform tweening in Go.
* [ganim8](https://github.com/yohamta/ganim8) - An animation library for Ebitengine inspired by [anim8](https://github.com/kikito/anim8).
* [reisen](https://github.com/zergon321/reisen) - A simple library to extract video and audio frames from media containers (based on libav).

### Physics

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Useful libraries for physics*

* [cp](https://github.com/jakecoffman/cp) - A 2D rigid body physics library - Chipmunk2D, ported to Go.
* [resolv](https://github.com/SolarLune/resolv) - 2D collision detection and resolution library.

### World

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Interaction with the game world*

* [ebiten-camera](https://github.com/scarycoffee/ebiten-camera) - A simple camera implementation based on vrld's HUMP for Love2d.
* [dngn](https://github.com/SolarLune/dngn) - A golang library specifically created to help make generating random maps easier.
* [paths](https://github.com/SolarLune/paths) - A pathfinding library written in Golang created mainly for video games.
* [go-astar](https://github.com/beefsack/go-astar) - A* pathfinding implementation for Go.
* [megophone](https://github.com/seedco/megophone) - The Double-Metaphone algorithm in Go.

### Integration

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Integration with other programs*

* [ldtkgo](https://github.com/SolarLune/ldtkgo) - LDtk-Go is a loader for "Level Designer Toolkit" projects written in pure Go.
* [go-tiled](https://github.com/lafriks/go-tiled) - Go library to parse Tiled map editor file format (TMX) and render map to image.
* [ebitengine-discord-rpc](https://github.com/EldersJavas/ebitengine-discord-rpc) - Discord Rich Presence for Ebitengine.

### Input

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Input and output across platforms*

* [ebitengine-input](https://github.com/quasilyte/ebitengine-input) - A Godot-inspired action input handling system for Ebitengine.
* [clipboard](https://github.com/golang-design/clipboard) - Cross platform (MacOS/Linux/Windows/Android/iOS) clipboard package in Go.
* [kibodo](https://code.rocketnine.space/tslocum/kibodo) - On-screen keyboard widget for Ebitengine.

### Games

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Games and emulators written in Ebiten*

* [aaaaxy](https://github.com/divVerent/aaaaxy) - A nonlinear 2D puzzle platformer taking place in non-Euclidean geometry.
* [bindless](https://github.com/tinne26/bindless) - Puzzles in a magnetic world for Ebitengine's first game jam (2022).
* [mag](https://github.com/kettek/ebijam22) - Defend the embryonic core from the onslaught of magnetic robottos.
* [attraction](https://github.com/jcgraybill/attraction) - A sokoban-like puzzle game, where you move magnetic pieces in order to collect gems within a limited number of moves.
* [worldwide](https://github.com/pokemium/worldwide) - A toy GameBoy Color emulator written in golang.
* [gosol](https://github.com/oddstream/gosol) - Polymorphic solitaire engine in Go+Ebitengine.
* [feta-feles-remastered](https://github.com/TheTophatDemon/Feta-Feles-Remastered) - An eerie bullet hell shooter, featuring a small story based around your "pet cat".
* [godanmaku](https://github.com/yohamta/godanmaku) - Simple shooting game using Ebitengine and Golang.
* [monovania](https://code.rocketnine.space/tslocum/monovania) - Metroidvania game.
* [brownboxbatman](https://code.rocketnine.space/tslocum/brownboxbatman) - A bullet hell video game.
* [citylimits](https://code.rocketnine.space/tslocum/citylimits) - A city-building simulation video game.
* [skulls](https://github.com/rootVIII/skulls) - A simple columns-like strategy game developed in Golang with the Ebitengine library (for Android).
* [go-inovation](https://github.com/hajimehoshi/go-inovation) - Port of "INO VATION! 2007". You are a wild boar. Collect the three sacred treasures!
* [ebiten-breakout](https://github.com/eliasdaler/ebiten_breakout) - A simple breakout game made in Ebitengine.
* [minesweeper-go](https://github.com/mevdschee/minesweeper.go) - Minesweeper game in Go that can compile to WASM (uses Ebitengine v2).
* [travel-game](https://github.com/danicat/travel-game) - A remake of an 80's card game classic "Around the World" (pt-br: "Volta ao Mundo").
* [lost-the-plot](https://github.com/TheMightyGit/losttheplot-ggj21) - Twitchty action gun-play of "Guess Who?" combined with the casual of "Tomb Raider".
* [btod](https://github.com/Zyko0/GameOff2021) - This is a runner game made in Go with Ebitengine.
* [carotid-artillery](https://code.rocketnine.space/tslocum/carotidartillery) - A top-down twin-stick shooter.
* [cr1ckt](https://github.com/sinisterstuf/cr1ckt) - Tap left and right to jump through the caves to the fruit... as long as the game.
* [go-space-crane](https://github.com/spiritofsim/go-space-crane) - Simple moonlander like game with some new mechanics.
* [kuronan-dash](https://github.com/kemokemo/kuronan-dash) - Doujin game "Kuronan Dash" from the comic "Nekomusume Doujinshi".
* [sokoban-go](https://github.com/x-hgg-x/sokoban-go) - Sokoban game in Go using Ebitengine game engine with ECS.
* [arkanoid-go](https://github.com/x-hgg-x/arkanoid-go) - Arkanoid game in Go using Ebitengine game engine with ECS.
* [space-invaders-go](https://github.com/x-hgg-x/space-invaders-go) - Space invaders game in Go using Ebitengine game engine with ECS.
* [fishfightback](https://code.rocketnine.space/tslocum/fishfightback) - A side-scrolling bullet hell video game.
* [gtris](https://github.com/luisparravicini/gtris) - A Tetris clone.
* [open-diablo-2](https://github.com/OpenDiablo2/OpenDiablo2) - An ARPG game engine in the same vein of the 2000's games, and supports playing Diablo 2.

### Demoscenes

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Demoscenes and simulations written in Ebitengine*

* [ray-engine](https://github.com/Myu-Unix/ray_engine) - A toy raycasting engine built with Go + Ebitengine v2 2D library.
* [protozoa](https://github.com/Zebbeni/protozoa) - A simulation of protozoan behavior and evolution. 
* [biogo](https://github.com/alexanderscrimgeour/biogo) - A simple genetic simulator written in Go.
* [fire](https://github.com/dim13/fire) - Experiments with Ebitengine - Doomfire.


### Applications

<a href="#contents"><img src="https://user-images.githubusercontent.com/19890545/150034365-6561ab71-5cb4-466f-996c-ae4204ef7c12.png" alt="back" title="back" width="16px"/></a> *Other useful programs that use or are made for Ebiten*

* [darktile](https://github.com/liamg/darktile) - A GPU rendered terminal emulator designed for tiling window managers.
* [screenpos](https://github.com/barjoio/screenpos) - A simple way to get a position on your screen using your keyboard and the visual aid of a grid.
* [wasmserve](https://github.com/hajimehoshi/wasmserve) - An HTTP server for Wasm testing like gopherjs serve.
* [ebiten-bunny-mark](https://github.com/sedyh/ebiten-bunny-mark) - An implementation of the popular graphics benchmark written on Ebitengine.
* [neko](https://github.com/crgimenes/neko) - Neko is a cross-platform open-source animated cursor-chasing cat.
* [sketchy](https://github.com/aldernero/sketchy) - A framework for creating generative art in Go.
