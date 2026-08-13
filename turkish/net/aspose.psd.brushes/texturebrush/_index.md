---
title: "Sınıf TextureBrush"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.TextureBrush sınıfı. TextureBrush sınıfının her özelliği, bir şeklin içini doldurmak için bir görüntü kullanan bir Brush nesnesidir. Bu sınıf kalıtılamaz"
type: docs
weight: 210
url: /tr/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

`TextureBrush` sınıfının her özelliği, bir şeklin içini doldurmak için bir görüntü kullanan bir [`Brush`](../../aspose.psd/brush/) nesnesidir. Bu sınıf kalıtılamaz.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Belirtilen görüntüyü kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Belirtilen görüntüyü ve sarma modunu kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan `TextureBrush` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | `TextureBrush` nesnesiyle ilişkili [`Image`](../../aspose.psd/image/) nesnesini alır. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | `TextureBrush` ile ilişkili [`ImageAttributes`](./imageattributes/) nesnesini alır. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | `TextureBrush` ile ilişkili [`Rectangle`](../../aspose.psd/rectangle/) nesnesini alır. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


