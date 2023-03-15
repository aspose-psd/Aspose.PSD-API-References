---
title: Struct Rectangle
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Rectangle yapı. Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tam sayıdan oluşan bir kümeyi depolar.
type: docs
weight: 5340
url: /tr/net/aspose.psd/rectangle/
---
## Rectangle structure

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tam sayıdan oluşan bir kümeyi depolar.

```csharp
public struct Rectangle
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Yeni bir örneğini başlatır.`Rectangle` belirtilen konum ve boyuta sahip yapı. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Yeni bir örneğini başlatır.`Rectangle` belirtilen konum ve boyuta sahip yapı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Yeni bir örneğini alır`Rectangle` sahip olan yapı[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) Ve[`Height`](./height/) değerler sıfıra ayarlandı. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Toplamı olan y koordinatını alır veya ayarlar.[`Y`](./y/) Ve[`Height`](./height/) bunun özellik değerleri`Rectangle`yapı. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Bunun yüksekliğini alır veya ayarlar`Rectangle`yapı. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Bunun tüm sayısal özelliklerinin olup olmadığını gösteren bir değer alır.`Rectangle` sıfır. değerlerine sahip |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Bunun sol kenarının x koordinatını alır veya ayarlar`Rectangle`yapı. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Bunun sol üst köşesinin koordinatlarını alır veya ayarlar.`Rectangle`yapı. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Toplamı olan x koordinatını alır veya ayarlar.[`X`](./x/) Ve[`Width`](./width/) bunun özellik değerleri`Rectangle`yapı. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Bunun boyutunu alır veya ayarlar`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Bunun üst kenarının y koordinatını alır veya ayarlar`Rectangle`yapı. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Bunun genişliğini alır veya ayarlar`Rectangle`yapı. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Bunun sol üst köşesinin x koordinatını alır veya ayarlar`Rectangle`yapı. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Bunun sol üst köşesinin y koordinatını alır veya ayarlar`Rectangle`yapı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Belirtileni dönüştürür[`RectangleF`](../rectanglef/) bir yapı`Rectangle` yuvarlayarak yapı[`RectangleF`](../rectanglef/) değerleri sonraki daha yüksek tamsayı değerlerine. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | oluşturur`Rectangle` belirtilen kenar konumlarına sahip yapı. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Yeni bir tane oluşturur`Rectangle` belirtilen iki noktadan Oluşturulan iki dikey`Rectangle` geçene eşit olacak*point1* Ve*point2* . Bunlar tipik olarak zıt köşeler olacaktır. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Belirtilenin şişirilmiş bir kopyasını oluşturur ve döndürür`Rectangle`yapı. Kopya belirtilen miktarda şişirilir. Orijinal`Rectangle` yapı değiştirilmeden kalır. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Üçte birini döndürür`Rectangle` diğer iki kesişimi temsil eden yapı`Rectangle` yapılar. Kavşak yoksa boş`Rectangle` döndürülür. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Belirtileni dönüştürür[`RectangleF`](../rectanglef/) bir`Rectangle` yuvarlayarak[`RectangleF`](../rectanglef/) değerleri en yakın tam sayı değerlerine. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Belirtileni dönüştürür[`RectangleF`](../rectanglef/) bir`Rectangle` keserek[`RectangleF`](../rectanglef/) değerler. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Bir alır`Rectangle` ikisinin birleşimini içeren yapı`Rectangle` yapılar. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Belirtilen noktanın bunun içinde olup olmadığını belirler.`Rectangle`yapı. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | ile temsil edilen dikdörtgen bölgenin olup olmadığını belirler.*rect* tamamen bunun içinde yer alır`Rectangle`yapı. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Belirtilen noktanın bunun içinde olup olmadığını belirler.`Rectangle`yapı. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | olup olmadığını test eder*obj* bir`Rectangle`bununla aynı konum ve büyüklükteki yapı`Rectangle`yapı. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Bunun için hash kodunu döndürür`Rectangle`yapı. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Bunu şişirir`Rectangle`belirtilen miktarda. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Bunu şişirir`Rectangle`belirtilen miktarda. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Bunu değiştirir`Rectangle` kendisinin ve belirtilenin kesişimi ile`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bu dikdörtgenin şununla kesişip kesişmediğini belirler:*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Dikdörtgenin genişliğini ve yüksekliğini pozitif, sol sağdan az ve üst kısım alttan küçük yaparak normalleştirir. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Bunun özniteliklerini dönüştürür`Rectangle` okunabilir bir dizeye. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | İki olup olmadığını test eder`Rectangle` yapılar eşit konum ve boyuta sahiptir. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | İki olup olmadığını test eder`Rectangle` yapılar konum veya boyut bakımından farklılık gösterir. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


