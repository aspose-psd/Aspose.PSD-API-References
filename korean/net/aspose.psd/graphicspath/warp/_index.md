---
title: GraphicsPath.Warp
second_title: .NET API 참조용 Aspose.PSD
description: GraphicsPath 방법. 사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.GraphicsPath .
type: docs
weight: 180
url: /ko/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | 배열[`PointF`](../../pointf/) 에 의해 정의된 사각형이 평행사변형을 정의하는 구조*srcRect*변환됩니다. 배열은 3개 또는 4개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 포함된 경우 평행사변형의 오른쪽 아래 모서리는 처음 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | ㅏ[`RectangleF`](../../rectanglef/) 에 의해 정의된 평행사변형으로 변환되는 사각형을 나타냅니다.*destPoints*. |

### 또한보십시오

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | 배열[`PointF`](../../pointf/) 에 의해 정의된 사각형이 평행사변형을 정의하는 구조*srcRect*변환됩니다. 배열은 3개 또는 4개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 포함된 경우 평행사변형의 오른쪽 아래 모서리는 처음 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | ㅏ[`RectangleF`](../../rectanglef/) 에 의해 정의된 평행사변형으로 변환되는 사각형을 나타냅니다.*destPoints*. |
| matrix | Matrix | ㅏ[`Matrix`](../../matrix/) 경로에 적용할 기하학적 변환을 지정합니다. |

### 또한보십시오

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | 배열[`PointF`](../../pointf/) 다음에 의해 정의된 사각형이 평행사변형을 정의하는 구조*srcRect*변환됩니다. 배열은 3개 또는 4개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 포함된 경우 평행사변형의 오른쪽 아래 모서리는 처음 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | ㅏ[`RectangleF`](../../rectanglef/) 에 의해 정의된 평행사변형으로 변환되는 사각형을 나타냅니다.*destPoints*. |
| matrix | Matrix | ㅏ[`Matrix`](../../matrix/) 경로에 적용할 기하학적 변환을 지정합니다. |
| warpMode | WarpMode | ㅏ[`WarpMode`](../../warpmode/) 이 워프 작업이 원근법 또는 쌍선형 모드를 사용하는지 여부를 지정하는 열거형입니다. |

### 또한보십시오

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| destPoints | PointF[] | 배열[`PointF`](../../pointf/) 에 의해 정의된 사각형이 평행사변형을 정의하는 구조*srcRect*변환됩니다. 배열은 3개 또는 4개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 포함된 경우 평행사변형의 오른쪽 아래 모서리는 처음 세 점에 의해 암시됩니다. |
| srcRect | RectangleF | ㅏ[`RectangleF`](../../rectanglef/) 에 의해 정의된 평행사변형으로 변환되는 사각형을 나타냅니다.*destPoints*. |
| matrix | Matrix | ㅏ[`Matrix`](../../matrix/) 경로에 적용할 기하학적 변환을 지정합니다. |
| warpMode | WarpMode | ㅏ[`WarpMode`](../../warpmode/) 이 워프 작업이 원근법 또는 쌍선형 모드를 사용하는지 여부를 지정하는 열거형입니다. |
| flatness | Single | 결과 경로의 평평한 정도를 지정하는 0에서 1 사이의 값입니다. 자세한 내용은 다음을 참조하십시오.[`Flatten`](../flatten/) 행동 양식. |

### 또한보십시오

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)


