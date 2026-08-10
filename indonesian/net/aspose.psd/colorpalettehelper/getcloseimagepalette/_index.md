---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode ColorPaletteHelper. Mendapatkan palet warna dari gambar raster yang mem-paletkan gambar jika gambar tidak memiliki satu. Jika palet sudah ada, akan digunakan alih-alih melakukan perhitungan"
type: docs
weight: 60
url: /id/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet sudah ada, akan digunakan alih-alih melakukan perhitungan.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | RasterImage | Gambar raster. |
| entriesCount | Int32 | Jumlah entri yang diinginkan. |

### Nilai Kembalian

Palet warna yang dimulai dengan warna paling sering dari *image* dan berisi *entriesCount* entri.

### Lihat Juga

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet sudah ada, akan digunakan alih-alih melakukan perhitungan.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | RasterImage | Gambar raster. |
| destBounds | Rectangle | Batas gambar tujuan. |
| entriesCount | Int32 | Jumlah entri yang diinginkan. |

### Nilai Kembalian

Palet warna yang dimulai dengan warna paling sering dari *image* dan berisi *entriesCount* entri.

### Lihat Juga

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Mendapatkan palet warna dari gambar raster (mem-palletkan gambar) jika gambar tidak memiliki palet. Jika palet sudah ada, akan digunakan alih-alih melakukan perhitungan.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | RasterImage | Gambar raster. |
| destBounds | Rectangle | Batas gambar tujuan. |
| entriesCount | Int32 | Jumlah entri yang diinginkan. |
| useImagePalette | Boolean | Jika diatur, akan menggunakan palet gambar sendiri jika tersedia |

### Nilai Kembalian

Palet warna yang dimulai dengan warna paling sering dari *image* dan berisi *entriesCount* entri.

### Lihat Juga

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


