---
title: "Класс Pen"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Pen. Определяет объект, используемый для рисования линий, кривых и фигур."
type: docs
weight: 5690
url: /ru/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Определяет объект, используемый для рисования линий, кривых и фигур.

```csharp
public class Pen : TransparencySupporter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Инициализирует новый экземпляр класса `Pen` с указанным [`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | Инициализирует новый экземпляр класса `Pen` с указанным цветом. |
| [Pen](pen/#constructor_1)(Brush, float) | Инициализирует новый экземпляр класса `Pen` с указанными [`Brush`](./brush/) и [`Width`](./width/). |
| [Pen](pen/#constructor_3)(Color, float) | Инициализирует новый экземпляр класса `Pen` с указанными свойствами [`Color`](./color/) и [`Width`](./width/). |

## Свойства

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Получает или задает выравнивание для этого `Pen`. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Получает или задает [`Brush`](./brush/), определяющий атрибуты этого `Pen`. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Получает или задает цвет этого `Pen`. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Получает или задает массив значений, определяющий составную ручку. Составная ручка рисует составную линию, состоящую из параллельных линий и промежутков. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Получает или задает пользовательскую насадку, используемую в конце линий, нарисованных этим `Pen`. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Получает или задает пользовательскую насадку, используемую в начале линий, рисуемых этим `Pen`. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Получает или задает стиль насадки, используемый в конце штрихов, составляющих пунктирные линии, рисуемые этим `Pen`. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Получает или задает расстояние от начала линии до начала шаблона штриха. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Получает или задает массив пользовательских штрихов и пробелов. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Получает или задает стиль, используемый для пунктирных линий, рисуемых этим `Pen`. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Получает или задает стиль насадки, используемый в конце линий, рисуемых этим `Pen`. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Получает или задает стиль соединения концов двух последовательных линий, рисуемых этим `Pen`. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Получает или задает предел толщины соединения на скошенном угле. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Получает или задает непрозрачность объекта. Значение должно быть от 0 до 1. Значение 0 означает, что объект полностью видим, значение 1 означает, что объект полностью непрозрачен. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Получает стиль линий, рисуемых этим `Pen`. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Получает или задает стиль насадки, используемый в начале линий, рисуемых этим `Pen`. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Получает или задает копию геометрического преобразования для этого `Pen`. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Получает или задает ширину этого `Pen` в единицах объекта Graphics, используемого для рисования. |

## Методы

| Имя | Описание |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Умножает матрицу преобразования для этого `Pen` на указанную [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Умножает матрицу преобразования для этого `Pen` на указанную [`Matrix`](../matrix/) в указанном порядке. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Сбрасывает матрицу геометрического преобразования для этого `Pen` к единичной. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Устанавливает значения, определяющие стиль насадки, используемый для завершения линий, рисуемых этим `Pen`. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |

## Примеры

Этот пример показывает создание и использование объектов Pen. Пример создает новое Image и рисует Rectangles на поверхности Image.

```csharp
[C#]

//Создайте экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создайте экземпляр Graphics и инициализируйте его объектом Image.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистите поверхность Graphics белым цветом.
    graphics.Clear(Aspose.PSD.Color.White);

    //Создайте экземпляр Pen с цветом красным и шириной 5.
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Создайте экземпляр HatchBrush и задайте его свойства.
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Создайте экземпляр Pen.
    //Инициализируйте его объектом HatchBrush и шириной.
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Рисуйте Rectangles, указывая объект Pen.
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Рисуйте Rectangles, указывая объект Pen.
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Создайте параметры экспорта и инициализируйте их.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Сохраните все изменения.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### См. также

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


