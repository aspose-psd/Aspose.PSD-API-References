---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD for .NET API Referansı
description: ColorPaletteHelper yöntem. Görüntüde palet olmaması durumunda raster görüntüden renk paleti alır görüntüsü paletler. Paletin mevcut olması durumunda hesaplamalar yapmak yerine kullanılacaktır.
type: docs
weight: 60
url: /tr/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Görüntüde palet olmaması durumunda raster görüntüden renk paleti alır (görüntüsü paletler). Paletin mevcut olması durumunda hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Tarama görüntüsü. |
| entriesCount | Int32 | İstenen girişler sayılır. |

### Geri dönüş değeri

En sık kullanılan renklerden başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* ad alanı [Aspose.PSD](../../colorpalettehelper/)
* toplantı [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Görüntüde palet olmaması durumunda raster görüntüden renk paleti alır (görüntüsü paletler). Paletin mevcut olması durumunda hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Tarama görüntüsü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen girişler sayılır. |

### Geri dönüş değeri

En sık kullanılan renklerden başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* ad alanı [Aspose.PSD](../../colorpalettehelper/)
* toplantı [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Görüntüde palet olmaması durumunda raster görüntüden renk paleti alır (görüntüsü paletler). Paletin mevcut olması durumunda hesaplamalar yapmak yerine kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Tarama görüntüsü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen girişler sayılır. |
| useImagePalette | Boolean | Ayarlanırsa, varsa kendi resim paletini kullanır |

### Geri dönüş değeri

En sık kullanılan renklerden başlayan renk paleti.*image* ve içerir*entriesCount* girişler.

### Ayrıca bakınız

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* ad alanı [Aspose.PSD](../../colorpalettehelper/)
* toplantı [Aspose.PSD](../../../)


