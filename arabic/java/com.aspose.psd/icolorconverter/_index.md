---
title: "IColorConverter"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "محول اللون."
type: docs
weight: 116
url: /ar/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

محول اللون.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | يحوِّل البيانات الممرَّرة إلى صيغة الإخراج. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


يحوِّل البيانات الممرَّرة إلى صيغة الإخراج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | تنسيق المصدر. |
| بيانات | byte[] | بيانات المصدر. |
| الإزاحة | int | الإزاحة بالبايت حيث يجب أن يبدأ نسخ البيانات. |
| bitStart | int | بداية البت. لاحظ أن هذه القيمة ليست قيمة محاذاة للبايت بل هي البت الفعلي حيث يجب أن يبدأ النسخ. |
| samplesCount | int | عدد العينات. |
| linesCount | int | عدد الأسطر. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | تنسيق الوجهة. |
| outputData | byte[] | بيانات الإخراج. |
| outputOffset | int | إزاحة الإخراج حيث يجب أن يبدأ نسخ البيانات. |

**Returns:**
int - عدد البايتات المحوّلة.
