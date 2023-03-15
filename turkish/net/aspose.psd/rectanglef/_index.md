---
title: Struct RectangleF
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.RectangleF yapı. Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan noktalı sayı kümesini saklar.
type: docs
weight: 5350
url: /tr/net/aspose.psd/rectanglef/
---
## RectangleF structure

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan noktalı sayı kümesini saklar.

```csharp
public struct RectangleF
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Yeni bir örneğini başlatır.`RectangleF` belirtilen konum ve boyuta sahip yapı. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Yeni bir örneğini başlatır.`RectangleF` belirtilen konum ve boyuta sahip yapı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Yeni bir örneğini alır`RectangleF` sahip olan yapı[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) Ve[`Height`](./height/) değerler sıfıra ayarlandı. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Toplamı olan y koordinatını alır veya ayarlar.[`Y`](./y/) Ve[`Height`](./height/) bunun`RectangleF`yapı. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Bunun yüksekliğini alır veya ayarlar`RectangleF`yapı. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | olup olmadığını gösteren bir değer alır.[`Width`](./width/) veya[`Height`](./height/) bunun özelliği`RectangleF` sıfır değerine sahiptir. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Bunun sol kenarının x koordinatını alır veya ayarlar`RectangleF`yapı. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Bunun sol üst köşesinin koordinatlarını alır veya ayarlar.`RectangleF`yapı. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Toplamı olan x koordinatını alır veya ayarlar.[`X`](./x/) Ve[`Width`](./width/) bunun`RectangleF`yapı. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Bunun boyutunu alır veya ayarlar`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Bunun üst kenarının y koordinatını alır veya ayarlar`RectangleF`yapı. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Bunun genişliğini alır veya ayarlar`RectangleF`yapı. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Bunun sol üst köşesinin x koordinatını alır veya ayarlar`RectangleF`yapı. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Bunun sol üst köşesinin y koordinatını alır veya ayarlar`RectangleF`yapı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | oluşturur`RectangleF` belirtilen konumlarda sol üst köşe ve sağ alt köşeye sahip yapı. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Yeni bir tane oluşturur[`Rectangle`](../rectangle/) belirtilen iki noktadan Yaratılanın iki köşesi[`Rectangle`](../rectangle/) geçene eşit olacak*point1* Ve*point2* . Bunlar tipik olarak zıt köşeler olacaktır. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Belirtilenin şişirilmiş bir kopyasını oluşturur ve döndürür`RectangleF`yapı. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değiştirilmeden kalır. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | a döndürür`RectangleF` iki dikdörtgenin kesişimini temsil eden yapı. Kavşak yoksa ve boşsa`RectangleF` döndürülür. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Bir birleşim oluşturan iki dikdörtgenin ikisini de içerebilen mümkün olan en küçük üçüncü dikdörtgeni oluşturur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Belirtilen noktanın bunun içinde olup olmadığını belirler.`RectangleF`yapı. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | ile temsil edilen dikdörtgen bölgenin olup olmadığını belirler.*rect* tamamen bunun içinde yer alır`RectangleF`yapı. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Belirtilen noktanın bunun içinde olup olmadığını belirler.`RectangleF`yapı. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | olup olmadığını test eder*obj* bir`RectangleF` bununla aynı konum ve boyutta`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Bunun için hash kodunu alır`RectangleF`yapı. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Bunu şişirir`RectangleF`belirtilen miktarda. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Bunu şişirir`RectangleF` belirtilen miktara göre yapı. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Bunu değiştirir`RectangleF`kendisinin ve belirtilenin kesişim noktası olan yapı`RectangleF`yapı. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Bu dikdörtgenin şununla kesişip kesişmediğini belirler:*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Dikdörtgenin genişliğini ve yüksekliğini pozitif, sol sağdan az ve üst kısım alttan küçük yaparak normalleştirir. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Bunun özniteliklerini dönüştürür`RectangleF` okunabilir bir dizeye. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | /. operatörünü uygular |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | İki olup olmadığını test eder`RectangleF` yapılar eşit konum ve boyuta sahiptir. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Belirtileni dönüştürür[`Rectangle`](../rectangle/) bir yapı`RectangleF`yapı. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | İki olup olmadığını test eder`RectangleF` yapılar konum veya boyut bakımından farklılık gösterir. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | *. operatörünü uygular |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


