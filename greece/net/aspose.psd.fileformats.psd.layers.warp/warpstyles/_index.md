---
title: "Enum WarpStyles"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Τύποι υποστηριζόμενων στυλ warp"
type: docs
weight: 4020
url: /el/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Τύποι υποστηριζόμενων στυλ παραμόρφωσης

```csharp
public enum WarpStyles
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | `0` | Το στυλ ορίζεται όταν το στρώμα δεν έχει παραμόρφωση |
| Custom | `1` | Στυλ με αυθαίρετη κίνηση σημείων |
| Arc | `2` | Στυλ τόξου του warp |
| ArcUpper | `3` | Στυλ άνω τόξου του warp |
| ArcLower | `4` | Στυλ κάτω τόξου του warp |
| Arch | `5` | Στυλ αψίδας του warp |
| Bulge | `6` | Στυλ διογκώματος του warp |
| Flag | `7` | Στυλ σημαίας του warp |
| Fish | `8` | Στυλ ψαριού του warp |
| Rise | `9` | Στυλ ανόδου του warp |
| Wave | `10` | Στυλ κυματισμού του warp |
| Twist | `11` | Τύπος στριψίματος του warp |
| Squeeze | `12` | Τύπος συμπίεσης του warp |
| Inflate | `13` | Τύπος φούσκας της παραμόρφωσης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να χειριστούμε το WarpSettings για να εκτελέσουμε μετασχηματισμό παραμόρφωσης στο SmartObjectLayer και στο TexLayer.

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

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


