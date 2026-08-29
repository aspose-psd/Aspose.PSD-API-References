---
title: "Enum TextRenderingHint"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.TextRenderingHint enum. Gibt die Qualität der Textdarstellung an"
type: docs
weight: 6200
url: /de/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

Gibt die Qualität der Textdarstellung an.

```csharp
public enum TextRenderingHint
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| SystemDefault | `0` | Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet, unter Verwendung des systemweiten Standard‑Rendering‑Hints. Der Text wird mit den vom Benutzer im System gewählten Font‑Smoothing‑Einstellungen gezeichnet. |
| SingleBitPerPixelGridFit | `1` | Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet. Hinting wird verwendet, um das Aussehen der Zeichen auf Strichen und Krümmungen zu verbessern. |
| SingleBitPerPixel | `2` | Jedes Zeichen wird mit seiner Glyphen‑Bitmap gezeichnet. Hinting wird nicht verwendet. |
| AntiAliasGridFit | `3` | Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap und Hinting gezeichnet. Viel bessere Qualität durch Antialiasing, jedoch mit höheren Leistungsaufwand. |
| AntiAlias | `4` | Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap ohne Hinting gezeichnet. Bessere Qualität durch Antialiasing. Unterschiede in der Strichbreite können auffallen, weil Hinting deaktiviert ist. |
| ClearTypeGridFit | `5` | Jedes Zeichen wird mit seinem Glyph ClearType-Bitmap und Hinting gezeichnet. Die höchste Qualitätseinstellung. Wird verwendet, um die ClearType-Schriftartfunktionen zu nutzen. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


