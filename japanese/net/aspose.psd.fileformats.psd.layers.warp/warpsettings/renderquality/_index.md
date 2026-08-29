---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD for .NET API Reference"
description: "WarpSettings プロパティ。速度と品質の間でワープレンダー品質の値を取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

ワープのレンダリング品質の値を取得または設定します - 速度と品質の間

```csharp
public RenderQuality RenderQuality { get; set; }
```

## 例

次のコードは、WarpSettings.RenderQuality プロパティを使用してワープ変形を構成する方法を示しています。

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Smart Layer から WarpSettings を取得します
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // ワープ処理領域のサイズを設定します
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // ここにエラーはないはずです
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 関連項目

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


