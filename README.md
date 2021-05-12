# VolumeNormalizer
Suppressing very loud audio whilst making quiet music audible.

# Basic Usage
Alright, so, you want to normalize the volume of a Sound object. Whatever the reason, we're going to start off by getting our module.

### Acquiring the module
You can get the module here on github or on roblox. 

#### Installing via roblox
First, you'll need to own the module. 
Then, you can either require the module by it's AssetId, like so:

```lua
local VolumeNormalizer = require(id)
```

Or insert from the Toolbox.


#### Installing via github

Download the file, and then drag it into studio. 

#### Finishing installation
If you're not requiring the module by ID, then you'll need to require the module manually, like so:
```lua
local VolumeNormalizer = require(--[[ path to module ]])
```

## Usage
So, now that we have our module, we can start using it! Let's start off with a basic example. Say, we have a radio gamepass in our game.
