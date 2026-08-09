---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية AiLayerSection. تحصل أو تعين فهرس اللون. يمكن أن يأخذ هذا المتغير قيمًا بين 1 و 26. كل عدد صحيح يمثل لونًا يمكن تعيينه للطبقة لأغراض تعريف المستخدم"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

يحصل أو يعيّن فهرس اللون. يمكن أن يأخذ هذا المتغيّر قيمًا بين –1 و 26. كل عدد صحيح يمثل لونًا يمكن تعيينه للطبقة لأغراض تعريف المستخدم.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

فهرس اللون.

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


