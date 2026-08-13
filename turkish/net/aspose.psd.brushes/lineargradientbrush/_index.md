---
title: "LinearGradientBrush sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.LinearGradientBrush sınıfı. Bir Brush'ı lineer gradyan ile kapsüller. Bu sınıf kalıtılamaz."
type: docs
weight: 140
url: /tr/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

Bir [`Brush`](../../aspose.psd/brush/) öğesini lineer gradyan ile kapsüller. Bu sınıf kalıtılamaz.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | `LinearGradientBrush` sınıfının yeni bir örneğini varsayılan parametrelerle başlatır. Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutundadır. |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | `LinearGradientBrush` sınıfının yeni bir örneğini belirtilen noktalar ve renklerle başlatır. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | `LinearGradientBrush` sınıfının yeni bir örneğini belirtilen noktalar ve renklerle başlatır. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | `LinearGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına göre başlatır. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | `LinearGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına göre başlatır. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | `LinearGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına göre başlatır. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | `LinearGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına göre başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Degrade açısını alır veya ayarlar. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir [`Blend`](../../aspose.psd/blend/) alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Bitiş gradyan rengini alır veya ayarlar. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Bu [`LinearGradientBrushBase`](../lineargradientbrushbase/) için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | Çok renkli bir lineer degrade tanımlayan bir [`ColorBlend`](../../aspose.psd/colorblend/) alır veya ayarlar. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Bu [`LinearGradientBrushBase`](../lineargradientbrushbase/) ile dönüşümler sırasında [`Angle`](../lineargradientbrushbase/angle/) değiştirildiğini gösteren bir değeri alır veya ayarlar. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | Gradyanın başlangıç ve bitiş renklerini alır veya ayarlar. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Gradyanın başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bölgeyi alır veya ayarlar. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Başlangıç gradyan rengini alır veya ayarlar. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Bu [`TransformBrush`](../transformbrush/) için yerel geometrik dönüşümü tanımlayan bir kopya [`Matrix`](../../aspose.psd/matrix/) alır veya ayarlar. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Bu [`TransformBrush`](../transformbrush/) için sarmalama modunu gösteren bir [`WrapMode`](../../aspose.psd/wrapmode/) enum değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Mevcut [`Brush`](../../aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Bu `LinearGradientBrush`'ın yerel geometrik dönüşümünü temsil eden [`Matrix`](../../aspose.psd/matrix/) öğesini, belirtilen [`Matrix`](../../aspose.psd/matrix/) ile, belirtilen [`Matrix`](../../aspose.psd/matrix/) önüne ekleyerek çarpar. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Bu `LinearGradientBrush`'ın yerel geometrik dönüşümünü temsil eden [`Matrix`](../../aspose.psd/matrix/) öğesini, belirtilen [`Matrix`](../../aspose.psd/matrix/) ile belirtilen sırada çarpar. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](../transformbrush/transform/) özelliğini birim haline sıfırlar. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşümün önüne ekler. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Yerel geometrik dönüşümü belirtilen ölçeklerde büyütür. Bu yöntem ölçekleme matrisini dönüşümün önüne ekler. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen ölçeklerde, belirtilen sırada büyütür. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Merkez rengi ve her iki uçta tek bir renge doğru lineer bir düşüşle lineer bir degrade oluşturur. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Merkez rengi ve her iki uçta tek bir renge doğru lineer bir düşüşle lineer bir degrade oluşturur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Çan şeklinde bir eğriye dayalı bir degrade düşüşü oluşturur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Çan şeklinde bir eğriye dayalı bir degrade düşüşü oluşturur. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlarda kaydırır. Bu yöntem çevirimi dönüşümün önüne ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada kaydırır. |

### Ayrıca Bakınız

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


