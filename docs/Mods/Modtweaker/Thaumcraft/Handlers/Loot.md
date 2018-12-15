# 奖励袋

这个是添加/删除奖励袋的奖励.

## Importing the package

You can [import](/AdvancedFunctions/Import/) the package and its methods to facilitate the retrival of the methods.  
```
import mods.thaumcraft.LootBag;
```

## 奖励参数
由数字来控制它的类型 0 - 2 .  
这将决定奖励袋的类型.  

- 0: 常见
- 1: 罕见
- 2: 稀有

## 添加物品

注意：黄金几率2000，钻石几率50。

```
//mods.thaumcraft.LootBag.addLoot(WeightedItemStack stack, int[] bagTypes)
mods.thaumcraft.LootBag.addLoot(<minecraft:dirt>%20000, [0,1,2]);
```


## 删除物品

```
//mods.thaumcraft.LootBag.removeLoot(IItemStack stack, int[] bagTypes);
mods.thaumcraft.LootBag.removeLoot(<minecraft:gold_nugget>, [1,2]);
```
