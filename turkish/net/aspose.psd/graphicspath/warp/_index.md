---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD for .NET API Referansı"
description: "GraphicsPath yöntemi. Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu GraphicsPath'e uygular."
type: docs
weight: 180
url: /tr/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu [`GraphicsPath`](../) üzerine uygular.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | PointF[] | Bir dizi [`PointF`](../../pointf/) yapısı, *srcRect* tarafından tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | RectangleF | Bir [`RectangleF`](../../rectanglef/) nesnesi, *destPoints* tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder. |

### Ayrıca Bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu [`GraphicsPath`](../) üzerine uygular.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | PointF[] | Bir dizi [`PointF`](../../pointf/) yapısı, *srcRect* tarafından tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | RectangleF | Bir [`RectangleF`](../../rectanglef/) nesnesi, *destPoints* tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder. |
| matrix | Matrix | Bir [`Matrix`](../../matrix/) yapısı, yola uygulanacak geometrik dönüşümü belirtir. |

### Ayrıca Bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu [`GraphicsPath`](../) üzerine uygular.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | PointF[] | Bir dizi [`PointF`](../../pointf/) yapısı, *srcRect* tarafından tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | RectangleF | Bir [`RectangleF`](../../rectanglef/) nesnesi, *destPoints* tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder. |
| matrix | Matrix | Bir [`Matrix`](../../matrix/) yapısı, yola uygulanacak geometrik dönüşümü belirtir. |
| warpMode | WarpMode | Bu eğme işleminin perspektif mi yoksa ikili (bilinear) modda mı olduğunu belirten bir [`WarpMode`](../../warpmode/) sayımı. |

### Ayrıca Bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Bir dikdörtgen ve paralelkenar tarafından tanımlanan bir bükülme dönüşümünü bu [`GraphicsPath`](../) üzerine uygular.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | PointF[] | Bir dizi [`PointF`](../../pointf/) yapısı, *srcRect* tarafından tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç ya da dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | RectangleF | Bir [`RectangleF`](../../rectanglef/) nesnesi, *destPoints* tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder. |
| matrix | Matrix | Bir [`Matrix`](../../matrix/) yapısı, yola uygulanacak geometrik dönüşümü belirtir. |
| warpMode | WarpMode | Bu eğme işleminin perspektif mi yoksa ikili (bilinear) modda mı olduğunu belirten bir [`WarpMode`](../../warpmode/) sayımı. |
| flatness | Single | 0 ile 1 arasında bir değer, ortaya çıkan yolun ne kadar düz olduğunu belirtir. Daha fazla bilgi için [`Flatten`](../flatten/) yöntemlerine bakın. |

### Ayrıca Bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


