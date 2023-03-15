---
title: Class LinearMulticolorGradientBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.LinearMulticolorGradientBrush kelas. Mewakili aBrush dengan gradien linier yang ditentukan oleh berbagai warna dan posisi yang sesuai. Kelas ini tidak dapat diwariskan.
type: docs
weight: 160
url: /id/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Mewakili a[`Brush`](../../aspose.psd/brush/) dengan gradien linier yang ditentukan oleh berbagai warna dan posisi yang sesuai. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas dengan parameter default. Warna awal hitam, warna akhir putih, sudut 45 derajat dan persegi panjang terletak di (0,0) dengan ukuran (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas dengan poin yang ditentukan. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas dengan poin yang ditentukan. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas berdasarkan persegi panjang dan sudut orientasi. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas berdasarkan persegi panjang dan sudut orientasi. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas berdasarkan persegi panjang dan sudut orientasi. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Menginisialisasi instance baru dari`LinearMulticolorGradientBrush` kelas berdasarkan persegi panjang dan sudut orientasi. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Mendapat atau mengatur sudut gradien. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk ini[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Mendapat atau menyetel a[`ColorBlend`](../../aspose.psd/colorblend/) yang mendefinisikan gradien linier multiwarna. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah[`Angle`](../lineargradientbrushbase/angle/) diubah selama transformasi dengan ini[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapat nilai yang menunjukkan apakah transformasi diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Mendapat atau menyetel wilayah persegi panjang yang menentukan titik awal dan akhir gradien. |
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

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


