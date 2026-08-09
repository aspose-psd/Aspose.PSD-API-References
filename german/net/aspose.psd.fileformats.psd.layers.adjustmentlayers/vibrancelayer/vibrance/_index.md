---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VibranceLayer-Eigenschaft. Gibt die Vibranz zurück oder legt sie fest"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Liest oder setzt die Lebendigkeit.

```csharp
public int Vibrance { get; set; }
```

### Property Value

Die Vibranz.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Die Vibranz muss im Bereich von -180 bis +180 liegen |

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


