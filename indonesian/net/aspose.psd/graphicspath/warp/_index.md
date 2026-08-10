---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode GraphicsPath. Menerapkan transformasi warp yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram ke GraphicsPath ini."
type: docs
weight: 180
url: /id/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [`GraphicsPath`](../) ini.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | PointF[] | Sebuah array dari struktur [`PointF`](../../pointf/) yang mendefinisikan sebuah paralelogram ke mana persegi panjang yang didefinisikan oleh *srcRect* diubah. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan oleh tiga titik pertama. |
| srcRect | RectangleF | Sebuah [`RectangleF`](../../rectanglef/) yang mewakili persegi panjang yang diubah menjadi paralelogram yang didefinisikan oleh *destPoints*. |

### Lihat Juga

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [`GraphicsPath`](../) ini.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | PointF[] | Sebuah array dari struktur [`PointF`](../../pointf/) yang mendefinisikan sebuah paralelogram ke mana persegi panjang yang didefinisikan oleh *srcRect* diubah. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan oleh tiga titik pertama. |
| srcRect | RectangleF | Sebuah [`RectangleF`](../../rectanglef/) yang mewakili persegi panjang yang diubah menjadi paralelogram yang didefinisikan oleh *destPoints*. |
| matrix | Matrix | Sebuah [`Matrix`](../../matrix/) yang menentukan transformasi geometris untuk diterapkan pada jalur. |

### Lihat Juga

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [`GraphicsPath`](../) ini.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | PointF[] | Sebuah array dari struktur [`PointF`](../../pointf/) yang mendefinisikan sebuah paralelogram ke mana persegi panjang yang didefinisikan oleh *srcRect* diubah. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan oleh tiga titik pertama. |
| srcRect | RectangleF | Sebuah [`RectangleF`](../../rectanglef/) yang mewakili persegi panjang yang diubah menjadi paralelogram yang didefinisikan oleh *destPoints*. |
| matrix | Matrix | Sebuah [`Matrix`](../../matrix/) yang menentukan transformasi geometris untuk diterapkan pada jalur. |
| warpMode | WarpMode | Sebuah enumerasi [`WarpMode`](../../warpmode/) yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |

### Lihat Juga

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan sebuah paralelogram, ke [`GraphicsPath`](../) ini.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | PointF[] | Sebuah array dari struktur [`PointF`](../../pointf/) yang mendefinisikan sebuah paralelogram ke mana persegi panjang yang didefinisikan oleh *srcRect* diubah. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diasumsikan oleh tiga titik pertama. |
| srcRect | RectangleF | Sebuah [`RectangleF`](../../rectanglef/) yang mewakili persegi panjang yang diubah menjadi paralelogram yang didefinisikan oleh *destPoints*. |
| matrix | Matrix | Sebuah [`Matrix`](../../matrix/) yang menentukan transformasi geometris untuk diterapkan pada jalur. |
| warpMode | WarpMode | Sebuah enumerasi [`WarpMode`](../../warpmode/) yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |
| flatness | Single | Nilai antara 0 hingga 1 yang menentukan seberapa datar jalur yang dihasilkan. Untuk informasi lebih lanjut, lihat metode [`Flatten`](../flatten/). |

### Lihat Juga

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


