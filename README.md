# TFC Plus - Bids and Pieces
A plugin for TerrafirmacraftPlus that aims to demonstrate various fully featured enhancements for gameplay and testing.

Please find the latest release at [courseforge](https://www.curseforge.com/minecraft/mc-mods/tfcplus-bids).

### Features
* [Clay and Fire Clay Crucible](../../wiki/Crucible) - new crucibles with improved mechanics
* [Ore Bits](../../wiki/Ore-Bits) - breaking ore chunks into smaller pieces
* [Metal Blowpipe](../../wiki/Metal-Blowpipe) - recipe based glassware crafting
* [Drinking Glass](../../wiki/Drinking-Glass) - various new drinking containers made out of glass
* [Furnace](../../wiki/Furnace) - for making glass in a crucible
* [Mud Brick Chimney](../../wiki/Mud-brick-chimney) - allows furnace construction before acquiring metal tools
* [Ceramic Pipe](../../wiki/Ceramic-Pipe) - used in making a mud brick chimney
* [Ceramic Mug](../../wiki/Clay-Mug) - a drinking container made out of clay
* [Drill](../../wiki/Drill) - a tool for drilling raw stone
* [Quarry](../../wiki/Quarry) - for harvesting Rough Stone block using the drill and wedge method, sedimentary rocks only
* [Rough Stone and Rough Stone Bricks](../../wiki/Rough-Stone) - new building blocks for sedimentary rocks
* [Adze](../../wiki/Adze) - a tool for carving blocks, making rough stone bricks, peeling logs and so on
* [Carving](../../wiki/Carving) - for shaping blocks with an adze, in like manner to TFC detailing with a chisel, and carving recipes
* [Peeled Log](../../wiki/Peeled-Log) - logs that had their bark stripped used to craft log walls
* [Log Walls](../../wiki/Log-Wall) - new building block with 6 variations for log cabin construction
* [Wood Pile](../../wiki/Wood-Pile) - for wood storage and seasoning peeled logs, stick bundles
* [New Firepit](../../wiki/Firepit) - new firepit that can consume custom fuels, requires kindling to light
* [Kindling](../../wiki/Kindling) - kindling for lighting new firepit
* [More Stick Bundles](../../wiki/Stick-Bundle) - small and tied bundles of sticks as fuel in new firepit
* [Bark](../../wiki/Bark) - comes from peeling logs, some can be used to extract tannin, or bast fibers
* [Bark Fiber and Bark Cordage](../../wiki/Bark-Fiber) - make tying material and cordage from bark fiber
* [Drying Rack](../../wiki/Drying-Rack) - for curing bark fibre strips and drying meat, cheese, and seaweed
* [Firewood](../../wiki/Firewood) - fuel for new firepit, needs to be seasoned
* [Chopping Block](../../wiki/Chopping-Block) - for peeling and splitting logs

### Translations

* Chinese by Eternal130 (v0.18.x)

### Compatibility

* Waila - block information for crucible, quarrying, glassmaking, wood pile items, drying rack, etc
* Not Enough Items - recipes for seasoning, quarrying, drying and new firepit fuels

### Compiling

Required libraries to be placed in `libs` folder (or the latest version as available):
```
[1.7.10]TerraFirmaCraftPlus-deobf-0.89.1.jar
Waila-1.5.10_1.7.10.jar
```

Set up your environment as follows:
```
./gradlew setupDevWorkspace
```

Build mod as follows:
```
gradlew build
```

You'll also need to specify `JAVA_HOME` to point your Java 8 JDK installation, for example:
```
set JAVA_HOME=c:\Program Files\Java\jdk1.8.0_202\
```
