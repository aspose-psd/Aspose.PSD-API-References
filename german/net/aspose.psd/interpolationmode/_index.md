---
title: Enum InterpolationMode
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.InterpolationMode opsomming. DieInterpolationMode Enumeration gibt den Algorithmus an der verwendet wird wenn Bilder skaliert oder gedreht werden.
type: docs
weight: 5030
url: /de/net/aspose.psd/interpolationmode/
---
## InterpolationMode enumeration

Die`InterpolationMode` Enumeration gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder gedreht werden.

```csharp
public enum InterpolationMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Invalid | `-1` | Ungültiger Interpolationsmodus. |
| Default | `0` | Gibt den Standardmodus an. |
| Low | `1` | Gibt eine Interpolation niedriger Qualität an. |
| High | `2` | Gibt eine hochwertige Interpolation an. |
| Bilinear | `3` | Gibt die bilineare Interpolation an. Es erfolgt keine Vorfilterung. Dieser Modus ist nicht geeignet, um ein Bild auf weniger als 50 Prozent seiner Originalgröße zu verkleinern. |
| Bicubic | `4` | Gibt bikubische Interpolation an. Es erfolgt keine Vorfilterung. Dieser Modus ist nicht geeignet, um ein Bild auf weniger als 25 Prozent seiner Originalgröße zu verkleinern. |
| NearestNeighbor | `5` | Gibt die Nächste-Nachbar-Interpolation an. |
| HighQualityBilinear | `6` | Gibt eine hochwertige, bilineare Interpolation an. Es wird eine Vorfilterung durchgeführt, um eine qualitativ hochwertige Schrumpfung sicherzustellen. |
| HighQualityBicubic | `7` | Gibt hochwertige, bikubische Interpolation an. Es wird eine Vorfilterung durchgeführt, um eine qualitativ hochwertige Schrumpfung sicherzustellen. Dieser Modus erzeugt transformierte Bilder in höchster Qualität. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


