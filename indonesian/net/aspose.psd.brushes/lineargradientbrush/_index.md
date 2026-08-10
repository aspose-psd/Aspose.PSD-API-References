---
title: "Kelas LinearGradientBrush"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.LinearGradientBrush. Membungkus sebuah Brush dengan gradien linier. Kelas ini tidak dapat diwariskan"
type: docs
weight: 140
url: /id/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

Membungkus sebuah [`Brush`](../../aspose.psd/brush/) dengan gradien linier. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` dengan parameter default. Warna awal adalah hitam, warna akhir adalah putih, sudutnya 45 derajat dan persegi panjang berada di (0,0) dengan ukuran (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` dengan titik dan warna yang ditentukan. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Menginisialisasi sebuah instance baru dari kelas `LinearGradientBrush` berdasarkan persegi panjang, warna awal dan akhir, serta sudut orientasi. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Mendapatkan atau mengatur sudut gradien. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Mendapatkan atau mengatur sebuah [`Blend`](../../aspose.psd/blend/) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Mendapatkan atau mengatur warna akhir gradien. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi gamma diaktifkan untuk [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | Mendapatkan atau mengatur sebuah [`ColorBlend`](../../aspose.psd/colorblend/) yang mendefinisikan gradien linear multicolor. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [`Angle`](../lineargradientbrushbase/angle/) berubah selama transformasi dengan [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | Mendapatkan atau mengatur warna awal dan akhir gradien. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Menampilkan atau mengatur wilayah persegi panjang yang menentukan titik awal dan akhir gradien. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Mendapatkan atau mengatur warna awal gradien. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Menampilkan atau mengatur salinan [`Matrix`](../../aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk [`TransformBrush`](../transformbrush/) ini. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Menampilkan atau mengatur enumerasi [`WrapMode`](../../aspose.psd/wrapmode/) yang menunjukkan mode pembungkus untuk [`TransformBrush`](../transformbrush/) ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari [`Brush`](../../aspose.psd/brush/) saat ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Mengalikan [`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari `LinearGradientBrush` ini dengan [`Matrix`](../../aspose.psd/matrix/) yang ditentukan dengan menambahkan [`Matrix`](../../aspose.psd/matrix/) yang ditentukan di depan. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Mengalikan [`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari `LinearGradientBrush` ini dengan [`Matrix`](../../aspose.psd/matrix/) yang ditentukan dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Mengatur ulang properti [`Transform`](../transformbrush/transform/) ke identitas. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi di depan. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Menskalakan transformasi geometris lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi di depan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan nilai yang ditentukan dalam urutan yang ditentukan. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Membuat gradien linier dengan warna tengah dan penurunan linier ke satu warna di kedua ujung. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Membuat gradien linier dengan warna tengah dan penurunan linier ke satu warna di kedua ujung. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Membuat penurunan gradien berdasarkan kurva berbentuk lonceng. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi di depan. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

### Lihat Juga

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


