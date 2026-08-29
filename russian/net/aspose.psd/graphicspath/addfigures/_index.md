---
title: "GraphicsPath.AddFigures"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод GraphicsPath. Добавляет новые фигуры"
type: docs
weight: 60
url: /ru/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

Добавляет новые фигуры.

```csharp
public void AddFigures(Figure[] figures)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| фигуры | Figure[] | Фигуры для добавления. |

## Примеры

В этом примере создаётся новое изображение и рисуются различные фигуры с использованием Figures и GraphicsPath на поверхности изображения

```csharp
[C#]

//Создайте экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создайте и инициализируйте экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить поверхность Graphics
    graphics.Clear(Color.Wheat);

    //Создайте экземпляр класса GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Создайте экземпляр класса Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Добавить фигуру к объекту Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Создайте экземпляр класса Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Добавить фигуру к объекту Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Добавьте объект Figure в GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Нарисуйте путь объектом Pen цвета чёрный
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Создайте параметры экспорта и инициализируйте их.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Сохраните все изменения.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### См. также

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


