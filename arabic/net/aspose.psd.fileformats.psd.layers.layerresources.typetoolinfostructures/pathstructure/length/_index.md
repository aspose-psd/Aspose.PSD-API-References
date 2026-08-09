---
title: "PathStructure.Length"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PathStructure. تحصل على طول OSTypeStructure بالبايت"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

تحصل على طول [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) بالبايت.

```csharp
public override int Length { get; }
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


