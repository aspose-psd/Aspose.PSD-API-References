---
title: "RawColor.RawColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RawColor-konstruktorn. Initierar en ny instans av RawColor-klassen"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

Initierar en ny instans av klassen [`RawColor`](../).

```csharp
public RawColor(ColorComponent[] components)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| komponenter | ColorComponent[] | De anpassade färgkomponenterna. |

### Se även

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

Initierar en ny instans av klassen [`RawColor`](../) från pixeldataformat med fördefinierade färglägen

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | Pixeldataformatet. |
| färgläge | Int16 | Läge för färgen att följa. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Antalet kanaler skiljer sig från PixelFormat, kanalindex kan inte erhållas. Skapa RawColor med argumentet Components' Array. |

### Se även

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


