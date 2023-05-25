---
title: CalculateOrderShippingTaxRateTask
description: API reference for CalculateOrderShippingTaxRateTask in Vendr, the eCommerce solution for Umbraco
---
## CalculateOrderShippingTaxRateTask

```csharp
public class CalculateOrderShippingTaxRateTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../../vendr-common/vendr-common-pipelines/pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.Order.Tasks](../)

### Constructors

#### CalculateOrderShippingTaxRateTask

```csharp
public CalculateOrderShippingTaxRateTask(IShippingCalculator shippingCalculator)
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->