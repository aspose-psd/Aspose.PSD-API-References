---
title: "Graphics.DrawRectangles"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует серию прямоугольников, заданных структурами RectangleF."
type: docs
weight: 320
url: /ru/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Рисует серию прямоугольников, заданных структурами [`RectangleF`](../../rectanglef/).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и стиль контуров прямоугольников. |
| rects | RectangleF[] | Массив структур [`RectangleF`](../../rectanglef/), представляющих прямоугольники для рисования. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *rects* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Рисует серию прямоугольников, заданных структурами [`Rectangle`](../../rectangle/).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и стиль контуров прямоугольников. |
| rects | Rectangle[] | Массив структур [`Rectangle`](../../rectangle/), представляющих прямоугольники для рисования. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *rects* равно null. |

## Примеры

Этот пример показывает создание и использование объектов Pen. Пример создает новое Image и рисует Rectangles на поверхности Image.

```csharp
[C#]

//Создайте экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создайте экземпляр Graphics и инициализируйте его объектом Image.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистите поверхность Graphics белым цветом.
    graphics.Clear(Aspose.PSD.Color.White);

    //Создайте экземпляр Pen с цветом красным и шириной 5.
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Создайте экземпляр HatchBrush и задайте его свойства.
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Создайте экземпляр Pen.
    //Инициализируйте его объектом HatchBrush и шириной.
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Рисуйте Rectangles, указывая объект Pen.
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Рисуйте Rectangles, указывая объект Pen.
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Создайте параметры экспорта и инициализируйте их.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Сохраните все изменения.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### См. также

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


