# 植物酿造

这个是添加/删除植物酿造合成

## Calling
你可以使用这个修改酿造合成 `mods.botania.Brew`

## Brew Names

To use this Package, you need to know botania's registered Brew Names.  
You can find them using [`/ct botbrews`](/Mods/Modtweaker/Botania/Commands/).

## 添加合成

```
//mods.botania.Brew.addRecipe(IIngredient[] input, String brewName);
mods.botania.Brew.addRecipe([<minecraft:nether_wart>, <minecraft:reeds>, <minecraft:redstone>], "speed");
```

## 删除合成

```
//mods.botania.Brew.removeRecipe(String brewName);
mods.botania.Brew.removeRecipe("absorption");
```
