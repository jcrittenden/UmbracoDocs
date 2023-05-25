---
title: CurrencyExchangeRateServiceBase
description: API reference for CurrencyExchangeRateServiceBase in Vendr, the eCommerce solution for Umbraco
---
## CurrencyExchangeRateServiceBase

```csharp
public abstract class CurrencyExchangeRateServiceBase : ICurrencyExchangeRateService
```

**Inheritance**

* interface [ICurrencyExchangeRateService](../../../vendr-core/vendr-core-services/icurrencyexchangerateservice/)

**Namespace**
* [Vendr.Infrastructure.Services](../)

### Methods

#### FetchExchangeRate

```csharp
public abstract decimal FetchExchangeRate(string fromCurrencyIsoCode, string toCurrencyIsoCode, 
    DateTime date)
```


---

#### FetchExchangeRates

```csharp
public abstract Dictionary<string, Dictionary<string, decimal>> FetchExchangeRates(
    string fromCurrencyIsoCode, string[] toCurrencyIsoCodes, DateTime dateFrom, DateTime dateTo)
```


---

#### GetExchangeRate

```csharp
public decimal GetExchangeRate(string fromCurrencyIsoCode, string toCurrencyIsoCode, DateTime date)
```


---

#### GetExchangeRates

```csharp
public Dictionary<string, Dictionary<string, decimal>> GetExchangeRates(string fromCurrencyIsoCode, 
    string[] toCurrencyIsoCodes, DateTime dateFrom, DateTime dateTo)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Infrastructure.dll -->