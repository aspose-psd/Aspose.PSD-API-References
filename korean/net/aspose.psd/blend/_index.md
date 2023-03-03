---
title: Class Blend
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Blend 수업. 혼합 패턴을 정의합니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 110
url: /ko/net/aspose.psd/blend/
---
## Blend class

혼합 패턴을 정의합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class Blend
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Blend](blend/#constructor)() | 의 새 인스턴스를 초기화합니다.`Blend` 수업. factor 및 blend 배열의 요소 수는 1. 와 같습니다. |
| [Blend](blend/#constructor_1)(int) | 의 새 인스턴스를 초기화합니다.`Blend` 지정된 수의 요소 및 위치가 있는 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | 그라디언트에 대한 혼합 계수의 배열을 가져오거나 설정합니다. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | 그라디언트의 혼합 위치 배열을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | 지정된 개체가`Blend` 클래스이며 이것과 동일합니다.`Blend` 클래스. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |

### 비고

일반적인 블렌드 클래스 사용법은 브러시에 대한 블렌드 패턴을 정의하는 것입니다. 따라서 혼합 속성을 신중하게 초기화해야 합니다. Null 배열은 허용되지 않습니다. 블렌드 계수 또는 위치 배열이 비어 있거나 길이가 동일하지 않은 경우 브러시는 적절한 예외를 발생시킵니다. 위치 배열에 두 개 이상의 요소가 있는 경우 첫 번째 요소는 0이어야 하고 마지막 요소는 1이어야 합니다.

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


