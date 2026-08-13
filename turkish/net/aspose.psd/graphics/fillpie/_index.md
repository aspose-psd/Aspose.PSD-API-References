---
title: "Graphics.FillPie"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Bir RectangleF yapısı ve iki radyal çizgi tarafından tanımlanan bir elips ile belirlenen bir dilim bölümünün içini doldurur."
type: docs
weight: 380
url: /tr/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Bir [`RectangleF`](../../rectanglef/) yapısı ve iki radyal çizgi tarafından tanımlanan bir elips ile belirlenen bir dilim bölümünün içini doldurur.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| startAngle | Single | Dilim bölümünün ilk kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweepAngle | Single | *startAngle* parametresinden dilim bölümünün ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Bir [`RectangleF`](../../rectanglef/) yapısı ve iki radyal çizgi tarafından tanımlanan bir elips ile belirlenen bir dilim bölümünün içini doldurur.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| startAngle | Single | Dilim bölümünün ilk kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweepAngle | Single | *startAngle* parametresinden dilim bölümünün ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta diliminin içini doldurur.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| x | Single | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Single | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Single | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Single | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Single | Dilim bölümünün ilk kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweepAngle | Single | *startAngle* parametresinden dilim bölümünün ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgi ile belirtilen bir elips tarafından tanımlanan bir pasta diliminin içini doldurur.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| x | Int32 | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Int32 | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Int32 | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | Int32 | Dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | Int32 | Dilim bölümünün ilk kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweepAngle | Int32 | *startAngle* parametresinden dilim bölümünün ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


