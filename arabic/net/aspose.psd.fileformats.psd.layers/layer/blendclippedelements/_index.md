---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية Layer. يحصل أو يضبط دمج العنصر المقصوص"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

يحصل أو يعيّن دمج العنصر المقصوص.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

دمج العنصر المقصوص.

## أمثلة

الكود التالي يوضح دعم خاصية BlendClippedElements.

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

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


