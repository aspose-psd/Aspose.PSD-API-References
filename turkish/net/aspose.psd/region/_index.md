---
title: "Region sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Region sınıfı. Dikdörtgenler ve yollarla oluşan bir grafik şeklinin iç kısmını tanımlar. Bu sınıf kalıtılamaz."
type: docs
weight: 5890
url: /tr/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Dikdörtgenler ve yollarla oluşturulmuş bir grafik şeklinin iç kısmını tanımlar. Bu sınıf miras alınamaz.

```csharp
public sealed class Region
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Region](region/#constructor)() | Yeni bir `Region` başlatır. |
| [Region](region/#constructor_1)(GraphicsPath) | Belirtilen [`GraphicsPath`](../graphicspath/) ile yeni bir `Region` başlatır. |
| [Region](region/#constructor_2)(Rectangle) | Belirtilen [`Rectangle`](../rectangle/) yapısından yeni bir `Region` başlatır. |
| [Region](region/#constructor_3)(RectangleF) | Belirtilen [`RectangleF`](../rectanglef/) yapısından yeni bir `Region` başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Bu `Region`'u, belirtilen [`GraphicsPath`](../graphicspath/) öğesinin bu `Region` ile kesişmeyen kısmını içerecek şekilde günceller. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Bu `Region`'u, belirtilen [`Rectangle`](../rectangle/) yapısının bu `Region` ile kesişmeyen kısmını içerecek şekilde günceller. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Bu `Region`'u, belirtilen [`RectangleF`](../rectanglef/) yapısının bu `Region` ile kesişmeyen kısmını içerecek şekilde günceller. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Bu `Region`'u, belirtilen `Region`'in bu `Region` ile kesişmeyen kısmını içerecek şekilde günceller. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Bu `Region`'ın tam bir derin kopyasını oluşturur. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Nesnelerin eşit olup olmadığını kontrol eder. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Belirtilen `Region`'ın, belirtilen çizim yüzeyinde bu `Region` ile aynı olup olmadığını test eder. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Bu `Region`'u, iç kısmının yalnızca belirtilen [`GraphicsPath`](../graphicspath/) ile kesişmeyen kısmını içerecek şekilde günceller. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Bu `Region`'u, iç kısmının yalnızca belirtilen [`Rectangle`](../rectangle/) yapısı ile kesişmeyen kısmını içerecek şekilde günceller. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Bu `Region`'u, iç kısmının yalnızca belirtilen [`RectangleF`](../rectanglef/) yapısı ile kesişmeyen kısmını içerecek şekilde günceller. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Bu `Region`'u, iç kısmının yalnızca belirtilen `Region` ile kesişmeyen kısmını içerecek şekilde günceller. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Geçerli nesnenin karma kodunu al. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Bu `Region`'u, kendisi ile belirtilen [`GraphicsPath`](../graphicspath/) kesişimi olacak şekilde günceller. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Bu `Region`'u, kendisi ile belirtilen [`Rectangle`](../rectangle/) yapısının kesişimi olacak şekilde günceller. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Bu `Region`'u, kendisi ile belirtilen [`RectangleF`](../rectanglef/) yapısının kesişimi olacak şekilde günceller. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Bu `Region`'u, kendisi ile belirtilen `Region` kesişimi olacak şekilde günceller. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Bu `Region`'ın belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Bu `Region`'ın belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Belirtilen [`Point`](../point/) yapısının bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Belirtilen [`PointF`](../pointf/) yapısının bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Belirtilen [`Rectangle`](../rectangle/) yapısının herhangi bir kısmının bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Belirtilen [`RectangleF`](../rectanglef/) yapısının herhangi bir kısmının bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Belirtilen noktanın bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Belirtilen [`Point`](../point/) yapısının, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Belirtilen [`PointF`](../pointf/) yapısının, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Belirtilen [`Rectangle`](../rectangle/) yapısının, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde herhangi bir kısmının bulunup bulunmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Belirtilen [`RectangleF`](../rectanglef/) yapısının herhangi bir kısmının, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Belirtilen noktanın, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Belirtilen noktanın, belirtilen [`Graphics`](../graphics/) nesnesi kullanılarak çizildiğinde bu `Region` nesnesi içinde olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Belirtilen dikdörtgenin herhangi bir kısmının bu `Region` içinde olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Belirtilen dikdörtgenin herhangi bir kısmının bu `Region` içinde olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Belirtilen dikdörtgenin herhangi bir kısmının, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde olup olmadığını test eder. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Belirtilen dikdörtgenin herhangi bir kısmının, belirtilen [`Graphics`](../graphics/) kullanılarak çizildiğinde bu `Region` içinde olup olmadığını test eder. |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Bu `Region`'ı boş bir iç bölgeye başlatır. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Bu `Region` nesnesini sonsuz bir iç bölgeye başlatır. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Bu `Region`'ı belirtilen [`Matrix`](../matrix/) ile dönüştürür. |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Bu `Region`'ın koordinatlarını belirtilen miktarda kaydırır. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Bu `Region`'ın koordinatlarını belirtilen miktarda kaydırır. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Bu `Region`'ı kendisi ile belirtilen [`GraphicsPath`](../graphicspath/) birleşimine günceller. |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Bu `Region`'ı kendisi ile belirtilen [`Rectangle`](../rectangle/) yapısının birleşimine günceller. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Bu `Region`'ı kendisi ile belirtilen [`RectangleF`](../rectanglef/) yapısının birleşimine günceller. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Bu `Region`'ı kendisi ile belirtilen `Region` birleşimine günceller. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Bu `Region`'ı, kendisi ile belirtilen [`GraphicsPath`](../graphicspath/) kesişiminin çıkarılmasıyla elde edilen birleşime günceller. |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Bu `Region`'ı, kendisi ile belirtilen [`Rectangle`](../rectangle/) yapısının kesişiminin çıkarılmasıyla elde edilen birleşime günceller. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Bu `Region`'ı, kendisi ile belirtilen [`RectangleF`](../rectanglef/) yapısının kesişiminin çıkarılmasıyla elde edilen birleşime günceller. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Bu `Region`'ı, kendisi ile belirtilen `Region` kesişiminin çıkarılmasıyla elde edilen birleşime günceller. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


