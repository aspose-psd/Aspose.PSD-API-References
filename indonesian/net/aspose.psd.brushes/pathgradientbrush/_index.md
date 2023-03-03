---
title: Class PathGradientBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.PathGradientBrush kelas. Merangkum aBrush objek dengan gradien. Kelas ini tidak dapat diwariskan.
type: docs
weight: 170
url: /id/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

Merangkum a[`Brush`](../../aspose.psd/brush/) objek dengan gradien. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Menginisialisasi instance baru dari`PathGradientBrush` kelas dengan jalur yang ditentukan. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Menginisialisasi instance baru dari`PathGradientBrush` kelas dengan poin yang ditentukan. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Menginisialisasi instance baru dari`PathGradientBrush` kelas dengan poin yang ditentukan. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Menginisialisasi instance baru dari`PathGradientBrush` kelas dengan poin yang ditentukan dan mode bungkus. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Menginisialisasi instance baru dari`PathGradientBrush` kelas dengan poin yang ditentukan dan mode bungkus. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Mendapat atau menyetel a[`Blend`](../../aspose.psd/blend/) yang menentukan posisi dan faktor yang menentukan penurunan kustom untuk gradien. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Mendapat atau mengatur warna di tengah gradien jalur. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Mendapat atau menetapkan titik tengah gradien jalur. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Mendapat atau menyetel titik fokus untuk penurunan gradien. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Mendapat jalur grafis tempat sikat ini dibuat. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapat nilai yang menunjukkan apakah transformasi diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Mendapat titik jalur kuas ini dibuat. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Mendapat atau menetapkan array warna yang sesuai dengan titik-titik di jalur ini`PathGradientBrush` isi. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Membuat gradien dengan warna tengah dan falloff linier ke satu warna di sekitarnya. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Membuat gradien dengan warna tengah dan falloff linier ke setiap warna di sekitarnya. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Membuat kuas gradien yang berubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Membuat kuas gradien yang berubah warna mulai dari pusat jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan terjemahan ke transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

### Perkataan

Warna tengah putih secara default. Seorang pengguna dapat mengubah nilai ini kapan saja nanti.

Array warna surround diinisialisasi oleh elemen tunggal yang berisi warna putih secara default. Warna surround dapat diubah nanti, namun setidaknya diperlukan satu elemen saat mengatur warna surround.

Lihat[`Blend`](./blend/) untuk detail lebih lanjut tentang inisialisasinya.

### Lihat juga

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


