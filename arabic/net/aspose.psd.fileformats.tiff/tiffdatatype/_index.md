---
title: "الفئة TiffDataType"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FileFormats.Tiff.TiffDataType. نوع بيانات tiff"
type: docs
weight: 4680
url: /ar/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

نوع بيانات tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | يحصل على حجم البيانات الإضافية بالبايتات (في حال عدم كفاية 12 بايتًا لاستيعاب بيانات العلامة). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | يحصل على عدد العناصر. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم البيانات الإضافية بالبايتات (في حال عدم كفاية 12 بايتًا لاستيعاب بيانات العلامة). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على تمثيل رقم معرف العلامة. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. العلامة الصالحة تحتوي على بيانات يمكن حفظها. العلامة غير الصالحة لا يمكن تخزينها. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف العلامة. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | يحصل على نوع العلامة. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | يحصل أو يضبط القيمة التي يحتويها نوع البيانات هذا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | يقرأ بيانات العلامة. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي بكائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مثل الكائن الآخر. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | ينفذ استنساخًا عميقًا لهذا المثيل. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | إرجاع String تمثل هذا المثيل. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات العلامة الإضافية. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات العلامة. |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


