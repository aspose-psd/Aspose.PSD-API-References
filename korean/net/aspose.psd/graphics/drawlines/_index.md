---
title: Graphics.DrawLines
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 배열을 연결하는 일련의 선분을 그립니다.Point 구조.
type: docs
weight: 260
url: /ko/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

배열을 연결하는 일련의 선분을 그립니다.[`Point`](../../point/) 구조.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 선분의 색상, 너비 및 스타일을 결정합니다. |
| points | Point[] | 의 배열[`Point`](../../point/) 연결할 점을 나타내는 구조. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |
| ArgumentException | 그만큼*points* 배열에 2개 미만의 포인트가 포함되어 있습니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

배열을 연결하는 일련의 선분을 그립니다.[`PointF`](../../pointf/) 구조.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 선분의 색상, 너비 및 스타일을 결정합니다. |
| points | PointF[] | 의 배열[`PointF`](../../pointf/) 연결할 점을 나타내는 구조. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |
| ArgumentException | 그만큼*points* 배열에 2개 미만의 포인트가 포함되어 있습니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


