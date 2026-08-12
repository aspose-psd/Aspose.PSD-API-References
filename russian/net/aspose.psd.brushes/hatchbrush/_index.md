---
title: "Класс HatchBrush"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Brushes.HatchBrush. Определяет прямоугольную кисть с штриховкой, цветом переднего плана и цветом фона. Этот класс не может быть наследован"
type: docs
weight: 130
url: /ru/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Определяет прямоугольную кисть с штриховкой, цветом переднего плана и цветом фона. Этот класс не может быть наследован.

```csharp
public sealed class HatchBrush : Brush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Получает или задает цвет промежутков между штриховыми линиями. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Получает или задает цвет штриховых линий. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Получает или задает стиль штриховки этой кисти. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Создает новый глубокий клон текущего [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |

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

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


