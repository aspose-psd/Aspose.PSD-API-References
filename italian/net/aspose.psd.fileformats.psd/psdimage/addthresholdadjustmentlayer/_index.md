---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo PsdImage. Aggiunge il Threshold adjustment layer"
type: docs
weight: 480
url: /it/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Aggiunge il Threshold adjustment layer.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Valore di ritorno

Il Threshold adjustment layer creato.

## Esempi

Il codice seguente dimostra il supporto del livello di regolazione ThresholdLayer.

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

// Ottieni, verifica e modifica il livello di regolazione Threshold dall'immagine.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Ottieni il livello di regolazione Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Verifica i parametri dei livelli.
            AssertAreEqual(level, (short)115);

            // Imposta i parametri dei livelli.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Aggiungi e imposta il livello di regolazione Threshold sull'immagine.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Aggiungi livello di regolazione Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Imposta i parametri dei livelli.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Vedi anche

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


