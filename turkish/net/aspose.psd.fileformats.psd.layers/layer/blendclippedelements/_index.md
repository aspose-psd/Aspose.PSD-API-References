---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Layer özelliği. Kesilmiş öğenin karıştırmasını alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Kırpılmış öğenin karıştırmasını alır veya ayarlar.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

Kesilmiş öğenin karıştırması.

## Örnekler

Aşağıdaki kod, BlendClippedElements özelliğinin desteğini gösterir.

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

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


