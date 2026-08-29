---
title: "Класс StreamSource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Sources.StreamSource. Представляет источник потока"
type: docs
weight: 6120
url: /ru/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

Представляет источник потока.

```csharp
public sealed class StreamSource : Source
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Инициализирует новый экземпляр класса `StreamSource`. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Инициализирует новый экземпляр класса `StreamSource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Получает значение, указывающее, следует ли освобождать поток, когда контейнер освобождается. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Получает поток. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Получает контейнер потока. |

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

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


