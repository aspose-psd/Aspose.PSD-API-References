---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD for .NET API Reference"
description: "WarpSettings コンストラクタ。WarpSettings クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

`[`WarpSettings`](../)` クラスの新しいインスタンスを初期化します。

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| meshPoints | PointF[] | ワープのメッシュポイント |
| bounds | Rectangle | ワープ画像の境界 |

## 例

次のコードは WarpSettings.GridSize プロパティのサポートを示しています。

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // ワープ設定を取得
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // 新しいサイズを設定
    // Photoshop の場合、値は 1 から 50 の間でなければならず、PSD ファイルを正しく保存できません。
    warpSettings.GridSize = new Size(100, 100);

    // 有効な値を設定
    warpSettings.GridSize = new Size(3, 3);

    // x3 グリッドでサンプルファイルをレンダリング
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### 関連項目

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

`[`WarpSettings`](../)` クラスの新しいインスタンスを初期化します。

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| meshPoints | PointF[] | ワープのメッシュポイント |
| bounds | Rectangle | ワープ画像の境界 |
| style | WarpStyles | ワープのスタイル |

## 例

次のコードは WarpSettings.GridSize プロパティのサポートを示しています。

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // ワープ設定を取得
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // 新しいサイズを設定
    // Photoshop の場合、値は 1 から 50 の間でなければならず、PSD ファイルを正しく保存できません。
    warpSettings.GridSize = new Size(100, 100);

    // 有効な値を設定
    warpSettings.GridSize = new Size(3, 3);

    // x3 グリッドでサンプルファイルをレンダリング
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### 関連項目

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

`[`WarpSettings`](../)` クラスの新しいインスタンスを初期化します。

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Warp 設定が適用された PS アイテム |
| bounds | Rectangle | ワープ画像の境界 |

### 関連項目

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

`[`WarpSettings`](../)` クラスの新しいインスタンスを初期化します。

```csharp
public WarpSettings(PlacedResource placedResource)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | PlacedResource | ワープ設定があるリソース |

### 関連項目

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


