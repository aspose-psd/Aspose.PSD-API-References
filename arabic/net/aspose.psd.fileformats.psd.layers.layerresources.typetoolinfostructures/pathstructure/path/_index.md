---
title: "PathStructure.Path"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PathStructure. تحصل أو تعين المسار"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

يحصل أو يعيّن المسار.

```csharp
public string Path { get; set; }
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


