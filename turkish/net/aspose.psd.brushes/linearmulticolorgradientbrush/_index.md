---
title: "Sınıf LinearMulticolorGradientBrush"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.LinearMulticolorGradientBrush sınıfı. Birden çok renk ve uygun konumlarla tanımlanan lineer degradeye sahip bir Fırçayı temsil eder. Bu sınıf miras alınamaz"
type: docs
weight: 160
url: /tr/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

Birden çok renk ve uygun konumlarla tanımlanan lineer degradeye sahip bir [`Brush`](../../aspose.psd/brush/) temsil eder. Bu sınıf miras alınamaz.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini varsayılan parametrelerle başlatır. Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda (1,1) boyutundadır. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini belirtilen noktalarla başlatır. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini belirtilen noktalarla başlatır. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve yön açısına dayanarak başlatır. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve yön açısına dayanarak başlatır. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve yön açısına dayanarak başlatır. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve yön açısına dayanarak başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Degrade açısını alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Bu [`LinearGradientBrushBase`](../lineargradientbrushbase/) için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Çok renkli bir lineer degrade tanımlayan bir [`ColorBlend`](../../aspose.psd/colorblend/) alır veya ayarlar. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Bu [`LinearGradientBrushBase`](../lineargradientbrushbase/) ile dönüşümler sırasında [`Angle`](../lineargradientbrushbase/angle/) değiştirildiğini gösteren bir değeri alır veya ayarlar. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Gradyanın başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bölgeyi alır veya ayarlar. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Bu [`TransformBrush`](../transformbrush/) için yerel geometrik dönüşümü tanımlayan bir kopya [`Matrix`](../../aspose.psd/matrix/) alır veya ayarlar. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Bu [`TransformBrush`](../transformbrush/) için sarmalama modunu gösteren bir [`WrapMode`](../../aspose.psd/wrapmode/) enum değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Mevcut [`Brush`](../../aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Bu [`LinearGradientBrush`](../lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [`Matrix`](../../aspose.psd/matrix/) değerini, belirtilen [`Matrix`](../../aspose.psd/matrix/) ile, belirtilen [`Matrix`](../../aspose.psd/matrix/) önüne ekleyerek çarpar. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Bu [`LinearGradientBrush`](../lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [`Matrix`](../../aspose.psd/matrix/) değerini, belirtilen sırada belirtilen [`Matrix`](../../aspose.psd/matrix/) ile çarpar. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](../transformbrush/transform/) özelliğini birim haline sıfırlar. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşümün önüne ekler. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Yerel geometrik dönüşümü belirtilen ölçeklerde büyütür. Bu yöntem ölçekleme matrisini dönüşümün önüne ekler. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen ölçeklerde, belirtilen sırada büyütür. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlarda kaydırır. Bu yöntem çevirimi dönüşümün önüne ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada kaydırır. |

### Ayrıca Bakınız

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


