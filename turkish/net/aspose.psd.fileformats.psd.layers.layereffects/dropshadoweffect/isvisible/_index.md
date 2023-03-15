---
title: DropShadowEffect.IsVisible
second_title: Aspose.PSD for .NET API Referansı
description: DropShadowEffect mülk. Bu örneğin görünür olup olmadığını belirten bir değer alır veya ayarlar.
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

Bu örneğin görünür olup olmadığını belirten bir değer alır veya ayarlar.

```csharp
public bool IsVisible { get; set; }
```

### Mülk değeri

`doğru` bu örnek görünüyorsa; aksi takdirde,`YANLIŞ` .

### Örnekler

Aşağıdaki kod, DropShadowEffect'in Opacity özelliğinin kullanımını gösterir.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Opaklık = 20 ile Örnek
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opaklık = 20 ile Örnek0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Ayrıca bakınız

* class [DropShadowEffect](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* toplantı [Aspose.PSD](../../../)


