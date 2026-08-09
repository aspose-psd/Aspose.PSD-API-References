---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VibranceLayer-Eigenschaft. Liest oder schreibt die Sättigung"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

Liest oder setzt die Sättigung.

```csharp
public int Saturation { get; set; }
```

### Property Value

Die Sättigung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Die Sättigung muss im Bereich von -100 bis +100 liegen |

## Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung der VibranceLayer Ebene und die Möglichkeit, diese Anpassung zu bearbeiten.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


