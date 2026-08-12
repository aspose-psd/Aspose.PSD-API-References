---
title: "Enum WarpStyles"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Typen van ondersteunde warp-stijlen"
type: docs
weight: 4020
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Typen van ondersteunde warpstijlen

```csharp
public enum WarpStyles
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | De stijl wordt ingesteld wanneer de laag zonder vervorming is. |
| Custom | `1` | Stijl met willekeurige verplaatsing van punten |
| Arc | `2` | Boogstijl van warp |
| ArcUpper | `3` | Bovenboogstijl van warp |
| ArcLower | `4` | Onderboogstijl van warp |
| Arch | `5` | Arch-stijl van warp |
| Bulge | `6` | Bultstijl van warp |
| Flag | `7` | Vlagstijl van warp |
| Fish | `8` | Vissestijl van warp |
| Rise | `9` | Stijgende stijl van warp |
| Wave | `10` | Golfstijl van warp |
| Twist | `11` | Draai-type van warp |
| Squeeze | `12` | Pers-type van warp |
| Inflate | `13` | Opblazen-type van warp |

## Voorbeelden

De volgende code toont hoe je WarpSettings kunt manipuleren om een warp-transformatie uit te voeren op SmartObjectLayer en TexLayer.

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

### Zie ook

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


