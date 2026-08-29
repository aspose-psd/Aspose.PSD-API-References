---
title: "VscgResource.Items"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية VscgResource. تحصل أو تعيين مصفوفة عناصر البنية. تحذير يجب أن تتطابق قيم مصفوفة Items مع خاصية KeyForData التي تحدد نوع إعدادات التعبئة المخزنة في الهياكل داخل Items"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/
---
{{< psd/tize >}}
## VscgResource.Items property

يحصل أو يضبط مصفوفة عناصر البنية. **Warning:** يجب أن تتطابق قيم مصفوفة `Items` مع خاصية `KeyForData`، التي تحدد نوع إعدادات التعبئة المخزنة في البنى داخل `Items`.

```csharp
public OSTypeStructure[] Items { get; }
```

### Property Value

مصفوفة عناصر [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/).

## أمثلة

الكود التالي يوضح دعم VscgResource.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// جارٍ فحص التغييرات
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### انظر أيضًا

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [VscgResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


