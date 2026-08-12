---
title: "Graphics.DrawClosedCurve"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует замкнутый кардинальный сплайн, определенный массивом структур PointF. Этот метод использует значение натяжения по умолчанию 0.5 и режим заполнения Alternate."
type: docs
weight: 200
url: /ru/net/aspose.psd/graphics/drawclosedcurve/
---
{{< psd/tize >}}
## DrawClosedCurve(Pen, PointF[]) {#drawclosedcurve}

Рисует замкнутый кардинальный сплайн, определенный массивом структур [`PointF`](../../pointf/). Этот метод использует значение натяжения по умолчанию 0.5 и режим заполнения Alternate.

```csharp
public void DrawClosedCurve(Pen pen, PointF[] points)
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

## DrawClosedCurve(Pen, PointF[], float) {#drawclosedcurve_1}

Рисует замкнутый кардинальный сплайн, определенный массивом структур [`PointF`](../../pointf/) с использованием указанного натяжения. Этот метод использует режим заполнения Alternate по умолчанию.

```csharp
public void DrawClosedCurve(Pen pen, PointF[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/), определяющий цвет, ширину и высоту кривой. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |
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

## DrawClosedCurve(Pen, Point[]) {#drawclosedcurve_2}

Рисует замкнутый кардинальный сплайн, определенный массивом структур [`Point`](../../point/). Этот метод использует значение натяжения по умолчанию 0.5 и режим заполнения Alternate.

```csharp
public void DrawClosedCurve(Pen pen, Point[] points)
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

## DrawClosedCurve(Pen, Point[], float) {#drawclosedcurve_3}

Рисует замкнутый кардинальный сплайн, определенный массивом структур [`Point`](../../point/) с использованием указанного натяжения. Этот метод использует режим заполнения Alternate по умолчанию.

```csharp
public void DrawClosedCurve(Pen pen, Point[] points, float tension)
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


