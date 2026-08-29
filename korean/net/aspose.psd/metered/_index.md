---
title: "클래스 Metered"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Metered 클래스. 메터링 키를 설정하는 메서드를 제공합니다."
type: docs
weight: 5610
url: /ko/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

계량 키를 설정하는 메서드를 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | 지정된 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | 제품 이름을 가져옵니다. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | 메터링 공개 및 개인 키를 설정합니다. 메터링 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며 일반적으로 이것만으로 충분합니다. 그러나 사용량 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다. 이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | 소비 크레딧을 가져옵니다 |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | 소비 파일 크기를 가져옵니다 |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | metered가 라이선스가 있는지 확인합니다 |

## 예제

이 예제에서는 metered 공개 및 개인 키를 설정하려고 시도합니다

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


