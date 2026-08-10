---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti AiLayerSection. Mendapatkan atau mengatur indeks warna. Argumen ini dapat memiliki nilai antara 1 dan 26. Setiap bilangan bulat mewakili warna yang dapat diberikan ke lapisan untuk tujuan identifikasi pengguna"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Mendapatkan atau mengatur indeks warna. Argumen ini dapat memiliki nilai antara –1 dan 26. Setiap integer mewakili warna yang dapat diberikan ke lapisan untuk tujuan identifikasi pengguna.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

Indeks warna.

## Contoh

Kode berikut menunjukkan dukungan properti HasMultiLayerMasks dan ColorIndex dalam AiLayerSection.

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### Lihat Juga

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


