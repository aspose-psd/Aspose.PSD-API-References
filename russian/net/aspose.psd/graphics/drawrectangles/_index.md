---
title: Graphics.DrawRectangles
second_title: Справочник по Aspose.PSD для .NET API
description: Graphics метод. Рисует серию прямоугольников указанныхRectangleF структуры.
type: docs
weight: 310
url: /ru/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Рисует серию прямоугольников, указанных[`RectangleF`](../../rectanglef/) структуры.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) который определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | RectangleF[] | Массив[`RectangleF`](../../rectanglef/) структуры, которые представляют прямоугольники для рисования. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *rects* нулевой. |

### Смотрите также

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* пространство имен [Aspose.PSD](../../graphics/)
* сборка [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Рисует серию прямоугольников, указанных[`Rectangle`](../../rectangle/) структуры.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) который определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | Rectangle[] | Массив[`Rectangle`](../../rectangle/) структуры, которые представляют прямоугольники для рисования. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *rects* нулевой. |

### Примеры

В этом примере показано создание и использование объектов Pen. В примере создается новое изображение и рисуются прямоугольники на поверхности изображения.

```csharp
[C#]

//Создаем экземпляр изображения
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем экземпляр Graphics и инициализируем его объектом Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Очистить графическую поверхность белым цветом
    graphics.Clear(Aspose.PSD.Color.White);

    //Создаем экземпляр Pen красного цвета и ширины 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Создаем экземпляр HatchBrush и устанавливаем его свойства
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Создаем экземпляр пера
    // инициализируем его объектом HatchBrush и шириной
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Рисуем прямоугольники, указав объект Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Рисуем прямоугольники, указав объект Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Создаем параметры экспорта и инициализируем их.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // сохранить все изменения.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Смотрите также

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* пространство имен [Aspose.PSD](../../graphics/)
* сборка [Aspose.PSD](../../../)


