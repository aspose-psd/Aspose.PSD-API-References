---
title: "Enum WarpStyles"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Unterstützte Warp‑Stilarten"
type: docs
weight: 4020
url: /de/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Typen der unterstützten Warp-Stile.

```csharp
public enum WarpStyles
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Der Stil wird festgelegt, wenn die Ebene ohne Verzerrung ist. |
| Custom | `1` | Stil mit beliebiger Punktbewegung |
| Arc | `2` | Bogenstil der Verzerrung |
| ArcUpper | `3` | Oberer Bogenstil der Verzerrung |
| ArcLower | `4` | Unterer Bogenstil der Verzerrung |
| Arch | `5` | Bogenstil der Verzerrung |
| Bulge | `6` | Wölbungsstil der Verzerrung |
| Flag | `7` | Flaggenstil der Verzerrung |
| Fish | `8` | Fischstil der Verzerrung |
| Rise | `9` | Aufstiegstil der Verzerrung |
| Wave | `10` | Wellenstil der Verzerrung |
| Twist | `11` | Drehtyp der Verzerrung |
| Squeeze | `12` | Quetschtyp der Verzerrung |
| Inflate | `13` | Aufblähtyp der Verzerrung |

## Beispiele

Der folgende Code zeigt, wie man WarpSettings manipuliert, um eine Warp-Transformation auf SmartObjectLayer und TexLayer durchzuführen.

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

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


