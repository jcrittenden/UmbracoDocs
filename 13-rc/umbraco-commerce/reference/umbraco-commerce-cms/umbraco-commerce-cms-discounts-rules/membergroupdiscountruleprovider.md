---
title: MemberGroupDiscountRuleProvider
description: API reference for MemberGroupDiscountRuleProvider in Umbraco Commerce
---
## MemberGroupDiscountRuleProvider

```csharp
public class MemberGroupDiscountRuleProvider : 
    OrderDiscountRuleProviderBase<MemberGroupDiscountRuleProviderSettings>
```

**Inheritance**

* Class [OrderDiscountRuleProviderBase&lt;!0&gt;](../../umbraco-commerce-core/umbraco-commerce-core-discounts/orderdiscountruleproviderbase-1.md)

**Namespace**
* [Umbraco.Commerce.Cms.Discounts.Rules](README.md)

### Constructors

#### MemberGroupDiscountRuleProvider

```csharp
public MemberGroupDiscountRuleProvider(Lazy<IMemberService> memberService)
```


### Methods

#### ValidateRule

```csharp
public override DiscountRuleResult ValidateRule(DiscountRuleContext ctx, 
    MemberGroupDiscountRuleProviderSettings settings)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.dll -->