# 物品要素

Modtweaker的Thaumcraft集成扩展 [IItemStacks](/Vanilla/Items/IItemStack/).  
That means that you can use the methods below on any IItemStack object: 

## 设置要素

You can use this to override what aspects an item would normally have.  
Requires a [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/)[] or many [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/) objects.

```
<minecraft:stone>.setAspects(<aspect:ignis>*5);
```


## 删除要素

You can use this to prevent certain aspects from being added to an item.  
Requires a [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/)[] or many [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/) objects.

```
<minecraft:iron_ore>.removeAspects(<aspect:terra>);
```
