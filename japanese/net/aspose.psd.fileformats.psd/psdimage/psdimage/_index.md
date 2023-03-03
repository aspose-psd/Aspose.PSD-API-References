---
title: PsdImage.PsdImage
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage コンストラクタ. の新しいインスタンスを初期化しますPsdImageラスター画像からの指定されたパスからのクラスパス内のpsd画像ではありません psd 画像をデフォルト パラメータで初期化するために使用  カラー モード  RGB4 チャネルチャネルあたり 8 ビット圧縮  Raw.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

の新しいインスタンスを初期化します[`PsdImage`](../)ラスター画像からの指定されたパスからのクラス（パス内のpsd画像ではありません）。 psd 画像をデフォルト パラメータで初期化するために使用 - カラー モード - RGB、4 チャネル、チャネルあたり 8 ビット、圧縮 - Raw.

```csharp
public PsdImage(string path)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | ピクセルとパレットのデータを読み込み、初期化するためのパス。 |

### 関連項目

* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

の新しいインスタンスを初期化します[`PsdImage`](../)ラスター イメージ (パス内の psd イメージではない) からの指定されたパスのクラスと、コンストラクター パラメーター.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | ピクセルとパレットのデータを読み込み、初期化するためのパス。 |
| colorMode | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度。 |
| channels | Int16 | PSD チャネルがカウントされます。 |
| psdVersion | Int32 | PSD版です。 |
| compression | CompressionMethod | 使用する圧縮。 |

### 関連項目

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

の新しいインスタンスを初期化します[`PsdImage`](../)ラスター画像 (ストリーム内の psd 画像ではない) からの指定されたパスからのクラス。 psd 画像をデフォルト パラメータで初期化するために使用 - カラー モード - RGB、4 チャネル、チャネルあたり 8 ビット、圧縮 - Raw.

```csharp
public PsdImage(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ピクセルとパレットのデータを読み込み、初期化するためのストリーム。 |

### 関連項目

* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

の新しいインスタンスを初期化します[`PsdImage`](../)ラスター イメージ (ストリーム内の psd イメージではない) からの指定されたパスのクラスとコンストラクター パラメーター.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ピクセルとパレットのデータを読み込み、初期化するためのストリーム。 |
| colorMode | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度。 |
| channels | Int16 | PSD チャネルがカウントされます。 |
| psdVersion | Int32 | PSD版です。 |
| compression | CompressionMethod | 使用する圧縮。 |

### 関連項目

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

の新しいインスタンスを初期化します[`PsdImage`](../)既存のラスター画像 (psd 画像ではない) からのクラスで、4 チャンネル、8 ビット/チャンネル、圧縮なしの RGB カラー モード.

```csharp
public PsdImage(RasterImage rasterImage)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rasterImage | RasterImage | ピクセルとパレットのデータを読み込み、初期化するイメージ。 |

### 関連項目

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

の新しいインスタンスを初期化します[`PsdImage`](../)コンストラクターパラメーターを持つ既存のラスターイメージ (psd イメージではない) からのクラス.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rasterImage | RasterImage | ピクセルとパレットのデータを読み込み、初期化するイメージ。 |
| colorMode | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度。 |
| channels | Int16 | PSD チャネルがカウントされます。 |
| psdVersion | Int32 | PSD版です。 |
| compression | CompressionMethod | 使用する圧縮。 |

### 関連項目

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

の新しいインスタンスを初期化します[`PsdImage`](../)幅と高さが指定されたクラス。空の psd イメージを初期化するために使用されます。

```csharp
public PsdImage(int width, int height)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| width | Int32 | 画像の幅。 |
| height | Int32 | 画像の高さ。 |

### 関連項目

* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

の新しいインスタンスを初期化します[`PsdImage`](../)指定された幅、高さ、パレット、カラー モード、チャネル数、チャネル ビット長、および指定された圧縮モード パラメータを持つクラス。空の psd イメージを初期化するために使用されます。

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| width | Int32 | 画像の幅。 |
| height | Int32 | 画像の高さ。 |
| colorPalette | IColorPalette | カラーパレット。 |
| colorMode | ColorModes | カラーモード。 |
| channelBitDepth | Int16 | チャネルごとの PSD ビット深度。 |
| channels | Int16 | PSD チャネルがカウントされます。 |
| psdVersion | Int32 | PSD版です。 |
| compression | CompressionMethod | 使用する圧縮。 |

### 関連項目

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


