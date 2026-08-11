---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD for .NET API Reference"
description: "FillLayer メソッド。すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。透明度がない画像に使用した場合、すべての色が単一の色に置き換えられることに注意してください。"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorArgb | Int32 | 非透明色を置き換えるための新しいカラー ARGB 値。 |

## 例

次のコードは CMYK カラーモード 16 ビットのサポートと、Aspose.PSD.Graphics クラスを使用した描画機能を示しています。

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 関連項目

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


