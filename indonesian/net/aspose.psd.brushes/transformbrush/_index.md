---
title: Class TransformBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.TransformBrush kelas. ABrush dengan kemampuan transformasi.
type: docs
weight: 220
url: /id/net/aspose.psd.brushes/transformbrush/
---
## TransformBrush class

A[`Brush`](../../aspose.psd/brush/) dengan kemampuan transformasi.

```csharp
public abstract class TransformBrush : Brush
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapat nilai yang menunjukkan apakah transformasi diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Mendapat atau menyetel salinan[`Matrix`](../../aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk ini`TransformBrush` . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Mendapat atau menyetel a[`WrapMode`](../../aspose.psd/wrapmode/) pencacahan yang menunjukkan mode bungkus untuk ini`TransformBrush` . |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari arus[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Mengalikan[`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal ini[`LinearGradientBrush`](../lineargradientbrush/) oleh yang ditentukan[`Matrix`](../../aspose.psd/matrix/) dengan mendahului yang ditentukan[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Mengalikan[`Matrix`](../../aspose.psd/matrix/) yang mewakili transformasi geometris lokal ini[`LinearGradientBrush`](../lineargradientbrush/) oleh yang ditentukan[`Matrix`](../../aspose.psd/matrix/) dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Mereset[`Transform`](./transform/) properti ke identitas. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Memutar transformasi geometrik lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan matriks penskalaan ke transformasi. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan terjemahan ke transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

### Lihat juga

* class [Brush](../../aspose.psd/brush/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


