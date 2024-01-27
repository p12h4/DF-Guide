### pre-TU 1.66.0033.0:
- Any crafted oak slabs are petrified oak slabs

- Any item can be placed into the fuel slot of a furnace

- Creating a world will set the "newSeaLevel" tag to 0, meaning that the sea level is Y63 instead of Y62

- Any item that requires support can be placed on top or on the side of a chest. This works by placing the block that requires support against a block, such as glass, that cannot support a block, and do this adjacent to a chest


### TU1:
- By exploding a chest while spam clicking an item inside, there is a chance that item drops a 0 stack item. This item allows for negative item stacks and overstacking, allowing for all items to have a range of -127 to 127 for stack size. 


### TU3:
- Block transmutation can work by updating a budded piston at the same time another piston pushes a block, merging the blocks. This allows for many variations of invalid data value blocks


### TU5:
- Ender Pearls stack up to 64, instead of 16

- Mining stone brick stairs in different orientations drop stone bricks with varying data values, allowing for invalid data value stone bricks 

- Updating the world to this TU will set the "newSeaLevel" tag to 0, meaning that the sea level is Y63 instead of Y62


### TU7:
- Using silk touch on leaves in differing orientations allows for invalid data value leaves


### TU14:
- Added the Trading Mechanic. There are currently five professions of villager, Farmer, Librarian, Priest, Blacksmith, and Butcher, and no careers. Nearly every trade that a villager has in this version will be considered unobtainable in future versions, thus introducing many variants of discontinued villagers

- Silk Touch can be applied to shears in an anvil

- Anvils drop the correct damage value of anvil when mined, meaning a slightly damaged anvil drops a data value 1 anvil and a very damaged anvil drops a data value 2 anvil. In future versions, crafting an anvil will create a data value 2 anvil, and mining any anvil will drop a data value 0 anvil, making data value 1 anvils discontinued

- Currently naming items in an anvil adds only 2 tags, the display name and the repair cost. This differs from named items in future versions, which have both a "createdOnHost" tag and a "createdByRestricted" tag


### TU17:
- By aligning against the side of a vine and placing a ladder inside the vine, the ladder will either become a data value 0 ladder or floating ladder, depending on direction, both of which will be unobtainable in future versions 


### TU19:
- Mobs can now equip armor, including helmets. Skeletons and zombies in the sun will cause the helmet to lose durability, which has a chance of reducing the helmet below 0 into negative durability. These negative durability helmets are not obtainable normally, and are technically unobservable fromr regular helmets. Negative durability helmets can be further combined in a crafting table to go further negative down to -32767

- Firework rockets do not have a flight duration when crafted

- Updating any mobs from earlier versions will cause them to lose the item they are holding, resulting in weaponless skeletons and weaponless zombie pigmen 

- Killing a mob attached to a fence with a lead will leave the lead attached to the fence


### TU25:
- Picking up stacks of doors in the inventory will behave oddly, leaving 1 door left in the inventory slot, and combining the rest of the stack with whatever the stack size is of the currently held item. Using this combining method, the item stack size can be overflowed past 64, allowing for overstacked and understacked items, which can be preserved in the inventory by dropping the stack on the ground and picking it up. The stack can only be stored in the inventory, it cannot be moved to a chest


### TU31:
- Villagers that spawn in this version will have certain trades with a rewardExp value set to 0, meaning these trades do not provide xp


### TU43:
- Mining frosted ice with silk touch drops the frosted ice item


### TU46:
- Crafting bone blocks creates bone blocks with a data value of 4

- Loading a spawner from earlier versions in this version and allowing it to spawn mobs once creates a mob spawner without any block entity data. This mob spawner will render as a pig spawner

- Naming items in an anvil adds only 3 tags, the display name, the repair cost, and a "createdOnHost" tag. This differs from named items in earlier versions, which are missing the "createdOnHost" tag

- Entites updated to this version have the drop chance of their left hand set to 0, even though it is normally 0.85


### TU54:

- Woodland Mansions can generate with spider rooms, which currently contain a spawner without entity data. The spawner will look like a pig spawner and not spawn anything

- Currently armor stands can be named with a nametag. The name does not render, however it does have a custom name


### TU60:
- Ender dragons can ride boats

- Cauldrons emit a signal strength of 6 instead of 3


### TU69:
- By filling up the snow golem spawn cap and then building a snow golem sideways around a piece of bedrock, the snow golem will attempt to spawn, fail, and then drop the bedrock as an item
