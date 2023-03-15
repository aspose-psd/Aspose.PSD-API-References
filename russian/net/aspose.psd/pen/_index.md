---
title: Class Pen
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Pen сорт. Определяет объект используемый для рисования линий кривых и фигур.
type: docs
weight: 5200
url: /ru/net/aspose.psd/pen/
---
## Pen class

Определяет объект, используемый для рисования линий, кривых и фигур.

```csharp
public class Pen : TransparencySupporter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Инициализирует новый экземпляр`Pen` класс с указанным[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Инициализирует новый экземпляр`Pen` класс с указанным цветом. |
| [Pen](pen/#constructor_1)(Brush, float) | Инициализирует новый экземпляр`Pen` класс с указанным[`Brush`](./brush/) и[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Инициализирует новый экземпляр`Pen` класс с указанным[`Color`](./color/) и[`Width`](./width/) свойства. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Получает или задает выравнивание для этого`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Получает или задает[`Brush`](./brush/) что определяет атрибуты этого`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Получает или устанавливает цвет этого`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Получает или задает массив значений, указывающий составное перо. Составное перо рисует составную линию, состоящую из параллельных линий и пробелов. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Получает или задает пользовательскую заглушку для использования в конце строк, нарисованных с помощью этого`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Получает или задает пользовательскую заглушку для использования в начале строк, нарисованных с помощью этого`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Получает или задает стиль заглавных букв, используемый в конце штрихов, составляющих пунктирные линии, нарисованные с помощью этого`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Получает или задает расстояние от начала линии до начала штрихового узора. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Получает или задает массив пользовательских дефисов и пробелов. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Получает или задает стиль, используемый для пунктирных линий, нарисованных с помощью этого`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Получает или задает стиль заглавных букв, используемый в конце строк, нарисованных с помощью этого`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Получает или задает стиль соединения концов двух последовательных линий, нарисованных с помощью этого`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Получает или задает предел толщины соединения на скошенном углу. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Получает или задает прозрачность объекта. Значение должно быть от 0 до 1. Значение 0 означает, что объект полностью виден, значение 1 означает, что объект полностью непрозрачен. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Получает стиль линий, нарисованных с помощью этого`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Получает или задает стиль заглавных букв, используемый в начале строк, нарисованных с помощью этого`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Получает или задает копию геометрического преобразования для этого`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Получает или задает ширину этого`Pen` , в единицах объекта Graphics, используемого для рисования. |

## Методы

| Имя | Описание |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Умножает матрицу преобразования для этого`Pen` указанным[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Умножает матрицу преобразования для этого`Pen` указанным[`Matrix`](../matrix/) в указанном порядке. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Сбрасывает матрицу геометрического преобразования для этого`Pen` к личности. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанный угол. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование по указанным коэффициентам. Этот метод добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование по указанным коэффициентам в указанном порядке. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Устанавливает значения, определяющие стиль заглавных букв, используемых для окончания линий, нарисованных этим`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примеры

В этом примере показано создание и использование объектов Pen. В примере создается новое изображение и рисуются прямоугольники на поверхности изображения.

```csharp
[C#]

//Создаем экземпляр изображения
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем экземпляр Graphics и инициализируем его объектом Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Очистить графическую поверхность белым цветом
    graphics.Clear(Aspose.PSD.Color.White);

    //Создаем экземпляр Pen красного цвета и ширины 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Создаем экземпляр HatchBrush и устанавливаем его свойства
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Создаем экземпляр пера
    // инициализируем его объектом HatchBrush и шириной
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Рисуем прямоугольники, указав объект Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Рисуем прямоугольники, указав объект Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Создаем параметры экспорта и инициализируем их.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // сохранить все изменения.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Смотрите также

* class [TransparencySupporter](../transparencysupporter/)
* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


