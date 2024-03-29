---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD für .NET-API-Referenz
description: VibranceLayer eigendom. Ruft die Vibration ab oder legt sie fest.
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

Ruft die Vibration ab oder legt sie fest.

```csharp
public int Vibrance { get; set; }
```

### Eigentumswert

Die Schwingung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Die Vibration muss im Bereich von -180 bis +180 liegen |

### Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung der VibranceLayer-Ebene und die Möglichkeit, diese Anpassung zu bearbeiten.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Erstellen einer neuen VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Siehe auch

* class [VibranceLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* Montage [Aspose.PSD](../../../)


