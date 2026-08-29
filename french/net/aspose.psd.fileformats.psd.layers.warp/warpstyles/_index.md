---
title: "Enum WarpStyles"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Types de styles de warp pris en charge"
type: docs
weight: 4020
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Types de styles de déformation supportés.

```csharp
public enum WarpStyles
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Le style est défini lorsque le calque n'est pas déformé |
| Custom | `1` | Style avec déplacement arbitraire des points |
| Arc | `2` | Style d'arc du warp |
| ArcUpper | `3` | Style d'arc supérieur du warp |
| ArcLower | `4` | Style d'arc inférieur du warp |
| Arch | `5` | Style d'arche du warp |
| Bulge | `6` | Style de renflement du warp |
| Flag | `7` | Style de drapeau du warp |
| Fish | `8` | Style de poisson du warp |
| Rise | `9` | Style de montée du warp |
| Wave | `10` | Style d'onde du warp |
| Twist | `11` | Type de torsion du warp |
| Squeeze | `12` | Type d'écrasement du warp |
| Inflate | `13` | Type d'inflation du warp |

## Exemples

Le code suivant montre comment manipuler WarpSettings pour effectuer une transformation de déformation sur SmartObjectLayer et TexLayer.

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

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


