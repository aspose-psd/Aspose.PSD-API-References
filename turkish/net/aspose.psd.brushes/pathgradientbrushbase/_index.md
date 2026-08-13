---
title: "Sınıf PathGradientBrushBase"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.PathGradientBrushBase sınıfı. Temel yol gradyanı işlevselliğine sahip bir Brush'ı temsil eder."
type: docs
weight: 180
url: /tr/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

Temel yol gradyanı işlevselliğine sahip bir [`Brush`](../../aspose.psd/brush/) temsil eder.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Gradyan düşüşü için odak noktasını alır veya ayarlar. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
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

## Açıklamalar

`PathGradientBrushBase` sınıfını oluştururken en az 2 nokta ile başlatılması gerektiğini unutmayın. Oluşturulan iç yol her zaman kapalı bir şekil olur, son nokta ilk noktaya bağlanır. Bu şekil bu `PathGradientBrushBase` ile doldurulur. GDI+ uygulaması, boş diziler veya aynı koordinatlara sahip nokta kümesi geçirildiğinde OutOfMemoryException hatası fırlatır. `PathGradientBrushBase`, nokta dizisi 2'den az nokta içerdiğinde bir istisna fırlatır; kabul edilemez nokta dizisi durumunda OutOfMemoryException yerine ArgumentException fırlatılır. Merkez noktası, varsayılan olarak verilen noktaların kütle merkezi olarak hesaplanır. Kullanıcı bu noktayı daha sonra değiştirebilir. Odak ölçeği varsayılan olarak boş bir nokta (0.0, 0.0) dir.

### Ayrıca Bakınız

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


