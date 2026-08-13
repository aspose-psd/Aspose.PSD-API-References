---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ILayerEffect method. Giriş katman piksel sınırlarına dayanarak efekt piksel sınırlarını hesaplar ve alır"
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Girdi katman piksel sınırlarına dayanarak efekt piksel sınırlarını hesaplar ve alır.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerBounds | Rectangle | Katman piksel sınırları. |
| globalAngle | Int32 | Küresel ışık açısını hesaplamak için küresel açı. |

### Dönüş Değeri

Giriş katman piksel sınırlarına dayanarak efekt piksel sınırları.

## Örnekler

Katmanın efektlerle sınırlamalarını nasıl alacağını ve doğru boyutta dışa aktarılacağını gösterir.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Orijinal katman konumundaki PsdImage sınırlamaları içinde kaydetmek için

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### Ayrıca Bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


