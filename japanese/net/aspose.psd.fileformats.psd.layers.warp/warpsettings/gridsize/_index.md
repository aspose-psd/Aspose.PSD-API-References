---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD for .NET API Reference"
description: "WarpSettings プロパティ。ワープグリッドのサイズを取得または設定します。デフォルトは 1 です。"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

ワープグリッドのサイズを取得または設定します。デフォルトは 1 です。

```csharp
public Size GridSize { get; set; }
```

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

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


