---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "حقل ResourceBlock. توقيع المورد لـ ImageReady"
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

توقيع المورد الخاص بـ ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## أمثلة

مثال الشيفرة التالي يوضح القدرة على تحميل وحفظ ملفات PSD مع الموارد ذات توقيع MeSa بشكل صحيح.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(2)1..psd";
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### انظر أيضًا

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


