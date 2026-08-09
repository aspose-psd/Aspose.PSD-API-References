---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة XmpBasicPackage. تعيّن القيمة"
type: docs
weight: 120
url: /ar/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

يضبط القيمة.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | String | التمثيل النصي للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| قيمة | IXmlValue | القيمة للإضافة إليها. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


