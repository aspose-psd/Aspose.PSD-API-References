---
title: Graphics
second_title: Справочник по Aspose.PSD для .NET API
description: Представляет графику в соответствии с графическим движком используемым в текущей сборке.
type: docs
weight: 4240
url: /ru/net/aspose.psd/graphics/
---
## Graphics class

Представляет графику в соответствии с графическим движком, используемым в текущей сборке.

```csharp
public sealed class Graphics
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Graphics](graphics)(Image) | Инициализирует новый экземпляр[`Graphics`](../graphics) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip) { get; set; } | Получает или задает область клипа. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality) { get; set; } | Получает или задает качество композитинга. |
| [DpiX](../../aspose.psd/graphics/dpix) { get; } | Получает горизонтальное разрешение этого Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy) { get; } | Получает вертикальное разрешение этого Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image) { get; } | Получает изображение. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode) { get; set; } | Получает или задает режим интерполяции. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall) { get; } | Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale) { get; set; } | Получает или задает масштаб между мировыми единицами и единицами страницы для этого Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit) { get; set; } | Получает или задает единицу измерения, используемую для координат страницы в этом Aspose.PSD.Graphics. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode) { get; set; } | Получает или задает режим сглаживания. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint) { get; set; } | Получает или задает подсказку рендеринга текста. |
| [Transform](../../aspose.psd/graphics/transform) { get; set; } | Получает или задает копию геометрического преобразования мира для этого[`Graphics`](../graphics) . |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate)() | Запускает кэширование следующих графических операций. Графические эффекты, примененные впоследствии, не будут применены немедленно, вместо этого EndUpdate вызовет одновременное применение всех эффектов. |
| [Clear](../../aspose.psd/graphics/clear)(Color) | Очищает графическую поверхность, используя указанный цвет. |
| [DrawArc](../../aspose.psd/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Рисует дугу, представляющую часть эллипса, заданного[`Rectangle`](../rectangle)структура. |
| [DrawArc](../../aspose.psd/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Рисует дугу, представляющую часть эллипса, заданного[`RectangleF`](../rectanglef)структура. |
| [DrawArc](../../aspose.psd/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawArc](../../aspose.psd/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Рисует сплайн Безье, определяемый четырьмя[`Point`](../point) структуры. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Рисует сплайн Безье, определяемый четырьмя[`PointF`](../pointf) структуры. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Рисует сплайн Безье, определяемый четырьмя упорядоченными парами координат, представляющими точки. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Рисует серию сплайнов Безье из массива[`PointF`](../pointf) структуры. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Рисует серию сплайнов Безье из массива[`Point`](../point) структуры. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`PointF`](../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`Point`](../point) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`PointF`](../pointf) конструкции с заданным натяжением. Этот метод использует значение по умолчаниюAlternate режим заполнения. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`Point`](../point) конструкции с заданным натяжением. Этот метод использует значение по умолчаниюAlternate режим заполнения. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Рисует кардинальный сплайн через заданный массив[`Point`](../point) структуры. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) конструкции с заданным натяжением. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Рисует кардинальный сплайн через заданный массив[`Point`](../point) конструкции с заданным натяжением. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) структуры. Рисунок начинается со смещения от начала массива. Этот метод использует натяжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) конструкции с заданным натяжением. Рисунок начинается со смещения от начала массива. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Рисует кардинальный сплайн через заданный массив[`Point`](../point) конструкции с заданным натяжением. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Рисует эллипс, заданный ограничивающей[`Rectangle`](../rectangle)структура. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Рисует эллипс, определяемый ограничивающей[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage)(Image, Point) | Рисует указанный[`Image`](./image) , используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_1)(Image, PointF) | Рисует указанный[`Image`](./image) , используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_2)(Image, PointF[]) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_6)(Image, Point[]) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_10)(Image, Rectangle) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_15)(Image, RectangleF) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_22)(Image, float, float) | Рисует указанный[`Image`](./image) , используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_20)(Image, int, int) | Рисует указанное изображение, используя исходный физический размер, в месте, указанном парой координат. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Рисует указанное изображение, используя исходный физический размер в указанном месте. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Рисует указанное изображение, используя исходный физический размер в указанном месте. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Рисует указанное изображение, используя его исходный физический размер в месте, указанном парой координат. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Рисует указанное изображение, используя исходный физический размер в указанном месте. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Рисует заданное изображение без масштабирования и при необходимости обрезает его, чтобы оно поместилось в указанный прямоугольник. |
| [DrawLine](../../aspose.psd/graphics/drawline#drawline)(Pen, Point, Point) | Рисует линию, соединяющую два[`Point`](../point) структуры. |
| [DrawLine](../../aspose.psd/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Рисует линию, соединяющую два[`PointF`](../pointf) структуры. |
| [DrawLine](../../aspose.psd/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Рисует линию, соединяющую две точки, заданные парами координат. |
| [DrawLine](../../aspose.psd/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Рисует линию, соединяющую две точки, заданные парами координат. |
| [DrawLines](../../aspose.psd/graphics/drawlines#drawlines)(Pen, PointF[]) | Рисует серию отрезков, соединяющих массив[`PointF`](../pointf) структуры. |
| [DrawLines](../../aspose.psd/graphics/drawlines#drawlines_1)(Pen, Point[]) | Рисует серию отрезков, соединяющих массив[`Point`](../point) структуры. |
| [DrawPath](../../aspose.psd/graphics/drawpath)(Pen, GraphicsPath) | Рисует[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.psd/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Рисует круговую форму, определяемую эллипсом, указанным[`Rectangle`](../rectangle) структура и две радиальные линии. |
| [DrawPie](../../aspose.psd/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Рисует круговую форму, определяемую эллипсом, указанным[`RectangleF`](../rectanglef) структура и две радиальные линии. |
| [DrawPie](../../aspose.psd/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Рисует круговую форму, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPie](../../aspose.psd/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Рисует круговую форму, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Рисует многоугольник, определяемый массивом[`PointF`](../pointf) структуры. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Рисует многоугольник, определяемый массивом[`Point`](../point) структуры. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Рисует прямоугольник, заданный[`Rectangle`](../rectangle)структура. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Рисует прямоугольник, заданный[`RectangleF`](../rectanglef)структура. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Рисует серию прямоугольников, указанных[`RectangleF`](../rectanglef) структуры. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Рисует серию прямоугольников, указанных[`Rectangle`](../rectangle) структуры. |
| [DrawString](../../aspose.psd/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты. |
| [DrawString](../../aspose.psd/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../brush) а также[`Font`](../font) объекты. |
| [DrawString](../../aspose.psd/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты. |
| [DrawString](../../aspose.psd/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты, использующие атрибуты форматирования указанных[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.psd/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../brush) а также[`Font`](../font) объекты, использующие атрибуты форматирования указанных[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.psd/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты, использующие атрибуты форматирования указанных[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate)() | Завершает кэширование графических операций, запущенных после вызова BeginUpdate. Предыдущие графические операции будут применены сразу при вызове этого метода. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`PointF`](../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`Point`](../point) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`PointF`](../pointf) структуры, использующие указанный режим заполнения. Этот метод использует натяжение по умолчанию 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`Point`](../point) структуры, использующие указанный режим заполнения. Этот метод использует натяжение по умолчанию 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`PointF`](../pointf) структуры с использованием указанного режима заполнения и напряжения. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`Point`](../point) структуры с использованием указанного режима заполнения и напряжения. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, указанным[`Rectangle`](../rectangle)структура. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, указанным[`RectangleF`](../rectanglef)структура. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillPath](../../aspose.psd/graphics/fillpath)(Brush, GraphicsPath) | Заполняет внутреннюю часть[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.psd/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, указанным[`RectangleF`](../rectanglef) структура и две радиальные линии. |
| [FillPie](../../aspose.psd/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, указанным[`RectangleF`](../rectanglef) структура и две радиальные линии. |
| [FillPie](../../aspose.psd/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPie](../../aspose.psd/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`PointF`](../pointf) структуры иAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`Point`](../point) структуры иAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`PointF`](../pointf) структуры, использующие указанный режим заливки. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`Point`](../point) структуры, использующие указанный режим заливки. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Заполняет внутреннюю часть прямоугольника, указанного[`Rectangle`](../rectangle)структура. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Заполняет внутреннюю часть прямоугольника, указанного[`RectangleF`](../rectanglef)структура. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Заполняет внутреннюю часть ряда прямоугольников, заданных параметром[`RectangleF`](../rectanglef) структуры. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Заполняет внутреннюю часть ряда прямоугольников, заданных параметром[`Rectangle`](../rectangle) структуры. |
| [FillRegion](../../aspose.psd/graphics/fillregion)(Brush, Region) | Заполняет внутреннюю часть[`Region`](../region) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform#multiplytransform)(Matrix) | Умножает[`Matrix`](../matrix) который представляет собой локальное геометрическое преобразование этого[`Graphics`](../graphics) указанным[`Matrix`](../matrix) путем добавления указанного[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Умножает[`Matrix`](../matrix) который представляет собой локальное геометрическое преобразование этого[`Graphics`](../graphics) указанным[`Matrix`](../matrix) в указанном порядке. |
| [ResetTransform](../../aspose.psd/graphics/resettransform)() | Сбрасывает[`Transform`](./transform) свойство к личности. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform#translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примеры

В этом примере класс Graphics используется для создания примитивных фигур на поверхности изображения. Чтобы продемонстрировать операцию, в примере создается новое изображение в формате PSD и рисуются примитивные фигуры на поверхности изображения с помощью методов Draw, предоставляемых классом Graphics, а затем экспортируется в формат файла PSD.

```csharp
[C#]

//Создаем экземпляр изображения 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем и инициализируем экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить графическую поверхность
    graphics.Clear(Color.Wheat);

    // Нарисуйте дугу, указав объект Pen, имеющий черный цвет, 
    //прямоугольник, окружающий дугу, начальный угол и угол развертки
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // Нарисуйте кривую Безье, задав объект Pen синего цвета и координаты Points.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Нарисуйте кривую, указав объект Pen зеленого цвета и массив точек
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    // Нарисовать линию 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // Нарисовать сегмент пирога
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // Нарисуйте многоугольник, указав объект Pen красного цвета и массив точек
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // Рисуем прямоугольник
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Создаем объект SolidBrush и устанавливаем его различные свойства
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Нарисуйте строку, используя объект SolidBrush и шрифт, в определенной точке
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Создаем экземпляр PngOptions и устанавливаем его различные свойства
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // сохранить все изменения.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
