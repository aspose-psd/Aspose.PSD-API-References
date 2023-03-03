---
title: Graphics.DrawLines
second_title: Справочник по Aspose.PSD для .NET API
description: Graphics метод. Рисует серию отрезков соединяющих массивPoint структуры.
type: docs
weight: 260
url: /ru/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Рисует серию отрезков, соединяющих массив[`Point`](../../point/) структуры.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) который определяет цвет, ширину и стиль сегментов линии. |
| points | Point[] | Массив[`Point`](../../point/) структуры, представляющие точки для соединения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |
| ArgumentException | *points* массив содержит менее 2 точек. |

### Смотрите также

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* пространство имен [Aspose.PSD](../../graphics/)
* сборка [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Рисует серию отрезков, соединяющих массив[`PointF`](../../pointf/) структуры.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) который определяет цвет, ширину и стиль сегментов линии. |
| points | PointF[] | Массив[`PointF`](../../pointf/) структуры, представляющие точки для соединения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -или- *points* нулевой. |
| ArgumentException | *points* массив содержит менее 2 точек. |

### Смотрите также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* пространство имен [Aspose.PSD](../../graphics/)
* сборка [Aspose.PSD](../../../)


