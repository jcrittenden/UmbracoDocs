---
title: ValidateProductAttributePresetAllowAttribute
description: API reference for ValidateProductAttributePresetAllowAttribute in Vendr, the eCommerce solution for Umbraco
---
## ValidateProductAttributePresetAllowAttribute

```csharp
public class ValidateProductAttributePresetAllowAttribute : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../../vendr-common/vendr-common-events/validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateProductAttributePresetAllowAttribute

```csharp
public ValidateProductAttributePresetAllowAttribute(
    ProductAttributePresetReadOnly productAttributePreset, AllowedProductAttribute allowedAttribute)
```


### Properties

#### AllowedAttribute

```csharp
public AllowedProductAttribute AllowedAttribute { get; }
```


---

#### ProductAttributePreset

```csharp
public ProductAttributePresetReadOnly ProductAttributePreset { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->