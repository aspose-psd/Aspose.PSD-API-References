---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية AiLayerSection. تحصل أو تعين قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات"
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات؛ وإلا `false`.

## أمثلة

الكود التالي يوضح دعم خصائص HasMultiLayerMasks و ColorIndex في AiLayerSection.

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

### انظر أيضًا

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


