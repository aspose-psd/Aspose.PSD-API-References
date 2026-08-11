---
title: "구조체 RectangleF"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.RectangleF 구조체. 사각형의 위치와 크기를 나타내는 네 개의 부동소수점 숫자를 저장합니다."
type: docs
weight: 5850
url: /ko/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자 집합을 저장합니다.

```csharp
public struct RectangleF
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | `RectangleF` 구조체의 새 인스턴스를 지정된 위치와 크기로 초기화합니다. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | `RectangleF` 구조체의 새 인스턴스를 지정된 위치와 크기로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | `RectangleF` 구조체의 새 인스턴스를 가져오며, [`X`](./x/), [`Y`](./y/), [`Width`](./width/), [`Height`](./height/) 값이 0으로 설정됩니다. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | 이 `RectangleF` 구조체의 [`Y`](./y/)와 [`Height`](./height/)의 합인 y좌표를 가져오거나 설정합니다. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | 이 `RectangleF` 구조체의 높이를 가져오거나 설정합니다. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | 이 `RectangleF`의 [`Width`](./width/) 또는 [`Height`](./height/) 속성이 0인지 여부를 나타내는 값을 가져옵니다. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | 이 `RectangleF` 구조의 왼쪽 가장자리의 x 좌표를 가져오거나 설정합니다. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | 이 `RectangleF` 구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | 이 `RectangleF` 구조의 [`X`](./x/)와 [`Width`](./width/)의 합인 x 좌표를 가져오거나 설정합니다. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | 이 `RectangleF`의 크기를 가져오거나 설정합니다. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | 이 `RectangleF` 구조의 상단 가장자리의 y 좌표를 가져오거나 설정합니다. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | 이 `RectangleF` 구조의 너비를 가져오거나 설정합니다. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | 이 `RectangleF` 구조의 왼쪽 위 모서리의 x 좌표를 가져오거나 설정합니다. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | 이 `RectangleF` 구조의 왼쪽 위 모서리의 y 좌표를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | 지정된 위치에 왼쪽 위 모서리와 오른쪽 아래 모서리를 갖는 `RectangleF` 구조를 생성합니다. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | 두 개의 지정된 점으로부터 새로운 [`Rectangle`](../rectangle/)을 생성합니다. 생성된 [`Rectangle`](../rectangle/)의 두 정점은 전달된 *point1*과 *point2*와 동일합니다. 일반적으로 이는 반대 꼭짓점이 됩니다. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | 지정된 `RectangleF` 구조의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 사각형은 변경되지 않습니다. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | 두 사각형의 교차점을 나타내는 `RectangleF` 구조를 반환합니다. 교차점이 없으면 빈 `RectangleF`가 반환됩니다. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | 두 사각형의 합집합을 포함할 수 있는 가장 작은 세 번째 사각형을 생성합니다. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | 지정된 점이 이 `RectangleF` 구조 내에 포함되는지 확인합니다. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | *rect*가 나타내는 사각형 영역이 이 `RectangleF` 구조에 완전히 포함되는지 확인합니다. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | 지정된 점이 이 `RectangleF` 구조 내에 포함되는지 확인합니다. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | *obj*가 이 `RectangleF`와 동일한 위치와 크기를 가진 `RectangleF`인지 테스트합니다. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | 이 `RectangleF` 구조의 해시 코드를 가져옵니다. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | 이 `RectangleF`를 지정된 양만큼 확대합니다. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | 이 `RectangleF` 구조를 지정된 양만큼 확대합니다. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | 이 `RectangleF` 구조를 자체와 지정된 `RectangleF` 구조의 교차점으로 교체합니다. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | 이 사각형이 *rect*와 교차하는지 확인합니다. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | 사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위가 아래보다 작도록 정규화합니다. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | 이 `RectangleF`의 속성을 사람이 읽을 수 있는 문자열로 변환합니다. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | / 연산자를 구현합니다. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | 두 `RectangleF` 구조가 위치와 크기가 동일한지 테스트합니다. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | 지정된 [`Rectangle`](../rectangle/) 구조를 `RectangleF` 구조로 변환합니다. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | 두 `RectangleF` 구조가 위치 또는 크기가 다른지 테스트합니다. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | 연산자 *를 구현합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


