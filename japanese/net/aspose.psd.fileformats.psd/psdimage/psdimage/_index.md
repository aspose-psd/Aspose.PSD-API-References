---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage コンストラクタ。指定されたパスのラスター画像（psd 画像ではない）から PsdImage クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用します：カラーモード rgb、4 チャンネル、チャンネルあたり 8 ビット、圧縮方式 Raw。"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

指定されたパスのラスター画像（psd 画像ではない）から [`PsdImage`](../) クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用します - カラーモード - rgb、4 チャンネル、チャンネルあたり 8 ビット、圧縮 - Raw。

```csharp
public PsdImage(string path)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | ピクセルとパレットデータを読み込み、初期化するためのパスです。 |

### 関連項目

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

指定されたパスからラスタ画像（パス内のpsd画像ではありません）を使用し、コンストラクタ パラメータで [`PsdImage`](../) クラスの新しいインスタンスを初期化します。

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | ピクセルとパレットデータを読み込み、初期化するためのパスです。 |
| カラーモード | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度です。 |
| channels | Int16 | PSD のチャンネル数です。 |
| psdVersion | Int32 | PSD バージョンです。 |
| compression | CompressionMethod | 使用する圧縮方式です。 |

### 関連項目

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

指定されたパスからラスタ画像（ストリーム内のpsd画像ではありません）を使用し、[`PsdImage`](../) クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用されます - カラーモード - rgb、4 チャネル、チャネルあたり 8 ビット、圧縮 - Raw。

```csharp
public PsdImage(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ピクセルとパレットデータを読み込み、初期化するためのストリームです。 |

### 関連項目

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

指定されたパスからラスタ画像（ストリーム内のpsd画像ではありません）を使用し、コンストラクタ パラメータで [`PsdImage`](../) クラスの新しいインスタンスを初期化します。

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ピクセルとパレットデータを読み込み、初期化するためのストリームです。 |
| カラーモード | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度です。 |
| channels | Int16 | PSD のチャンネル数です。 |
| psdVersion | Int32 | PSD バージョンです。 |
| compression | CompressionMethod | 使用する圧縮方式です。 |

### 関連項目

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

既存のラスタ画像（psd 画像ではありません）から、RGB カラーモード、4 チャネル、チャネルあたり 8 ビット、圧縮なしで [`PsdImage`](../) クラスの新しいインスタンスを初期化します。

```csharp
public PsdImage(RasterImage rasterImage)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rasterImage | RasterImage | ピクセルとパレットデータを読み込み、初期化するための画像です。 |

### 関連項目

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

既存のラスタ画像（psd 画像ではありません）から、コンストラクタ パラメータで [`PsdImage`](../) クラスの新しいインスタンスを初期化します。

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rasterImage | RasterImage | ピクセルとパレットデータを読み込み、初期化するための画像です。 |
| カラーモード | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度です。 |
| channels | Int16 | PSD のチャンネル数です。 |
| psdVersion | Int32 | PSD バージョンです。 |
| compression | CompressionMethod | 使用する圧縮方式です。 |

### 関連項目

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

指定された幅と高さで [`PsdImage`](../) クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用されます。

```csharp
public PsdImage(int width, int height)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | Int32 | 画像の幅です。 |
| height | Int32 | 画像の高さです。 |

### 関連項目

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

指定された幅、高さ、パレット、カラーモード、チャネル数、チャネルビット長、および指定された圧縮モード パラメータで [`PsdImage`](../) クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用されます。

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| width | Int32 | 画像の幅です。 |
| height | Int32 | 画像の高さです。 |
| colorPalette | IColorPalette | カラーパレットです。 |
| カラーモード | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度です。 |
| channels | Int16 | PSD のチャンネル数です。 |
| psdVersion | Int32 | PSD バージョンです。 |
| compression | CompressionMethod | 使用する圧縮方式です。 |

### 関連項目

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


