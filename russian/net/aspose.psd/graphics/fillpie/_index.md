---
title: "Graphics.FillPie"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой RectangleF, и двумя радиальными линиями."
type: docs
weight: 380
url: /ru/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [`RectangleF`](../../rectanglef/), и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | Single | Угол в градусах, измеряемый по часовой стрелке от параметра *startAngle* до второй стороны сектора пирога. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. |

### См. также

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, указанным структурой [`RectangleF`](../../rectanglef/), и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/), представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся секция пирога. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | Single | Угол в градусах, измеряемый по часовой стрелке от параметра *startAngle* до второй стороны сектора пирога. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. |

### См. также

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| x | Single | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| y | Single | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| width | Single | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| height | Single | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | Single | Угол в градусах, измеряемый по часовой стрелке от параметра *startAngle* до второй стороны сектора пирога. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. |

### См. также

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| x | Int32 | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| y | Int32 | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| width | Int32 | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| height | Int32 | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся секция пирога. |
| startAngle | Int32 | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | Int32 | Угол в градусах, измеряемый по часовой стрелке от параметра *startAngle* до второй стороны сектора пирога. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. |

### См. также

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


