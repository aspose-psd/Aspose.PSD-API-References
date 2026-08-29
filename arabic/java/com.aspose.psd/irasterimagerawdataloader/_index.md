---
title: "IRasterImageRawDataLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "محمل البيانات الخام للصورة النقطية."
type: docs
weight: 137
url: /ar/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

محمل البيانات الخام للصورة النقطية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | يحصل على إعدادات البيانات الخام الحالية. |
| [isRawDataAvailable()](#isRawDataAvailable--) | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | يحمّل البيانات الخام. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات دون تحويل.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الخام مدعومًا.

**Returns:**
منطقي -  true  إذا كان تحميل البيانات الخام مدعومًا؛ وإلا،  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


يحمّل البيانات الخام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل لتحميل البيانات الخام منه. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | إعدادات البيانات الخام لاستخدامها مع البيانات المحملة. ملاحظة: إذا لم تكن البيانات بالتنسيق المحدد فسيتم إجراء تحويل للبيانات. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | محمل البيانات الخام. |

