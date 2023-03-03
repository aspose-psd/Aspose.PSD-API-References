---
title: Class TextureBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.TextureBrush kelas. Setiap properti dariTextureBrush kelas adalahBrush objek yang menggunakan gambar untuk mengisi interior bentuk. Kelas ini tidak dapat diwariskan.
type: docs
weight: 210
url: /id/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Setiap properti dari`TextureBrush` kelas adalah[`Brush`](../../aspose.psd/brush/) objek yang menggunakan gambar untuk mengisi interior bentuk. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Menginisialisasi instance baru dari`TextureBrush` kelas yang menggunakan image. yang ditentukan |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Menginisialisasi instance baru dari`TextureBrush` kelas yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Menginisialisasi instance baru dari`TextureBrush` kelas yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Menginisialisasi instance baru dari`TextureBrush` kelas yang menggunakan gambar yang ditentukan dan mode bungkus. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Menginisialisasi instance baru dari`TextureBrush` kelas yang menggunakan gambar tertentu, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Menginisialisasi instance baru dari`TextureBrush` kelas yang menggunakan gambar tertentu, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Menginisialisasi instance baru dari`TextureBrush`kelas yang menggunakan gambar yang ditentukan, mode bungkus, dan persegi panjang pembatas. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Menginisialisasi instance baru dari`TextureBrush`kelas yang menggunakan gambar yang ditentukan, mode bungkus, dan persegi panjang pembatas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Mendapatkan[`Image`](../../aspose.psd/image/) objek yang terkait dengan ini`TextureBrush` objek. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Mendapatkan[`ImageAttributes`](./imageattributes/) terkait dengan ini`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Mendapatkan[`Rectangle`](../../aspose.psd/rectangle/) terkait dengan ini`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapat nilai yang menunjukkan apakah transformasi diubah dalam beberapa cara. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |
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

* class [TransformBrush](../transformbrush/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


