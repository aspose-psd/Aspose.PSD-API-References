---
title: "License.SetLicense"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة License. تُرخص المكوّن"
type: docs
weight: 20
url: /ar/net/aspose.psd/license/setlicense/
---
{{< psd/tize >}}
## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licenseName)
```

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (بدء التشغيل).

5. مورد مدمج في تجميع استدعاء العميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مدمج في تجميع استدعاء العميل.

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد تجميع الدخول، ثم في الموارد المدمجة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مدمج. استخدم سلسلة فارغة للتبديل إلى وضع التقييم.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من تدفق.

## أمثلة

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### انظر أيضًا

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


