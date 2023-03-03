---
title: PathStructure.PathStructure
second_title: Aspose.PSD لمرجع .NET API
description: PathStructure البناء. يقوم بتهيئة مثيل جديد لملفPathStructure فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

يقوم بتهيئة مثيل جديد لملف[`PathStructure`](../) فئة .

```csharp
public PathStructure(ClassID keyName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| keyName | ClassID | اسم المفتاح. |

### أمثلة

يوضح الكود التالي القدرة على تحميل الملف ببنية PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### أنظر أيضا

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* المجسم [Aspose.PSD](../../../)


