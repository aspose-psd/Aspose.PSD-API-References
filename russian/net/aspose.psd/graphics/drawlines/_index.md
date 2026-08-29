---
title: "Graphics.DrawLines"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует серию отрезков, соединяющих массив структур Point."
type: docs
weight: 270
url: /ru/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Рисует серию отрезков, соединяющих массив структур [`Point`](../../point/).

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) определяет цвет, ширину и стиль отрезков. |
| points | Point[] | Массив структур [`Point`](../../point/), представляющих точки для соединения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |
| ArgumentException | Массив *points* содержит менее 2 точек. |

### См. также

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Рисует серию отрезков, соединяющих массив структур [`PointF`](../../pointf/).

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) определяет цвет, ширину и стиль отрезков. |
| points | PointF[] | Массив структур [`PointF`](../../pointf/), представляющих точки для соединения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* равно null. -or- *points* равно null. |
| ArgumentException | Массив *points* содержит менее 2 точек. |

### См. также

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


