---
title: "IPartialArgb64PixelLoader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "محمل بكسلات ARGB 64-بت."
type: docs
weight: 131
url: /ar/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

محمل بكسلات ARGB 64-بت.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | يعالج البكسلات المحمّلة. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


يعالج البكسلات المحمّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل البكسلات. |
| بكسلات | long[] | بكسلات ARGB 64-بت. |
| start | [Point](../../com.aspose.psd/point) | نقطة بكسلات البداية. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست المستطيل الكامل المتاح. |
| end | [Point](../../com.aspose.psd/point) | نقطة بكسلات النهاية. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست المستطيل الكامل المتاح. |

