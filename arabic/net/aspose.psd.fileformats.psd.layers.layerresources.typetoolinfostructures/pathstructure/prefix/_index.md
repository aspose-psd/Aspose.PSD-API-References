---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PathStructure. تحصل أو تعين بادئة المسار"
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

يحصل أو يعيّن بادئة المسار.

```csharp
public string Prefix { get; set; }
```

### Property Value

المسار الكامل.

## أمثلة

الكود التالي يوضح القدرة على تحميل ملف باستخدام بنية PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### انظر أيضًا

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


