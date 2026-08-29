---
title: "Класс GraphicsPath"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.GraphicsPath. Представляет серию соединённых линий и кривых. Этот класс нельзя наследовать."
type: docs
weight: 4790
url: /ru/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Представляет серию соединённых линий и кривых. Этот класс не может быть унаследован.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Инициализирует новый экземпляр класса `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Инициализирует новый экземпляр класса `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Инициализирует новый экземпляр класса `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Инициализирует новый экземпляр класса `GraphicsPath`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Получает или задает границы объекта. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Получает фигуры пути. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Получает или задает перечисление [`FillMode`](../fillmode/), которое определяет, как заполняются внутренние области фигур в этом `GraphicsPath`. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Добавляет новую фигуру. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Добавляет новые фигуры. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Добавляет указанный `GraphicsPath` к этому пути. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Добавляет указанный `GraphicsPath` к этому пути. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Выполняет глубокое клонирование этого графического пути. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Преобразует каждую кривую в этом пути в последовательность соединённых отрезков. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Применяет указанное преобразование, а затем преобразует каждую кривую в этом `GraphicsPath` в последовательность соединённых отрезков. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Преобразует каждую кривую в этом `GraphicsPath` в последовательность соединённых отрезков. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/) и с использованием указанного [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/) и с использованием указанного [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/) и с использованием указанного [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Указывает, находится ли указанная точка внутри (под) контура этого `GraphicsPath`, когда он отрисован указанным [`Pen`](../pen/) и с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Указывает, находится ли указанная точка внутри этого `GraphicsPath` в видимой области отсечения указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Указывает, находится ли указанная точка внутри этого `GraphicsPath`, используя указанный [`Graphics`](../graphics/). |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Удаляет фигуру. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Удаляет фигуры. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Очищает графический путь и устанавливает [`FillMode`](../fillmode/) в Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Меняет порядок фигур, форм и точек в каждой форме этого `GraphicsPath` на обратный. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Добавляет дополнительный контур к пути. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Добавляет дополнительный контур к `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Заменяет этот `GraphicsPath` кривыми, которые ограничивают область, заполняемую при отрисовке этого пути указанным pen. |

## Примеры

В этом примере используется класс GraphicsPath и класс Graphics для создания и манипулирования фигурами на поверхности изображения. Пример создает новое изображение и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отрисовки путей на поверхности. В конце изображение экспортируется в формат файла Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Добавьте фигуры в объект Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Добавьте объект Figure в GraphicsPath
    graphicspath.AddFigure(figure);

    //Нарисуйте путь объектом Pen цвета чёрный
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Создайте экземпляр TiffOptions и задайте его различные свойства
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Сохраните все изменения.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### См. также

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


