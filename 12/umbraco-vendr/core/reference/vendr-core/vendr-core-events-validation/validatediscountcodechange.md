---
title: ValidateDiscountCodeChange
description: API reference for ValidateDiscountCodeChange in Vendr, the eCommerce solution for Umbraco
---
## ValidateDiscountCodeChange

```csharp
public class ValidateDiscountCodeChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../../vendr-common/vendr-common-events/validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateDiscountCodeChange

```csharp
public ValidateDiscountCodeChange(DiscountReadOnly discount, 
    ChangingValue<DiscountCode> discountCode)
```


### Properties

#### Discount

```csharp
public DiscountReadOnly Discount { get; }
```


---

#### DiscountCode

```csharp
public ChangingValue<DiscountCode> DiscountCode { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->