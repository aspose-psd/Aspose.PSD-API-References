---
title: "Kelas PathGradientBrush"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.PathGradientBrush. Mengenkapsulasi objek Brush dengan gradien. Kelas ini tidak dapat diwariskan."
type: docs
weight: 170
url: /id/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

Mengenkapsulasi objek [`Brush`](../../aspose.psd/brush/) dengan gradien. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Menginisialisasi instance baru dari kelas `PathGradientBrush` dengan jalur yang ditentukan. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Menginisialisasi instance baru dari kelas `PathGradientBrush` dengan titik-titik yang ditentukan. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Menginisialisasi instance baru dari kelas `PathGradientBrush` dengan titik-titik yang ditentukan. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Menginisialisasi instance baru dari kelas `PathGradientBrush` dengan titik-titik yang ditentukan dan mode pembungkus. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Menginisialisasi instance baru dari kelas `PathGradientBrush` dengan titik-titik yang ditentukan dan mode pembungkus. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Mendapatkan atau mengatur sebuah [`Blend`](../../aspose.psd/blend/) yang menentukan posisi dan faktor yang mendefinisikan penurunan khusus untuk gradien. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Mendapatkan atau mengatur warna di tengah gradien jalur. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Mendapatkan atau mengatur titik pusat gradien jalur. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Mendapatkan jalur grafis yang menjadi dasar kuas ini. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | Mendapatkan atau mengatur sebuah [`ColorBlend`](../../aspose.psd/colorblend/) yang mendefinisikan gradien linear multicolor. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Mendapatkan titik-titik jalur yang menjadi dasar kuas ini. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Mendapatkan atau mengatur array warna yang sesuai dengan titik-titik pada jalur yang diisi oleh `PathGradientBrush` ini. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Menampilkan atau mengatur salinan [`Matrix`](../../aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk [`TransformBrush`](../transformbrush/) ini. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Menampilkan atau mengatur enumerasi [`WrapMode`](../../aspose.psd/wrapmode/) yang menunjukkan mode pembungkus untuk [`TransformBrush`](../transformbrush/) ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari [`Brush`](../../aspose.psd/brush/) saat ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Mengalikan [`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [`LinearGradientBrush`](../lineargradientbrush/) ini dengan [`Matrix`](../../aspose.psd/matrix/) yang ditentukan dengan menambahkan [`Matrix`](../../aspose.psd/matrix/) yang ditentukan di depan. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Mengalikan [`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [`LinearGradientBrush`](../lineargradientbrush/) ini dengan [`Matrix`](../../aspose.psd/matrix/) yang ditentukan dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Mengatur ulang properti [`Transform`](../transformbrush/transform/) ke identitas. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi di depan. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Menskalakan transformasi geometris lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi di depan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan nilai yang ditentukan dalam urutan yang ditentukan. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Membuat gradien dengan warna tengah dan penurunan linier ke satu warna di sekitarnya. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Membuat gradien dengan warna tengah dan penurunan linier ke setiap warna di sekitarnya. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Membuat kuas gradien yang mengubah warna mulai dari tengah jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Membuat kuas gradien yang mengubah warna mulai dari tengah jalur ke luar hingga batas jalur. Transisi dari satu warna ke warna lain didasarkan pada kurva berbentuk lonceng. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi di depan. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

## Catatan

Warna tengah secara default berwarna putih. Pengguna dapat mengubah nilai ini kapan saja nanti.

Array warna sekeliling diinisialisasi dengan satu elemen yang berisi warna putih secara default. Warna sekeliling dapat diubah nanti, namun setidaknya satu elemen diperlukan saat mengatur warna sekeliling.

Lihat [`Blend`](./blend/) untuk detail lebih lanjut tentang inisialisasinya.

### Lihat Juga

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


