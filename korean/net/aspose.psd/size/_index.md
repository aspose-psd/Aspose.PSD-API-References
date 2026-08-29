---
title: "구조체 Size"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Size struct. 크기를 나타냅니다."
type: docs
weight: 6050
url: /ko/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

크기를 나타냅니다.

```csharp
public struct Size
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Size](size/#constructor)(Point) | 지정된 [`Point`](../point/)에서 `Size` 구조체의 새 인스턴스를 초기화합니다. |
| [Size](size/#constructor_1)(int, int) | 지정된 차원에서 `Size` 구조체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | `[`Width`](./width/)`와 `[`Height`](./height/)` 값이 0으로 설정된 `Size` 구조체의 새 인스턴스를 가져옵니다. |
| [Height](../../aspose.psd/size/height/) { get; set; } | `Size`의 수직 구성 요소를 가져오거나 설정합니다. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | 이 `Size`의 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다. |
| [Width](../../aspose.psd/size/width/) { get; set; } | `Size`의 수평 구성 요소를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | 한 `Size` 구조체의 너비와 높이를 다른 `Size` 구조체의 너비와 높이에 더합니다. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | 지정된 [`SizeF`](../sizef/) 구조체를 `Size` 구조체로 변환하며, `Size` 구조체의 값을 다음 높은 정수값으로 반올림합니다. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | 지정된 [`SizeF`](../sizef/) 구조체를 `Size` 구조체로 변환하며, [`SizeF`](../sizef/) 구조체의 값을 가장 가까운 정수값으로 반올림합니다. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | 한 `Size` 구조체의 너비와 높이를 다른 `Size` 구조체의 너비와 높이에서 빼습니다. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | 지정된 [`SizeF`](../sizef/) 구조체를 `Size` 구조체로 변환하며, [`SizeF`](../sizef/) 구조체의 값을 다음 낮은 정수값으로 내림합니다. |
| override [Equals](../../aspose.psd/size/equals/)(object) | 지정된 객체가 이 `Size`와 동일한 차원을 가진 `Size`인지 테스트합니다. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | 이 `Size` 구조체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../aspose.psd/size/tostring/)() | 이 `Size`를 나타내는 사람이 읽을 수 있는 문자열을 생성합니다. |
| [operator +](../../aspose.psd/size/op_addition/) | 한 `Size` 구조체의 너비와 높이를 다른 `Size` 구조체의 너비와 높이에 더합니다. |
| [operator ==](../../aspose.psd/size/op_equality/) | 두 `Size` 구조체가 같은지 테스트합니다. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | 지정된 `Size`를 [`Point`](../point/)으로 변환합니다. |
| [implicit operator](../../aspose.psd/size/op_implicit/) | 지정된 `Size`를 [`SizeF`](../sizef/)으로 변환합니다. |
| [operator !=](../../aspose.psd/size/op_inequality/) | 두 `Size` 구조체가 다른지 테스트합니다. |
| [operator -](../../aspose.psd/size/op_subtraction/) | 한 `Size` 구조체의 너비와 높이를 다른 `Size` 구조체의 너비와 높이에서 빼습니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


