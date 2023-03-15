---
title: Class PathMulticolorGradientBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.PathMulticolorGradientBrush kelas. Merangkum aBrush objek dengan gradien. Kelas ini tidak dapat diwariskan.
type: docs
weight: 190
url: /id/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
## PathMulticolorGradientBrush class

Merangkum a[`Brush`](../../aspose.psd/brush/) objek dengan gradien. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor)(GraphicsPath) | Menginisialisasi instance baru dari`PathMulticolorGradientBrush` kelas dengan jalur yang ditentukan. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_1)(PointF[]) | Menginisialisasi instance baru dari`PathMulticolorGradientBrush` kelas dengan poin yang ditentukan. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_3)(Point[]) | Menginisialisasi instance baru dari`PathMulticolorGradientBrush` kelas dengan poin yang ditentukan. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_2)(PointF[], WrapMode) | Menginisialisasi instance baru dari`PathMulticolorGradientBrush` kelas dengan poin yang ditentukan dan mode bungkus. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_4)(Point[], WrapMode) | Menginisialisasi instance baru dari`PathMulticolorGradientBrush` kelas dengan poin yang ditentukan dan mode bungkus. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Mendapat atau menetapkan titik tengah gradien jalur. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Mendapat atau menyetel titik fokus untuk penurunan gradien. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Mendapat jalur grafis tempat sikat ini dibuat. |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors/) { get; set; } | Mendapat atau menyetel a[`ColorBlend`](../../aspose.psd/colorblend/) yang mendefinisikan gradien linier multiwarna. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapat nilai yang menunjukkan apakah transformasi diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Mendapat titik jalur kuas ini dibuat. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Mendapat atau menyetel salinan[`Matrix`](../../aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk ini[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Mendapat atau menyetel a[`WrapMode`](../../aspose.psd/wrapmode/) pencacahan yang menunjukkan mode bungkus untuk ini[`TransformBrush`](../transformbrush/) . |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari arus[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Mengalikan[`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal ini[`LinearGradientBrush`](../lineargradientbrush/) oleh yang ditentukan[`Matrix`](../../aspose.psd/matrix/) dengan mendahului yang ditentukan[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Mengalikan[`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal ini[`LinearGradientBrush`](../lineargradientbrush/) oleh yang ditentukan[`Matrix`](../../aspose.psd/matrix/) dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Mereset[`Transform`](../transformbrush/transform/) properti ke identitas. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Memutar transformasi geometrik lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan matriks penskalaan ke transformasi. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan terjemahan ke transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

### Lihat juga

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


