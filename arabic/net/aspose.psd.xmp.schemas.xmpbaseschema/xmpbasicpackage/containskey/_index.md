---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة XmpBasicPackage. تحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح"
type: docs
weight: 40
url: /ar/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

يحدد ما إذا كان المفتاح المحدد يحتوي على المفتاح.

```csharp
public override bool ContainsKey(string key)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | String | المفتاح الذي سيتم فحصه. |

### قيمة الإرجاع

يرجع true إذا كان المفتاح المحدد يحتوي على المفتاح.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


