---
title: "Sınıf PathGradientBrush"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.PathGradientBrush sınıfı. Gradient içeren bir Brush nesnesini kapsüller. Bu sınıf miras alınamaz."
type: docs
weight: 170
url: /tr/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

Bir gradyan içeren bir [`Brush`](../../aspose.psd/brush/) nesnesini kapsüller. Bu sınıf kalıtılamaz.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Belirtilen yol ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Belirtilen noktalar ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Belirtilen noktalar ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Belirtilen noktalar ve sarma modu ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Belirtilen noktalar ve sarma modu ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir [`Blend`](../../aspose.psd/blend/) alır veya ayarlar. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Yol gradientinin merkezindeki rengi alır veya ayarlar. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Gradyan düşüşü için odak noktasını alır veya ayarlar. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | Çok renkli bir lineer degrade tanımlayan bir [`ColorBlend`](../../aspose.psd/colorblend/) alır veya ayarlar. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | `PathGradientBrush`'ın doldurduğu yoldaki noktalara karşılık gelen renk dizisini alır veya ayarlar. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Merkez rengi ve bir çevre rengine doğru lineer bir düşüşle bir gradient oluşturur. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Merkez rengi ve her bir çevre rengine doğru lineer bir düşüşle bir gradient oluşturur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradient fırça oluşturur. Bir renkten diğerine geçiş çan şeklinde bir eğriye dayanır. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradient fırça oluşturur. Bir renkten diğerine geçiş çan şeklinde bir eğriye dayanır. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlarda kaydırır. Bu yöntem çevirimi dönüşümün önüne ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada kaydırır. |

## Açıklamalar

Merkez rengi varsayılan olarak beyazdır. Kullanıcı bu değeri daha sonra istediği zaman değiştirebilir.

Çevre renkleri dizisi varsayılan olarak beyaz renk içeren tek bir öğe ile başlatılır. Çevre renkleri daha sonra değiştirilebilir, ancak çevre renklerini ayarlarken en az bir öğe gereklidir.

Başlatmasıyla ilgili daha fazla ayrıntı için [`Blend`](./blend/) bölümüne bakın.

### Ayrıca Bakınız

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


