---
title: "Yapı Rectangle"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Rectangle yapısı. Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tam sayı seti saklar."
type: docs
weight: 5870
url: /tr/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tamsayı setini depolar.

```csharp
public struct Rectangle
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Belirtilen konum ve boyutla `Rectangle` yapısının yeni bir örneğini başlatır. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Belirtilen konum ve boyutla `Rectangle` yapısının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Sıfır olarak ayarlanmış [`X`](./x/), [`Y`](./y/), [`Width`](./width/) ve [`Height`](./height/) değerlerine sahip `Rectangle` yapısının yeni bir örneğini alır. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Bu `Rectangle` yapısının [`Y`](./y/) ve [`Height`](./height/) özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Bu `Rectangle` yapısının yüksekliğini alır veya ayarlar. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Bu `Rectangle` nesnesinin tüm sayısal özelliklerinin sıfır değerine sahip olup olmadığını gösteren bir değeri alır. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Bu `Rectangle` yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Bu `Rectangle` yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Bu `Rectangle` yapısının [`X`](./x/) ve [`Width`](./width/) özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Bu `Rectangle` nesnesinin boyutunu alır veya ayarlar. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Bu `Rectangle` yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Bu `Rectangle` yapısının genişliğini alır veya ayarlar. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Bu `Rectangle` yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Bu `Rectangle` yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Belirtilen [`RectangleF`](../rectanglef/) yapısını, [`RectangleF`](../rectanglef/) değerlerini bir sonraki üst tam sayıya yuvarlayarak bir `Rectangle` yapısına dönüştürür. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Belirtilen kenar konumlarıyla bir `Rectangle` yapısı oluşturur. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Belirtilen iki noktadan yeni bir `Rectangle` oluşturur. Oluşturulan `Rectangle`'ın iki kenarı, verilen *point1* ve *point2* değerlerine eşit olur. Bunlar genellikle karşıt köşeler olur. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Belirtilen `Rectangle` yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal `Rectangle` yapısı değişmeden kalır. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | İki diğer `Rectangle` yapısının kesişimini temsil eden üçüncü bir `Rectangle` yapısı döndürür. Kesişme yoksa, boş bir `Rectangle` döndürülür. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Belirtilen [`RectangleF`](../rectanglef/) değerlerini en yakın tam sayıya yuvarlayarak bir `Rectangle`'a dönüştürür. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Belirtilen [`RectangleF`](../rectanglef/) değerlerini kırparak bir `Rectangle`'a dönüştürür. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | İki `Rectangle` yapısının birleşimini içeren bir `Rectangle` yapısı alır. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Belirtilen noktanın bu `Rectangle` yapısı içinde olup olmadığını belirler. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | *rect* tarafından temsil edilen dikdörtgen bölgenin tamamen bu `Rectangle` yapısı içinde olup olmadığını belirler. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Belirtilen noktanın bu `Rectangle` yapısı içinde olup olmadığını belirler. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | *obj*'nin bu `Rectangle` yapısı ile aynı konuma ve boyuta sahip bir `Rectangle` yapısı olup olmadığını test eder. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Bu `Rectangle` yapısının hash kodunu döndürür. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Bu `Rectangle`'ı belirtilen miktarda şişirir. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Bu `Rectangle`'ı belirtilen miktarda şişirir. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Bu `Rectangle`'ı, kendisi ile belirtilen `Rectangle`'ın kesişimiyle değiştirir. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Bu dikdörtgenin *rect* ile kesişip kesişmediğini belirler. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Dikdörtgeni genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Bu `Rectangle`'ın özelliklerini insan tarafından okunabilir bir dizeye dönüştürür. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | İki `Rectangle` yapısının aynı konuma ve boyuta sahip olup olmadığını test eder. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | İki `Rectangle` yapısının konum veya boyut açısından farklı olup olmadığını test eder. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


