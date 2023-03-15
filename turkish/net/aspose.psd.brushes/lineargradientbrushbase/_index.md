---
title: Class LinearGradientBrushBase
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.LinearGradientBrushBase sınıf. bir temsil ederBrush gradyan yetenekleri ve uygun özelliklerle.
type: docs
weight: 150
url: /tr/net/aspose.psd.brushes/lineargradientbrushbase/
---
## LinearGradientBrushBase class

bir temsil eder[`Brush`](../../aspose.psd/brush/) gradyan yetenekleri ve uygun özelliklerle.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Gradyan açısını alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Bunun için gama düzeltmesinin etkinleştirilip etkinleştirilmediğini gösteren bir değer alır veya ayarlar`LinearGradientBrushBase` . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | olup olmadığını gösteren bir değer alır veya ayarlar.[`Angle`](./angle/) bununla dönüşümler sırasında değiştirilir`LinearGradientBrushBase` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin herhangi bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüşüm matrisini ayarlamak veya , dönüşüm matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Degradenin başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölge alır veya ayarlar. |
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


