---
title: UmbracoProductVariantSummary
description: API reference for UmbracoProductVariantSummary in Vendr, the eCommerce solution for Umbraco
---
## UmbracoProductVariantSummary

```csharp
public class UmbracoProductVariantSummary : ProductVariantSummaryBase
```

**Inheritance**

* class [ProductVariantSummaryBase](../../../vendr-core/vendr-core-models/productvariantsummarybase/)

**Namespace**
* [Vendr.Umbraco.Adapters](../)

### Constructors

#### UmbracoProductVariantSummary (1 of 2)

```csharp
public UmbracoProductVariantSummary(IPublishedContent product, 
    IReadOnlyCollection<InUseProductAttribute> attributes, ProductVariantItem variant, 
    string languageIsoCode)
```

---

#### UmbracoProductVariantSummary (2 of 2)

```csharp
public UmbracoProductVariantSummary(IPublishedContent product, 
    IReadOnlyCollection<InUseProductAttribute> attributes, ProductVariantItem variant, 
    string languageIsoCode, VendrServiceContext vendrServices, 
    PublishedContentHelperAccessor publishedContentHelperAccessor)
```


### Properties

#### Attributes

```csharp
public override IReadOnlyDictionary<string, string> Attributes { get; }
```


---

#### Name

```csharp
public override string Name { get; }
```


---

#### Prices

```csharp
public override IEnumerable<ProductPrice> Prices { get; }
```


---

#### Reference

```csharp
public override string Reference { get; }
```


---

#### Sku

```csharp
public override string Sku { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Umbraco.dll -->