---
title: "구조체 Point"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Point 구조체. 2차원 평면에서 점을 정의하는 정수 x와 y좌표의 순서쌍을 나타냅니다."
type: docs
weight: 5760
url: /ko/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

2차원 평면에서 점을 정의하는 정수 x 및 y 좌표의 순서쌍을 나타냅니다.

```csharp
public struct Point
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Point](point/#constructor_1)(int) | `Point` 구조체의 새 인스턴스를 정수 값으로 지정된 좌표를 사용하여 초기화합니다. |
| [Point](point/#constructor)(Size) | `Size` 구조체에서 `Point` 구조체의 새 인스턴스를 초기화합니다. |
| [Point](point/#constructor_2)(int, int) | 지정된 좌표로 `Point` 구조체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | [`X`](./x/)와 [`Y`](./y/) 값이 0으로 설정된 `Point` 구조체의 새 인스턴스를 가져옵니다. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | 이 `Point`가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [X](../../aspose.psd/point/x/) { get; set; } | 이 `Point`의 x좌표를 가져오거나 설정합니다. |
| [Y](../../aspose.psd/point/y/) { get; set; } | 이 `Point`의 y좌표를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | 지정된 [`Size`](../size/)를 지정된 `Point`에 추가합니다. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | 지정된 [`PointF`](../pointf/)의 값을 다음 높은 정수값으로 반올림하여 `Point`로 변환합니다. |
| static [Round](../../aspose.psd/point/round/)(PointF) | 지정된 [`PointF`](../pointf/)를 가장 가까운 정수로 반올림하여 `Point` 객체로 변환합니다. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | 지정된 [`Size`](../size/)를 지정된 `Point`에서 빼는 결과를 반환합니다. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | 지정된 [`PointF`](../pointf/)의 값을 잘라내어 `Point`로 변환합니다. |
| override [Equals](../../aspose.psd/point/equals/)(object) | 이 `Point`가 지정된 객체와 동일한 좌표를 포함하는지 여부를 지정합니다. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | 이 `Point`에 대한 해시 코드를 반환합니다. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | 이 `Point`를 지정된 `Point`만큼 이동합니다. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | 이 `Point`를 지정된 양만큼 이동합니다. |
| override [ToString](../../aspose.psd/point/tostring/)() | 이 `Point`를 사람이 읽을 수 있는 문자열로 변환합니다. |
| [operator +](../../aspose.psd/point/op_addition/) | 주어진 [`Size`](../size/)만큼 `Point`를 이동합니다. |
| [operator ==](../../aspose.psd/point/op_equality/) | 두 `Point` 객체를 비교합니다. 결과는 두 `Point` 객체의 [`X`](./x/) 및 [`Y`](./y/) 속성 값이 같은지 여부를 지정합니다. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | 지정된 `Point` 구조체를 [`Size`](../size/) 구조체로 변환합니다. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | 지정된 `Point` 구조체를 [`PointF`](../pointf/) 구조체로 변환합니다. |
| [operator !=](../../aspose.psd/point/op_inequality/) | 두 `Point` 객체를 비교합니다. 결과는 두 `Point` 객체의 [`X`](./x/) 또는 [`Y`](./y/) 속성 값이 서로 다른지 여부를 지정합니다. |
| [operator -](../../aspose.psd/point/op_subtraction/) | 주어진 [`Size`](../size/)의 음수만큼 `Point`를 이동합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


