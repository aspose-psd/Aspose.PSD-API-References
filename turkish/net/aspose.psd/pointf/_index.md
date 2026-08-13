---
title: "Yapı PointF"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.PointF yapısı. İki boyutlu bir düzlemde bir noktayı tanımlayan, kayan noktalı x ve y koordinatlarından oluşan sıralı bir çift temsil eder."
type: docs
weight: 5800
url: /tr/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

İki boyutlu bir düzlemde bir noktayı tanımlayan kayan noktalı x ve y koordinatlarından oluşan sıralı bir çift temsil eder.

```csharp
public struct PointF
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PointF](pointf/)(float, float) | Belirtilen koordinatlarla `PointF` yapısının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Sıfır olarak ayarlanmış [`X`](./x/) ve [`Y`](./y/) değerlerine sahip `PointF` yapısının yeni bir örneğini alır. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Bu `PointF` nesnesinin boş olup olmadığını gösteren bir değeri alır. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Bu `PointF` nesnesinin x koordinatını alır veya ayarlar. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Bu `PointF` nesnesinin y koordinatını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Belirtilen [`Size`](../size/) ile verilen bir `PointF` nesnesini kaydırır. |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Belirtilen [`SizeF`](../sizef/) ile verilen bir `PointF` nesnesini kaydırır. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Belirtilen bir boyutun negatifine göre bir `PointF` nesnesini kaydırır. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Belirtilen bir boyutun negatifine göre bir `PointF` nesnesini kaydırır. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Bu `PointF` nesnesinin belirtilen Nesne ile aynı koordinatları içerip içermediğini belirtir. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Bu `PointF` yapısı için bir karma kodu döndürür. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Bu `PointF` nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Verilen bir [`Size`](../size/) ile bir `PointF` nesnesini kaydırır. (2 operatör) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | İki `PointF` yapısını karşılaştırır. Sonuç, iki `PointF` yapısının [`X`](./x/) ve [`Y`](./y/) özellik değerlerinin eşit olup olmadığını belirtir. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Belirtilen noktaların koordinatlarının eşit olmadığını belirler. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Verilen bir [`Size`](../size/) değerinin negatifine göre bir `PointF` nesnesini kaydırır. (2 operatör) |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


