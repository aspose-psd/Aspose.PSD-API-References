---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "ThresholdLayer propriété. Obtient et définit le niveau du seuil"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

Obtient et définit le niveau de seuil.

```csharp
public short Level { get; set; }
```

### Property Value

Le niveau.

## Exemples

Le code suivant montre la prise en charge du calque d'ajustement ThresholdLayer.

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Obtenez, vérifiez et modifiez le calque d'ajustement Threshold à partir de l'image.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Obtenez le calque d'ajustement Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Vérifiez les paramètres des calques.
            AssertAreEqual(level, (short)115);

            // Définissez les paramètres des calques.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Ajoutez et définissez le calque d'ajustement Threshold à l'image.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Ajoutez le calque d'ajustement Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Définissez les paramètres des calques.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Voir aussi

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


