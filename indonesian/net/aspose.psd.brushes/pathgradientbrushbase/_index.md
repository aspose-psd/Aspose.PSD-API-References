---
title: "Kelas PathGradientBrushBase"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.PathGradientBrushBase. Mewakili kuas dengan fungsionalitas gradien jalur dasar."
type: docs
weight: 180
url: /id/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

Mewakili sebuah [`Brush`](../../aspose.psd/brush/) dengan fungsionalitas gradien jalur dasar.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Mendapatkan atau mengatur titik pusat gradien jalur. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Mendapatkan jalur grafis yang menjadi dasar kuas ini. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Mendapatkan titik-titik jalur yang menjadi dasar kuas ini. |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi di depan. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

## Catatan

Catatan bahwa saat membuat kelas `PathGradientBrushBase` harus diinisialisasi dengan setidaknya 2 titik. Jalur internal yang dibuat akan selalu menjadi bentuk tertutup, titik terakhir menghubungkan titik pertama. Bentuk itu diisi dengan `PathGradientBrushBase` ini. Implementasi GDI+ melempar OutOfMemoryException ketika diberikan array kosong atau kumpulan titik dengan koordinat yang sama. `PathGradientBrushBase` melempar pengecualian ketika array titik berisi kurang dari 2 titik; ArgumentException dilemparkan alih-alih OutOfMemoryException ketika array titik tidak dapat diterima. Titik pusat dihitung sebagai pusat massa dari titik-titik yang diberikan secara default. Pengguna dapat mengubah titik ini nanti. Skala fokus adalah titik kosong (0.0, 0.0) secara default.

### Lihat Juga

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


