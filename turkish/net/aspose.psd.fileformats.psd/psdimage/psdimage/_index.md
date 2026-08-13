---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage yapıcı. Belirtilen yoldaki raster görüntüsünden (psd görüntüsü değil) yeni bir PsdImage sınıfı örneği başlatır. Varsayılan parametrelerle psd görüntüsü başlatmak için kullanılır: Renk modu rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma Raw"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Belirtilen yoldaki raster görüntüsünden (psd görüntüsü değil) [`PsdImage`](../) sınıfının yeni bir örneğini başlatır. Varsayılan parametrelerle psd görüntüsü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

```csharp
public PsdImage(string path)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | String | Piksel ve palet verilerini yüklemek ve başlatmak için yol. |

### Ayrıca Bakınız

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Belirtilen yoldaki raster görüntüsünden (psd görüntüsü değil) [`PsdImage`](../) sınıfının yeni bir örneğini, yapıcı parametreleriyle başlatır.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | String | Piksel ve palet verilerini yüklemek ve başlatmak için yol. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanal sayısı. |
| psdVersion | Int32 | PSD sürümü. |
| sıkıştırma | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca Bakınız

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Belirtilen yoldaki raster görüntüsünden (psd görüntüsü değil, akış içinde) [`PsdImage`](../) sınıfının yeni bir örneğini başlatır. Varsayılan parametrelerle psd görüntüsü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Piksel ve palet verilerini yüklemek ve başlatmak için akış. |

### Ayrıca Bakınız

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Belirtilen yoldan raster görüntü (akışta psd görüntüsü değil) kullanarak [`PsdImage`](../) sınıfının yeni bir örneğini, yapıcı parametreleriyle başlatır.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Piksel ve palet verilerini yüklemek ve başlatmak için akış. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanal sayısı. |
| psdVersion | Int32 | PSD sürümü. |
| sıkıştırma | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca Bakınız

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Mevcut raster görüntüden (psd görüntüsü değil) RGB renk modu, 4 kanal, 8 bit/kanal ve sıkıştırma olmadan [`PsdImage`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak görüntü. |

### Ayrıca Bakınız

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Mevcut raster görüntüden (psd görüntüsü değil) yapıcı parametreleriyle [`PsdImage`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | RasterImage | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak görüntü. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanal sayısı. |
| psdVersion | Int32 | PSD sürümü. |
| sıkıştırma | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca Bakınız

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Belirtilen genişlik ve yükseklik ile [`PsdImage`](../) sınıfının yeni bir örneğini başlatır. Boş psd görüntüsü oluşturmak için kullanılır.

```csharp
public PsdImage(int width, int height)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | Int32 | görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |

### Ayrıca Bakınız

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Belirtilen genişlik, yükseklik, palet, renk modu, kanal sayısı ve kanal bit uzunluğu ile belirtilen sıkıştırma modu parametrelerini kullanarak [`PsdImage`](../) sınıfının yeni bir örneğini başlatır. Boş psd görüntüsü oluşturmak için kullanılır.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | Int32 | görüntü genişliği. |
| height | Int32 | Görüntü yüksekliği. |
| colorPalette | IColorPalette | Renk paleti. |
| colorMode | ColorModes | Renk modu. |
| channelBitDepth | Int16 | Kanal başına PSD bit derinliği. |
| channels | Int16 | PSD kanal sayısı. |
| psdVersion | Int32 | PSD sürümü. |
| sıkıştırma | CompressionMethod | Kullanılacak sıkıştırma. |

### Ayrıca Bakınız

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


