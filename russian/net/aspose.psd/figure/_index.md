---
title: "Класс Figure"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Figure. Фигура. Контейнер для фигур."
type: docs
weight: 1210
url: /ru/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

Фигура. Контейнер для форм.

```csharp
public class Figure : ObjectWithBounds
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Figure](figure/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Получает или задает границы объекта. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Получает или задает значение, указывающее, закрыта ли эта фигура. Закрытая фигура будет иметь значение только в случае, когда первая и последняя формы фигуры являются непрерывными. В таком случае первая точка первой формы будет соединена прямой линией с последней точкой последней формы. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Получает все сегменты фигуры. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Получает формы фигуры. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Добавляет форму к фигуре. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Добавляет диапазон фигур в фигуру. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Удаляет форму из фигуры. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Удаляет диапазон фигур из фигуры. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Обращает порядок фигур в этом рисунке и порядок точек фигур. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |

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


