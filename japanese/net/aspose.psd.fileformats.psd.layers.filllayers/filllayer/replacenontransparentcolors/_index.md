---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD for .NET API リファレンス
description: FillLayer 方法. すべての不透明な色を新しい色に置き換え元のアルファ値を維持して滑らかなエッジを保存します
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

すべての不透明な色を新しい色に置き換え、元のアルファ値を維持して滑らかなエッジを保存します。

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newColorArgb | Int32 | 透明でない色を置き換える新しい色の ARGB 値。 |

### 例

次のコードは、CMYK ColorMode 16 ビットのサポートと、Aspose.PSD.Graphics クラスを使用した描画機能を示しています。

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### 関連項目

* class [FillLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 組み立て [Aspose.PSD](../../../)


