---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Ajoute le calque d'ajustement du seuil"
type: docs
weight: 480
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Ajoute le calque de réglage du seuil.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Valeur de retour

Le calque d'ajustement du seuil créé.

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

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


