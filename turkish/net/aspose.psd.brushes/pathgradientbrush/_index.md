---
title: Class PathGradientBrush
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.PathGradientBrush sınıf. KapsüllerBrush gradyanlı nesne. Bu sınıf miras alınamaz.
type: docs
weight: 170
url: /tr/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

Kapsüller[`Brush`](../../aspose.psd/brush/) gradyanlı nesne. Bu sınıf miras alınamaz.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Yeni bir örneğini başlatır.`PathGradientBrush` belirtilen yola sahip sınıf. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Yeni bir örneğini başlatır.`PathGradientBrush` belirtilen noktalara sahip sınıf. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Yeni bir örneğini başlatır.`PathGradientBrush` belirtilen noktalara sahip sınıf. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Yeni bir örneğini başlatır.`PathGradientBrush` belirtilen noktalar ve sarma modu ile sınıf. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Yeni bir örneğini başlatır.`PathGradientBrush` belirtilen noktalar ve sarma modu ile sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Alır veya ayarlar[`Blend`](../../aspose.psd/blend/) gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirtir. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Yol gradyanının ortasındaki rengi alır veya ayarlar. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Degrade düşüşü için odak noktasını alır veya ayarlar. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin herhangi bir şekilde değiştirilip değiştirilmediğini gösteren bir değer alır. Örneğin, dönüşüm matrisini ayarlamak veya , dönüşüm matrisini değiştiren yöntemlerden herhangi birini çağırmak. Özellik, GDI+. ile geriye dönük uyumluluk için sunulmuştur |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Bu yoldaki noktalara karşılık gelen bir renk dizisini alır veya ayarlar.`PathGradientBrush` doldurur. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Bir merkez rengi ve onu çevreleyen bir renge doğrusal bir sapma ile bir degrade oluşturur. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Merkez rengi olan bir degrade ve çevresindeki her renge doğrusal bir düşüş oluşturur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklindeki bir eğriye dayalıdır. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklindeki bir eğriye dayalıdır. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlara çevirir. Bu yöntem, çeviriyi transform. 'nin başına ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Yerel geometrik dönüşümü, belirtilen sırayla belirtilen boyutlara çevirir. |

### Notlar

Merkez rengi varsayılan olarak beyazdır. Bir kullanıcı bu değeri daha sonra istediği zaman değiştirebilir.

Çevreleyen renkler dizisi, varsayılan olarak beyaz renk içeren tek bir öğe tarafından başlatılır. Çevre renkleri daha sonra değiştirilebilir, ancak çevre renkleri ayarlanırken en az bir öğe gereklidir.

Bkz.[`Blend`](./blend/) başlatılması hakkında daha fazla ayrıntı için.

### Ayrıca bakınız

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* ad alanı [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* toplantı [Aspose.PSD](../../)


