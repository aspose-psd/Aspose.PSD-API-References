---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "PsdImage method. Menambahkan lapisan Penyesuaian Posterize"
type: docs
weight: 430
url: /id/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

Menambahkan lapisan Penyesuaian Posterize.

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### Nilai Kembalian

Instansi PosterizeLayer.

## Contoh

Kode berikut menunjukkan kemampuan untuk menambahkan PosterizeAdjustmentLayer melalui PsdImage.

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// Periksa perubahan yang disimpan
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
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

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


