# rftools controls autocrafting - draconic evolution fusion crafting automation

for this program you need - 12 nodes, 1 network card, 4 cpus, 1 ram.
alocate all ram slots to program, allocate 14 (from 0 to 13) slots for items.

nodes have channel "fusion" and names from "i1" to "i12"

0 crafting recipe slot goes up to fusion crafting core, others - to injectors.

what program does? it iterates over patterns chest and tryies craft each recipe from items which are in left chest. if it fails - it goes to next one in patterns chest.
if item can be crafted, program waits for results in fusion core from crafting card. then it finishes, results goes to right chest.

you can hook left chest to applied energistics 2 interfaces ant pipe out items to interface from right chest. 
you can craft everything from AE2 witch have 1 item for core and 8 other different items. (i thing everything is automateable)

