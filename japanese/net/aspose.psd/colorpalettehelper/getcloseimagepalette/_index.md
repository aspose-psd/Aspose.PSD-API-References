---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD for .NET API リファレンス
description: ColorPaletteHelper 方法. イメージにカラー パレットがない場合にラスター イメージからカラー パレットを取得します イメージをパレット化しますパレットが存在する場合は計算を実行する代わりに使用されます.
type: docs
weight: 60
url: /ja/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

イメージにカラー パレットがない場合に、ラスター イメージからカラー パレットを取得します (イメージをパレット化します)。パレットが存在する場合は、計算を実行する代わりに使用されます.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | RasterImage | ラスター画像。 |
| entriesCount | Int32 | 必要なエントリがカウントされます。 |

### 戻り値

から最も頻繁に使用される色から始まるカラー パレット。*image*および含む*entriesCount*エントリー.

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* 名前空間 [Aspose.PSD](../../colorpalettehelper/)
* 組み立て [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

イメージにカラー パレットがない場合に、ラスター イメージからカラー パレットを取得します (イメージをパレット化します)。パレットが存在する場合は、計算を実行する代わりに使用されます.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | RasterImage | ラスター画像。 |
| destBounds | Rectangle | 宛先イメージの境界。 |
| entriesCount | Int32 | 必要なエントリがカウントされます。 |

### 戻り値

から最も頻繁に使用される色から始まるカラー パレット。*image*および含む*entriesCount*エントリー.

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* 名前空間 [Aspose.PSD](../../colorpalettehelper/)
* 組み立て [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

イメージにカラー パレットがない場合に、ラスター イメージからカラー パレットを取得します (イメージをパレット化します)。パレットが存在する場合は、計算を実行する代わりに使用されます.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | RasterImage | ラスター画像。 |
| destBounds | Rectangle | 宛先イメージの境界。 |
| entriesCount | Int32 | 必要なエントリがカウントされます。 |
| useImagePalette | Boolean | 設定されている場合、利用可能な場合は独自の画像パレットを使用します |

### 戻り値

から最も頻繁に使用される色から始まるカラー パレット。*image*および含む*entriesCount*エントリー.

### 関連項目

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* 名前空間 [Aspose.PSD](../../colorpalettehelper/)
* 組み立て [Aspose.PSD](../../../)


