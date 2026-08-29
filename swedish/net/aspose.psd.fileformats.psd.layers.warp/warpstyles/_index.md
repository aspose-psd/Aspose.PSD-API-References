---
title: "Enum WarpStyles"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Typer av stöd för warp‑stilar som stöds"
type: docs
weight: 4020
url: /sv/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Typer av warp-stilar som stöds

```csharp
public enum WarpStyles
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Stilen sätts när lagret är utan deformation |
| Custom | `1` | Stil med godtycklig rörelse av punkter |
| Arc | `2` | Bågstil för warp |
| ArcUpper | `3` | Övre bågstil för warp |
| ArcLower | `4` | Nedre bågstil för warp |
| Arch | `5` | Båge‑stil för warp |
| Bulge | `6` | Bukt‑stil för warp |
| Flag | `7` | Flaggstil för warp |
| Fish | `8` | Fiskstil för warp |
| Rise | `9` | Uppstigningsstil för warp |
| Wave | `10` | Vågstil för warp |
| Twist | `11` | Vridningstyp för warp |
| Squeeze | `12` | Komprimeringstyp för warp |
| Inflate | `13` | Uppblåstyp för warp |

## Exempel

Följande kod visar hur man manipulerar WarpSettings för att utföra warp‑transformation på SmartObjectLayer och TexLayer.

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

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


