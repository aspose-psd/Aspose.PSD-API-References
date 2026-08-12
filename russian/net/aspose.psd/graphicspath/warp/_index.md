---
title: "GraphicsPath.Warp"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод GraphicsPath. Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому GraphicsPath."
type: docs
weight: 180
url: /ru/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный *srcRect*. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | Объект [`RectangleF`](../../rectanglef/), представляющий прямоугольник, преобразуемый в параллелограмм, определённый *destPoints*. |

### См. также

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный *srcRect*. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | Объект [`RectangleF`](../../rectanglef/), представляющий прямоугольник, преобразуемый в параллелограмм, определённый *destPoints*. |
| matrix | Matrix | Объект [`Matrix`](../../matrix/), задающий геометрическое преобразование, применяемое к пути. |

### См. также

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный *srcRect*. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | Объект [`RectangleF`](../../rectanglef/), представляющий прямоугольник, преобразуемый в параллелограмм, определённый *destPoints*. |
| matrix | Matrix | Объект [`Matrix`](../../matrix/), задающий геометрическое преобразование, применяемое к пути. |
| warpMode | WarpMode | Перечисление [`WarpMode`](../../warpmode/), указывающее, использует ли данная операция искажения перспективный или билинейный режим. |

### См. также

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | PointF[] | Массив структур [`PointF`](../../pointf/), определяющих параллелограмм, в который преобразуется прямоугольник, заданный *srcRect*. Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | RectangleF | Объект [`RectangleF`](../../rectanglef/), представляющий прямоугольник, преобразуемый в параллелограмм, определённый *destPoints*. |
| matrix | Matrix | Объект [`Matrix`](../../matrix/), задающий геометрическое преобразование, применяемое к пути. |
| warpMode | WarpMode | Перечисление [`WarpMode`](../../warpmode/), указывающее, использует ли данная операция искажения перспективный или билинейный режим. |
| flatness | Single | Значение от 0 до 1, определяющее степень плоскостности полученного пути. Для получения дополнительной информации см. методы [`Flatten`](../flatten/). |

### См. также

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


