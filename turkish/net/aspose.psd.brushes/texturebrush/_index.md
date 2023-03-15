---
title: Class TextureBrush
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.TextureBrush sınıf. Her özellikTextureBrush sınıf birBrush bir şeklin içini doldurmak için bir görüntü kullanan nesne. Bu sınıf miras alınamaz.
type: docs
weight: 210
url: /tr/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Her özellik`TextureBrush` sınıf bir[`Brush`](../../aspose.psd/brush/) bir şeklin içini doldurmak için bir görüntü kullanan nesne. Bu sınıf miras alınamaz.

```csharp
public sealed class TextureBrush : TransformBrush
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Yeni bir örneğini başlatır.`TextureBrush` belirtilen image. kullanan sınıf |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Yeni bir örneğini başlatır.`TextureBrush` belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan sınıf. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Yeni bir örneğini başlatır.`TextureBrush` belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan sınıf. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Yeni bir örneğini başlatır.`TextureBrush` belirtilen görüntüyü ve sarma modunu kullanan sınıf. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Yeni bir örneğini başlatır.`TextureBrush` belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü niteliklerini kullanan sınıf. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Yeni bir örneğini başlatır.`TextureBrush` belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü niteliklerini kullanan sınıf. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Yeni bir örneğini başlatır.`TextureBrush`belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan sınıf. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Yeni bir örneğini başlatır.`TextureBrush`belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Şunu alır:[`Image`](../../aspose.psd/image/) bununla ilişkili nesne`TextureBrush` nesne. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Şunu alır:[`ImageAttributes`](./imageattributes/) bununla ilişkili`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Şunu alır:[`Rectangle`](../../aspose.psd/rectangle/) bununla ilişkili`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin herhangi bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüşüm matrisini ayarlamak veya , dönüşüm matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Bir kopya alır veya ayarlar[`Matrix`](../../aspose.psd/matrix/) bunun için yerel bir geometrik dönüşümü tanımlayan[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Alır veya ayarlar[`WrapMode`](../../aspose.psd/wrapmode/) bunun için sarma modunu gösteren numaralandırma[`TransformBrush`](../transformbrush/) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Geçerli olanın yeni bir derin klonunu oluşturur.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | [`Matrix`](../../aspose.psd/matrix/) bunun yerel geometrik dönüşümünü temsil eden[`LinearGradientBrush`](../lineargradientbrush/) belirtilen tarafından[`Matrix`](../../aspose.psd/matrix/) belirtilenin başına ekleyerek[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | [`Matrix`](../../aspose.psd/matrix/) bunun yerel geometrik dönüşümünü temsil eden[`LinearGradientBrush`](../lineargradientbrush/) belirtilen tarafından[`Matrix`](../../aspose.psd/matrix/) belirtilen sırada. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | sıfırlar[`Transform`](../transformbrush/transform/) kimlik için özellik. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem, dönüşü transform. 'nin başına ekler |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarda döndürür. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Yerel geometrik dönüşümü belirtilen miktarlarda ölçekler. Bu yöntem, ölçeklendirme matrisini transform. 'nin başına ekler. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarlarda ölçekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlara çevirir. Bu yöntem, çeviriyi transform. 'nin başına ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırayla belirtilen boyutlara çevirir. |

### Ayrıca bakınız

* class [TransformBrush](../transformbrush/)
* ad alanı [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* toplantı [Aspose.PSD](../../)


