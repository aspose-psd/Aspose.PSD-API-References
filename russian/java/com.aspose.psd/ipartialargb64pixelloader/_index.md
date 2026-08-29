---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Загрузчик 64‑битных ARGB‑пикселей."
type: docs
weight: 131
url: /ru/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Загрузчик 64‑битных ARGB‑пикселей.
## Методы

| Метод | Описание |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Обрабатывает загруженные пиксели. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Обрабатывает загруженные пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник пикселей. |
| пиксели | long[] | Эти 64‑битные ARGB‑пиксели. |
| start | [Point](../../com.aspose.psd/point) | Точка начальных пикселей. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.psd/point) | Точка конечных пикселей. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

