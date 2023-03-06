---
title: PsdImage.PsdImage
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage inşaatçı. Yeni bir örneğini başlatır.PsdImage raster görüntüden belirtilen yoldan sınıf yoldaki psd görüntüsü değil. psd görüntüsünü varsayılan parametrelerle başlatmak için kullanılır  Renk modu  rgb 4 kanal kanal başına 8 bit Sıkıştırma  Raw.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Yeni bir örneğini başlatır.[`PsdImage`](../) raster görüntüden belirtilen yoldan sınıf (yoldaki psd görüntüsü değil). psd görüntüsünü varsayılan parametrelerle başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

```csharp
public PsdImage(string path)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Piksel ve palet verilerini yükleme ve başlatma yolu. |

### Ayrıca bakınız

* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Yeni bir örneğini başlatır.[`PsdImage`](../) yapıcı parametreleriyle raster görüntüden (yoldaki psd görüntüsü değil) belirtilen yoldan sınıf.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| path | String | Piksel ve palet verilerini yükleme ve başlatma yolu. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanalları sayılır. |
| psdVersion | Int32 | PSD versiyonu. |
| compression | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca bakınız

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Yeni bir örneğini başlatır.[`PsdImage`](../) raster görüntüden belirtilen yoldan sınıf (akıştaki psd görüntüsü değil). psd görüntüsünü varsayılan parametrelerle başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Piksel ve palet verilerini yüklemek ve bununla başlatmak için akış. |

### Ayrıca bakınız

* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Yeni bir örneğini başlatır.[`PsdImage`](../) yapıcı parametreleriyle raster görüntüden (akıştaki psd görüntüsü değil) belirtilen yoldan sınıf.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Piksel ve palet verilerini yüklemek ve bununla başlatmak için akış. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanalları sayılır. |
| psdVersion | Int32 | PSD versiyonu. |
| compression | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca bakınız

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Yeni bir örneğini başlatır.[`PsdImage`](../) kanallı 8 bit/kanallı ve sıkıştırmasız RGB renk modu ile mevcut raster görüntüden (psd görüntüsü değil) sınıf.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerinin yükleneceği ve başlatılacağı görüntü. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Yeni bir örneğini başlatır.[`PsdImage`](../) yapıcı parametreleriyle mevcut raster görüntüden (psd görüntüsü değil) sınıf.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerinin yükleneceği ve başlatılacağı görüntü. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanalları sayılır. |
| psdVersion | Int32 | PSD versiyonu. |
| compression | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca bakınız

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Yeni bir örneğini başlatır.[`PsdImage`](../) belirtilen genişlik ve yüksekliğe sahip sınıf. Boş psd görüntüsünü başlatmak için kullanılır.

```csharp
public PsdImage(int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |

### Ayrıca bakınız

* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Yeni bir örneğini başlatır.[`PsdImage`](../) belirtilen genişlik, yükseklik, paletleyici, renk modu, kanal sayısı ve kanal bit uzunluğu ve belirtilen sıkıştırma modu parametreleri ile sınıf. Boş psd görüntüsünü başlatmak için kullanılır.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Int32 | Görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |
| colorPalette | IColorPalette | Renk paleti. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanalları sayılır. |
| psdVersion | Int32 | PSD versiyonu. |
| compression | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca bakınız

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


