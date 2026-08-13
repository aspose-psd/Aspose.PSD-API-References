---
title: "Yapı RectangleF"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.RectangleF yapısı. Bir dikdörtgenin konum ve boyutunu temsil eden dört kayan nokta sayısını saklar."
type: docs
weight: 5880
url: /tr/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan nokta sayısından oluşan bir küme depolar.

```csharp
public struct RectangleF
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | `RectangleF` yapısının belirtilen konum ve boyutla yeni bir örneğini başlatır. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | `RectangleF` yapısının belirtilen konum ve boyutla yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | `RectangleF` yapısının [`X`](./x/), [`Y`](./y/), [`Width`](./width/) ve [`Height`](./height/) değerleri sıfır olarak ayarlanmış yeni bir örneğini alır. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Bu `RectangleF` yapısının [`Y`](./y/) ve [`Height`](./height/) toplamı olan y-koordinatını alır veya ayarlar. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Bu `RectangleF` yapısının yüksekliğini alır veya ayarlar. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Bu `RectangleF`'nin [`Width`](./width/) veya [`Height`](./height/) özelliğinin değeri sıfır olup olmadığını gösteren bir değer alır. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Bu `RectangleF` yapısının sol kenarının x-koordinatını alır veya ayarlar. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Bu `RectangleF` yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Bu `RectangleF` yapısının [`X`](./x/) ve [`Width`](./width/) toplamı olan x-koordinatını alır veya ayarlar. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Bu `RectangleF`'nin boyutunu alır veya ayarlar. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Bu `RectangleF` yapısının üst kenarının y-koordinatını alır veya ayarlar. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Bu `RectangleF` yapısının genişliğini alır veya ayarlar. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Bu `RectangleF` yapısının sol üst köşesinin x-koordinatını alır veya ayarlar. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Bu `RectangleF` yapısının sol üst köşesinin y-koordinatını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Belirtilen konumlardaki sol üst ve sağ alt köşelerle bir `RectangleF` yapısı oluşturur. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Belirtilen iki noktadan yeni bir [`Rectangle`](../rectangle/) oluşturur. Oluşturulan [`Rectangle`](../rectangle/) nin iki köşesi verilen *point1* ve *point2* değerlerine eşit olur. Bunlar genellikle karşıt köşelerdir. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Belirtilen `RectangleF` yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | İki dikdörtgenin kesişimini temsil eden bir `RectangleF` yapısı döndürür. Kesişim yoksa boş bir `RectangleF` döndürülür. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Birleşim oluşturan iki dikdörtgeni de içerebilecek en küçük üçüncü dikdörtgeni oluşturur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Belirtilen noktanın bu `RectangleF` yapısı içinde olup olmadığını belirler. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | *rect* tarafından temsil edilen dikdörtgen bölgenin tamamen bu `RectangleF` yapısı içinde olup olmadığını belirler. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Belirtilen noktanın bu `RectangleF` yapısı içinde olup olmadığını belirler. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | *obj*'nin bu `RectangleF` ile aynı konuma ve boyuta sahip bir `RectangleF` olup olmadığını test eder. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Bu `RectangleF` yapısının hash kodunu alır. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Bu `RectangleF`'yi belirtilen miktarda şişirir. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Bu `RectangleF` yapısını belirtilen miktarda şişirir. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Bu `RectangleF` yapısını kendisi ile belirtilen `RectangleF` yapısının kesişimiyle değiştirir. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bu dikdörtgenin *rect* ile kesişip kesişmediğini belirler. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Dikdörtgeni genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | `RectangleF` nesnesinin özelliklerini insan tarafından okunabilir bir dizeye dönüştürür. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | / operatörünü uygular. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | İki `RectangleF` yapısının konum ve boyutunun eşit olup olmadığını test eder. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Belirtilen [`Rectangle`](../rectangle/) yapısını bir `RectangleF` yapısına dönüştürür. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | İki `RectangleF` yapısının konum veya boyut açısından farklı olup olmadığını test eder. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | * operatörünü uygular. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


