---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GraphicsPath 메서드. 사각형과 평행사변형으로 정의된 왜곡 변환을 이 GraphicsPath에 적용합니다."
type: docs
weight: 180
url: /ko/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

사각형과 평행사변형으로 정의된 왜곡 변환을 이 [`GraphicsPath`](../)에 적용합니다.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | `[`PointF`](../../pointf/)` 구조체 배열로, *srcRect* 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있는 경우, 평행사변형의 오른쪽 아래 모서는 첫 번째 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/)`는 *destPoints* 로 정의된 평행사변형으로 변환되는 사각형을 나타냅니다. |

### 또 보기

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

사각형과 평행사변형으로 정의된 왜곡 변환을 이 [`GraphicsPath`](../)에 적용합니다.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | `[`PointF`](../../pointf/)` 구조체 배열로, *srcRect* 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있는 경우, 평행사변형의 오른쪽 아래 모서는 첫 번째 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/)`는 *destPoints* 로 정의된 평행사변형으로 변환되는 사각형을 나타냅니다. |
| matrix | Matrix | `[`Matrix`](../../matrix/)`는 경로에 적용할 기하학적 변환을 지정합니다. |

### 또 보기

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

사각형과 평행사변형으로 정의된 왜곡 변환을 이 [`GraphicsPath`](../)에 적용합니다.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | `[`PointF`](../../pointf/)` 구조체 배열로, *srcRect* 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있는 경우, 평행사변형의 오른쪽 아래 모서는 첫 번째 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/)`는 *destPoints* 로 정의된 평행사변형으로 변환되는 사각형을 나타냅니다. |
| matrix | Matrix | `[`Matrix`](../../matrix/)`는 경로에 적용할 기하학적 변환을 지정합니다. |
| warpMode | WarpMode | `[`WarpMode`](../../warpmode/)` 열거형은 이 왜곡 작업이 원근법 모드인지 또는 이중선형 모드인지를 지정합니다. |

### 또 보기

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

사각형과 평행사변형으로 정의된 왜곡 변환을 이 [`GraphicsPath`](../)에 적용합니다.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | `[`PointF`](../../pointf/)` 구조체 배열로, *srcRect* 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있는 경우, 평행사변형의 오른쪽 아래 모서는 첫 번째 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | `[`RectangleF`](../../rectanglef/)`는 *destPoints* 로 정의된 평행사변형으로 변환되는 사각형을 나타냅니다. |
| matrix | Matrix | `[`Matrix`](../../matrix/)`는 경로에 적용할 기하학적 변환을 지정합니다. |
| warpMode | WarpMode | `[`WarpMode`](../../warpmode/)` 열거형은 이 왜곡 작업이 원근법 모드인지 또는 이중선형 모드인지를 지정합니다. |
| flatness | Single | 0에서 1 사이의 값으로 결과 경로가 얼마나 평평한지를 지정합니다. 자세한 내용은 [`Flatten`](../flatten/) 메서드를 참조하십시오. |

### 또 보기

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


