---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Соответствует 32-битным ARGB‑пикселям, загруженным частично."
type: docs
weight: 130
url: /ru/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Соответствует 32-битным ARGB‑пикселям, загруженным частично.
## Методы

| Метод | Описание |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Обрабатывает загруженные пиксели. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Обрабатывает загруженные пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник пикселей. |
| пиксели | int[] | Пиксели в формате argb |
| start | [Point](../../com.aspose.psd/point) | Точка начальных пикселей. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.psd/point) | Точка конечных пикселей. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

