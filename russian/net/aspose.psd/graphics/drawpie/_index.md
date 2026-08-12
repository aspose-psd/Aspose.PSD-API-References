---
title: "Graphics.DrawPie"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует форму сектора, определённую эллипсом, указанным структурой RectangleF, и двумя радиальными линиями"
type: docs
weight: 290
url: /ru/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Рисует форму сектора, определённую эллипсом, указанным структурой [`RectangleF`](../../rectanglef/), и двумя радиальными линиями.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и стиль формы сектора. |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/), представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся форма сектора. |
| startAngle | Single | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | Single | Угол, измеряемый в градусах по часовой стрелке от параметра *startAngle* до второй стороны сектора. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и стиль формы сектора. |
| x | Single | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма сектора. |
| y | Single | Y‑координата верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| width | Single | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| height | Single | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| startAngle | Single | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | Single | Угол, измеряемый в градусах по часовой стрелке от параметра *startAngle* до второй стороны сектора. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. |

### См. также

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Рисует форму пирога, определённую эллипсом, заданным структурой [`Rectangle`](../../rectangle/) и двумя радиальными линиями.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и стиль формы сектора. |
| rect | Rectangle | Структура [`Rectangle`](../../rectangle/), представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся форма пирога. |
| startAngle | Single | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | Single | Угол, измеряемый в градусах по часовой стрелке от параметра *startAngle* до второй стороны сектора. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и стиль формы сектора. |
| x | Int32 | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма сектора. |
| y | Int32 | Y‑координата верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| width | Int32 | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| height | Int32 | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| startAngle | Int32 | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | Int32 | Угол, измеряемый в градусах по часовой стрелке от параметра *startAngle* до второй стороны сектора. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. |

### См. также

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


