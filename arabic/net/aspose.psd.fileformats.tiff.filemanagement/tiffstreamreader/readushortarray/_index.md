---
title: "TiffStreamReader.ReadUShortArray"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة TiffStreamReader. تقرأ مصفوفة من القيم الصحيحة غير الموقّعة من الدفق"
type: docs
weight: 220
url: /ar/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readushortarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadUShortArray method

يقرأ مصفوفة من القيم الصحيحة غير موقعة من الدفق.

```csharp
public ushort[] ReadUShortArray(long position, long count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضع | Int64 | الموضع للقراءة منه. |
| العدد | Int64 | عدد العناصر. |

### قيمة الإرجاع

المصفوفة من القيم الصحيحة غير الموقّعة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | count;عدد البايتات الإجمالي سالب. + count + x2= + totalBytes |

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


