---
title: "AiLayerSection.ColorIndex"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство AiLayerSection. Получает или задает индекс цвета. Этот параметр может принимать значения от 1 до 26. Каждый целочисленный параметр представляет цвет, который может быть назначен слою для целей идентификации пользователя."
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Получает или задает индекс цвета. Этот аргумент может принимать значения от –1 до 26. Каждое целое число представляет цвет, который может быть назначен слою для идентификации пользователем.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

Индекс цвета.

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


