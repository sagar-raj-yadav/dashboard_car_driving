
Amazon manages a warehouse with sequentially numbered product slots starting from 1. You are given an array inventory[n] where inventorylil is the product ID inc A perfect slot is a slot where the product ID equals its slot number.

You are allowed to perform the following operation any number of times (possibly zero):

Choose any index i, remove the product in the slot

When you remove a product at position i, all products to its right shift one slot to the left.

Determine the maximum number of perfect slots achievable after any number of removals.

Example

n=7

inventory = [1, 3, 2, 5, 4, 5, 3]

Optimal removals: (Assuming 1-based indexing of inventory)

1. Remove inventory[2] = 3 → inventory = [1,2,5,4,5.3

2. Remove inventory[6] = 3→ inventory = [1.2.5.4.5]

Perfect slots in final inventory:

inventory[1]= 1, inventory[2] = 2, inventory/[4] = 4 Inventory[5] = 5



Perfect slots in final Inventory:

inventory([1]= 1, Inventory(2) = 2, Inventory(4)-4, inventory[5] = 5

Hence, the maximum possible perfect slots is 4.

Note that there can be more than one final array with maximum perfect slots, like [1, 2, 5, 4, 5, 3] in this case.

Function Description

Complete the function maximizePerfectSlots in the editor with the following parameters:

int inventory[n]: array of product IDs in slots

Returns

int: the maximum number of perfect slots










