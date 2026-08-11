---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD for .NET API Reference"
description: "IGradientFillSettings プロパティ。正規化されたグラデーションスケール（パーセント）を取得または設定します"
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

**normalized** グラデーションスケール（パーセンテージ）を取得または設定します。

```csharp
public int Scale { get; set; }
```

### Property Value

スケールです。

## 例

次の例は、Scale プロパティを使用してグラデーション付きの FillLayer をスケーリングする方法を示しています。

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // フィルレイヤーを取得する
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

    // スケール値を更新する
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


