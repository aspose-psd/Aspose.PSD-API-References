---
title: "DropShadowEffect.IsVisible"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "DropShadowEffect properti. Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat"
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` jika instance ini terlihat; jika tidak, `false`.

## Contoh

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

### Lihat Juga

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


