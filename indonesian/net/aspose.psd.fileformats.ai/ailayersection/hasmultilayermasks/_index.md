---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti AiLayerSection. Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilayer"
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilapisan.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` jika instance ini memiliki masker multilayer; jika tidak, `false`.

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


