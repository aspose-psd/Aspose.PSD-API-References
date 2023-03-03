---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD لمرجع .NET API
description: ResourceBlock مجال. توقيع المورد ImageReady.
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

توقيع المورد ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### أمثلة

يوضح مثال الكود التالي القدرة على تصحيح تحميل ملفات PSD وحفظها بموارد بتوقيع MeSa.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(21..psd");
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### أنظر أيضا

* class [ResourceBlock](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* المجسم [Aspose.PSD](../../../)


