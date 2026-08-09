---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة IColorConverter. تحول البيانات الممررة إلى صيغة الإخراج"
type: docs
weight: 10
url: /ar/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

يحوِّل البيانات الممرَّرة إلى صيغة الإخراج.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | تنسيق المصدر. |
| البيانات | Byte[] | بيانات المصدر. |
| offset | Int32 | الإزاحة بالبايتات حيث يجب أن يبدأ نسخ البيانات. |
| bitStart | Int32 | بداية البت. ملاحظة أن هذه القيمة ليست قيمة محاذاة بالبايت بل هي البت الفعلي حيث يجب أن يبدأ النسخ. |
| samplesCount | Int32 | عدد العينات. |
| linesCount | Int32 | عدد الأسطر. |
| destFormat | PixelDataFormat | تنسيق الوجهة. |
| outputData | Byte[] | بيانات الإخراج. |
| outputOffset | Int32 | إزاحة الإخراج حيث يجب أن يبدأ نسخ البيانات. |

### قيمة الإرجاع

عدد البايتات المحوّلة.

### انظر أيضًا

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


