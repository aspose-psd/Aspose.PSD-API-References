---
title: Class ArcShape
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Shapes.ArcShape сорт. Представляет форму дуги.
type: docs
weight: 5460
url: /ru/net/aspose.psd.shapes/arcshape/
---
## ArcShape class

Представляет форму дуги.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Инициализирует новый экземпляр`ArcShape` класс. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Инициализирует новый экземпляр`ArcShape` класс. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Инициализирует новый экземпляр`ArcShape` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Получает границы объекта. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Получает центр фигуры. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Получает конечную точку формы. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Получает или задает значение, указывающее, закрыта ли упорядоченная фигура. При обработке замкнутой упорядоченной формы начальная и конечная точки не имеют значения. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Получает точку левого нижнего прямоугольника. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Получает левую верхнюю точку прямоугольника. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Получает высоту прямоугольника. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Получает ширину прямоугольника. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Получает правую нижнюю точку прямоугольника. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Получает правую верхнюю точку прямоугольника. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Получает сегменты формы. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Получает или задает начальный угол. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Получает начальную точку формы. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Получает или задает угол развертки. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Меняет порядок точек этой фигуры на обратный. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |

### Примеры

В этом примере создается новое изображение и рисуются различные фигуры с помощью Figures и GraphicsPath на поверхности изображения.

```csharp
[C#]

//Создаем экземпляр изображения
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем и инициализируем экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить графическую поверхность
    graphics.Clear(Color.Wheat);

    //Создаем экземпляр класса GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Создаем экземпляр класса Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // Добавляем фигуру к объекту Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Создаем экземпляр класса Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // Добавляем фигуру к объекту Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Добавить объект Figure в GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Нарисовать путь с помощью объекта Pen черного цвета
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Создаем параметры экспорта и инициализируем их.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // сохранить все изменения.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Смотрите также

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* пространство имен [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* сборка [Aspose.PSD](../../)


