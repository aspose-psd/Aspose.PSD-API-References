---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD for .NET API Referansı"
description: "AiLayerSection özelliği. Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar"
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` eğer bu örnek çok katmanlı maskelere sahipse; aksi takdirde `false`.

## Örnekler

Aşağıdaki kod, AiLayerSection içinde HasMultiLayerMasks ve ColorIndex özelliklerinin desteğini gösterir.

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

### Ayrıca Bakınız

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


