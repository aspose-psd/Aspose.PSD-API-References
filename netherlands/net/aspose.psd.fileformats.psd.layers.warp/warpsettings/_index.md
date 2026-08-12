---
title: "Klasse WarpSettings"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings klasse. Parameters van laag met warp"
type: docs
weight: 4010
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

Parameters van laag met warp

```csharp
public class WarpSettings
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | Initialiseert een nieuw exemplaar van de `WarpSettings` klasse. |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | Initialiseert een nieuw exemplaar van de `WarpSettings` klasse. |
| [WarpSettings](warpsettings/#constructor_2)(PointF[], Rectangle) | Initialiseert een nieuw exemplaar van de `WarpSettings` klasse. |
| [WarpSettings](warpsettings/#constructor_3)(PointF[], Rectangle, WarpStyles) | Initialiseert een nieuw exemplaar van de `WarpSettings` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | Haalt op of stelt de grenzen van de warp-afbeelding in |
| [GridSize](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/) { get; set; } | Haalt op of stelt de grootte van het warp-rooster in. Standaard is 1. |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | Photoshop-meshpunten |
| [RenderQuality](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/) { get; set; } | Haalt op of stelt de waarde van warp-renderkwaliteit in - tussen snelheid en kwaliteit |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | Haalt op of stelt de rotatiewaarde in |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | Haalt op of stelt de stijl van warp in |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | Haalt op of stelt de waarde van warp in |

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


