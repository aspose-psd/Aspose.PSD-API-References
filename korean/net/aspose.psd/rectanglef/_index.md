---
title: Struct RectangleF
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.RectangleF 구조체. 사각형의 위치와 크기를 나타내는 4개의 부동 소수점 숫자 집합을 저장합니다.
type: docs
weight: 5350
url: /ko/net/aspose.psd/rectanglef/
---
## RectangleF structure

사각형의 위치와 크기를 나타내는 4개의 부동 소수점 숫자 집합을 저장합니다.

```csharp
public struct RectangleF
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | 의 새 인스턴스를 초기화합니다.`RectangleF` 지정된 위치와 크기의 구조. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | 의 새 인스턴스를 초기화합니다.`RectangleF` 지정된 위치와 크기의 구조. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | 의 새 인스턴스를 가져옵니다.`RectangleF` 가지고 있는 구조[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) 그리고[`Height`](./height/) 0으로 설정된 값. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | 의 합인 y 좌표를 가져오거나 설정합니다.[`Y`](./y/) 그리고[`Height`](./height/) 이의`RectangleF`구조. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | 높이를 가져오거나 설정합니다.`RectangleF`구조. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | 여부를 나타내는 값을 가져옵니다.[`Width`](./width/) 또는[`Height`](./height/) 이것의 재산`RectangleF` 값이 0입니다. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | 왼쪽 가장자리의 x 좌표를 가져오거나 설정합니다.`RectangleF`구조. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | 왼쪽 위 모서리의 좌표를 가져오거나 설정합니다.`RectangleF`구조. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | 합계인 x 좌표를 가져오거나 설정합니다.[`X`](./x/) 그리고[`Width`](./width/) 이의`RectangleF`구조. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | 이 크기를 가져오거나 설정합니다.`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | 이 위쪽 가장자리의 y 좌표를 가져오거나 설정합니다.`RectangleF`구조. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | 이 너비를 가져오거나 설정합니다.`RectangleF`구조. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | 왼쪽 위 모서리의 x 좌표를 가져오거나 설정합니다.`RectangleF`구조. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | 왼쪽 위 모서리의 y 좌표를 가져오거나 설정합니다.`RectangleF`구조. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | 생성`RectangleF` 지정된 위치에서 왼쪽 위 모서리와 오른쪽 아래 모서리가 있는 구조. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | 새로 만들기[`Rectangle`](../rectangle/) 지정된 두 지점에서. 생성된 두 정점[`Rectangle`](../rectangle/) 통과한 것과 같을 것입니다.*point1* 그리고*point2* . 이들은 일반적으로 반대 정점입니다. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | 지정된`RectangleF`구조. 사본은 지정된 양만큼 부풀려집니다. 원래 직사각형은 수정되지 않은 상태로 유지됩니다. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | 반환`RectangleF` 두 직사각형의 교차점을 나타내는 구조체입니다. 교차점이 없고 비어 있는 경우`RectangleF` 반환됩니다. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | 합집합을 형성하는 두 개의 사각형을 모두 포함할 수 있는 가능한 가장 작은 세 번째 사각형을 만듭니다. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | 지정된 포인트가 이 안에 포함되는지 확인합니다.`RectangleF`구조. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | 직사각형 영역이*rect* 이 안에 완전히 포함되어 있습니다`RectangleF`구조. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | 지정된 포인트가 이 안에 포함되는지 확인합니다.`RectangleF`구조. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | 여부를 테스트합니다.*obj* 이다`RectangleF` 같은 위치와 크기로`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | 이에 대한 해시 코드를 가져옵니다.`RectangleF`구조. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | 팽창`RectangleF`지정된 금액만큼. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | 팽창`RectangleF` 지정된 금액으로 구조. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | 이것을 대체합니다.`RectangleF`자신과 지정된 것이 교차하는 구조`RectangleF`구조. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | 이 사각형이*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | 직사각형의 너비와 높이를 양수로 만들고 왼쪽은 오른쪽보다 작게, 위쪽은 아래쪽보다 작게 만들어 직사각형을 정규화합니다. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | 지정된 양만큼 이 사각형의 위치를 조정합니다. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | 이것의 속성을 변환합니다.`RectangleF` 사람이 읽을 수 있는 문자열로. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | 연산자 구현 /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | 두`RectangleF` 구조는 위치와 크기가 동일합니다. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | 지정된[`Rectangle`](../rectangle/) 에 구조`RectangleF`구조. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | 두`RectangleF` 구조는 위치나 크기가 다릅니다. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | 연산자 *. 를 구현합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


