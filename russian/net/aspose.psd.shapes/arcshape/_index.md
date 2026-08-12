---
title: "Класс ArcShape"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.Shapes.ArcShape класс. Представляет форму дуги"
type: docs
weight: 5960
url: /ru/net/aspose.psd.shapes/arcshape/
---
{{< psd/tize >}}
## ArcShape class

Представляет дуговую форму.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Инициализирует новый экземпляр класса `ArcShape`. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Инициализирует новый экземпляр класса `ArcShape`. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Инициализирует новый экземпляр класса `ArcShape`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Получает границы объекта. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Получает центр формы. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Получает конечную точку фигуры. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Получает значение, указывающее, имеет ли форма сегменты. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Получает или задает значение, указывающее, закрыта ли упорядоченная форма. При обработке закрытой упорядоченной формы начальная и конечная точки не имеют значения. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Получает точку левого нижнего угла прямоугольника. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Получает точку левого верхнего угла прямоугольника. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Получает высоту прямоугольника. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Получает ширину прямоугольника. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Получает точку правого нижнего угла прямоугольника. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Получает точку правого верхнего угла прямоугольника. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Получает сегменты фигуры. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Получает или задает начальный угол. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Получает начальную точку фигуры. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Получает или задает угол охвата. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Изменяет порядок точек для этой фигуры. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |

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

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


