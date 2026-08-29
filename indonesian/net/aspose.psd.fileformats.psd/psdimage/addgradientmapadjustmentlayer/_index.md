---
title: "PsdImage.AddGradientMapAdjustmentLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode PsdImage. Menambahkan lapisan Penyesuaian GradientMap"
type: docs
weight: 360
url: /id/net/aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddGradientMapAdjustmentLayer method

Menambahkan lapisan Penyesuaian PetaGradien.

```csharp
public GradientMapLayer AddGradientMapAdjustmentLayer()
```

### Nilai Kembalian

Instansi GradientMap.

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

* class [GradientMapLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


