#Introduction

<img alt="Screenshot" width="500" src="https://raw.githubusercontent.com/joeedh/gameblendjs/master/screenshot.png">
</img>

GameBlendJS is a WebGL/Babylon.js based game engine.  It 
uses the .blend file format from Blender as it's main file format.  

Since .blend files are structured memory dumps, GameBlendJS 
implements Blender's data structures as JS classes.

BlendJS uses its own class system and supports aspect-oriented
programming, which is more suited for game development (it's
much more powerful than normal mixins).

#Source Locations
1. JavaScript sources are in public/scripts
2. Blender python sources blender/dm

#Status

Still in implementation phase.  Current project
is finishing the logic node system.

#Requirements

1. Node.js
2. NPM

#Installation
Execute `npm update` in command line.

#Starting server
Execure `node bin/www` in command line.  You should see
something like `Starting server on port 3000.`

Then navigate to http://localhost:3000