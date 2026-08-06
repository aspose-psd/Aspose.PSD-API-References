---
title: "IPartialArgb32PixelLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يتوافق مع بكسلات ARGB 32-بت التي تم تحميلها جزئيًا."
type: docs
weight: 130
url: /ar/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

يتوافق مع بكسلات ARGB 32-بت التي تم تحميلها جزئيًا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | يعالج البكسلات المحمّلة. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


يعالج البكسلات المحمّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل البكسلات. |
| بكسلات | int[] | البكسلات بتنسيق argb |
| start | [Point](../../com.aspose.psd/point) | نقطة بكسلات البداية. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست المستطيل الكامل المتاح. |
| end | [Point](../../com.aspose.psd/point) | نقطة بكسلات النهاية. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست المستطيل الكامل المتاح. |

