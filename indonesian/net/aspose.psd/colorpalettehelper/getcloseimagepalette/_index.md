---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD untuk Referensi .NET API
description: ColorPaletteHelper metode. Mendapat palet warna dari gambar raster membuat palet gambar jika gambar tidak memilikinya. Jika ada palet itu akan digunakan sebagai gantinya melakukan perhitungan.
type: docs
weight: 60
url: /id/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Mendapat palet warna dari gambar raster (membuat palet gambar) jika gambar tidak memilikinya. Jika ada palet, itu akan digunakan sebagai gantinya melakukan perhitungan.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | RasterImage | Gambar raster. |
| entriesCount | Int32 | Jumlah entri yang diinginkan. |

### Nilai Pengembalian

Palet warna yang dimulai dengan warna paling sering dari*image* dan berisi*entriesCount* entri.

### Lihat juga

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* ruang nama [Aspose.PSD](../../colorpalettehelper/)
* perakitan [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Mendapat palet warna dari gambar raster (membuat palet gambar) jika gambar tidak memilikinya. Jika ada palet, itu akan digunakan sebagai gantinya melakukan perhitungan.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | RasterImage | Gambar raster. |
| destBounds | Rectangle | Batas gambar tujuan. |
| entriesCount | Int32 | Jumlah entri yang diinginkan. |

### Nilai Pengembalian

Palet warna yang dimulai dengan warna paling sering dari*image* dan berisi*entriesCount* entri.

### Lihat juga

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* ruang nama [Aspose.PSD](../../colorpalettehelper/)
* perakitan [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Mendapat palet warna dari gambar raster (membuat palet gambar) jika gambar tidak memilikinya. Jika ada palet, itu akan digunakan sebagai gantinya melakukan perhitungan.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | RasterImage | Gambar raster. |
| destBounds | Rectangle | Batas gambar tujuan. |
| entriesCount | Int32 | Jumlah entri yang diinginkan. |
| useImagePalette | Boolean | Jika disetel, itu akan menggunakan palet gambarnya sendiri jika tersedia |

### Nilai Pengembalian

Palet warna yang dimulai dengan warna paling sering dari*image* dan berisi*entriesCount* entri.

### Lihat juga

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* ruang nama [Aspose.PSD](../../colorpalettehelper/)
* perakitan [Aspose.PSD](../../../)


