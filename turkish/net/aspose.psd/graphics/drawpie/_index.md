---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics metodu. Bir RectangleF yapısı ve iki radyal çizgiyle tanımlanan bir elips tarafından tanımlanan bir pasta şekli çizer."
type: docs
weight: 290
url: /tr/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Bir [`RectangleF`](../../rectanglef/) yapısı ve iki radyal çizgiyle tanımlanan bir elips tarafından tanımlanan bir pasta şekli çizer.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) pastanın rengini, genişliğini ve stilini belirler. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) yapısı, pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |
| startAngle | Single | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Single | *startAngle* parametresinden pasta şeklinin ikinci kenarına doğru saat yönünde derece cinsinden ölçülen açı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) pastanın rengini, genişliğini ve stilini belirler. |
| x | Single | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Single | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Single | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Single | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Single | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Single | *startAngle* parametresinden pasta şeklinin ikinci kenarına doğru saat yönünde derece cinsinden ölçülen açı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Bir [`Rectangle`](../../rectangle/) yapısı ve iki radyal çizgiyle tanımlanan bir elips tarafından tanımlanan bir pasta şekli çizer.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) pastanın rengini, genişliğini ve stilini belirler. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) yapısı, pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |
| startAngle | Single | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Single | *startAngle* parametresinden pasta şeklinin ikinci kenarına doğru saat yönünde derece cinsinden ölçülen açı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) pastanın rengini, genişliğini ve stilini belirler. |
| x | Int32 | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Int32 | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Int32 | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Int32 | Pastanın geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Int32 | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | Int32 | *startAngle* parametresinden pasta şeklinin ikinci kenarına doğru saat yönünde derece cinsinden ölçülen açı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


