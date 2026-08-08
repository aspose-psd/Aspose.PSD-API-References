---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Соответствует пикселям, загруженным частично."
type: docs
weight: 132
url: /ru/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Соответствует пикселям, загруженным частично.
## Методы

| Метод | Описание |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Обрабатывает загруженные пиксели. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Обрабатывает загруженные пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник пикселей. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Пиксели. |
| start | [Point](../../com.aspose.psd/point) | Точка начальных пикселей. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.psd/point) | Точка конечных пикселей. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

