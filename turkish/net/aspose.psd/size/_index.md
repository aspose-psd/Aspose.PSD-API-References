---
title: "Yapı Size"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Size yapısı. Boyutu temsil eder"
type: docs
weight: 6080
url: /tr/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Boyutu temsil eder.

```csharp
public struct Size
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Size](size/#constructor)(Point) | Belirtilen [`Point`](../point/) öğesinden yeni bir `Size` yapısı örneği başlatır. |
| [Size](size/#constructor_1)(int, int) | Belirtilen boyutlardan yeni bir `Size` yapısı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Sıfır olarak ayarlanmış [`Width`](./width/) ve [`Height`](./height/) değerlerine sahip yeni bir `Size` yapısı örneğini alır. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Bu `Size` nesnesinin dikey bileşenini alır veya ayarlar. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Bu `Size` nesnesinin genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değeri alır. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Bu `Size` nesnesinin yatay bileşenini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Bir `Size` yapısının genişlik ve yüksekliğini başka bir `Size` yapısının genişlik ve yüksekliğine ekler. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Belirtilen [`SizeF`](../sizef/) yapısını, `Size` yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir `Size` yapısına dönüştürür. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Belirtilen [`SizeF`](../sizef/) yapısını, [`SizeF`](../sizef/) değerlerini en yakın tam sayıya yuvarlayarak bir `Size` yapısına dönüştürür. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Bir `Size` yapısının genişlik ve yüksekliğini başka bir `Size` yapısının genişlik ve yüksekliğinden çıkarır. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Belirtilen [`SizeF`](../sizef/) yapısını, [`SizeF`](../sizef/) değerlerini bir sonraki alt tam sayıya kırparak bir `Size` yapısına dönüştürür. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Belirtilen nesnenin bu `Size` ile aynı boyutlara sahip bir `Size` olup olmadığını test eder. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Bu `Size` yapısı için bir karma kodu döndürür. |
| override [ToString](../../aspose.psd/size/tostring/)() | Bu `Size` nesnesini temsil eden insan tarafından okunabilir bir dize oluşturur. |
| [operator +](../../aspose.psd/size/op_addition/) | Bir `Size` yapısının genişlik ve yüksekliğini başka bir `Size` yapısının genişlik ve yüksekliğine ekler. |
| [operator ==](../../aspose.psd/size/op_equality/) | İki `Size` yapısının eşit olup olmadığını test eder. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Belirtilen `Size` değerini bir [`Point`](../point/) nesnesine dönüştürür. |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Belirtilen `Size` değerini bir [`SizeF`](../sizef/) nesnesine dönüştürür. |
| [operator !=](../../aspose.psd/size/op_inequality/) | İki `Size` yapısının farklı olup olmadığını test eder. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Bir `Size` yapısının genişlik ve yüksekliğini başka bir `Size` yapısının genişlik ve yüksekliğinden çıkarır. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


