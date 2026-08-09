---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة TiffStreamReader. تقرأ مصفوفة من القيم الصحيحة الموقعة من الدفق"
type: docs
weight: 140
url: /ar/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

يقرأ مصفوفة من القيم الصحيحة الموقعة من الدفق.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضع | Int64 | الموضع للقراءة منه. |
| العدد | Int64 | عدد العناصر. |

### قيمة الإرجاع

مصفوفة القيم الصحيحة الموقعة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | count;عدد البايتات الإجمالي سالب. + count + x4= + totalBytes |

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


