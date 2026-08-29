---
title: "枚举 WarpStyles"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles 枚举。支持的扭曲样式类型"
type: docs
weight: 4020
url: /zh/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

支持的变形样式类型

```csharp
public enum WarpStyles
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 当图层未变形时设置此样式 |
| Custom | `1` | 点的任意移动样式 |
| Arc | `2` | 弧形扭曲样式 |
| ArcUpper | `3` | 上弧形扭曲样式 |
| ArcLower | `4` | 下弧形扭曲样式 |
| Arch | `5` | 拱形扭曲样式 |
| Bulge | `6` | 凸起扭曲样式 |
| Flag | `7` | 旗帜扭曲样式 |
| Fish | `8` | 鱼形扭曲样式 |
| Rise | `9` | 上升扭曲样式 |
| Wave | `10` | 波浪扭曲样式 |
| Twist | `11` | 扭转扭曲类型 |
| Squeeze | `12` | 压缩扭曲类型 |
| Inflate | `13` | 膨胀扭曲类型 |

## 示例

以下代码演示如何操作 WarpSettings 对 SmartObjectLayer 和 TexLayer 进行扭曲变换。

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

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


