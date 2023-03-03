---
title: Struct SizeF
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.SizeF 구조체. 일반적으로 직사각형의 너비와 높이인 부동 소수점 숫자의 정렬된 쌍을 저장합니다.
type: docs
weight: 5560
url: /ko/net/aspose.psd/sizef/
---
## SizeF structure

일반적으로 직사각형의 너비와 높이인 부동 소수점 숫자의 정렬된 쌍을 저장합니다.

```csharp
public struct SizeF
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | 의 새 인스턴스를 초기화합니다.`SizeF` 지정된 구조[`PointF`](../pointf/) . |
| [SizeF](sizef/#constructor_1)(SizeF) | 의 새 인스턴스를 초기화합니다.`SizeF` 지정된 구조`SizeF` . |
| [SizeF](sizef/#constructor_2)(float, float) | 의 새 인스턴스를 초기화합니다.`SizeF` 지정된 차원의 구조. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | 의 새 인스턴스를 가져옵니다.`SizeF` 가지고 있는 구조[`Width`](./width/) 그리고[`Height`](./height/) 0으로 설정된 값. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | 이 항목의 수직 구성 요소를 가져오거나 설정합니다.`SizeF` . |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | 이 여부를 나타내는 값을 가져옵니다.`SizeF` 너비와 높이가 0입니다. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | 이것의 수평 구성 요소를 가져오거나 설정합니다.`SizeF` . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | 너비와 높이를 하나 더합니다.`SizeF` 구조를 다른 너비와 높이로`SizeF`구조. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | 너비와 높이를 뺍니다.`SizeF` 다른 너비와 높이의 구조`SizeF`구조. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | 지정된 개체가`SizeF` 이것과 같은 치수로`SizeF` . |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | 이에 대한 해시 코드를 반환합니다.[`Size`](../size/)구조. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | 변환`SizeF` ~에게[`PointF`](../pointf/) . |
| [ToSize](../../aspose.psd/sizef/tosize/)() | 변환`SizeF` ~에게[`Size`](../size/) 크기 값이 잘린 구조. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | 이것을 나타내는 사람이 읽을 수 있는 문자열을 만듭니다.`SizeF` . |
| [operator +](../../aspose.psd/sizef/op_addition/) | 너비와 높이를 하나 더합니다.`SizeF` 구조를 다른 너비와 높이로`SizeF`구조. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | 두`SizeF` 구조가 동일합니다. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | 지정된`SizeF` ~에게[`PointF`](../pointf/) . |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | 두`SizeF` 구조가 다릅니다. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | 너비와 높이를 뺍니다.`SizeF` 다른 너비와 높이의 구조`SizeF`구조. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


