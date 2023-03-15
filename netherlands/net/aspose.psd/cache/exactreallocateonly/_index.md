---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD voor .NET API-referentie
description: Cache eigendom. Haalt of stelt een waarde in die aangeeft of hertoewijzing exact moet zijn of niet. Als hertoewijzing niet exact is zouden de prestaties hoger moeten zijn.
type: docs
weight: 50
url: /nl/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Haalt of stelt een waarde in die aangeeft of hertoewijzing exact moet zijn of niet. Als hertoewijzing niet exact is, zouden de prestaties hoger moeten zijn.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Eigendoms-waarde

`WAAR` als hertoewijzing exact is; anders,`vals` .

### Opmerkingen

De exacte hertoewijzing voert alleen een nieuwe toewijzing van extra geheugen uit tot aan de opgegeven bovengrens. Wanneer de bovengrens voor in-memory wordt overschreden tijdens hertoewijzing, worden de gegevens in de cache indien mogelijk naar schijf gekopieerd. Wanneer de bovengrens voor schijfgeheugen wordt overschreden tijdens hertoewijzing, de juiste uitzondering wordt gegenereerd. De prestaties zouden hoger moeten zijn als deze optie is uitgeschakeld, aangezien er indien mogelijk geen extra kopiëren wordt uitgevoerd, dit kan er echter ook toe leiden dat de bovenlimieten voor geheugen of schijf worden overschreden.

### Zie ook

* class [Cache](../)
* naamruimte [Aspose.PSD](../../cache/)
* montage [Aspose.PSD](../../../)


