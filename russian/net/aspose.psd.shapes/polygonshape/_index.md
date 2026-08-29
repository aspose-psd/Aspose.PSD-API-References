---
title: "Класс PolygonShape"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.Shapes.PolygonShape класс. Представляет форму многоугольника"
type: docs
weight: 6010
url: /ru/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Представляет форму многоугольника.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Инициализирует новый экземпляр класса `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Инициализирует новый экземпляр класса `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Инициализирует новый экземпляр класса `PolygonShape`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Получает границы объекта. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Получает центр формы. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Получает конечную точку фигуры. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Получает значение, указывающее, имеет ли форма сегменты. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Получает или задает значение, указывающее, закрыта ли фигура. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Получает или задает точки кривой. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Получает сегменты фигуры. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Получает начальную точку фигуры. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Изменяет порядок точек для этой фигуры. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


