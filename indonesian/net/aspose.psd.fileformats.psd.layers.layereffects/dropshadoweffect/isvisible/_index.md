---
title: DropShadowEffect.IsVisible
second_title: Aspose.PSD untuk Referensi .NET API
description: DropShadowEffect Properti. Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terlihat.
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terlihat.

```csharp
public bool IsVisible { get; set; }
```

### Nilai properti

`BENAR` jika contoh ini terlihat; jika tidak,`PALSU` .

### Contoh

Kode berikut menunjukkan penggunaan properti Opacity dari DropShadowEffect.

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

    // Contoh dengan Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Contoh dengan Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Lihat juga

* class [DropShadowEffect](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* perakitan [Aspose.PSD](../../../)


