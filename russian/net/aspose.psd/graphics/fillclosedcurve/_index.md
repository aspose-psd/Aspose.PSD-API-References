---
title: "Graphics.FillClosedCurve"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур PointF. Этот метод использует напряжение по умолчанию 0,5 и режим заполнения Alternate."
type: docs
weight: 350
url: /ru/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур [`PointF`](../../pointf/). Этот метод использует напряжение по умолчанию 0,5 и режим заполнения Alternate.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *points* равен null. |

### См. также

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур [`PointF`](../../pointf/) с использованием указанного режима заполнения. Этот метод использует напряжение по умолчанию 0,5.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |
| fillmode | FillMode | Элемент перечисления [`FillMode`](../../fillmode/), определяющий способ заполнения кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *points* равен null. |

### См. также

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур [`PointF`](../../pointf/) с использованием указанного режима заполнения и напряжения.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | Объект [`Brush`](../../brush/), определяющий характеристики заполнения. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих сплайн. |
| fillmode | FillMode | Элемент перечисления [`FillMode`](../../fillmode/), определяющий способ заполнения кривой. |
| натяжение | Single | Значение, большее или равное 0.0F, которое задаёт напряжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *points* равен null. |

### См. также

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур [`Point`](../../point/). Этот метод использует напряжение по умолчанию 0,5 и режим заполнения Alternate.

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| points | Point[] | Массив структур [`Point`](../../point/), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *points* равен null. |

### См. также

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур [`Point`](../../point/) с использованием указанного режима заполнения. Этот метод использует напряжение по умолчанию 0,5.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| points | Point[] | Массив структур [`Point`](../../point/), определяющих сплайн. |
| fillmode | FillMode | Элемент перечисления [`FillMode`](../../fillmode/), определяющий способ заполнения кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *points* равен null. |

### См. также

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

Заполняет внутреннюю часть замкнутой кривой Кардинального сплайна, определяемой массивом структур [`Point`](../../point/) с использованием указанного режима заполнения и напряжения.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) определяет характеристики заливки. |
| points | Point[] | Массив структур [`Point`](../../point/), определяющих сплайн. |
| fillmode | FillMode | Элемент перечисления [`FillMode`](../../fillmode/), определяющий способ заполнения кривой. |
| натяжение | Single | Значение, большее или равное 0.0F, которое задаёт напряжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *points* равен null. |

### См. также

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


