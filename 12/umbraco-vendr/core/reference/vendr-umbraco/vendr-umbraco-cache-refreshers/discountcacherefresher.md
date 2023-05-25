---
title: DiscountCacheRefresher
description: API reference for DiscountCacheRefresher in Vendr, the eCommerce solution for Umbraco
---
## DiscountCacheRefresher

```csharp
public class DiscountCacheRefresher : 
    VendrEntityStateCacheRefresherBase<DiscountCacheRefresher, IDiscountService, DiscountReadOnly>
```

**Inheritance**

* class [VendrEntityStateCacheRefresherBase&lt;TInstanceType,TService,TEntity&gt;](../vendrentitystatecacherefresherbase-3/)

**Namespace**
* [Vendr.Umbraco.Cache.Refreshers](../)

### Constructors

#### DiscountCacheRefresher

```csharp
public DiscountCacheRefresher(AppCaches appCaches, IJsonSerializer serializer, 
    IEventAggregator eventAggregator, ICacheRefresherNotificationFactory factory, 
    Lazy<IDiscountService> entityService, Lazy<ILogger<DiscountCacheRefresher>> logger)
```


### Properties

#### Name

```csharp
public override string Name { get; }
```


---

#### RefresherUniqueId

```csharp
public override Guid RefresherUniqueId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Umbraco.dll -->