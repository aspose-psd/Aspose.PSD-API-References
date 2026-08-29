---
title: "TiffDataType.CompareTo"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة TiffDataType. تقارن النسخة الحالية مع كائن آخر من نفس النوع وتُرجع عددًا صحيحًا يشير إلى ما إذا كانت النسخة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر"
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.tiff/tiffdatatype/compareto/
---
{{< psd/tize >}}
## TiffDataType.CompareTo method

يقارن المثيل الحالي بكائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مثل الكائن الآخر.

```csharp
public int CompareTo(object obj)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | Object | كائن للمقارنة مع هذه النسخة. |

### قيمة الإرجاع

عدد صحيح موقع 32 بت يشير إلى الترتيب النسبي للكائنات التي يتم مقارنتها. قيمة الإرجاع لها هذه المعاني: القيمة المعنى أقل من الصفر هذه النسخة أقل من *obj*. صفر هذه النسخة مساوية لـ *obj*. أكبر من الصفر هذه النسخة أكبر من *obj*.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | النوع المتوقع هو TiffDataType. |

### انظر أيضًا

* class [TiffDataType](../)
* namespace [Aspose.PSD.FileFormats.Tiff](../../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../../)


