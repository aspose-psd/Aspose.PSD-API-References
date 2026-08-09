---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Methode. Fügt die Vibrance-Anpassungsebene hinzu."
type: docs
weight: 490
url: /de/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Fügt die Vibrance-Anpassungsebene hinzu.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Rückgabewert

Eine neu erstellte Vibrance-Ebene.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


