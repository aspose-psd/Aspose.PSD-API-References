---
title: "Yapı SizeF"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.SizeF yapısı. Genellikle bir dikdörtgenin genişliği ve yüksekliği olan sıralı bir kayan nokta sayı çifti saklar."
type: docs
weight: 6090
url: /tr/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Genellikle bir dikdörtgenin genişliği ve yüksekliği olan, sıralı bir kayan nokta sayısı çiftini depolar.

```csharp
public struct SizeF
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Belirtilen [`PointF`](../pointf/) üzerinden yeni bir `SizeF` yapısı örneği başlatır. |
| [SizeF](sizef/#constructor_1)(SizeF) | Belirtilen `SizeF` üzerinden yeni bir `SizeF` yapısı örneği başlatır. |
| [SizeF](sizef/#constructor_2)(float, float) | Belirtilen boyutlardan `SizeF` yapısının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | `SizeF` yapısının, [`Width`](./width/) ve [`Height`](./height/) değerleri sıfıra ayarlanmış yeni bir örneğini alır. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Bu `SizeF` nesnesinin dikey bileşenini alır veya ayarlar. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Bu `SizeF` nesnesinin sıfır genişlik ve yüksekliğe sahip olup olmadığını gösteren bir değeri alır. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Bu `SizeF` nesnesinin yatay bileşenini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Bir `SizeF` yapısının genişlik ve yüksekliğini, başka bir `SizeF` yapısının genişlik ve yüksekliğine ekler. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Bir `SizeF` yapısının genişlik ve yüksekliğini, başka bir `SizeF` yapısının genişlik ve yüksekliğinden çıkarır. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Belirtilen nesnenin bu `SizeF` ile aynı boyutlara sahip bir `SizeF` olup olmadığını test eder. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Bu [`Size`](../size/) yapısı için bir karma kodu döndürür. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | `SizeF` değerini bir [`PointF`](../pointf/) değerine dönüştürür. |
| [ToSize](../../aspose.psd/sizef/tosize/)() | `SizeF` değerini, kesilmiş boyut değerlerine sahip bir [`Size`](../size/) yapısına dönüştürür. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Bu `SizeF` nesnesini temsil eden insan tarafından okunabilir bir dize oluşturur. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Bir `SizeF` yapısının genişlik ve yüksekliğini, başka bir `SizeF` yapısının genişlik ve yüksekliğine ekler. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | İki `SizeF` yapısının eşit olup olmadığını test eder. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Belirtilen `SizeF` değerini bir [`PointF`](../pointf/) değerine dönüştürür. |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | İki `SizeF` yapısının farklı olup olmadığını test eder. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Bir `SizeF` yapısının genişlik ve yüksekliğini, başka bir `SizeF` yapısının genişlik ve yüksekliğinden çıkarır. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


