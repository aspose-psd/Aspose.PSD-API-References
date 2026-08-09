---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ PathStructure. يهيئ نسخة جديدة من الفئة PathStructure"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

يهيئ نسخة جديدة من الفئة [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| keyName | ClassID | اسم المفتاح. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


