---
title: Graphics.DrawCurve
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 지정된 배열을 통해 기본 스플라인을 그립니다.PointF 구조. 이 방법은 기본 장력 0.5. 를 사용합니다.
type: docs
weight: 200
url: /ko/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../../pointf/) 구조. 이 방법은 기본 장력 0.5. 를 사용합니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 의 배열[`PointF`](../../pointf/) 스플라인을 정의하는 구조. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../../pointf/) 지정된 장력을 사용하는 구조물.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 의 배열[`PointF`](../../pointf/) 곡선을 정의하는 점을 나타내는 구조. |
| tension | Single | 곡선의 장력을 지정하는 0.0F 이상의 값. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../../pointf/) 구조. 도면은 배열의 시작 부분에서 오프셋을 시작합니다. 이 방법은 0.5. 의 기본 장력을 사용합니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 의 배열[`PointF`](../../pointf/) 스플라인을 정의하는 구조. |
| offset | Int32 | 배열의 첫 번째 요소에서 오프셋*points* 매개변수를 곡선의 시작점으로 설정합니다. |
| numberOfSegments | Int32 | 곡선에 포함할 시작점 뒤의 세그먼트 수입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../../pointf/) 지정된 장력을 사용하는 구조. 도면은 배열의 시작 부분에서 오프셋을 시작합니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 의 배열[`PointF`](../../pointf/) 스플라인을 정의하는 구조. |
| offset | Int32 | 배열의 첫 번째 요소에서 오프셋*points* 매개변수를 곡선의 시작점으로 설정합니다. |
| numberOfSegments | Int32 | 곡선에 포함할 시작점 뒤의 세그먼트 수입니다. |
| tension | Single | 곡선의 장력을 지정하는 0.0F 이상의 값. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

지정된 배열을 통해 기본 스플라인을 그립니다.[`Point`](../../point/) 구조.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | Point[] | 의 배열[`Point`](../../point/) 스플라인을 정의하는 구조. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

지정된 배열을 통해 기본 스플라인을 그립니다.[`Point`](../../point/) 지정된 장력을 사용하는 구조물.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | Point[] | 의 배열[`Point`](../../point/) 스플라인을 정의하는 구조. |
| tension | Single | 곡선의 장력을 지정하는 0.0F 이상의 값. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

지정된 배열을 통해 기본 스플라인을 그립니다.[`Point`](../../point/) 지정된 장력을 사용하는 구조물.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | Point[] | 의 배열[`Point`](../../point/) 스플라인을 정의하는 구조. |
| offset | Int32 | 배열의 첫 번째 요소에서 오프셋*points* 매개변수를 곡선의 시작점으로 설정합니다. |
| numberOfSegments | Int32 | 곡선에 포함할 시작점 뒤의 세그먼트 수입니다. |
| tension | Single | 곡선의 장력을 지정하는 0.0F 이상의 값. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *points* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


