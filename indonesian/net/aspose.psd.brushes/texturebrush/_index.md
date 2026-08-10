---
title: "Kelas TextureBrush"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.TextureBrush. Setiap properti dari kelas TextureBrush adalah objek Brush yang menggunakan gambar untuk mengisi interior sebuah bentuk. Kelas ini tidak dapat diwariskan"
type: docs
weight: 210
url: /id/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Setiap properti dari kelas `TextureBrush` adalah objek [`Brush`](../../aspose.psd/brush/) yang menggunakan gambar untuk mengisi interior sebuah bentuk. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan dan mode pembungkus. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Menginisialisasi sebuah instance baru dari kelas `TextureBrush` yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Mendapatkan objek [`Image`](../../aspose.psd/image/) yang terkait dengan objek `TextureBrush` ini. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Mendapatkan [`ImageAttributes`](./imageattributes/) yang terkait dengan `TextureBrush` ini. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Mendapatkan [`Rectangle`](../../aspose.psd/rectangle/) yang terkait dengan `TextureBrush` ini. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus. |
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

### Lihat Juga

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


