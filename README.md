# Minecraft Mapping and Coding

## Workshop Description
The gamification of products and services is serious business these days. Learn how to create a custom adventure map in Minecraft that could make learning feel more like a game than a chore. In this workshop, you will explore WorldPainter to create your own custom map. Then, you will learn the fundamentals of using command blocks and code to bring your map to life.

## Creating a World
- Minecraft
  - Set mode to Adventure Mode and cheats to on
- World Painter (http://www.worldpainter.net/)
  - Make sure that cheats are on and the mode is Adventure Mode

## Populating the World
- Entities
  - Use all of your normal Minecraft skills to build a compelling world to explore
- Command Blocks
  - Command blocks should be used for all sorts of systems in your game, from quests to dialogue to scene-setting
  - Keep some sort of text editor open so that you can make commands outside of the limiting Minecraft interface and simply copy them in
- Important Command Block Commands
  - Repeater top block `/fill ~ ~-1 ~ ~ ~-1 ~ redstone_block`
  - Repeater bottom block `/fill ~ ~1 ~ ~ ~1 ~ air`
  - Test for area `/testfor @a[<x>,<y>,<z>,<radius>]`
  - Say something in chat `/tellraw @a {text:<text>}`
  - Command blocks do not speak `/gamerule commandBlockOutput false`

## Quests
- Quest Books
  - Creating and Giving a book `/give @p written_book 1 0 {    title:"<Book Title>",    author:"Quests",    pages:["[Page 1 text]",        "[Page 2 text]","[Page 3 text]","[Etc.]"]}`
  - Clearing all books `/clear @a written_book 0 100 {author:Quests}`
- Background Commands

## Recommended Tools & Resources
### Tools
- MCedit world editor - http://www.mcedit.net/ (PC only)
- World Painter - http://www.worldpainter.net/ (open source)
- Newgrounds - Skincraft - http://www.newgrounds.com/portal/view/571250 (web-based)
- Custom NPCs - http://www.minecraftmods.com/custom-npcs/ (install)
- Tinkercad to create 3D objects for minecraft - https://www.tinkercad.com/ (web)

### Resources
- #wearetherangers - http://wearetherangers.com/wildlife-in-crisis/ (download)
- quest intro with code samples at the end - https://www.youtube.com/watch?v=dSD6imXI6Kg
- Command blocks  - http://minecraft.gamepedia.com/Command_Block
- Setting up dialog - http://www.planetminecraft.com/blog/how-to-create-dialogue-adventure-mapcommand-block-tutorial/
