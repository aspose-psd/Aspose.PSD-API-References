---
title: "Enum WarpStyles"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Desteklenen warp stilleri türleri"
type: docs
weight: 4050
url: /tr/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Desteklenen warp stillerinin tipleri

```csharp
public enum WarpStyles
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | Stil, katman deformasyonsuz olduğunda ayarlanır |
| Custom | `1` | Nokta hareketlerinin rastgele olduğu stil |
| Arc | `2` | Warp'ın yay stili |
| ArcUpper | `3` | Warp'ın üst yay stili |
| ArcLower | `4` | Warp'ın alt yay stili |
| Arch | `5` | Warp'ın kemer stili |
| Bulge | `6` | Warp'ın şişme stili |
| Flag | `7` | Warp'ın bayrak stili |
| Fish | `8` | Warp'ın balık stili |
| Rise | `9` | Warp'ın yükselme stili |
| Wave | `10` | Warp'ın dalga stili |
| Twist | `11` | Warp'ın bükülme tipi |
| Squeeze | `12` | Warp'ın sıkıştırma tipi |
| Inflate | `13` | Bükülme türünü şişir |

## Örnekler

Aşağıdaki kod, WarpSettings'i manipüle ederek SmartObjectLayer ve TexLayer üzerinde çarpıtma dönüşümünü nasıl yapacağınızı gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


