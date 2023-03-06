---
title: Struct Point
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Point yapı. İki boyutlu bir düzlemde bir noktayı tanımlayan sıralı bir tamsayı x ve y koordinat çiftini temsil eder.
type: docs
weight: 5260
url: /tr/net/aspose.psd/point/
---
## Point structure

İki boyutlu bir düzlemde bir noktayı tanımlayan sıralı bir tamsayı x ve y koordinat çiftini temsil eder.

```csharp
public struct Point
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Point](point/#constructor_1)(int) | Yeni bir örneğini başlatır.`Point` bir tamsayı değeriyle belirtilen koordinatları kullanan yapı. |
| [Point](point/#constructor)(Size) | Yeni bir örneğini başlatır.`Point` gelen yapı[`Size`](../size/)yapı. |
| [Point](point/#constructor_2)(int, int) | Yeni bir örneğini başlatır.`Point` belirtilen koordinatlara sahip yapı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Yeni bir örneğini alır`Point` sahip olan yapı[`X`](./x/) Ve[`Y`](./y/) değerler sıfıra ayarlandı. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Bunun olup olmadığını gösteren bir değer alır.`Point` boş. |
| [X](../../aspose.psd/point/x/) { get; set; } | Bunun x koordinatını alır veya ayarlar`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Bunun y koordinatını alır veya ayarlar`Point` . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Belirtileni ekler[`Size`](../size/) belirtilene`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Belirtileni dönüştürür[`PointF`](../pointf/) bir`Point` değerleri yuvarlayarak[`PointF`](../pointf/) sonraki daha yüksek tamsayı değerlerine. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Belirtileni dönüştürür[`PointF`](../pointf/) bir`Point` yuvarlayarak nesne`Point` değerleri en yakın tamsayıya. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Belirtilen çıkarma işleminin sonucunu döndürür[`Size`](../size/) belirtilenden`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Belirtileni dönüştürür[`PointF`](../pointf/) bir`Point` değerlerini keserek`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Bunun olup olmadığını belirtir`Point` belirtilenle aynı koordinatları içerirObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Bunun için bir karma kod döndürür`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Bunu çevirir`Point` belirtilen tarafından`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Bunu çevirir`Point`belirtilen miktarda. |
| override [ToString](../../aspose.psd/point/tostring/)() | Bunu dönüştürür`Point` okunabilir bir dizeye. |
| [operator +](../../aspose.psd/point/op_addition/) | a çevirir`Point` verilen tarafından[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | İkiyi karşılaştırır`Point` nesneler. Sonuç, değerlerinin olup olmadığını belirtir.[`X`](./x/) Ve[`Y`](./y/) ikisinin özellikleri`Point` nesneler eşittir. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Belirtileni dönüştürür`Point` bir yapı[`Size`](../size/)yapı. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Belirtileni dönüştürür`Point` yapısı[`PointF`](../pointf/)yapı. |
| [operator !=](../../aspose.psd/point/op_inequality/) | İkiyi karşılaştırır`Point` nesneler. Sonuç, değerlerinin olup olmadığını belirtir.[`X`](./x/) veya[`Y`](./y/) ikisinin özellikleri`Point` nesneler eşit değil. |
| [operator -](../../aspose.psd/point/op_subtraction/) | a çevirir`Point` verilen bir negatif tarafından[`Size`](../size/) . |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


