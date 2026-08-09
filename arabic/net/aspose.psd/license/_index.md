---
title: "الفئة License"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.License. توفر طرقًا لترخيص المكوّن"
type: docs
weight: 5540
url: /ar/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | يُهيئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | يرخص المكوّن. |

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد تجميع الدخول، ثم في الموارد المدمجة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


