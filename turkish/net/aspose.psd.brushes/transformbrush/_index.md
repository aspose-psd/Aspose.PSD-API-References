---
title: "Sınıf TransformBrush"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.TransformBrush sınıfı. Dönüştürme yeteneklerine sahip bir Brush"
type: docs
weight: 220
url: /tr/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

Dönüştürme yeteneklerine sahip bir [`Brush`](../../aspose.psd/brush/).

```csharp
public abstract class TransformBrush : Brush
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | `TransformBrush` için yerel geometrik dönüşümü tanımlayan bir kopya [`Matrix`](../../aspose.psd/matrix/) alır veya ayarlar. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | `TransformBrush` için sarma modunu belirten bir [`WrapMode`](../../aspose.psd/wrapmode/) enum değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Mevcut [`Brush`](../../aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Bu [`LinearGradientBrush`](../lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [`Matrix`](../../aspose.psd/matrix/) değerini, belirtilen [`Matrix`](../../aspose.psd/matrix/) ile, belirtilen [`Matrix`](../../aspose.psd/matrix/) önüne ekleyerek çarpar. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Bu [`LinearGradientBrush`](../lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [`Matrix`](../../aspose.psd/matrix/) değerini, belirtilen sırada belirtilen [`Matrix`](../../aspose.psd/matrix/) ile çarpar. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](./transform/) özelliğini birim (identity) haline sıfırlar. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşümün önüne ekler. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen ölçeklerde büyütür. Bu yöntem ölçekleme matrisini dönüşümün önüne ekler. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen ölçeklerde, belirtilen sırada büyütür. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlarda kaydırır. Bu yöntem çevirimi dönüşümün önüne ekler. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada kaydırır. |

### Ayrıca Bakınız

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


