---
title: GraphicsPath
second_title: Справочник по Aspose.PSD для .NET API
description: Представляет набор соединенных линий и кривых. Этот класс не может быть унаследован.
type: docs
weight: 4250
url: /ru/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Представляет набор соединенных линий и кривых. Этот класс не может быть унаследован.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds) { get; } | Получает или устанавливает границы объекта. |
| [Figures](../../aspose.psd/graphicspath/figures) { get; } | Получает цифры пути. |
| [FillMode](../../aspose.psd/graphicspath/fillmode) { get; set; } | Получает или задает[`FillMode`](../fillmode) перечисление, которое определяет, как внутренности фигур в этом[`GraphicsPath`](../graphicspath) заполнены. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure)(Figure) | Добавляет новую фигуру. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures)(Figure[]) | Добавляет новые фигуры. |
| [AddPath](../../aspose.psd/graphicspath/addpath#addpath)(GraphicsPath) | Добавляет указанный[`GraphicsPath`](../graphicspath) на этот путь. |
| [AddPath](../../aspose.psd/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Добавляет указанный[`GraphicsPath`](../graphicspath) на этот путь. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone)() | Выполняет глубокое клонирование этого графического пути. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten)() | Преобразует каждую кривую на этом пути в последовательность соединенных сегментов линии. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten_1)(Matrix) | Применяет указанное преобразование, а затем преобразует каждую кривую в этот[`GraphicsPath`](../graphicspath) в последовательность соединенных отрезков линии. |
| [Flatten](../../aspose.psd/graphicspath/flatten#flatten_2)(Matrix, float) | Преобразует каждую кривую в этот[`GraphicsPath`](../graphicspath) в последовательность соединенных отрезков линии. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible)(Point) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_2)(PointF) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_6)(float, float) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_4)(int, int) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) в видимой области клипа указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) , используя указанный[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure)(Figure) | Удаляет фигурку. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures)(Figure[]) | Удаляет фигуры. |
| [Reset](../../aspose.psd/graphicspath/reset)() | Очищает путь к графике и устанавливает[`FillMode`](../fillmode) кAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse)() | Меняет порядок фигур, фигур и точек в каждой фигуре этого изображения на противоположный.[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.psd/graphicspath/transform)(Matrix) | Применяет указанное преобразование к фигуре. |
| [Warp](../../aspose.psd/graphicspath/warp#warp)(PointF[], RectangleF) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.psd/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.psd/graphicspath/widen#widen)(Pen) | Добавляет дополнительный контур пути. |
| [Widen](../../aspose.psd/graphicspath/widen#widen_1)(Pen, Matrix) | Добавляет дополнительный контур к[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.psd/graphicspath/widen#widen_2)(Pen, Matrix, float) | Заменяет это[`GraphicsPath`](../graphicspath) с кривыми, которые охватывают область, которая заполняется, когда этот путь рисуется указанным пером. |

### Примеры

В этих примерах используются GraphicsPath и класс Graphics для создания и управления рисунками на поверхности изображения. Пример создает новое изображение и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отображения путей на поверхности. Наконец, изображение экспортируется в формат файла Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Добавляем фигуры к объекту Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Добавить объект Figure в GraphicsPath
    graphicspath.AddFigure(figure);

    // Нарисовать путь с помощью объекта Pen черного цвета
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Создаем экземпляр TiffOptions и устанавливаем его различные свойства
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // сохранить все изменения.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Смотрите также

* class [ObjectWithBounds](../objectwithbounds)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
