---
title: "Enum LayerLockType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType‑enum. Alternativ för lagerlåsning"
type: docs
weight: 2890
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
{{< psd/tize >}}
## LayerLockType enumeration

Låsningsalternativ för lager

```csharp
[Flags]
public enum LayerLockType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen lagerlåsning |
| LockTransparentPixels | `1` | Delvis lås ett lager - Begränsar redigering till lagerets ogenomskinliga delar. Detta alternativ är motsvarande Preserve Transparency-alternativet i tidigare versioner av Photoshop. |
| LockImagePixels | `2` | Delvis lås ett lager - Förhindrar ändring av lagrets pixlar med målarverktygen. |
| LockPosition | `4` | Delvis lås ett lager - Förhindrar att lagrets pixlar flyttas. |
| LockAll | `7` | Lås alla egenskaper för ett lager |

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


