---
title: "Enum InterpolationMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.InterpolationMode enum. Die InterpolationMode‑Aufzählung gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden."
type: docs
weight: 5520
url: /de/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

Die `InterpolationMode`-Aufzählung gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden.

```csharp
public enum InterpolationMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Invalid | `-1` | Ungültiger Interpolationsmodus. |
| Default | `0` | Gibt den Standardmodus an. |
| Low | `1` | Gibt eine Interpolation von geringer Qualität an. |
| High | `2` | Gibt eine Interpolation von hoher Qualität an. |
| Bilinear | `3` | Gibt bilineare Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 50 % seiner Originalgröße zu verkleinern. |
| Bicubic | `4` | Gibt bikubische Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 25 % seiner Originalgröße zu verkleinern. |
| NearestNeighbor | `5` | Gibt die Nächster-Nachbar-Interpolation an. |
| HighQualityBilinear | `6` | Gibt hochqualitative, bilineare Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten. |
| HighQualityBicubic | `7` | Gibt hochqualitative, bikubische Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten. Dieser Modus erzeugt die qualitativ hochwertigsten transformierten Bilder. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


