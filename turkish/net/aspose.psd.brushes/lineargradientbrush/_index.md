---
title: Class LinearGradientBrush
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.LinearGradientBrush sınıf. KapsüllerBrush doğrusal bir gradyan ile. Bu sınıf miras alınamaz.
type: docs
weight: 140
url: /tr/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Kapsüller[`Brush`](../../aspose.psd/brush/) doğrusal bir gradyan ile. Bu sınıf miras alınamaz.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Yeni bir örneğini başlatır.`LinearGradientBrush` varsayılan parametrelerle sınıf. Başlangıç rengi siyah, bitiş rengi beyaz, açı 45 derece ve dikdörtgen (0,0) konumunda (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Yeni bir örneğini başlatır.`LinearGradientBrush` belirtilen noktalara ve renklere sahip sınıf. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Yeni bir örneğini başlatır.`LinearGradientBrush` belirtilen noktalara ve renklere sahip sınıf. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Yeni bir örneğini başlatır.`LinearGradientBrush` bir dikdörtgene, başlangıç ve bitiş renklerine ve bir oryantasyon açısına dayalı sınıf. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Yeni bir örneğini başlatır.`LinearGradientBrush` bir dikdörtgene, başlangıç ve bitiş renklerine ve bir oryantasyon açısına dayalı sınıf. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Yeni bir örneğini başlatır.`LinearGradientBrush` bir dikdörtgene, başlangıç ve bitiş renklerine ve bir oryantasyon açısına dayalı sınıf. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Yeni bir örneğini başlatır.`LinearGradientBrush` bir dikdörtgene, başlangıç ve bitiş renklerine ve bir oryantasyon açısına dayalı sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Gradyan açısını alır veya ayarlar. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Alır veya ayarlar[`Blend`](../../aspose.psd/blend/) gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirtir. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Bitiş degrade rengini alır veya ayarlar. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Bunun için gama düzeltmesinin etkinleştirilip etkinleştirilmediğini gösteren bir değer alır veya ayarlar[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | olup olmadığını gösteren bir değer alır veya ayarlar.[`Angle`](../lineargradientbrushbase/angle/) bununla dönüşümler sırasında değiştirilir[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin herhangi bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüşüm matrisini ayarlamak veya , dönüşüm matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Degradenin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölge alır veya ayarlar. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Başlangıç degrade rengini alır veya ayarlar. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Bir kopya alır veya ayarlar[`Matrix`](../../aspose.psd/matrix/) bunun için yerel bir geometrik dönüşümü tanımlayan[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Alır veya ayarlar[`WrapMode`](../../aspose.psd/wrapmode/) bunun için sarma modunu gösteren numaralandırma[`TransformBrush`](../transformbrush/) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Geçerli olanın yeni bir derin klonunu oluşturur.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | [`Matrix`](../../aspose.psd/matrix/) bunun yerel geometrik dönüşümünü temsil eden`LinearGradientBrush` belirtilen tarafından[`Matrix`](../../aspose.psd/matrix/) belirtilenin başına ekleyerek[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | [`Matrix`](../../aspose.psd/matrix/) bunun yerel geometrik dönüşümünü temsil eden`LinearGradientBrush` belirtilen tarafından[`Matrix`](../../aspose.psd/matrix/) belirtilen sırada. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | sıfırlar[`Transform`](../transformbrush/transform/) kimlik için özellik. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem, dönüşü transform. 'nin başına ekler |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarda döndürür. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Yerel geometrik dönüşümü belirtilen miktarlarda ölçekler. Bu yöntem, ölçeklendirme matrisini transform. 'nin başına ekler. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarlarda ölçekler. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Bir merkez rengi ve her iki uçta da tek bir renge doğru doğrusal bir sapma ile doğrusal bir gradyan oluşturur. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Bir merkez rengi ve her iki uçta da tek bir renge doğru doğrusal bir sapma ile doğrusal bir gradyan oluşturur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Çan şeklindeki bir eğriye dayalı olarak bir degrade düşüşü oluşturur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Çan şeklindeki bir eğriye dayalı olarak bir degrade düşüşü oluşturur. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlara çevirir. Bu yöntem, çeviriyi transform. 'nin başına ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırayla belirtilen boyutlara çevirir. |

### Ayrıca bakınız

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* ad alanı [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* toplantı [Aspose.PSD](../../)


