## Commands
The bot uses these commands in the chat for doing certain actions. They are also fed into the language model for training it. 
Put these commands (just one per message!) in the example conversations in the bot profile, so that the bot uses them in it's LLM during message generation and therefore becomes literally alive.

 - `!attack(mob)` - Attacks a specified mob (`mob`)
 - `!attack(player)` - Attacks a specified player (`player`)
 - `!clearFurnace` - Clears the furnace
 - `!collectAllBlocks(block)` - Collect all specified blocks nearby (`block`)
 - `!collectBlocks(block, num)` - Collect certain amount (`num`) of specified blocks (`block`).

- - Note: The bot equips appropriate tools to collect the blocks, for example it won't be able to mine stone if they don't have a pickaxe, or won't be able to mine iron ore if they don't have at least stone pickaxe.
 - `!consume(item)` - Eat or drink an `item`
 - `!сraftable` - Check craftable items.
 - `!craftRecipe(item,num)` - Craft a specified item (`item`) of a specified amount (`num`).
 - - Note: The bot will use the crafting table nearby if necessary (crafting table have a 3x3 crafting grid, while without crafting table the crafting grid is just 2x2)
 - `!discard(item,num)` - Throw a specified amount (`num`) of items (`item`) away.
 - `!endGoal` - End the ongoing goal of the bot and stops self-prompting.
 - `!entities` - Shows the mobs and players nearby.
 - `!equip(item)` - Equip a specified item (`item`)
 - `!followPlayer(player,num)` - Follow a player (`player`) at the specified distance (`num`).


 - `!givePlayer(name,item,num)` - Give a specified player (`name`) a specified item (`item`) in a certain quantity (`num`)
 - `!goal(goal)` - Sets a goal for the bot, activates self-prompting loop.
 - `!goToBed` - Automatically finds a bed and uses it to sleep.
 - `!goToPlace(name)` - Go to the specified place (`name`)
 - `!goToPlayer(name,distance)` - Go to the specified player (`player`) at the specified distance (`distance`) in blocks away from him.

 - `!inventory` - Check the inventory. Shows items in the inventory.

 - `!modes` - Lists bot modes.
 - `!moveAway(num)` - Step away from the mob or player or place on certain amount (num) of blocks.

 - `!nearbyBlocks` - Check blocks in the vicinity of the bot.
 - `!newAction(name)` - Sets up a new action named `name` for generating the code.

 - `!placeHere(block)` - Place a block (`block`) near the bot himself.
 - `!putInChest(item,num)` - Put a certain item (`item`) in a certain quantity (`num`) in the nearby chest.

 - `!rememberHere(name)` - Save the location and name it `name`.

 - `!savedPlaces` - Places recognized by the bot.
 - `!setMode(mode,bool)` - Sets (`bool`) a certain mode (`mod`) on (`true`) or off (`false`)
 - `!smeltItem(item,num)` - Smelt/cook an item (`item`) in a certain quantity (`num`) in the furnace. Won't work if there's no furnace nearby.
 - `!stats` - 
Status of the player and the game state (location, health, hunger, time of the day and weather)
 - `!stay(time)` - Stay and wait for a certain amount of time (`time`). Set `time` to -1 to wait forever.



 - `!takeFromChest(item,num)` - Take an item (`item`) in a certain quantity (`num`) from the chest. Won't work if there are no chests.
 - `!viewChest` - Check the items in the chest. Won't work if there are no chests nearby.
