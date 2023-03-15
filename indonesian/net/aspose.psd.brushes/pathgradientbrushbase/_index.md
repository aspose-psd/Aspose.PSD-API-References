---
title: Class PathGradientBrushBase
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.PathGradientBrushBase kelas. Mewakili aBrush dengan fungsionalitas gradien jalur dasar.
type: docs
weight: 180
url: /id/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Mewakili a[`Brush`](../../aspose.psd/brush/) dengan fungsionalitas gradien jalur dasar.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Mendapat atau menetapkan titik tengah gradien jalur. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Mendapat atau menyetel titik fokus untuk penurunan gradien. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Mendapat jalur grafis tempat sikat ini dibuat. |
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

### Perkataan

Perhatikan bahwa saat membuat`PathGradientBrushBase` kelas itu harus diinisialisasi dengan 2 poin setidaknya. Jalur internal yang dibuat akan selalu tertutup, titik terakhir menghubungkan titik pertama. Bentuk itu diisi dengan ini`PathGradientBrushBase`. Implementasi GDI+ melontarkan sebuahOutOfMemoryException ketika melewati array kosong atau kumpulan titik yang memiliki koordinat yang sama. The`PathGradientBrushBase` melempar pengecualian ketika array poin berisi kurang dari 2 poin, ituArgumentException is dilempar daripadaOutOfMemoryException ketika array poin tidak dapat diterima. Titik pusat dihitung sebagai pusat massa untuk poin yang diteruskan secara default. Pengguna dapat mengubah titik ini nanti. Skala fokus adalah titik kosong (0,0, 0,0) secara default.

### Lihat juga

* class [TransformBrush](../transformbrush/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


