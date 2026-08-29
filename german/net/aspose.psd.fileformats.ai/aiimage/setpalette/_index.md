---
title: "AiImage.SetPalette"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "AiImage-Methode. Setzt die Bildpalette"
type: docs
weight: 200
url: /de/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

Setzt die Bildpalette.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Palette | IColorPalette | Die zu setzende Palette. |
| updateColors | Boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden abstürzen lassen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotImplementedException | Nicht implementiert |

### Siehe auch

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


