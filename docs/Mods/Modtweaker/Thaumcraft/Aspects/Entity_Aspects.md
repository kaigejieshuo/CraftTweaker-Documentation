# 生物要素

Modtweaker的Thaumcraft集成扩展 [IEntityDefinition](/Vanilla/Entities/IEntityDefinition/).  
That means that you can use the methods below on any IEntityDefinition object: 

## 设置要素

You can use this to override what aspects an entity would normally have.  
Requires a [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/)[] or many [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/) objects.

```
<entity:sheep>.setAspects(<aspect:terra>*5);
```


## 删除要素

You can use this to prevent certain aspects from being added to an entity.  
Requires a [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/)[] or many [CTAspectStack](/Mods/Modtweaker/Thaumcraft/Aspects/CTAspect/) objects.

```
<entity:blaze>.removeAspects(<aspect:ignis>);
```
