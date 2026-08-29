---
title: "Figure.AddShape"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Figure. Добавляет форму в фигуру"
type: docs
weight: 60
url: /ru/net/aspose.psd/figure/addshape/
---
{{< psd/tize >}}
## Figure.AddShape method

Добавляет форму к фигуре.

```csharp
public void AddShape(Shape shape)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| форма | Форма | Форма для добавления. |

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

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


