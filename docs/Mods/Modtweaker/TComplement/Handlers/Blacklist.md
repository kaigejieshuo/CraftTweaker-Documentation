# 方块列表

The Blacklist package is used for adding/removing recipes from/to the melter Blacklist.

## Calling
你可以使用这个修改方块列表 `mods.tcomplement.Blacklist`

## 方块列表添加

```
//mods.tcomplement.Blacklist.addRecipe(ILiquidStack output, IItemStack input);
mods.tcomplement.Blacklist.addRecipe(<liquid:seared_stone>, <minecraft:stone>);
```

## 方块列表删除

```
//mods.tcomplement.Blacklist.removeRecipe(IItemStack input);
mods.tcomplement.Blacklist.removeRecipe(<minecraft:cobblestone>);
```
