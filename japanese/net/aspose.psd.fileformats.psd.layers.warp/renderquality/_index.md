---
title: "列挙型 RenderQuality"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality 列挙型。ワープのレンダリング品質を説明します"
type: docs
weight: 3990
url: /ja/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

ワープのレンダリング品質を説明します。

```csharp
public enum RenderQuality
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Turbo | `4` | 最速のオプションですが、品質が低下します。 |
| VeryFast | `18` | 高速が必要な場合、小さな曲率に適している可能性があります。 |
| Fast | `35` | 品質のわずかな低下でレンダリングを高速化できます。 |
| Normal | `60` | ほとんどの曲率に推奨される値 |
| Good | `130` | 標準品質より高く、速度は遅くなります。強い歪み向けに推奨されます。 |
| Excellent | `260` | 最も遅いオプションです。強い歪みと高解像度向けに推奨されます。 |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


