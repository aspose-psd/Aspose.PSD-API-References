---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ColorPaletteHelper metodu. Görüntünün renk paleti yoksa raster görüntüden renk paleti alır ve görüntüyü paletler. Palet mevcutsa, hesaplamalar yerine mevcut palet kullanılacaktır."
type: docs
weight: 60
url: /tr/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleyerek) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | RasterImage | Raster görüntüsü. |
| entriesCount | Int32 | İstenen giriş sayısı. |

### Dönüş Değeri

En sık kullanılan renklerle *image*'den başlayan ve *entriesCount* giriş içeren renk paleti.

### Ayrıca Bakınız

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleyerek) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | RasterImage | Raster görüntüsü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen giriş sayısı. |

### Dönüş Değeri

En sık kullanılan renklerle *image*'den başlayan ve *entriesCount* giriş içeren renk paleti.

### Ayrıca Bakınız

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletleyerek) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | RasterImage | Raster görüntüsü. |
| destBounds | Rectangle | Hedef görüntü sınırları. |
| entriesCount | Int32 | İstenen giriş sayısı. |
| useImagePalette | Boolean | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır. |

### Dönüş Değeri

En sık kullanılan renklerle *image*'den başlayan ve *entriesCount* giriş içeren renk paleti.

### Ayrıca Bakınız

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


