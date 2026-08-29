---
title: "IPartialPixelLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يتوافق مع البكسلات التي تم تحميلها جزئيًا."
type: docs
weight: 132
url: /ar/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

يتوافق مع البكسلات التي تم تحميلها جزئيًا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | يعالج البكسلات المحمّلة. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


يعالج البكسلات المحمّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل البكسلات. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | البكسلات. |
| start | [Point](../../com.aspose.psd/point) | نقطة بكسلات البداية. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست المستطيل الكامل المتاح. |
| end | [Point](../../com.aspose.psd/point) | نقطة بكسلات النهاية. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست المستطيل الكامل المتاح. |

