---
title: "Graphics.DrawImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует указанное Image, используя его оригинальный физический размер в указанном месте."
type: docs
weight: 230
url: /ru/net/aspose.psd/graphics/drawimage/
---
{{< psd/tize >}}
## DrawImage(Image, PointF) {#drawimage_1}

Рисует указанное [`Image`](../image/), используя его оригинальный физический размер, в указанном месте.

```csharp
public void DrawImage(Image sourceImage, PointF point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| point | PointF | Структура [`PointF`](../../pointf/), представляющая верхний левый угол нарисованного изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float) {#drawimage_22}

Рисует указанное [`Image`](../image/), используя его оригинальный физический размер, в указанном месте.

```csharp
public void DrawImage(Image sourceImage, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| x | Single | Координата x верхнего левого угла рисуемого изображения. |
| y | Single | Координата y верхнего левого угла рисуемого изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF) {#drawimage_15}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, RectangleF rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/), определяющая местоположение и размер нарисованного изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit) {#drawimage_11}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectDestination | Rectangle | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit) {#drawimage_16}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectDestination | RectangleF | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_12}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectDestination | Rectangle | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица. |
| imageAttributes | ImageAttributes | Атрибуты изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_17}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectDestination | RectangleF | Прямоугольник назначения, в котором будет выполняться отрисовка. |
| graphicsUnit | GraphicsUnit | Графическая единица. |
| imageAttributes | ImageAttributes | Атрибуты изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit) {#drawimage_13}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectSource | Rectangle | Исходный прямоугольник. |
| rectDestination | Rectangle | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit) {#drawimage_18}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectSource | RectangleF | Исходный прямоугольник. |
| rectDestination | RectangleF | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_14}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectSource | Rectangle | Исходный прямоугольник. |
| rectDestination | Rectangle | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица. |
| imageAttributes | ImageAttributes | Атрибуты изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_19}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rectSource | RectangleF | Исходный прямоугольник. |
| rectDestination | RectangleF | Прямоугольник назначения. |
| graphicsUnit | GraphicsUnit | Графическая единица измерения, которую следует использовать. |
| imageAttributes | ImageAttributes | Атрибуты изображения, которые следует использовать. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[]) {#drawimage_6}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, Point[] destPoints)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | Point[] | Массив из трёх структур PointF, определяющих параллелограмм. |

### См. также

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle) {#drawimage_7}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | Point[] | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | Rectangle | Исходный прямоугольник. |

### См. также

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit) {#drawimage_8}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | Point[] | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | Rectangle | Исходный прямоугольник. |
| srcUnit | GraphicsUnit | Единицы измерения. |

### См. также

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_9}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | Point[] | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | Rectangle | Исходный прямоугольник. |
| srcUnit | GraphicsUnit | Единицы измерения. |
| imageAttributes | ImageAttributes | Атрибуты изображения. |

### См. также

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[]) {#drawimage_2}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, PointF[] destPoints)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | PointF[] | Массив из трёх структур PointF, определяющих параллелограмм. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | изображение |

### См. также

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF) {#drawimage_3}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | PointF[] | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | RectangleF | Исходный прямоугольник. |

### См. также

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit) {#drawimage_4}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | PointF[] | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | RectangleF | Исходный прямоугольник. |
| srcUnit | GraphicsUnit | Единицы измерения. |

### См. также

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_5}

Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для отрисовки. |
| destPoints | PointF[] | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | RectangleF | Исходный прямоугольник. |
| srcUnit | GraphicsUnit | Единицы измерения. |
| imageAttributes | ImageAttributes | Атрибуты изображения. |

### См. также

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float, float, float) {#drawimage_23}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| x | Single | Координата x верхнего левого угла рисуемого изображения. |
| y | Single | Координата y верхнего левого угла рисуемого изображения. |
| width | Single | Ширина отрисованного изображения. |
| height | Single | Высота отрисованного изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point) {#drawimage}

Рисует указанное [`Image`](../image/), используя его оригинальный физический размер, в указанном месте.

```csharp
public void DrawImage(Image sourceImage, Point point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| point | Point | [`Point`](../../point/) структура, представляющая расположение верхнего левого угла отрисованного изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int) {#drawimage_20}

Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат.

```csharp
public void DrawImage(Image sourceImage, int x, int y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| x | Int32 | Координата x верхнего левого угла рисуемого изображения. |
| y | Int32 | Координата y верхнего левого угла рисуемого изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle) {#drawimage_10}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, Rectangle rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) структура, определяющая расположение и размер отрисованного изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int, int, int) {#drawimage_21}

Рисует указанное [`Image`](../image/) в указанном месте и с указанным размером.

```csharp
public void DrawImage(Image sourceImage, int x, int y, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | Image | Изображение, которое будет отрисовано. |
| x | Int32 | Координата x верхнего левого угла рисуемого изображения. |
| y | Int32 | Координата y верхнего левого угла рисуемого изображения. |
| width | Int32 | Ширина отрисованного изображения. |
| height | Int32 | Высота отрисованного изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *sourceImage* равно null. |

### См. также

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


