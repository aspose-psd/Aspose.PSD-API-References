---
title: "구조체 SizeF"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.SizeF 구조체. 일반적으로 사각형의 너비와 높이를 나타내는 부동소수점 숫자 쌍을 저장합니다."
type: docs
weight: 6060
url: /ko/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

보통 사각형의 너비와 높이를 나타내는 부동 소수점 숫자 쌍을 저장합니다.

```csharp
public struct SizeF
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | 지정된 [`PointF`](../pointf/)에서 `SizeF` 구조체의 새 인스턴스를 초기화합니다. |
| [SizeF](sizef/#constructor_1)(SizeF) | 지정된 `SizeF`에서 `SizeF` 구조체의 새 인스턴스를 초기화합니다. |
| [SizeF](sizef/#constructor_2)(float, float) | 지정된 차원에서 `SizeF` 구조체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | `[`Width`](./width/)`와 `[`Height`](./height/)` 값이 0으로 설정된 `SizeF` 구조체의 새 인스턴스를 가져옵니다. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | 이 `SizeF`의 수직 구성 요소를 가져오거나 설정합니다. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | 이 `SizeF`가 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | 이 `SizeF`의 수평 구성 요소를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | 하나의 `SizeF` 구조의 너비와 높이를 다른 `SizeF` 구조의 너비와 높이에 더합니다. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | 하나의 `SizeF` 구조의 너비와 높이를 다른 `SizeF` 구조의 너비와 높이에서 빼습니다. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | 지정된 객체가 이 `SizeF`와 동일한 차원을 가진 `SizeF`인지 테스트합니다. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | 이 [`Size`](../size/) 구조에 대한 해시 코드를 반환합니다. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | `SizeF`를 [`PointF`](../pointf/) 로 변환합니다. |
| [ToSize](../../aspose.psd/sizef/tosize/)() | `SizeF`를 잘린 크기 값으로 [`Size`](../size/) 구조로 변환합니다. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | 이 `SizeF`를 나타내는 사람이 읽을 수 있는 문자열을 생성합니다. |
| [operator +](../../aspose.psd/sizef/op_addition/) | 하나의 `SizeF` 구조의 너비와 높이를 다른 `SizeF` 구조의 너비와 높이에 더합니다. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | 두 `SizeF` 구조가 같은지 테스트합니다. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | 지정된 `SizeF`를 [`PointF`](../pointf/) 로 변환합니다. |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | 두 `SizeF` 구조가 다른지 테스트합니다. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | 하나의 `SizeF` 구조의 너비와 높이를 다른 `SizeF` 구조의 너비와 높이에서 빼습니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


