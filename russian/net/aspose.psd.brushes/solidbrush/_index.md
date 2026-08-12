---
title: "Класс SolidBrush"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Brushes.SolidBrush. Solid brush предназначен для непрерывного рисования конкретным цветом. Этот класс не может быть унаследован."
type: docs
weight: 200
url: /ru/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Сплошная кисть предназначена для непрерывного рисования определённым цветом. Этот класс не может быть наследован.

```csharp
public sealed class SolidBrush : Brush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Инициализирует новый экземпляр класса `SolidBrush`. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Инициализирует новый экземпляр класса `SolidBrush`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Получает или задает цвет кисти. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Создает новый глубокий клон текущего [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |

## Примеры

В этом примере используется класс Graphics для создания примитивных фигур на поверхности Image. Чтобы продемонстрировать работу, пример создает новое изображение в формате PSD и рисует примитивные фигуры на поверхности Image с помощью методов Draw, предоставленных классом Graphics, затем экспортирует его в формат PSD.

```csharp
[C#]

//Создайте экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создайте и инициализируйте экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить поверхность Graphics
    graphics.Clear(Color.Wheat);

    //Нарисуйте дугу, указав объект Pen с чёрным цветом, 
    //прямоугольник, окружающий дугу, начальный угол и угол разворота
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Нарисуйте кривую Безье, указав объект Pen с синим цветом и координатные точки.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Нарисуйте кривую, указав объект Pen с зелёным цветом и массив точек
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Нарисуйте эллипс, используя объект Pen и окружающий его прямоугольник
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Нарисуйте линию 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Нарисуйте сектор пирога
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Нарисуйте многоугольник, указав объект Pen с красным цветом и массив точек
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Нарисуйте прямоугольник
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Создайте объект SolidBrush и задайте его различные свойства
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Нарисуйте строку, используя объект SolidBrush и шрифт, в указанной точке
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Создайте экземпляр PngOptions и задайте его различные свойства
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Сохраните все изменения.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### См. также

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


