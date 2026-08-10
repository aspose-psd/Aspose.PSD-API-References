---
title: "Kelas PathMulticolorGradientBrush"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.PathMulticolorGradientBrush. Mengenkapsulasi objek Brush dengan gradien. Kelas ini tidak dapat diwariskan"
type: docs
weight: 190
url: /id/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
{{< psd/tize >}}
## PathMulticolorGradientBrush class

Mengenkapsulasi objek [`Brush`](../../aspose.psd/brush/) dengan gradien. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor)(GraphicsPath) | Menginisialisasi sebuah instance baru dari kelas `PathMulticolorGradientBrush` dengan jalur yang ditentukan. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_1)(PointF[]) | Menginisialisasi sebuah instance baru dari kelas `PathMulticolorGradientBrush` dengan titik-titik yang ditentukan. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_3)(Point[]) | Menginisialisasi sebuah instance baru dari kelas `PathMulticolorGradientBrush` dengan titik-titik yang ditentukan. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_2)(PointF[], WrapMode) | Menginisialisasi sebuah instance baru dari kelas `PathMulticolorGradientBrush` dengan titik-titik yang ditentukan dan mode pembungkus. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_4)(Point[], WrapMode) | Menginisialisasi sebuah instance baru dari kelas `PathMulticolorGradientBrush` dengan titik-titik yang ditentukan dan mode pembungkus. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Mendapatkan atau mengatur titik pusat gradien jalur. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Mendapatkan atau mengatur titik fokus untuk penurunan gradien. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Mendapatkan jalur grafis yang menjadi dasar kuas ini. |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors/) { get; set; } | Mendapatkan atau mengatur sebuah [`ColorBlend`](../../aspose.psd/colorblend/) yang mendefinisikan gradien linear multicolor. |
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

### Lihat Juga

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


