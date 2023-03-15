---
title: Struct Size
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Size yapı. Boyutu temsil eder.
type: docs
weight: 5550
url: /tr/net/aspose.psd/size/
---
## Size structure

Boyutu temsil eder.

```csharp
public struct Size
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Size](size/#constructor)(Point) | Yeni bir örneğini başlatır.`Size` belirtilen yapı[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | Yeni bir örneğini başlatır.`Size` belirtilen boyutlardan yapı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Yeni bir örneğini alır`Size` sahip olan yapı[`Width`](./width/) Ve[`Height`](./height/) değerler sıfıra ayarlandı. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Bunun dikey bileşenini alır veya ayarlar`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Bunun olup olmadığını gösteren bir değer alır.`Size` 0. genişliğe ve yüksekliğe sahip |
| [Width](../../aspose.psd/size/width/) { get; set; } | Bunun yatay bileşenini alır veya ayarlar`Size` . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Birinin genişliğini ve yüksekliğini ekler`Size` diğerinin genişliğine ve yüksekliğine yapı`Size`yapı. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Belirtileni dönüştürür[`SizeF`](../sizef/) bir yapı`Size` değerlerini yuvarlayarak yapı`Size` sonraki daha yüksek tamsayı değerlerine yapı. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Belirtileni dönüştürür[`SizeF`](../sizef/) bir yapı`Size` değerlerini yuvarlayarak yapı[`SizeF`](../sizef/) en yakın tamsayı değerlerine yapı. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Birinin genişliğini ve yüksekliğini çıkarır`Size` diğerinin genişliğinden ve yüksekliğinden yapı`Size`yapı. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Belirtileni dönüştürür[`SizeF`](../sizef/) bir yapı`Size` değerlerini keserek yapı[`SizeF`](../sizef/) sonraki alt tamsayı değerlerine yapı. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Belirtilen nesnenin bir nesne olup olmadığını test eder.`Size` bununla aynı boyutlara sahip`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Bunun için bir karma kod döndürür`Size`yapı. |
| override [ToString](../../aspose.psd/size/tostring/)() | Bunu temsil eden insanlar tarafından okunabilir bir dize oluşturur.`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | Birinin genişliğini ve yüksekliğini ekler`Size` diğerinin genişliğine ve yüksekliğine yapı`Size`yapı. |
| [operator ==](../../aspose.psd/size/op_equality/) | İki olup olmadığını test eder`Size` yapılar eşittir. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Belirtileni dönüştürür`Size` bir[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Belirtileni dönüştürür`Size` bir[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | İki olup olmadığını test eder`Size` yapılar farklıdır. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Birinin genişliğini ve yüksekliğini çıkarır`Size` diğerinin genişliğinden ve yüksekliğinden yapı`Size`yapı. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


