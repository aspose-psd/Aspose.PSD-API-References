---
title: "Enum InterpolationMode"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.InterpolationMode‑enum. InterpolationMode‑enumerationen specificerar den algoritm som används när bilder skalas eller roteras."
type: docs
weight: 5520
url: /sv/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

`InterpolationMode`‑enumerationen specificerar den algoritm som används när bilder skalas eller roteras.

```csharp
public enum InterpolationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Invalid | `-1` | Ogiltigt interpolationsläge. |
| Default | `0` | Anger standardläge. |
| Low | `1` | Anger interpolering med låg kvalitet. |
| High | `2` | Anger interpolering med hög kvalitet. |
| Bilinear | `3` | Anger bilinjär interpolering. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att minska en bild till under 50 % av dess originalstorlek. |
| Bicubic | `4` | Anger bikubisk interpolering. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att minska en bild till under 25 % av dess originalstorlek. |
| NearestNeighbor | `5` | Anger närmaste-granne interpolering. |
| HighQualityBilinear | `6` | Anger högkvalitativ, bilinjär interpolering. Förfiltrering utförs för att säkerställa högkvalitativ minskning. |
| HighQualityBicubic | `7` | Anger högkvalitativ, bikubisk interpolation. Förfiltrering utförs för att säkerställa högkvalitativ krympning. Detta läge producerar de högsta kvaliteten på transformerade bilder. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


