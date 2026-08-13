---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD for .NET API Referansı"
description: "AiLayerSection özelliği. Rengin indeksini alır veya ayarlar. Bu argüman 1 ile 26 arasında değer alabilir. Her tam sayı, kullanıcı tanımlama amaçları için katmana atanabilecek bir rengi temsil eder."
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Renk dizinini alır veya ayarlar. Bu argüman –1 ile 26 arasında değer alabilir. Her tam sayı, kullanıcı tanımlama amaçları için katmana atanabilecek bir rengi temsil eder.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

Rengin indeksi.

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


