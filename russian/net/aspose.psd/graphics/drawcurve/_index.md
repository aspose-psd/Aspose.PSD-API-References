---
title: DrawCurve
second_title: Справочник по Aspose.PSD для .NET API
description: Рисует кардинальный сплайн через заданный массивPointFaspose.psd/pointf структуры. Этот метод использует натяжение по умолчанию 05.
type: docs
weight: 200
url: /ru/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Рисует кардинальный сплайн через заданный массив[`PointF`](../../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | PointF[] | Массив[`PointF`](../../pointf) структуры, определяющие сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Рисует кардинальный сплайн через заданный массив[`PointF`](../../pointf) конструкции с заданным натяжением.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | PointF[] | Массив[`PointF`](../../pointf) структуры, представляющие точки, определяющие кривую. |
| tension | Single | Значение больше или равно 0,0F, которое определяет натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Рисует кардинальный сплайн через заданный массив[`PointF`](../../pointf) структуры. Рисунок начинается со смещения от начала массива. Этот метод использует натяжение по умолчанию 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | PointF[] | Массив[`PointF`](../../pointf) структуры, определяющие сплайн. |
| offset | Int32 | Смещение от первого элемента в массиве*points* параметра в начальную точку кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки для включения в кривую. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Рисует кардинальный сплайн через заданный массив[`PointF`](../../pointf) конструкции с заданным натяжением. Рисунок начинается со смещения от начала массива.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | PointF[] | Массив[`PointF`](../../pointf) структуры, определяющие сплайн. |
| offset | Int32 | Смещение от первого элемента в массиве*points* параметра в начальную точку кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки для включения в кривую. |
| tension | Single | Значение больше или равно 0,0F, которое определяет натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Рисует кардинальный сплайн через заданный массив[`Point`](../../point) структуры.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | Point[] | Массив[`Point`](../../point) структуры, определяющие сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Рисует кардинальный сплайн через заданный массив[`Point`](../../point) конструкции с заданным натяжением.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | Point[] | Массив[`Point`](../../point) структуры, определяющие сплайн. |
| tension | Single | Значение больше или равно 0,0F, которое определяет натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Рисует кардинальный сплайн через заданный массив[`Point`](../../point) конструкции с заданным натяжением.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и высоту кривой. |
| points | Point[] | Массив[`Point`](../../point) структуры, определяющие сплайн. |
| offset | Int32 | Смещение от первого элемента в массиве*points* параметра в начальную точку кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки для включения в кривую. |
| tension | Single | Значение больше или равно 0,0F, которое определяет натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
