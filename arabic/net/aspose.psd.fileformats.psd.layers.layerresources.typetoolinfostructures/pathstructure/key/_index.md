---
title: "PathStructure.Key"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PathStructure. تحصل على مفتاح البنية"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

يحصل على مفتاح البنية.

```csharp
public override int Key { get; }
```

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


