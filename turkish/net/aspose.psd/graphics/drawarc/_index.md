---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Bir çift koordinat, genişlik ve yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer."
type: docs
weight: 170
url: /tr/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yayının rengini, genişliğini ve stilini belirler. |
| x | Single | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Single | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Single | Elipsi tanımlayan dikdörtgenin genişliği. |
| height | Single | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| startAngle | Single | Yay başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | Single | Yayın bitiş noktasına *startAngle* parametresinden saat yönünde ölçülen açı (derece). |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

[`RectangleF`](../../rectanglef/) yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yayının rengini, genişliğini ve stilini belirler. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) elipsin sınırlarını tanımlayan yapı. |
| startAngle | Single | Yay başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | Single | Yayın bitiş noktasına *startAngle* parametresinden saat yönünde ölçülen açı (derece). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yayının rengini, genişliğini ve stilini belirler. |
| x | Int32 | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | Int32 | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | Int32 | Elipsi tanımlayan dikdörtgenin genişliği. |
| height | Int32 | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| startAngle | Int32 | Yay başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | Int32 | Yayın bitiş noktasına *startAngle* parametresinden saat yönünde ölçülen açı (derece). |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Bir [`Rectangle`](../../rectangle/) yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yayının rengini, genişliğini ve stilini belirler. |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) elipsin sınırlarını tanımlayan yapı. |
| startAngle | Single | Yay başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | Single | Yayın bitiş noktasına *startAngle* parametresinden saat yönünde ölçülen açı (derece). |

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


