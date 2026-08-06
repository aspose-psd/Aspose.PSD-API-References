---
title: "IPartialRawDataLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "محمل البيانات الجزئية."
type: docs
weight: 133
url: /ar/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

محمل البيانات الجزئية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | يعالج البيانات المحمَّلة. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | يعالج البيانات المحمَّلة. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


يعالج البيانات المحمَّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل البيانات. |
| بيانات | byte[] | البيانات الخام. |
| start | [Point](../../com.aspose.psd/point) | نقطة بدء البيانات. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملاً لدينا. |
| end | [Point](../../com.aspose.psd/point) | نقطة نهاية البيانات. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملاً لدينا. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


يعالج البيانات المحمَّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل البيانات. |
| بيانات | byte[] | البيانات الخام. |
| start | [Point](../../com.aspose.psd/point) | نقطة بدء البيانات. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملاً لدينا. |
| end | [Point](../../com.aspose.psd/point) | نقطة نهاية البيانات. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملاً لدينا. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

