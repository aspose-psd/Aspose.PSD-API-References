---
title: "列挙型 WarpStyles"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles 列挙型。サポートされているワープスタイルの種類"
type: docs
weight: 4020
url: /ja/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

サポートされているワープスタイルのタイプです。

```csharp
public enum WarpStyles
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | レイヤーが変形していないときにこのスタイルが設定されます |
| Custom | `1` | ポイントの任意の移動によるスタイル |
| Arc | `2` | ワープのアークスタイル |
| ArcUpper | `3` | ワープの上部アークスタイル |
| ArcLower | `4` | ワープの下部アークスタイル |
| Arch | `5` | ワープのアーチスタイル |
| Bulge | `6` | ワープの膨らみスタイル |
| Flag | `7` | ワープのフラッグスタイル |
| Fish | `8` | ワープの魚スタイル |
| Rise | `9` | ワープの上昇スタイル |
| Wave | `10` | ワープの波スタイル |
| Twist | `11` | ワープのねじれタイプ |
| Squeeze | `12` | ワープの圧縮タイプ |
| Inflate | `13` | ワープの膨張タイプ |

## 例

次のコードは、WarpSettings を操作して SmartObjectLayer と TexLayer に対してワープ変換を行う方法を示しています。

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


