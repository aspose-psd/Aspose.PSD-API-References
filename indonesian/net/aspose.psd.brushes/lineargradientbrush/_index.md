---
title: Class LinearGradientBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.LinearGradientBrush kelas. Merangkum aBrush dengan gradien linier. Kelas ini tidak dapat diwariskan.
type: docs
weight: 140
url: /id/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Merangkum a[`Brush`](../../aspose.psd/brush/) dengan gradien linier. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Menginisialisasi instance baru dari`LinearGradientBrush` kelas dengan parameter default. Warna awal hitam, warna akhir putih, sudut 45 derajat dan persegi panjang terletak di (0,0) dengan ukuran (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Menginisialisasi instance baru dari`LinearGradientBrush` kelas dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Menginisialisasi instance baru dari`LinearGradientBrush` kelas dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Menginisialisasi instance baru dari`LinearGradientBrush` kelas berdasarkan persegi panjang, warna awal dan akhir, dan sudut orientasi. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Menginisialisasi instance baru dari`LinearGradientBrush` kelas berdasarkan persegi panjang, warna awal dan akhir, dan sudut orientasi. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Menginisialisasi instance baru dari`LinearGradientBrush` kelas berdasarkan persegi panjang, warna awal dan akhir, dan sudut orientasi. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Menginisialisasi instance baru dari`LinearGradientBrush` kelas berdasarkan persegi panjang, warna awal dan akhir, dan sudut orientasi. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Mendapat atau mengatur sudut gradien. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Mendapat atau menyetel a[`Blend`](../../aspose.psd/blend/) yang menentukan posisi dan faktor yang menentukan penurunan kustom untuk gradien. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Mendapat atau menyetel warna gradien akhir. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk ini[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah[`Angle`](../lineargradientbrushbase/angle/) diubah selama transformasi dengan ini[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapat nilai yang menunjukkan apakah transformasi diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Mendapat atau menyetel wilayah persegi panjang yang menentukan titik awal dan akhir gradien. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Mendapat atau menyetel warna gradien awal. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Mendapat atau menyetel salinan[`Matrix`](../../aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk ini[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Mendapat atau menyetel a[`WrapMode`](../../aspose.psd/wrapmode/) pencacahan yang menunjukkan mode bungkus untuk ini[`TransformBrush`](../transformbrush/) . |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari arus[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Mengalikan[`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal ini`LinearGradientBrush` oleh yang ditentukan[`Matrix`](../../aspose.psd/matrix/) dengan mendahului yang ditentukan[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Mengalikan[`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal ini`LinearGradientBrush` oleh yang ditentukan[`Matrix`](../../aspose.psd/matrix/) dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Mereset[`Transform`](../transformbrush/transform/) properti ke identitas. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Memutar transformasi geometrik lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan matriks penskalaan ke transformasi. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Membuat gradien linier dengan warna tengah dan penurunan linier ke satu warna di kedua ujungnya. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Membuat gradien linier dengan warna tengah dan penurunan linier ke satu warna di kedua ujungnya. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan terjemahan ke transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

### Lihat juga

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


