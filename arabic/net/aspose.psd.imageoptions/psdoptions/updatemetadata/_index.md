---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdOptions. يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تحديث البيانات الوصفية. إذا كانت القيمة true سيتم تحديث البيانات الوصفية أثناء حفظ الصورة"
type: docs
weight: 110
url: /ar/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

يحصل أو يضبط قيمة تشير إلى ما إذا كان [update metadata]. إذا كانت القيمة true، سيتم تحديث البيانات الوصفية أثناء حفظ الصورة.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` إذا [update metadata]; وإلا `false`.

## أمثلة

الكود التالي يوضح استخدام خيار UpdateMetadata لتحديث قيمة CreatorTool في بيانات xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // إذا كنت تريد تغيير أداة الإنشاء، تأكد من أن خاصية "UpdateMetadata" مضبوطة على true. يتم ضبطها على true افتراضيًا.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // حفظ الصورة. 
    image.Save(path, psdOptions);

    // التحقق من أداة الإنشاء في الكود.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // هنا سيتم تحديث معلومات أداة الإنشاء.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### انظر أيضًا

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


