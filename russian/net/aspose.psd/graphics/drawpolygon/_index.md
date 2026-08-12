---
title: "Graphics.DrawPolygon"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует многоугольник, определяемый массивом структур PointF"
type: docs
weight: 300
url: /ru/net/aspose.psd/graphics/drawpolygon/
---
{{< psd/tize >}}
## DrawPolygon(Pen, PointF[]) {#drawpolygon}

Рисует многоугольник, определяемый массивом структур [`PointF`](../../pointf/).

```csharp
public void DrawPolygon(Pen pen, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) который определяет цвет, ширину и стиль многоугольника. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), представляющих вершины многоугольника. |

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

## DrawPolygon(Pen, Point[]) {#drawpolygon_1}

Рисует многоугольник, определяемый массивом структур [`Point`](../../point/).

```csharp
public void DrawPolygon(Pen pen, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) который определяет цвет, ширину и стиль многоугольника. |
| points | Point[] | Массив структур [`Point`](../../point/), представляющих вершины многоугольника. |

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


