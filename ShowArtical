# Inventory = {'Bob': {'rope': 1, 'torch': 6, 'gold coin': 42, 'dagger': 1, 'arrow': 12},
#              'Jon': {'rope': 3, 'torch': 5, 'gold coin': 72, 'dagger': 4, 'arrow': 4},
#              'Reagan': {'rope': 99, 'torch': 100, 'gold coin': 99999, 'dagger': 723, 'arrow': 1000000}
#              }
#
#
# print('Inventory:')
# print(str(displayInventory(Inventory, 'arrow')) + ' arrow')
# print(str(displayInventory(Inventory, 'gold coin')) + ' gold coin')
# print(str(displayInventory(Inventory, 'rope')) + ' rope')
# print(str(displayInventory(Inventory, 'torch')) + ' torch')
# print(str(displayInventory(Inventory, 'dagger')) + ' dagger')
# print('Total number of items : ' +
#       str(displayInventory(Inventory, 'arrow') +
#           displayInventory(Inventory, 'gold coin') +
#           displayInventory(Inventory, 'rope') +
#           displayInventory(Inventory, 'torch') +
#           displayInventory(Inventory, 'dagger')
#           )
#       )

def displayinventory(inventory):                 # 显示该列表
    print('Inventory:')
    count = 0
    for k in inventory.keys():
        count += inventory[k]
        print(str(inventory[k]) + '  ' + k)
    print('Total number of items: ' + str(count))


def addtoinventory(inventory, addeditems):       # 把列表清单加入到字典中
    for item in addeditems:
        if item in inventory.keys():
            inventory[item] += 1
        else:
            inventory.setdefault(item, 1)
            continue
    return inventory


inv = {'gold coin': 42, 'rope': 1}
dragonLoot = ['gold coin', 'dagger', 'gold coin', 'gold coin', 'ruby', 'reagan', 'sword']
inv = addtoinventory(inv, dragonLoot)
print(inv)
displayinventory(inv)
