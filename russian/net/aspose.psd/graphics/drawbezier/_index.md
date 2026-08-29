---
title: "Graphics.DrawBezier"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует сплайн Безье, определяемый четырьмя упорядоченными парами координат, представляющими точки."
type: docs
weight: 180
url: /ru/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) определяет цвет, ширину и стиль кривой. |
| x1 | Single | Координата x начальной точки кривой. |
| y1 | Single | Координата y начальной точки кривой. |
| x2 | Single | Координата x первой управляющей точки кривой. |
| y2 | Single | Координата y первой управляющей точки кривой. |
| x3 | Single | Координата x второй управляющей точки кривой. |
| y3 | Single | Координата y второй управляющей точки кривой. |
| x4 | Single | Координата x конечной точки кривой. |
| y4 | Single | Координата y конечной точки кривой. |

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

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Рисует сплайн Безье, определяемый четырьмя структурами [`PointF`](../../pointf/).

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) определяет цвет, ширину и стиль кривой. |
| pt1 | PointF | [`PointF`](../../pointf/) структура, представляющая начальную точку кривой. |
| pt2 | PointF | [`PointF`](../../pointf/) структура, представляющая первую управляющую точку кривой. |
| pt3 | PointF | [`PointF`](../../pointf/) структура, представляющая вторую управляющую точку кривой. |
| pt4 | PointF | [`PointF`](../../pointf/) структура, представляющая конечную точку кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Рисует сплайн Безье, определённый четырьмя структурами [`Point`](../../point/).

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) структура, определяющая цвет, ширину и стиль кривой. |
| pt1 | Point | [`Point`](../../point/) структура, представляющая начальную точку кривой. |
| pt2 | Point | [`Point`](../../point/) структура, представляющая первую управляющую точку кривой. |
| pt3 | Point | [`Point`](../../point/) структура, представляющая вторую управляющую точку кривой. |
| pt4 | Point | [`Point`](../../point/) структура, представляющая конечную точку кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. |

### См. также

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


