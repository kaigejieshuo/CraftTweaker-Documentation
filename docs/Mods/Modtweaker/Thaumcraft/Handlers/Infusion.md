# 注魔

这个是添加/删除注魔合成.

## Importing the package

You can [import](/AdvancedFunctions/Import/) the package and its methods to facilitate the retrival of the methods.  
```
import mods.thaumcraft.Infusion;
```

## 添加合成

```
//mods.thaumcraft.Infusion.registerRecipe(String name, String research, IItemStack output, int instability, CTAspectStack[] aspects, IIngredient centralItem, IIngredient[] recipe);
mods.thaumcraft.Infusion.registerRecipe("testName", "", <minecraft:diamond>, 20, [<aspect:aer>, <aspect:ignis>], <minecraft:grass>, [<minecraft:stick>, <minecraft:dirt>]);
```


## 删除合成

```
//mods.thaumcraft.Infusion.removeRecipe(String name);
mods.thaumcraft.Infusion.removeRecipe("recipeName");


//mods.thaumcraft.Infusion.removeRecipe(IItemStack output);
mods.thaumcraft.Infusion.removeRecipe(<thaumcraft:mirror_essentia>);
```
