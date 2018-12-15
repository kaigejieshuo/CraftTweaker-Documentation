# 冶金

This package allows you to add and remove items to/from the Smelting bonus list.(妈耶，这个我翻译烦了,不想翻译了)  
The Smelting Bonus list is queried whenever an infernal furnace cooks an item.

## Importing the package

You can [import](/AdvancedFunctions/Import/) the package and its methods to facilitate the retrival of the methods.  
```
import mods.thaumcraft.SmeltingBonus;
```

## 添加物品

Notice: Input needs to be either an IItemStack or an IOreDictEntry

```
//mods.thaumcraft.SmeltingBonus.addSmeltingBonus(IIngredient input, WeightedItemStack stack)
mods.thaumcraft.SmeltingBonus.addSmeltingBonus(<minecraft:cobblestone>, <minecraft:button> % 20);
```


## 删除物品

Notice: Input needs to be either an IItemStack or an IOreDictEntry

```
//mods.thaumcraft.SmeltingBonus.removeSmeltingBonus(IIngredient input, IItemStack stack);
mods.thaumcraft.SmeltingBonus.removeSmeltingBonus(<minecraft:gold_ore>, <minecraft:gold_nugget>);
```
