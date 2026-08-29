---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "ColorPaletteHelper メソッド。ラスタ画像からカラーパレットを取得し、画像にパレットがない場合は画像をパレット化します。パレットが存在する場合は、計算を行う代わりにそのパレットが使用されます。"
type: docs
weight: 60
url: /ja/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

画像にパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | RasterImage | ラスター画像。 |
| entriesCount | Int32 | 希望するエントリ数です。 |

### 戻り値

*image* の最も頻繁に出現する色から始まり、*entriesCount* エントリを含むカラーパレットです。

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

画像にパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | RasterImage | ラスター画像。 |
| destBounds | Rectangle | 対象画像の境界です。 |
| entriesCount | Int32 | 希望するエントリ数です。 |

### 戻り値

*image* の最も頻繁に出現する色から始まり、*entriesCount* エントリを含むカラーパレットです。

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

画像にパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | RasterImage | ラスター画像。 |
| destBounds | Rectangle | 対象画像の境界です。 |
| entriesCount | Int32 | 希望するエントリ数です。 |
| useImagePalette | Boolean | 設定されている場合、利用可能なら独自の画像パレットを使用します。 |

### 戻り値

*image* の最も頻繁に出現する色から始まり、*entriesCount* エントリを含むカラーパレットです。

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


