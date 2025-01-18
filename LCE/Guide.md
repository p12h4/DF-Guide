### pre-TU 1.66.0033.0:
- Wooden slabs crafted in this version later turn into petrified oak slabs

- Any item can be placed into the fuel slot of a furnace

- Creating a world will set the "newSeaLevel" tag to 0, meaning that the sea level is y level 63 instead of y level 62

- Placing a glass block adjacent to a chest and trying to place a support block onto that glass block will place the support block onto the chest
<br>


### TU1:
- By exploding a chest while spam clicking an item inside, there is a chance that item drops a 0 stack item. This item allows for negative item stacks and overstacking, allowing for all items to have a range of -127 to 127 for stack size
<br>


### TU5:
- Ender Pearls stack up to 64, instead of 16

- Mining stone brick stairs in different orientations drop stone bricks with varying data values, allowing for invalid data value stone bricks 

- Updating the world to this TU will set the "newSeaLevel" tag to 0, meaning that the sea level is Y63 instead of Y62
<br>


### TU7:
- Using silk touch on leaves in differing orientations allows for invalid data value leaves
<br>


### TU14:
- Silk Touch can be applied to shears in an anvil

- Renaming items in an anvil only adds the display name and repair cost tag. In future versions, renaming items would also add a "createdOnHost" tag and a "createdByRestricted" tag
<br>


### TU17:
- By aligning against the side of a vine and placing a ladder inside the vine, the ladder will be floating or invisible with unique properties, depending on direction
<br>


### TU19:
- Skeletons and zombies wearing helmets in the sun will cause the helmet to lose durability, which has a chance of reducing the helmet below 0 into negative durability

- Firework rockets do not have a flight duration when crafted

- Updating any mobs from earlier versions will cause them to lose the item they are holding, resulting in weaponless skeletons and weaponless zombie pigmen 

- Killing a mob attached to a fence with a lead will leave the lead attached to the fence
<br>


### TU25:
- Picking up stacks of doors in the inventory will behave oddly, leaving 1 door left in the inventory slot, and combining the rest of the stack with whatever the stack size is of the currently held item. Using this combining method, the item stack size can be overflowed past 64, allowing for overstacked and understacked items, which can be preserved in the inventory by dropping the stack on the ground and picking it up. The stack can only be stored in the inventory, it cannot be moved to a chest
<br>


### TU31:
- Villagers that spawn in this version will have certain trades with a rewardExp value set to 0, meaning these trades do not provide xp
<br>


### TU43:
- Mining frosted ice with silk touch drops the frosted ice block
<br>


### TU46:
- Crafting bone blocks creates bone blocks with a data value of 4

- Loading a spawner from earlier versions in this version and allowing it to spawn mobs once creates a mob spawner without any block entity data. This mob spawner will render as a pig spawner

- Naming items in an anvil adds only 3 tags, the display name, the repair cost, and a "createdOnHost" tag. In future versions, renaming items would also add a "createdByRestricted" tag

- Entites updated to this version have the drop chance of their left hand set to 0, even though it is normally 0.85
<br>


### TU54:

- Woodland Mansions can generate with spider rooms, which currently contain a spawner without entity data. This mob spawner will render as a pig spawner

- Armor stands can be named with a name tag. The name won't render, however the custom name will be saved
<br>


### TU60:
- Ender dragons can ride boats

- Cauldrons emit a signal strength of 6 instead of 3
<br>


### TU69:
- By filling up the snow golem spawn cap and then building a snow golem sideways next to a piece of bedrock, the snow golem will attempt to spawn, fail, and then drop the bedrock as an item