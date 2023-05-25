---
title: TaxClassEditDto
description: API reference for TaxClassEditDto in Vendr, the eCommerce solution for Umbraco
---
## TaxClassEditDto

```csharp
public class TaxClassEditDto : TaxClassDto, IHasPath, INotificationModel
```

**Inheritance**

* class [TaxClassDto](../taxclassdto/)
* interface [IHasPath](../ihaspath/)

**Namespace**
* [Vendr.Umbraco.Web.Models](../)

### Constructors

#### TaxClassEditDto

The default constructor.

```csharp
public TaxClassEditDto()
```


### Properties

#### Notifications

```csharp
public List<BackOfficeNotification> Notifications { get; set; }
```


---

#### Path

```csharp
public List<string> Path { get; set; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Umbraco.Web.dll -->