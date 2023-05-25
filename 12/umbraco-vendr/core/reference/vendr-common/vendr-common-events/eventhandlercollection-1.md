---
title: EventHandlerCollection<TEvent>
description: API reference for EventHandlerCollection<TEvent> in Vendr, the eCommerce solution for Umbraco
---
## EventHandlerCollection&lt;TEvent&gt;

```csharp
public class EventHandlerCollection<TEvent> : ComposedCollection<IEventHandlerFor<TEvent>>
    where TEvent : IEvent
```

**Inheritance**

* class [ComposedCollection&lt;T&gt;](../../vendr-common-composing/composedcollection-1/)

**Namespace**
* [Vendr.Common.Events](../)

### Constructors

#### EventHandlerCollection&lt;TEvent&gt;

```csharp
public EventHandlerCollection(Func<IEnumerable<IEventHandlerFor<TEvent>>> itemsFactory)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Common.dll -->