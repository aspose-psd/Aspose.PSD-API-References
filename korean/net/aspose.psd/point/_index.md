---
title: Struct Point
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Point 구조체. 2차원 평면에서 한 점을 정의하는 정수 x 및 y 좌표의 정렬된 쌍을 나타냅니다.
type: docs
weight: 5260
url: /ko/net/aspose.psd/point/
---
## Point structure

2차원 평면에서 한 점을 정의하는 정수 x 및 y 좌표의 정렬된 쌍을 나타냅니다.

```csharp
public struct Point
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Point](point/#constructor_1)(int) | 의 새 인스턴스를 초기화합니다.`Point` 정수 값으로 지정된 좌표를 사용하는 구조. |
| [Point](point/#constructor)(Size) | 의 새 인스턴스를 초기화합니다.`Point` 에서 구조[`Size`](../size/)구조. |
| [Point](point/#constructor_2)(int, int) | 의 새 인스턴스를 초기화합니다.`Point` 지정된 좌표가 있는 구조. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | 의 새 인스턴스를 가져옵니다.`Point` 가지고 있는 구조[`X`](./x/) 그리고[`Y`](./y/) 0으로 설정된 값. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`Point` 비어 있습니다. |
| [X](../../aspose.psd/point/x/) { get; set; } | 이것의 x 좌표를 가져오거나 설정합니다.`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | 이것의 y 좌표를 가져오거나 설정합니다.`Point` . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | 지정된 항목을 추가합니다.[`Size`](../size/) 지정된`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | 지정된[`PointF`](../pointf/) ~에게`Point` 의 값을 반올림하여[`PointF`](../pointf/) 다음으로 높은 정수 값으로. |
| static [Round](../../aspose.psd/point/round/)(PointF) | 지정된[`PointF`](../pointf/) ~에게`Point` 반올림하여 객체`Point` 값을 가장 가까운 정수로. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | 지정된 빼기 결과를 반환합니다.[`Size`](../size/) 지정된 것에서`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | 지정된[`PointF`](../pointf/) ~에게`Point` 의 값을 잘라내어`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | 이 여부를 지정합니다.`Point` 지정된 것과 동일한 좌표를 포함합니다.Object . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | 이에 대한 해시 코드를 반환합니다.`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | 번역`Point` 지정된`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | 번역`Point`지정된 금액만큼. |
| override [ToString](../../aspose.psd/point/tostring/)() | 이것을 변환`Point` 사람이 읽을 수 있는 문자열로. |
| [operator +](../../aspose.psd/point/op_addition/) | 번역`Point` 주어진[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | 두 개를 비교합니다.`Point` 사물. 결과는[`X`](./x/) 그리고[`Y`](./y/) 둘의 속성`Point` 개체가 같습니다. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | 지정된`Point` 에 구조[`Size`](../size/)구조. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | 지정된`Point` 에 구조[`PointF`](../pointf/)구조. |
| [operator !=](../../aspose.psd/point/op_inequality/) | 두 개를 비교합니다.`Point` 사물. 결과는[`X`](./x/) 또는[`Y`](./y/) 둘의 속성`Point` 개체가 같지 않습니다. |
| [operator -](../../aspose.psd/point/op_subtraction/) | 번역`Point` 주어진 부정에 의해[`Size`](../size/) . |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


