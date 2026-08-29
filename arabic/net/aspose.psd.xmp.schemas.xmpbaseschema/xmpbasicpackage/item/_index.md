---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية XmpBasicPackage. تحصل أو تعيّن الكائن بالمفتاح المحدد"
type: docs
weight: 20
url: /ar/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

يحصل أو يضبط الكائن بالمفتاح المحدد.

```csharp
public override object this[string key] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| المفتاح | المفتاح الذي يحدد القيمة. |

### قيمة الإرجاع

يرجع الكائن بالمفتاح المحدد.

### Property Value

الكائن.

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


