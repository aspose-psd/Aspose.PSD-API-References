---
title: "Класс Graphics"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Graphics. Представляет графику в соответствии с графическим движком, используемым в текущей сборке"
type: docs
weight: 4780
url: /ru/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Представляет графику в соответствии с графическим движком, используемым в текущей сборке.

```csharp
public sealed class Graphics
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Graphics](graphics/)(Image) | Инициализирует новый экземпляр класса `Graphics`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Получает или задает область обрезки. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Получает или задает качество композитинга. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Получает горизонтальное разрешение этого Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Получает вертикальное разрешение этого Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Получает изображение. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Получает или задает режим интерполяции. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Получает или задает масштаб между мировыми единицами и единицами страницы для этого Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Получает или задает единицу измерения, используемую для координат страницы в этом Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Получает или задает параметры изображения, используемые для создания рисуемых векторных изображений. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Получает или задает режим сглаживания. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Получает или задает подсказку рендеринга текста. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Получает или задает копию геометрического преобразования мира для этого `Graphics`. |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Начинает кэширование последующих графических операций. Графические эффекты, применяемые после этого, не будут применяться немедленно; вместо этого вызов EndUpdate приведёт к одновременному применению всех эффектов. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Очищает графическую поверхность с использованием указанного цвета. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Рисует дугу, представляющую часть эллипса, заданную структурой [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Рисует дугу, представляющую часть эллипса, заданную структурой [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Рисует сплайн Безье, определённый четырьмя структурами [`Point`](../point/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Рисует сплайн Безье, определённый четырьмя структурами [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Рисует серию сплайнов Безье из массива структур [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Рисует серию сплайнов Безье из массива структур [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [`PointF`](../pointf/). Этот метод использует напряжение по умолчанию 0,5 и режим заполнения Alternate. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [`Point`](../point/). Этот метод использует напряжение по умолчанию 0,5 и режим заполнения Alternate. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [`PointF`](../pointf/) с заданным напряжением. Этот метод использует режим заполнения Alternate по умолчанию. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [`Point`](../point/) с заданным напряжением. Этот метод использует режим заполнения Alternate по умолчанию. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Рисует кардинальный сплайн через указанный массив структур [`PointF`](../pointf/). Этот метод использует напряжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Рисует кардинальный сплайн через указанный массив структур [`Point`](../point/). |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Рисует кардинальный сплайн через указанный массив структур [`PointF`](../pointf/) с заданным напряжением. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Рисует кардинальный сплайн через указанный массив структур [`Point`](../point/) с заданным напряжением. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Рисует кардинальный сплайн через указанный массив структур [`PointF`](../pointf/). Рисование начинается со смещения от начала массива. Этот метод использует напряжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Рисует кардинальный сплайн через указанный массив структур [`PointF`](../pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Рисует кардинальный сплайн через указанный массив структур [`Point`](../point/) с заданным напряжением. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Рисует эллипс, заданный ограничивающей структурой [`Rectangle`](../rectangle/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Рисует эллипс, определённый ограничивающей структурой [`RectangleF`](../rectanglef/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Рисует указанное изображение [`Image`](./image/), используя его оригинальный физический размер, в указанном месте. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Рисует указанное изображение [`Image`](./image/), используя его оригинальный физический размер, в указанном месте. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Рисует указанное изображение [`Image`](./image/), используя его оригинальный физический размер, в указанном месте. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного *изображения* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанное изображение [`Image`](./image/) в указанном месте и с указанным размером. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы поместить в указанный прямоугольник. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Рисует линию, соединяющую две структуры [`Point`](../point/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Рисует линию, соединяющую две структуры [`PointF`](../pointf/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Рисует серию отрезков, соединяющих массив структур [`PointF`](../pointf/). |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Рисует серию отрезков, соединяющих массив структур [`Point`](../point/). |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Рисует [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Рисует форму сектора, определённую эллипсом, заданным структурой [`Rectangle`](../rectangle/) и двумя радиальными линиями. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Рисует форму сектора, определённую эллипсом, заданным структурой [`RectangleF`](../rectanglef/) и двумя радиальными линиями. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Рисует многоугольник, определённый массивом структур [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Рисует многоугольник, определённый массивом структур [`Point`](../point/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Рисует прямоугольник, заданный структурой [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Рисует прямоугольник, заданный структурой [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Рисует серию прямоугольников, заданных структурами [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Рисует серию прямоугольников, заданных структурами [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Рисует указанный текст в указанном месте с указанными объектами [`Brush`](../brush/) и [`Font`](../font/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Рисует указанный текст в указанном прямоугольнике с указанными объектами [`Brush`](../brush/) и [`Font`](../font/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Рисует указанный текст в указанном месте с указанными объектами [`Brush`](../brush/) и [`Font`](../font/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Рисует указанный текст в указанном месте с указанными объектами [`Brush`](../brush/) и [`Font`](../font/), используя атрибуты форматирования указанного [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Рисует указанный текст в указанном прямоугольнике с указанными объектами [`Brush`](../brush/) и [`Font`](../font/), используя атрибуты форматирования указанного [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Рисует указанный текст в указанном месте с указанными объектами [`Brush`](../brush/) и [`Font`](../font/), используя атрибуты форматирования указанного [`StringFormat`](../stringformat/). |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Завершает кэширование графических операций, начатое после вызова BeginUpdate. Предшествующие графические операции будут применены сразу при вызове этого метода. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определённой массивом структур [`PointF`](../pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения Alternate. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определённой массивом структур [`Point`](../point/). Этот метод использует напряжение по умолчанию 0.5 и режим заполнения Alternate. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определённой массивом структур [`PointF`](../pointf/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определённой массивом структур [`Point`](../point/), используя указанный режим заполнения. Этот метод использует напряжение по умолчанию 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определённой массивом структур [`PointF`](../pointf/), используя указанный режим заливки и натяжение. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определённой массивом структур [`Point`](../point/), используя указанный режим заливки и натяжение. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным структурой [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным структурой [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Заполняет внутреннюю часть [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным структурой [`RectangleF`](../rectanglef/) и двумя радиальными линиями. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным структурой [`RectangleF`](../rectanglef/) и двумя радиальными линиями. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, заданных структурами [`PointF`](../pointf/) и Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, заданных структурами [`Point`](../point/) и Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, заданных структурами [`PointF`](../pointf/), используя указанный режим заливки. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, заданных структурами [`Point`](../point/), используя указанный режим заливки. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Заполняет внутреннюю часть прямоугольника, заданного структурой [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Заполняет внутреннюю часть прямоугольника, заданного структурой [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Заполняет внутренние части серии прямоугольников, заданных структурами [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Заполняет внутренние части серии прямоугольников, заданных структурами [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Заполняет внутреннюю часть [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Умножает [`Matrix`](../matrix/), представляющую локальное геометрическое преобразование этого `Graphics`, на указанный [`Matrix`](../matrix/), предварительно добавляя указанный [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Умножает [`Matrix`](../matrix/), представляющую локальное геометрическое преобразование этого `Graphics`, на указанный [`Matrix`](../matrix/) в указанном порядке. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Сбрасывает свойство [`Transform`](./transform/) к единичному. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в заданном порядке. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в заданном порядке. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в заданном порядке. |

## Примеры

В этом примере используется класс Graphics для создания примитивных фигур на поверхности Image. Чтобы продемонстрировать работу, пример создает новое изображение в формате PSD и рисует примитивные фигуры на поверхности Image с помощью методов Draw, предоставленных классом Graphics, затем экспортирует его в формат PSD.

```csharp
[C#]

//Создайте экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создайте и инициализируйте экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить поверхность Graphics
    graphics.Clear(Color.Wheat);

    //Нарисуйте дугу, указав объект Pen с чёрным цветом, 
    //прямоугольник, окружающий дугу, начальный угол и угол разворота
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Нарисуйте кривую Безье, указав объект Pen с синим цветом и координатные точки.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Нарисуйте кривую, указав объект Pen с зелёным цветом и массив точек
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Нарисуйте эллипс, используя объект Pen и окружающий его прямоугольник
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Нарисуйте линию 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Нарисуйте сектор пирога
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Нарисуйте многоугольник, указав объект Pen с красным цветом и массив точек
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Нарисуйте прямоугольник
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Создайте объект SolidBrush и задайте его различные свойства
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Нарисуйте строку, используя объект SolidBrush и шрифт, в указанной точке
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Создайте экземпляр PngOptions и задайте его различные свойства
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Сохраните все изменения.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


