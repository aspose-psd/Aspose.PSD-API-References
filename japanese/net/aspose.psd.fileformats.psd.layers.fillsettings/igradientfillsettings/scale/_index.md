---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD for .NET API リファレンス
description: IGradientFillSettings 財産. スケールを取得または設定します
type: docs
weight: 100
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

スケールを取得または設定します。

```csharp
public int Scale { get; set; }
```

### プロパティ値

スケール.

### 例

次の例は、Scale プロパティを使用して FillLayer をグラデーションでスケーリングする方法を示しています。

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // 塗りつぶしレイヤーを取得
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // スケール値を更新
    settings.Scale = 200;
    fillLayer.Update(); // ピクセルデータを更新

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* interface [IGradientFillSettings](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* 組み立て [Aspose.PSD](../../../)


