---
title: "Graphics.DrawCurve"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует кардинальный сплайн через указанный массив структур PointF. Этот метод использует напряжение по умолчанию 0.5"
type: docs
weight: 210
url: /ru/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Рисует кардинальный сплайн через указанный массив структур [`PointF`](../../pointf/). Этот метод использует напряжение по умолчанию 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Рисует кардинальный сплайн через указанный массив структур [`PointF`](../../pointf/) с заданным напряжением.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), представляющих точки, определяющие кривую. |
| натяжение | Single | Значение, большее или равное 0.0F, которое задаёт напряжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Рисует кардинальный сплайн через указанный массив структур [`PointF`](../../pointf/). Рисование начинается со смещения от начала массива. Этот метод использует напряжение по умолчанию 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |
| offset | Int32 | Смещение от первого элемента массива параметра *points* до начальной точки кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки, включаемых в кривую. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Рисует кардинальный сплайн через указанный массив структур [`PointF`](../../pointf/) с заданным напряжением. Рисование начинается со смещения от начала массива.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |
| offset | Int32 | Смещение от первого элемента массива параметра *points* до начальной точки кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | Single | Значение, большее или равное 0.0F, которое задаёт напряжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Рисует кардинальный сплайн через указанный массив структур [`Point`](../../point/) .

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | Point[] | Массив структур [`Point`](../../point/), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Рисует кардинальный сплайн через указанный массив структур [`Point`](../../point/) с заданным напряжением.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | Point[] | Массив структур [`Point`](../../point/), определяющих сплайн. |
| натяжение | Single | Значение, большее или равное 0.0F, которое задаёт напряжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Рисует кардинальный сплайн через указанный массив структур [`Point`](../../point/) с заданным напряжением.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | Point[] | Массив структур [`Point`](../../point/), определяющих сплайн. |
| offset | Int32 | Смещение от первого элемента массива параметра *points* до начальной точки кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | Single | Значение, большее или равное 0.0F, которое задаёт напряжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


