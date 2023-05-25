---
title: ITransactionApiContainer
description: API reference for ITransactionApiContainer in Vendr, the eCommerce solution for Umbraco
---
## ITransactionApiContainer

```csharp
public interface ITransactionApiContainer
```

**Namespace**
* [Vendr.Common](../)

### Methods

#### AddTransactionApi

```csharp
public void AddTransactionApi(string key, ITransactionApi api)
```


---

#### FindTransactionApi

```csharp
public ITransactionApi FindTransactionApi(string key)
```


---

#### GetOrAddTransactionApi

```csharp
public ITransactionApi GetOrAddTransactionApi(string key, Func<ITransactionApi> factory)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Common.dll -->