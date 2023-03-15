---
title: Class License
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.License فصل. يوفر طرقًا لترخيص المكون.
type: docs
weight: 5050
url: /ar/net/aspose.psd/license/
---
## License class

يوفر طرقًا لترخيص المكون.

```csharp
public class License
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [License](license/)() | تهيئة مثيل جديد لهذه الفئة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | تراخيص المكون . |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | تراخيص المكون . |

### أمثلة

في هذا المثال ، سيتم إجراء محاولة للعثور على ملف ترخيص يسمى MyLicense.lic في المجلد الذي يحتوي على المكون ، في المجلد الذي يحتوي على التجميع الاستدعاء ، في مجلد تجميع الإدخال ثم في الموارد المضمنة للتجميع المتصل.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


