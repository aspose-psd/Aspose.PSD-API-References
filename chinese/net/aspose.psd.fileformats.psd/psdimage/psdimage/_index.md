---
title: PsdImage
second_title: Aspose.PSD for .NET API 参考
description: 从光栅图像的指定路径不是路径中的 psd 图像初始化PsdImageaspose.psd.fileformats.psd/psdimage类的新实例用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb4 通道每通道 8 位压缩 - 原始
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

从光栅图像的指定路径（不是路径中的 psd 图像）初始化[`PsdImage`](../../psdimage)类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩 - 原始。

```csharp
public PsdImage(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载像素和调色板数据并进行初始化的路径。 |

### 也可以看看

* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

使用构造函数从光栅图像（不是路径中的 psd 图像）的指定路径初始化[`PsdImage`](../../psdimage)类的新实例参数。

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载像素和调色板数据并进行初始化的路径。 |
| colorMode | ColorModes | 颜色模式。 |
| channelBitDepth | Int16 | 每个通道的 PSD 位深度。 |
| channels | Int16 | PSD 通道计数。 |
| psdVersion | Int32 | PSD 版本。 |
| compression | CompressionMethod | 要使用的压缩。 |

### 也可以看看

* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

从光栅图像（不是流中的 psd 图像）的指定路径初始化[`PsdImage`](../../psdimage)类的新实例。用于使用默认参数初始化 psd 图像 - 颜色模式 - rgb，4 通道，每通道 8 位，压缩 - 原始。

```csharp
public PsdImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中加载像素和调色板数据并进行初始化的流。 |

### 也可以看看

* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

使用构造函数从光栅图像（不是流中的 psd 图像）的指定路径初始化[`PsdImage`](../../psdimage)类的新实例参数。

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中加载像素和调色板数据并进行初始化的流。 |
| colorMode | ColorModes | 颜色模式。 |
| channelBitDepth | Int16 | 每个通道的 PSD 位深度。 |
| channels | Int16 | PSD 通道计数。 |
| psdVersion | Int32 | PSD 版本。 |
| compression | CompressionMethod | 要使用的压缩。 |

### 也可以看看

* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

从现有的光栅图像（不是 psd 图像）初始化[`PsdImage`](../../psdimage)类的新实例，RGB 颜色模式为 4通道 8 位/通道，无压缩。

```csharp
public PsdImage(RasterImage rasterImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 要从中加载像素和调色板数据并进行初始化的图像。 |

### 也可以看看

* class [RasterImage](../../../aspose.psd/rasterimage)
* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

使用构造函数参数从现有光栅图像（不是 psd 图像）初始化[`PsdImage`](../../psdimage)类的新实例。

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 要从中加载像素和调色板数据并进行初始化的图像。 |
| colorMode | ColorModes | 颜色模式。 |
| channelBitDepth | Int16 | 每个通道的 PSD 位深度。 |
| channels | Int16 | PSD 通道计数。 |
| psdVersion | Int32 | PSD 版本。 |
| compression | CompressionMethod | 要使用的压缩。 |

### 也可以看看

* class [RasterImage](../../../aspose.psd/rasterimage)
* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

初始化具有指定宽度和高度的[`PsdImage`](../../psdimage)类的新实例。用于初始化空的 psd 图像。

```csharp
public PsdImage(int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |

### 也可以看看

* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

初始化[`PsdImage`](../../psdimage)类的新实例，具有指定的宽度、高度、调色板、颜色模式、通道数和通道位长和指定的压缩模式参数。用于初始化空的 psd 图像。

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |
| colorPalette | IColorPalette | 调色板。 |
| colorMode | ColorModes | 颜色模式。 |
| channelBitDepth | Int16 | 每个通道的 PSD 位深度。 |
| channels | Int16 | PSD 通道计数。 |
| psdVersion | Int32 | PSD 版本。 |
| compression | CompressionMethod | 要使用的压缩。 |

### 也可以看看

* interface [IColorPalette](../../../aspose.psd/icolorpalette)
* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
