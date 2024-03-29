---
title: PsdImage.PsdImage
second_title: Aspose.PSD for .NET API Reference
description: PsdImage constructor. Initializes a new instance of the PsdImage class from specified path from raster image not psd image in path. Used to initialize psd image with default parameters  Color mode  rgb 4 channels 8 bit per channel Compression  Raw
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Initializes a new instance of the [`PsdImage`](../) class from specified path from raster image (not psd image in path). Used to initialize psd image with default parameters - Color mode - rgb, 4 channels, 8 bit per channel, Compression - Raw.

```csharp
public PsdImage(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load pixel and palette data from and initialize with. |

### See Also

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initializes a new instance of the [`PsdImage`](../) class from specified path from raster image (not psd image in path) with constructor parameters.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load pixel and palette data from and initialize with. |
| colorMode | ColorModes | The color mode. |
| channelBitDepth | Int16 | The PSD bit depth per channel. |
| channels | Int16 | The PSD channels count. |
| psdVersion | Int32 | The PSD version. |
| compression | CompressionMethod | The compression to use. |

### See Also

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initializes a new instance of the [`PsdImage`](../) class from specified path from raster image (not psd image in stream). Used to initialize psd image with default parameters - Color mode - rgb, 4 channels, 8 bit per channel, Compression - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load pixel and palette data from and initialize with. |

### See Also

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initializes a new instance of the [`PsdImage`](../) class from specified path from raster image (not psd image in stream) with constructor parameters.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load pixel and palette data from and initialize with. |
| colorMode | ColorModes | The color mode. |
| channelBitDepth | Int16 | The PSD bit depth per channel. |
| channels | Int16 | The PSD channels count. |
| psdVersion | Int32 | The PSD version. |
| compression | CompressionMethod | The compression to use. |

### See Also

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initializes a new instance of the [`PsdImage`](../) class from existing raster image (not psd image) with RGB color mode with 4 channels 8 bit/channel and no compression.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to load pixel and palette data from and initialize with. |

### See Also

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initializes a new instance of the [`PsdImage`](../) class from existing raster image (not psd image) with constructor parameters.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to load pixel and palette data from and initialize with. |
| colorMode | ColorModes | The color mode. |
| channelBitDepth | Int16 | The PSD bit depth per channel. |
| channels | Int16 | The PSD channels count. |
| psdVersion | Int32 | The PSD version. |
| compression | CompressionMethod | The compression to use. |

### See Also

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initializes a new instance of the [`PsdImage`](../) class with specified width and height. Used to initialize empty psd image.

```csharp
public PsdImage(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |

### See Also

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initializes a new instance of the [`PsdImage`](../) class with specified width,height, paletter, color mode, channels count and channels bit-length and specified compression mode parameters. Used to initialize empty psd image.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |
| colorPalette | IColorPalette | The color palette. |
| colorMode | ColorModes | The color mode. |
| channelBitDepth | Int16 | The PSD bit depth per channel. |
| channels | Int16 | The PSD channels count. |
| psdVersion | Int32 | The PSD version. |
| compression | CompressionMethod | The compression to use. |

### See Also

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


