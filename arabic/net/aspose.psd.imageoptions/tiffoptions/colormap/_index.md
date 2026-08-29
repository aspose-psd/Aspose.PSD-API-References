---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية TiffOptions. يحصل أو يضبط خريطة الألوان"
type: docs
weight: 70
url: /ar/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

يحصل أو يعيّن خريطة الألوان.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

خريطة الألوان.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | قيمة |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | قد يتم تعريف خريطة الألوان للعينات لكل بكسل مساوية لـ 1 فقط. أو لم يتم تعريف عدد البتات لكل عينة. |
| ArgumentOutOfRangeException | value;يجب أن يتطابق طول المصفوفة مع الصيغة التالية: 3 * (2**BitsPerSample). |

### انظر أيضًا

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


