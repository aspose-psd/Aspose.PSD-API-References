---
title: "Matrix.Matrix"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор Matrix. Инициализирует новый экземпляр класса Matrix как единичную матрицу."
type: docs
weight: 10
url: /ru/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Инициализирует новый экземпляр класса Matrix как единичную матрицу.

```csharp
public Matrix()
```

### См. также

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Инициализирует новый экземпляр класса [`Matrix`](../).

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| m11 | Single | m00 M11 Масштаб X |
| m12 | Single | m10 M12 Сдвиг Y |
| m21 | Single | m01 M21 Сдвиг X |
| m22 | Single | m11 M22 Масштаб Y |
| m31 | Single | m02 M31 Перемещение X |
| m32 | Single | m12 M32 Перевести Y |

### См. также

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Инициализирует новый экземпляр класса [`Matrix`](../), задавая геометрическое преобразование, определённое указанным прямоугольником и массивом точек.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/), представляющая прямоугольник, который будет преобразован. |
| plgpts | PointF[] | Массив из трёх структур [`PointF`](../../pointf/), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### См. также

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Инициализирует новый экземпляр класса [`Matrix`](../), задавая геометрическое преобразование, определённое указанным прямоугольником и массивом точек.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Структура [`Rectangle`](../../rectangle/), представляющая прямоугольник, который будет преобразован. |
| plgpts | Point[] | Массив из трёх структур [`Point`](../../point/), представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### См. также

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Создаёт копию класса [`Matrix`](../).

```csharp
public Matrix(Matrix origin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | Matrix | Базовая матрица для копирования |

### См. также

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


