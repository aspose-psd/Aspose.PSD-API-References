---
title: GraphicsPath.Warp
second_title: Aspose.PSD for .NET API Referansı
description: GraphicsPath yöntem. Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.GraphicsPath .
type: docs
weight: 180
url: /tr/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf/) dikdörtgenin tanımladığı bir paralelkenarı tanımlayan yapılar*srcRect*dönüştürülür. Dizi, üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder.*destPoints*. |

### Ayrıca bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* ad alanı [Aspose.PSD](../../graphicspath/)
* toplantı [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf/) dikdörtgenin tanımladığı bir paralelkenarı tanımlayan yapılar*srcRect*dönüştürülür. Dizi, üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder.*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) yola uygulanacak bir geometrik dönüşümü belirtir. |

### Ayrıca bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* ad alanı [Aspose.PSD](../../graphicspath/)
* toplantı [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf/) dikdörtgenin tanımladığı bir paralelkenarı tanımlayan yapılar*srcRect*dönüştürülür. Dizi, üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder.*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) yola uygulanacak bir geometrik dönüşümü belirtir. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) Bu çarpıtma işleminin perspektif mi yoksa çift doğrusal kip mi kullandığını belirten numaralandırma. |

### Ayrıca bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* ad alanı [Aspose.PSD](../../graphicspath/)
* toplantı [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Buna bir dikdörtgen ve bir paralelkenar tarafından tanımlanan bir çarpıtma dönüşümü uygular.[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destPoints | PointF[] | bir dizi[`PointF`](../../pointf/) dikdörtgenin tanımladığı bir paralelkenarı tanımlayan yapılar*srcRect*dönüştürülür. Dizi, üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ alt köşesi ilk üç nokta tarafından belirtilir. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eder.*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) yola uygulanacak bir geometrik dönüşümü belirtir. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) Bu çarpıtma işleminin perspektif mi yoksa çift doğrusal kip mi kullandığını belirten numaralandırma. |
| flatness | Single | Ortaya çıkan yolun ne kadar düz olduğunu belirten 0 ile 1 arasında bir değer. Daha fazla bilgi için bkz.[`Flatten`](../flatten/) yöntemler. |

### Ayrıca bakınız

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* ad alanı [Aspose.PSD](../../graphicspath/)
* toplantı [Aspose.PSD](../../../)


