---
title: Layer.BlendModeKey
second_title: Aspose.PSD for .NET API Referansı
description: Layer mülk. Karışım modu tuşunu alır veya ayarlar.
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

Karışım modu tuşunu alır veya ayarlar.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### Mülk değeri

Karışım modu tuşu.

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de PassThrough katman karıştırma modunu nasıl kullanabileceğinizi gösterir.

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca bakınız

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)


