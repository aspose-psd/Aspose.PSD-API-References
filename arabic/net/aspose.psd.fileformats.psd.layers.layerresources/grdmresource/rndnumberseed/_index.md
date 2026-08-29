---
title: "GrdmResource.RndNumberSeed"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية GrdmResource. بذرة الرقم العشوائي المستخدمة لتوليد الألوان لتدرج الضوضاء"
type: docs
weight: 150
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/
---
{{< psd/tize >}}
## GrdmResource.RndNumberSeed property

البذرة العشوائية المستخدمة لتوليد الألوان لتدرج الضوضاء.

```csharp
public int RndNumberSeed { get; set; }
```

## أمثلة

الكود التالي يوضح دعم مورد GrdmResource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // تحقق من القيم الحالية
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // اللون الأحمر لنقطة التدرج اللوني الثانية
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // تحقق من القيم المتغيرة
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### انظر أيضًا

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


