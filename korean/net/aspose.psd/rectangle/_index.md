---
title: "구조체 Rectangle"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Rectangle 구조체. 사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다."
type: docs
weight: 5840
url: /ko/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다.

```csharp
public struct Rectangle
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | 지정된 위치와 크기로 `Rectangle` 구조체의 새 인스턴스를 초기화합니다. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | 지정된 위치와 크기로 `Rectangle` 구조체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | `Rectangle` 구조체의 새 인스턴스를 가져오며, 이 인스턴스는 [`X`](./x/), [`Y`](./y/), [`Width`](./width/), [`Height`](./height/) 값이 0으로 설정됩니다. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | 이 `Rectangle` 구조체의 [`Y`](./y/) 및 [`Height`](./height/) 속성 값의 합인 y좌표를 가져오거나 설정합니다. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | 이 `Rectangle` 구조체의 높이를 가져오거나 설정합니다. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | 이 `Rectangle`의 모든 숫자 속성이 0값을 갖는지 여부를 나타내는 값을 가져옵니다. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | 이 `Rectangle` 구조체의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | 이 `Rectangle` 구조체의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | 이 `Rectangle` 구조체의 [`X`](./x/) 및 [`Width`](./width/) 속성 값의 합인 x좌표를 가져오거나 설정합니다. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | 이 `Rectangle`의 크기를 가져오거나 설정합니다. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | 이 `Rectangle` 구조체의 위쪽 가장자리 y좌표를 가져오거나 설정합니다. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | 이 `Rectangle` 구조체의 너비를 가져오거나 설정합니다. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | 이 `Rectangle` 구조체의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | 이 `Rectangle` 구조의 왼쪽 위 모서리의 y 좌표를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | 지정된 [`RectangleF`](../rectanglef/) 구조를 `Rectangle` 구조로 변환합니다. 이때 [`RectangleF`](../rectanglef/) 값들을 다음 높은 정수 값으로 반올림합니다. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | 지정된 가장자리 위치를 사용하여 `Rectangle` 구조를 생성합니다. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | 지정된 두 점으로부터 새로운 `Rectangle`을 생성합니다. 생성된 `Rectangle`의 두 수직 변은 전달된 *point1*과 *point2*와 동일합니다. 이는 일반적으로 반대 꼭짓점이 됩니다. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | 지정된 `Rectangle` 구조의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 `Rectangle` 구조는 변경되지 않습니다. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | 두 개의 다른 `Rectangle` 구조의 교차점을 나타내는 세 번째 `Rectangle` 구조를 반환합니다. 교차점이 없으면 빈 `Rectangle`이 반환됩니다. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | 지정된 [`RectangleF`](../rectanglef/)을 `Rectangle`으로 변환합니다. 이때 [`RectangleF`](../rectanglef/) 값들을 가장 가까운 정수 값으로 반올림합니다. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | 지정된 [`RectangleF`](../rectanglef/)을 `Rectangle`으로 변환합니다. 이때 [`RectangleF`](../rectanglef/) 값들을 잘라내어 정수 부분만 남깁니다. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | 두 `Rectangle` 구조의 합집합을 포함하는 `Rectangle` 구조를 가져옵니다. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | 지정된 점이 이 `Rectangle` 구조 내에 포함되는지 확인합니다. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | *rect*가 나타내는 사각형 영역이 이 `Rectangle` 구조에 완전히 포함되는지 확인합니다. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | 지정된 점이 이 `Rectangle` 구조 내에 포함되는지 확인합니다. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | *obj*가 이 `Rectangle` 구조와 동일한 위치와 크기를 가진 `Rectangle` 구조인지 테스트합니다. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | 이 `Rectangle` 구조의 해시 코드를 반환합니다. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | 지정된 양만큼 이 `Rectangle`을 확대합니다. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | 지정된 양만큼 이 `Rectangle`을 확대합니다. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | 이 `Rectangle`을 자체와 지정된 `Rectangle`의 교차점으로 교체합니다. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | 이 사각형이 *rect*와 교차하는지 확인합니다. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | 사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위가 아래보다 작도록 정규화합니다. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | 이 `Rectangle`의 속성을 사람이 읽을 수 있는 문자열로 변환합니다. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | 두 `Rectangle` 구조가 동일한 위치와 크기를 가지고 있는지 테스트합니다. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | 두 `Rectangle` 구조가 위치 또는 크기가 다른지 테스트합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


