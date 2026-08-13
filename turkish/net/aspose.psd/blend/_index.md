---
title: "Blend sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Blend sınıfı. Bir karışım deseni tanımlar. Bu sınıf miras alınamaz"
type: docs
weight: 110
url: /tr/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

Bir karışım deseni tanımlar. Bu sınıf kalıtılamaz.

```csharp
public sealed class Blend
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Blend](blend/#constructor)() | Yeni bir `Blend` sınıfı örneği başlatır. Faktor ve blend dizilerindeki öğe sayısı 1 olacaktır. |
| [Blend](blend/#constructor_1)(int) | Belirtilen faktör ve konum sayısıyla yeni bir `Blend` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Gradyan için blend faktörleri dizisini alır veya ayarlar. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Gradyan için blend konumları dizisini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Belirtilen nesnenin bir `Blend` sınıfı olup olmadığını ve bu `Blend` sınıfına eşit olup olmadığını test eder. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Bu örnek için bir hash kodu döndürür. |

## Açıklamalar

Tipik blend sınıfı kullanımı, fırça için bir blend deseni tanımlamaktır. Bu nedenle blend özellikleri dikkatlice başlatılmalıdır. Null dizilerine izin verilmez. Blend faktörleri veya konum dizileri boşsa ya da uzunlukları aynı değilse, fırça uygun bir istisna fırlatır. Konum dizisinde iki veya daha fazla öğe varsa, ilk öğe 0, son öğe 1 olmalıdır.

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


