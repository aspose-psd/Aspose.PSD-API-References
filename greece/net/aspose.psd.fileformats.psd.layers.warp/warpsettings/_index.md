---
title: "Κλάση WarpSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings κλάση. Παράμετροι του στρώματος με παραμόρφωση"
type: docs
weight: 4010
url: /el/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

Παράμετροι του στρώματος με παραμόρφωση

```csharp
public class WarpSettings
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor_2)(PointF[], Rectangle) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor_3)(PointF[], Rectangle, WarpStyles) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `WarpSettings`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | Λαμβάνει ή ορίζει τα όρια της εικόνας παραμόρφωσης |
| [GridSize](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος του πλέγματος παραμόρφωσης. Η προεπιλογή είναι 1. |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | Σημεία πλέγματος Photoshop |
| [RenderQuality](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/) { get; set; } | Λαμβάνει ή ορίζει την τιμή της ποιότητας απόδοσης παραμόρφωσης - μεταξύ ταχύτητας και ποιότητας |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | Λαμβάνει ή ορίζει την τιμή περιστροφής |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | Λαμβάνει ή ορίζει το στυλ της παραμόρφωσης |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | Λαμβάνει ή ορίζει την τιμή της παραμόρφωσης |

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


