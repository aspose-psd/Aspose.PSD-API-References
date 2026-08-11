---
title: "구조체 PointF"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.PointF 구조체. 2차원 평면에서 점을 정의하는 부동소수점 x 및 y 좌표의 순서쌍을 나타냅니다."
type: docs
weight: 5770
url: /ko/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

2차원 평면에서 점을 정의하는 부동소수점 x 및 y 좌표의 순서쌍을 나타냅니다.

```csharp
public struct PointF
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PointF](pointf/)(float, float) | 지정된 좌표를 사용하여 `PointF` 구조체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | `PointF` 구조체의 새 인스턴스를 가져오며, [`X`](./x/) 및 [`Y`](./y/) 값이 0으로 설정됩니다. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | 이 `PointF`가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | 이 `PointF`의 x좌표를 가져오거나 설정합니다. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | 이 `PointF`의 y좌표를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | 지정된 [`Size`](../size/)만큼 주어진 `PointF`를 변환합니다. |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | 지정된 [`SizeF`](../sizef/)만큼 주어진 `PointF`를 변환합니다. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | 지정된 크기의 음수만큼 `PointF`를 변환합니다. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | 지정된 크기의 음수만큼 `PointF`를 변환합니다. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | 이 `PointF`가 지정된 객체와 동일한 좌표를 포함하는지 여부를 지정합니다. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | 이 `PointF` 구조체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | 이 `PointF`를 사람이 읽을 수 있는 문자열로 변환합니다. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | 주어진 [`Size`](../size/)만큼 `PointF`를 변환합니다. (연산자 2개) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | 두 `PointF` 구조체를 비교합니다. 결과는 두 `PointF` 구조체의 [`X`](./x/) 및 [`Y`](./y/) 속성 값이 동일한지 여부를 지정합니다. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | 지정된 점들의 좌표가 동일하지 않은지 여부를 판단합니다. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | 주어진 [`Size`](../size/)의 음수만큼 `PointF`를 변환합니다. (연산자 2개) |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


