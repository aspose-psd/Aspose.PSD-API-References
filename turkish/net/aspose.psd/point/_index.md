---
title: "Struct Point"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Point struct. İki boyutlu bir düzlemde bir noktayı tanımlayan, tamsayı x ve y koordinatlarından oluşan sıralı bir çift temsil eder."
type: docs
weight: 5790
url: /tr/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

İki boyutlu bir düzlemde bir noktayı tanımlayan tamsayı x ve y koordinatlarından oluşan sıralı bir çift temsil eder.

```csharp
public struct Point
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Point](point/#constructor_1)(int) | `Point` yapısının yeni bir örneğini, bir tamsayı değeriyle belirtilen koordinatları kullanarak başlatır. |
| [Point](point/#constructor)(Size) | `Point` yapısının yeni bir örneğini, [`Size`](../size/) yapısından başlatır. |
| [Point](point/#constructor_2)(int, int) | Belirtilen koordinatlarla `Point` yapısının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | `Point` yapısının, [`X`](./x/) ve [`Y`](./y/) değerleri sıfıra ayarlanmış yeni bir örneğini alır. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Bu `Point` nesnesinin boş olup olmadığını gösteren bir değer alır. |
| [X](../../aspose.psd/point/x/) { get; set; } | Bu `Point` nesnesinin x koordinatını alır veya ayarlar. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Bu `Point` nesnesinin y koordinatını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Belirtilen [`Size`](../size/) değerini belirtilen `Point` nesnesine ekler. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Belirtilen [`PointF`](../pointf/) değerini, [`PointF`](../pointf/) değerlerini bir sonraki daha yüksek tam sayıya yuvarlayarak bir `Point` nesnesine dönüştürür. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Belirtilen [`PointF`](../pointf/) değerini, `Point` değerlerini en yakın tam sayıya yuvarlayarak bir `Point` nesnesine dönüştürür. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Belirtilen `Point` nesnesinden belirtilen [`Size`](../size/) değerini çıkararak sonucu döndürür. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Belirtilen [`PointF`](../pointf/) değerini, `Point` değerlerini kırparak bir `Point` nesnesine dönüştürür. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Bu `Point` nesnesinin, belirtilen Nesne ile aynı koordinatları içerip içermediğini belirtir. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Bu `Point` nesnesi için bir hash kodu döndürür. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Bu `Point` nesnesini belirtilen `Point` kadar kaydırır. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Bu `Point` nesnesini belirtilen miktarda kaydırır. |
| override [ToString](../../aspose.psd/point/tostring/)() | Bu `Point` nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [operator +](../../aspose.psd/point/op_addition/) | Bir `Point` nesnesini verilen bir [`Size`](../size/) ile kaydırır. |
| [operator ==](../../aspose.psd/point/op_equality/) | İki `Point` nesnesini karşılaştırır. Sonuç, iki `Point` nesnesinin [`X`](./x/) ve [`Y`](./y/) özelliklerinin değerlerinin eşit olup olmadığını belirtir. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Belirtilen `Point` yapısını bir [`Size`](../size/) yapısına dönüştürür. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Belirtilen `Point` yapısını [`PointF`](../pointf/) yapısına dönüştürür. |
| [operator !=](../../aspose.psd/point/op_inequality/) | İki `Point` nesnesini karşılaştırır. Sonuç, iki `Point` nesnesinin [`X`](./x/) veya [`Y`](./y/) özelliklerinin değerlerinin eşit olmaması durumunu belirtir. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Bir `Point`i verilen bir [`Size`](../size/) değerinin negatifine göre çevirir. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


