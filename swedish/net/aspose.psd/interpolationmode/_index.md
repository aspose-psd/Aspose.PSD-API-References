---
title: Enum InterpolationMode
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.InterpolationMode uppräkning. DenInterpolationMode uppräkning anger algoritmen som används när bilder skalas eller roteras.
type: docs
weight: 5030
url: /sv/net/aspose.psd/interpolationmode/
---
## InterpolationMode enumeration

Den`InterpolationMode` uppräkning anger algoritmen som används när bilder skalas eller roteras.

```csharp
public enum InterpolationMode
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Invalid | `-1` | Ogiltigt interpolationsläge. |
| Default | `0` | Anger standardläge. |
| Low | `1` | Anger interpolation av låg kvalitet. |
| High | `2` | Anger interpolation av hög kvalitet. |
| Bilinear | `3` | Anger bilinjär interpolation. Ingen förfiltrering görs. Det här läget är inte lämpligt för att krympa en bild under 50 procent av dess ursprungliga storlek. |
| Bicubic | `4` | Anger bikubisk interpolation. Ingen förfiltrering görs. Det här läget är inte lämpligt för att krympa en bild under 25 procent av dess ursprungliga storlek. |
| NearestNeighbor | `5` | Anger närmaste granne-interpolation. |
| HighQualityBilinear | `6` | Anger bilinjär interpolation av hög kvalitet. Förfiltrering utförs för att säkerställa krympning av hög kvalitet. |
| HighQualityBicubic | `7` | Anger bikubisk interpolation av hög kvalitet. Förfiltrering utförs för att säkerställa högkvalitativ krympning. Detta läge ger transformerade bilder av högsta kvalitet. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


