---
title: Struct Size
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Size 구조체. 크기를 나타냅니다.
type: docs
weight: 5550
url: /ko/net/aspose.psd/size/
---
## Size structure

크기를 나타냅니다.

```csharp
public struct Size
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Size](size/#constructor)(Point) | 의 새 인스턴스를 초기화합니다.`Size` 지정된 구조[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | 의 새 인스턴스를 초기화합니다.`Size` 지정된 차원의 구조. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | 의 새 인스턴스를 가져옵니다.`Size` 가지고 있는 구조[`Width`](./width/) 그리고[`Height`](./height/) 0으로 설정된 값. |
| [Height](../../aspose.psd/size/height/) { get; set; } | 이 항목의 수직 구성 요소를 가져오거나 설정합니다.`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`Size` 너비와 높이는 0. 입니다. |
| [Width](../../aspose.psd/size/width/) { get; set; } | 이것의 수평 구성 요소를 가져오거나 설정합니다.`Size` . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | 너비와 높이를 하나 더합니다.`Size` 구조를 다른 너비와 높이로`Size`구조. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | 지정된[`SizeF`](../sizef/) 에 구조`Size` 의 값을 반올림하여 구조`Size` 구조를 다음으로 높은 정수 값으로 바꿉니다. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | 지정된[`SizeF`](../sizef/) 에 구조`Size` 의 값을 반올림하여 구조[`SizeF`](../sizef/) 구조를 가장 가까운 정수 값으로 변환합니다. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | 너비와 높이를 뺍니다.`Size` 다른 너비와 높이의 구조`Size`구조. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | 지정된[`SizeF`](../sizef/) 에 구조`Size` 의 값을 잘라 구조[`SizeF`](../sizef/) 구조를 다음으로 낮은 정수 값으로 바꿉니다. |
| override [Equals](../../aspose.psd/size/equals/)(object) | 지정된 개체가`Size` 이것과 같은 치수로`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | 이에 대한 해시 코드를 반환합니다.`Size`구조. |
| override [ToString](../../aspose.psd/size/tostring/)() | 이것을 나타내는 사람이 읽을 수 있는 문자열을 만듭니다.`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | 너비와 높이를 하나 더합니다.`Size` 구조를 다른 너비와 높이로`Size`구조. |
| [operator ==](../../aspose.psd/size/op_equality/) | 두`Size` 구조가 동일합니다. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | 지정된`Size` ~에게[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | 지정된`Size` ~에게[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | 두`Size` 구조가 다릅니다. |
| [operator -](../../aspose.psd/size/op_subtraction/) | 너비와 높이를 뺍니다.`Size` 다른 너비와 높이의 구조`Size`구조. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


