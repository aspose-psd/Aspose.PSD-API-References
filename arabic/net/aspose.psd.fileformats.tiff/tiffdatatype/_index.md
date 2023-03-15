---
title: Class TiffDataType
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Tiff.TiffDataType فصل. نوع بيانات tiff .
type: docs
weight: 4210
url: /ar/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

نوع بيانات tiff .

```csharp
public abstract class TiffDataType : IComparable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | الحصول على حجم البيانات الإضافي بالبايت (في حالة عدم كفاية 12 بايت لملاءمة بيانات العلامة). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | يحصل على عدد العناصر . |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | الحصول على حجم البيانات الإضافي بالبايت (في حالة عدم كفاية 12 بايت لملاءمة بيانات العلامة). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على تمثيل صحيح لمعرف العلامة . |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. تحتوي العلامة الصالحة على بيانات يمكن الاحتفاظ بها. لا يمكن تخزين العلامة غير الصالحة. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف العلامة . |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | يحصل على نوع العلامة . |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | الحصول على القيمة التي يحتوي عليها نوع البيانات هذا أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | يقرأ بيانات العلامة . |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي بكائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يحدث في نفس الموضع في ترتيب الفرز مثل الكائن الآخر. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | يقوم بعمل نسخة عميقة من هذا المثيل. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات العلامة الإضافية . |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات العلامة . |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* المجسم [Aspose.PSD](../../)


