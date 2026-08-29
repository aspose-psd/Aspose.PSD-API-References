---
title: "Layer.BlendClippedElements"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство Layer. Получает или задает смешивание обрезанного элемента"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Получает или задает режим смешивания обрезанного элемента.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

Смешивание обрезанного элемента.

## Примеры

Следующий код демонстрирует поддержку свойства BlendClippedElements.

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


