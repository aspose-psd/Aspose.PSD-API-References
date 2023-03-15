---
title: PathStructure.Prefix
second_title: Aspose.PSD لمرجع .NET API
description: PathStructure ملكية. الحصول على بادئة المسار أو تحديدها.
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
## PathStructure.Prefix property

الحصول على بادئة المسار أو تحديدها.

```csharp
public string Prefix { get; set; }
```

### Property_Value

المسار الكامل .

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

* class [PathStructure](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* المجسم [Aspose.PSD](../../../)


