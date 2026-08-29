---
title: "GifOptions.ColorResolution"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GifOptions egenskap. Hämtar eller anger GIF:s färgupplösning"
type: docs
weight: 30
url: /sv/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

Hämtar eller anger GIF:s färglösning.

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

Färglösningen.

## Anmärkningar

Färglösning - Antalet bitar per primärfärg som är tillgängliga för den ursprungliga bilden, minus 1. Detta värde representerar storleken på hela paletten som färgerna i grafiken valdes från, inte antalet färger som faktiskt används i grafiken. Till exempel, om värdet i detta fält är 3, hade paletten för den ursprungliga bilden 4 bitar per primärfärg tillgängliga för att skapa bilden. Detta värde bör sättas för att indikera rikedom i den ursprungliga paletten, även om inte varje färg från hela paletten är tillgänglig på källmaskinen.

### Se även

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


