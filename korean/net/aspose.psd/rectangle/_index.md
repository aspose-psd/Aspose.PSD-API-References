---
title: Struct Rectangle
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Rectangle 구조체. 사각형의 위치와 크기를 나타내는 4개의 정수 집합을 저장합니다.
type: docs
weight: 5340
url: /ko/net/aspose.psd/rectangle/
---
## Rectangle structure

사각형의 위치와 크기를 나타내는 4개의 정수 집합을 저장합니다.

```csharp
public struct Rectangle
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | 의 새 인스턴스를 초기화합니다.`Rectangle` 지정된 위치와 크기의 구조. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | 의 새 인스턴스를 초기화합니다.`Rectangle` 지정된 위치와 크기의 구조. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | 의 새 인스턴스를 가져옵니다.`Rectangle` 가지고 있는 구조[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) 그리고[`Height`](./height/) 0으로 설정된 값. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | 의 합인 y 좌표를 가져오거나 설정합니다.[`Y`](./y/) 그리고[`Height`](./height/) 이것의 속성 값`Rectangle`구조. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | 높이를 가져오거나 설정합니다.`Rectangle`구조. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | 이 모든 숫자 속성이`Rectangle` 값이 0입니다. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | 왼쪽 가장자리의 x 좌표를 가져오거나 설정합니다.`Rectangle`구조. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | 왼쪽 위 모서리의 좌표를 가져오거나 설정합니다.`Rectangle`구조. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | 합계인 x 좌표를 가져오거나 설정합니다.[`X`](./x/) 그리고[`Width`](./width/) 이것의 속성 값`Rectangle`구조. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | 이 크기를 가져오거나 설정합니다.`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | 이 위쪽 가장자리의 y 좌표를 가져오거나 설정합니다.`Rectangle`구조. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | 이 너비를 가져오거나 설정합니다.`Rectangle`구조. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | 왼쪽 위 모서리의 x 좌표를 가져오거나 설정합니다.`Rectangle`구조. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | 왼쪽 위 모서리의 y 좌표를 가져오거나 설정합니다.`Rectangle`구조. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | 지정된[`RectangleF`](../rectanglef/) 에 구조`Rectangle` 반올림하여 구조[`RectangleF`](../rectanglef/) 값을 다음으로 높은 정수 값으로 바꿉니다. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | 생성`Rectangle` 지정된 가장자리 위치가 있는 구조. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | 새로 만들기`Rectangle` 지정된 두 지점에서. 생성된 두 수직`Rectangle` 통과한 것과 같을 것입니다.*point1* 그리고*point2* . 이들은 일반적으로 반대 정점입니다. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | 지정된`Rectangle`구조. 사본은 지정된 양만큼 부풀려집니다. 원래`Rectangle` 구조는 수정되지 않은 상태로 유지됩니다. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | 세 번째 반환`Rectangle` 다른 두 개의 교차점을 나타내는 구조`Rectangle` 구조. 교차가 없으면 빈`Rectangle` 반환됩니다. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | 지정된[`RectangleF`](../rectanglef/) ~에게`Rectangle` 반올림하여[`RectangleF`](../rectanglef/) 값을 가장 가까운 정수 값으로 변환합니다. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | 지정된[`RectangleF`](../rectanglef/) ~에게`Rectangle` 잘라서[`RectangleF`](../rectanglef/) 값. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | 가져오기`Rectangle` 2개의 합집합을 포함하는 구조`Rectangle` 구조. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | 지정된 포인트가 이 안에 포함되는지 확인합니다.`Rectangle`구조. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | 직사각형 영역이*rect* 이 안에 완전히 포함되어 있습니다`Rectangle`구조. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | 지정된 포인트가 이 안에 포함되는지 확인합니다.`Rectangle`구조. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | 여부를 테스트합니다.*obj* 이다`Rectangle`동일한 위치와 크기의 구조`Rectangle`구조. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | 이에 대한 해시 코드를 반환합니다.`Rectangle`구조. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | 팽창`Rectangle`지정된 금액만큼. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | 팽창`Rectangle`지정된 금액만큼. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | 이것을 대체합니다.`Rectangle` 자체와 지정된 교차로`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | 이 사각형이*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | 직사각형의 너비와 높이를 양수로 만들고 왼쪽은 오른쪽보다 작게, 위쪽은 아래쪽보다 작게 만들어 직사각형을 정규화합니다. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | 이것의 속성을 변환합니다.`Rectangle` 사람이 읽을 수 있는 문자열로. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | 두`Rectangle` 구조는 위치와 크기가 동일합니다. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | 두`Rectangle` 구조는 위치나 크기가 다릅니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


