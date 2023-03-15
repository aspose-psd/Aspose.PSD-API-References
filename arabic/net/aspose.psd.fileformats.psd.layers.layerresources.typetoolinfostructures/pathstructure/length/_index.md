---
title: PathStructure.Length
second_title: Aspose.PSD لمرجع .NET API
description: PathStructure ملكية. يحصل على ملفOSTypeStructure الطول بالبايت.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

يحصل على ملف[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) الطول بالبايت.

```csharp
public override int Length { get; }
```

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


