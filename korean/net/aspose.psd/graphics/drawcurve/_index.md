---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. 지정된 PointF 구조 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 장력 0.5를 사용합니다."
type: docs
weight: 210
url: /ko/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

지정된 [`PointF`](../../pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 장력 0.5를 사용합니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 스플라인을 정의하는 [`PointF`](../../pointf/) 구조의 배열입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

지정된 장력을 사용하여 지정된 [`PointF`](../../pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 곡선을 정의하는 점들을 나타내는 [`PointF`](../../pointf/) 구조의 배열입니다. |
| 장력 | 단일 | 곡선의 장력을 지정하는 0.0F 이상 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

지정된 [`PointF`](../../pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작부터 오프셋을 두고 시작합니다. 이 메서드는 기본 장력 0.5를 사용합니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 스플라인을 정의하는 [`PointF`](../../pointf/) 구조의 배열입니다. |
| offset | Int32 | *points* 매개변수 배열의 첫 번째 요소에서 곡선의 시작점까지의 오프셋입니다. |
| numberOfSegments | Int32 | 곡선에 포함될 시작점 이후의 세그먼트 수입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

지정된 장력을 사용하여 지정된 [`PointF`](../../pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작부터 오프셋을 두고 시작합니다.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | PointF[] | 스플라인을 정의하는 [`PointF`](../../pointf/) 구조의 배열입니다. |
| offset | Int32 | *points* 매개변수 배열의 첫 번째 요소에서 곡선의 시작점까지의 오프셋입니다. |
| numberOfSegments | Int32 | 곡선에 포함될 시작점 이후의 세그먼트 수입니다. |
| 장력 | 단일 | 곡선의 장력을 지정하는 0.0F 이상 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

지정된 [`Point`](../../point/) 구조 배열을 통해 카디널 스플라인을 그립니다.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | Point[] | 스플라인을 정의하는 [`Point`](../../point/) 구조체 배열. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

지정된 장력을 사용하여 지정된 [`Point`](../../point/) 구조체 배열을 통해 카디널 스플라인을 그립니다.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | Point[] | 스플라인을 정의하는 [`Point`](../../point/) 구조체 배열. |
| 장력 | 단일 | 곡선의 장력을 지정하는 0.0F 이상 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

지정된 장력을 사용하여 지정된 [`Point`](../../point/) 구조체 배열을 통해 카디널 스플라인을 그립니다.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)`는 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | Point[] | 스플라인을 정의하는 [`Point`](../../point/) 구조체 배열. |
| offset | Int32 | *points* 매개변수 배열의 첫 번째 요소에서 곡선의 시작점까지의 오프셋입니다. |
| numberOfSegments | Int32 | 곡선에 포함될 시작점 이후의 세그먼트 수입니다. |
| 장력 | 단일 | 곡선의 장력을 지정하는 0.0F 이상 값입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *points*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


