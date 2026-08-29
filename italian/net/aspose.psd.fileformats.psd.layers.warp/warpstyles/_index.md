---
title: "Enum WarpStyles"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Tipi di stili di warp supportati"
type: docs
weight: 4020
url: /it/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Tipi di stili warp supportati

```csharp
public enum WarpStyles
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Lo stile è impostato quando il livello non ha deformazione. |
| Custom | `1` | Stile con movimento arbitrario dei punti |
| Arc | `2` | Stile ad arco del warp |
| ArcUpper | `3` | Stile ad arco superiore del warp |
| ArcLower | `4` | Stile ad arco inferiore del warp |
| Arch | `5` | Stile a volta del warp |
| Bulge | `6` | Stile a rigonfiamento del warp |
| Flag | `7` | Stile a bandiera del warp |
| Fish | `8` | Stile a pesce del warp |
| Rise | `9` | Stile di sollevamento del warp |
| Wave | `10` | Stile Wave del warp |
| Twist | `11` | Tipo Twist del warp |
| Squeeze | `12` | Tipo Squeeze del warp |
| Inflate | `13` | Tipo Inflate del warp |

## Esempi

Il codice seguente dimostra come manipolare WarpSettings per eseguire la trasformazione di warp su SmartObjectLayer e TexLayer.

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

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


