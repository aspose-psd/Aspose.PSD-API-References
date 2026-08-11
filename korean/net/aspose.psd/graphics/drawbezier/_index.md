---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. 점을 나타내는 네 개의 순서쌍 좌표로 정의된 베지어 스플라인을 그립니다."
type: docs
weight: 180
url: /ko/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

점을 나타내는 네 개의 순서쌍 좌표로 정의된 베지어 스플라인을 그립니다.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은(는) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| x1 | 단일 | 곡선 시작점의 x 좌표입니다. |
| y1 | 단일 | 곡선 시작점의 y 좌표입니다. |
| x2 | 단일 | 곡선 첫 번째 제어점의 x 좌표입니다. |
| y2 | 단일 | 곡선 첫 번째 제어점의 y 좌표입니다. |
| x3 | 단일 | 곡선 두 번째 제어점의 x 좌표입니다. |
| y3 | 단일 | 곡선 두 번째 제어점의 y 좌표입니다. |
| x4 | 단일 | 곡선 끝점의 x 좌표입니다. |
| y4 | 단일 | 곡선의 끝점의 y 좌표. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

네 개의 [`PointF`](../../pointf/) 구조로 정의된 베지어 스플라인을 그립니다.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은(는) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | PointF | [`PointF`](../../pointf/) 구조는 곡선의 시작점을 나타냅니다. |
| pt2 | PointF | [`PointF`](../../pointf/) 구조는 곡선의 첫 번째 제어점을 나타냅니다. |
| pt3 | PointF | [`PointF`](../../pointf/) 구조는 곡선의 두 번째 제어점을 나타냅니다. |
| pt4 | PointF | [`PointF`](../../pointf/) 구조는 곡선의 끝점을 나타냅니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

네 개의 [`Point`](../../point/) 구조로 정의된 베지어 스플라인을 그립니다.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 구조는 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | Point | [`Point`](../../point/) 구조는 곡선의 시작점을 나타냅니다. |
| pt2 | Point | [`Point`](../../point/) 구조는 곡선의 첫 번째 제어점을 나타냅니다. |
| pt3 | Point | [`Point`](../../point/) 구조는 곡선의 두 번째 제어점을 나타냅니다. |
| pt4 | Point | [`Point`](../../point/) 구조는 곡선의 끝점을 나타냅니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


