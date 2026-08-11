---
title: "Blend 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Blend 클래스. 블렌드 패턴을 정의합니다. 이 클래스는 상속할 수 없습니다."
type: docs
weight: 110
url: /ko/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

블렌드 패턴을 정의합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class Blend
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Blend](blend/#constructor)() | 새 `Blend` 클래스 인스턴스를 초기화합니다. factor 및 blend 배열의 요소 수는 1과 같습니다. |
| [Blend](blend/#constructor_1)(int) | 지정된 factor와 position 수를 사용하여 새 `Blend` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | 그라디언트에 대한 blend factor 배열을 가져오거나 설정합니다. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | 그라디언트에 대한 blend position 배열을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | 지정된 객체가 `Blend` 클래스인지 그리고 이 `Blend` 클래스와 동등한지 테스트합니다. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |

## 비고

일반적인 blend 클래스 사용은 브러시용 blend 패턴을 정의하는 것입니다. 따라서 blend 속성은 신중하게 초기화해야 합니다. null 배열은 허용되지 않습니다. blend factor 또는 position 배열이 비어 있거나 길이가 동일하지 않으면 브러시가 적절한 예외를 발생시킵니다. position 배열에 두 개 이상의 요소가 있는 경우 첫 번째 요소는 0이어야 하고 마지막 요소는 1이어야 합니다.

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


