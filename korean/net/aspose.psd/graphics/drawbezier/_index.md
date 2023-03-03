---
title: Graphics.DrawBezier
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 점을 나타내는 4개의 정렬된 좌표 쌍으로 정의된 베지어 스플라인을 그립니다.
type: docs
weight: 170
url: /ko/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

점을 나타내는 4개의 정렬된 좌표 쌍으로 정의된 베지어 스플라인을 그립니다.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| x1 | Single | 곡선 시작점의 x 좌표입니다. |
| y1 | Single | 곡선 시작점의 y 좌표입니다. |
| x2 | Single | 곡선의 첫 번째 제어점의 x 좌표입니다. |
| y2 | Single | 곡선의 첫 번째 제어점의 y 좌표입니다. |
| x3 | Single | 곡선의 두 번째 제어점의 x 좌표입니다. |
| y3 | Single | 곡선의 두 번째 제어점의 y 좌표입니다. |
| x4 | Single | 곡선 끝점의 x 좌표입니다. |
| y4 | Single | 곡선 끝점의 y 좌표입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

4개로 정의된 베지어 스플라인을 그립니다.[`PointF`](../../pointf/) 구조.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | PointF | [`PointF`](../../pointf/) 곡선의 시작점을 나타내는 구조체입니다. |
| pt2 | PointF | [`PointF`](../../pointf/) 곡선의 첫 번째 제어점을 나타내는 구조체입니다. |
| pt3 | PointF | [`PointF`](../../pointf/) 곡선의 두 번째 제어점을 나타내는 구조체입니다. |
| pt4 | PointF | [`PointF`](../../pointf/) 곡선의 끝점을 나타내는 구조체입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

4개로 정의된 베지어 스플라인을 그립니다.[`Point`](../../point/) 구조.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 스타일을 결정하는 구조입니다. |
| pt1 | Point | [`Point`](../../point/) 곡선의 시작점을 나타내는 구조체입니다. |
| pt2 | Point | [`Point`](../../point/) 곡선의 첫 번째 제어점을 나타내는 구조체입니다. |
| pt3 | Point | [`Point`](../../point/) 곡선의 두 번째 제어점을 나타내는 구조체입니다. |
| pt4 | Point | [`Point`](../../point/) 곡선의 끝점을 나타내는 구조체입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


