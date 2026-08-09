---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 构造函数。从指定路径的光栅图像（而非 PSD 图像）初始化 PsdImage 类的新实例。用于使用默认参数初始化 PSD 图像：颜色模式 rgb，4 通道，每通道 8 位，压缩方式 Raw。"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

从指定路径的光栅图像（而非 PSD 图像）初始化 [`PsdImage`](../) 类的新实例。用于使用默认参数初始化 PSD 图像——颜色模式：rgb，4 通道，每通道 8 位，压缩方式：Raw。

```csharp
public PsdImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 用于加载像素和调色板数据并进行初始化的路径。 |

### 另请参阅

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

使用构造函数参数，从指定的光栅图像路径（路径中不是 PSD 图像）初始化一个新的 [`PsdImage`](../) 类实例。

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | 用于加载像素和调色板数据并进行初始化的路径。 |
| colorMode | 颜色模式 | 颜色模式。 |
| 通道位深 | Int16 | 每个通道的 PSD 位深。 |
| channels | Int16 | PSD 通道数。 |
| psdVersion | Int32 | PSD 版本。 |
| 压缩 | CompressionMethod | 要使用的压缩方式。 |

### 另请参阅

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

使用构造函数参数，从指定的光栅图像路径（流中不是 PSD 图像）初始化一个新的 [`PsdImage`](../) 类实例。用于使用默认参数初始化 PSD 图像——颜色模式：rgb，4 个通道，每通道 8 位，压缩方式：Raw。

```csharp
public PsdImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 用于加载像素和调色板数据并进行初始化的流。 |

### 另请参阅

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

使用构造函数参数，从指定的光栅图像路径（流中不是 PSD 图像）初始化一个新的 [`PsdImage`](../) 类实例。

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 用于加载像素和调色板数据并进行初始化的流。 |
| colorMode | 颜色模式 | 颜色模式。 |
| 通道位深 | Int16 | 每个通道的 PSD 位深。 |
| channels | Int16 | PSD 通道数。 |
| psdVersion | Int32 | PSD 版本。 |
| 压缩 | CompressionMethod | 要使用的压缩方式。 |

### 另请参阅

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

从现有的光栅图像（不是 PSD 图像）初始化一个新的 [`PsdImage`](../) 类实例，使用 RGB 颜色模式、4 个通道、每通道 8 位且无压缩。

```csharp
public PsdImage(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于加载像素和调色板数据并进行初始化的图像。 |

### 另请参阅

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

使用构造函数参数，从现有的光栅图像（不是 PSD 图像）初始化一个新的 [`PsdImage`](../) 类实例。

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于加载像素和调色板数据并进行初始化的图像。 |
| colorMode | 颜色模式 | 颜色模式。 |
| 通道位深 | Int16 | 每个通道的 PSD 位深。 |
| channels | Int16 | PSD 通道数。 |
| psdVersion | Int32 | PSD 版本。 |
| 压缩 | CompressionMethod | 要使用的压缩方式。 |

### 另请参阅

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

使用指定的宽度和高度初始化一个新的 [`PsdImage`](../) 类实例。用于初始化空的 PSD 图像。

```csharp
public PsdImage(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 该图像宽度。 |
| 高度 | Int32 | 图像高度。 |

### 另请参阅

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

使用指定的宽度、高度、调色板、颜色模式、通道数、通道位长以及压缩模式参数初始化一个新的 [`PsdImage`](../) 类实例。用于初始化空的 PSD 图像。

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 该图像宽度。 |
| 高度 | Int32 | 图像高度。 |
| colorPalette | IColorPalette | 颜色调色板。 |
| colorMode | 颜色模式 | 颜色模式。 |
| 通道位深 | Int16 | 每个通道的 PSD 位深。 |
| channels | Int16 | PSD 通道数。 |
| psdVersion | Int32 | PSD 版本。 |
| 压缩 | CompressionMethod | 要使用的压缩方式。 |

### 另请参阅

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


