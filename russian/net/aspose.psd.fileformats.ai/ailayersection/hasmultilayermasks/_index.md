---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Справочник API Aspose.PSD для .NET"
description: "AiLayerSection свойство. Получает или задает значение, указывающее, имеет ли этот экземпляр многослойные маски"
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Получает или задает значение, указывающее, имеет ли данный экземпляр многослойные маски.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` если этот экземпляр имеет многослойные маски; иначе, `false`.

## Примеры

Следующий код демонстрирует поддержку свойств HasMultiLayerMasks и ColorIndex в AiLayerSection.

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

### См. также

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


