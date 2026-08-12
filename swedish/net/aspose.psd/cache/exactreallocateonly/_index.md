---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Cache‑egenskap. Hämtar eller anger ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokeringen inte är exakt bör prestandan vara högre"
type: docs
weight: 50
url: /sv/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Hämtar eller anger ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokering inte är exakt bör prestandan vara högre.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` om omallokeringen är exakt; annars `false`.

## Anmärkningar

Den exakta omallokeringen kommer endast att omallokera ytterligare minne upp till den angivna övre gränsen. När den övre gränsen för minne i RAM anges under omallokeringen kopieras den cachade datan till disk om möjligt. När den övre gränsen för diskmemory anges under omallokeringen kastas ett lämpligt undantag. Prestandan bör vara högre om detta alternativ är avstängt eftersom ingen extra kopiering kommer att utföras om möjligt, men detta kan även leda till att de angivna övre gränserna för minne eller disk överskrids.

### Se även

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


