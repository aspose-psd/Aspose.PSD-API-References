---
title: "GradientMapLayer.GradientSettings"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti GradientMapLayer. Mendapatkan atau mengatur instance pengaturan Gradient yang diteruskan dari instance GrdmResource"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/gradientsettings/
---
{{< psd/tize >}}
## GradientMapLayer.GradientSettings property

Mendapatkan atau mengatur instance pengaturan Gradient yang diteruskan dari instance GrdmResource.

```csharp
public GradientMapSettings GradientSettings { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan lapisan peta gradasi.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Tambahkan lapisan penyesuaian peta gradasi.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Periksa perubahan yang disimpan
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Lihat Juga

* class [GradientMapSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/)
* class [GradientMapLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


