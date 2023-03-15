---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD för .NET API-referens
description: Cache fast egendom. Hämtar eller sätter ett värde som indikerar om omfördelningen ska vara exakt eller inte. Om omfördelningen inte är exakt bör prestandan vara högre.
type: docs
weight: 50
url: /sv/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Hämtar eller sätter ett värde som indikerar om omfördelningen ska vara exakt eller inte. Om omfördelningen inte är exakt bör prestandan vara högre.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Fastighetsvärde

`Sann` om omfördelningen är exakt; annat,`falsk` .

### Anmärkningar

Den exakta omallokeringen kommer att utföra omallokering av ytterligare minne endast upp till den angivna övre gränsen. När den övre gränsen för in-memory passerar under omallokering kommer cachad data att kopieras till disk om möjligt. När den övre gränsen för diskminne passerar under omallokering, lämpligt undantag kastas. Prestandan bör vara högre om det här alternativet är avstängt eftersom ingen ytterligare kopiering kommer att utföras om möjligt, men detta kan också leda till att övre gränser som anges för minne eller disk passerar.

### Se även

* class [Cache](../)
* namnutrymme [Aspose.PSD](../../cache/)
* hopsättning [Aspose.PSD](../../../)


