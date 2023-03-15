---
title: Class TransformBrush
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.TransformBrush sınıf. birBrush dönüşüm yetenekleriyle.
type: docs
weight: 220
url: /tr/net/aspose.psd.brushes/transformbrush/
---
## TransformBrush class

bir[`Brush`](../../aspose.psd/brush/) dönüşüm yetenekleriyle.

```csharp
public abstract class TransformBrush : Brush
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin herhangi bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüşüm matrisini ayarlamak veya , dönüşüm matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Bir kopya alır veya ayarlar[`Matrix`](../../aspose.psd/matrix/) bunun için yerel bir geometrik dönüşümü tanımlayan`TransformBrush` . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Alır veya ayarlar[`WrapMode`](../../aspose.psd/wrapmode/) bunun için sarma modunu gösteren numaralandırma`TransformBrush` . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Geçerli olanın yeni bir derin klonunu oluşturur.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | [`Matrix`](../../aspose.psd/matrix/) bunun yerel geometrik dönüşümünü temsil eden[`LinearGradientBrush`](../lineargradientbrush/) belirtilen tarafından[`Matrix`](../../aspose.psd/matrix/) belirtilenin başına ekleyerek[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | [`Matrix`](../../aspose.psd/matrix/) bunun yerel geometrik dönüşümünü temsil eden[`LinearGradientBrush`](../lineargradientbrush/) belirtilen tarafından[`Matrix`](../../aspose.psd/matrix/) belirtilen sırada. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | sıfırlar[`Transform`](./transform/) kimlik için özellik. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem, dönüşü transform. 'nin başına ekler |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarda döndürür. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen miktarlarda ölçekler. Bu yöntem, ölçeklendirme matrisini transform. 'nin başına ekler. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırada belirtilen miktarlarda ölçekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlara çevirir. Bu yöntem, çeviriyi transform. 'nin başına ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırayla belirtilen boyutlara çevirir. |

### Ayrıca bakınız

* class [Brush](../../aspose.psd/brush/)
* ad alanı [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* toplantı [Aspose.PSD](../../)


