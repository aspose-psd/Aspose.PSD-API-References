---
title: "Classe WarpSettings"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings. Paramètres du calque avec warp"
type: docs
weight: 4010
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

Paramètres du calque avec déformation.

```csharp
public class WarpSettings
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | Initialise une nouvelle instance de la classe `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | Initialise une nouvelle instance de la classe `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor_2)(PointF[], Rectangle) | Initialise une nouvelle instance de la classe `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor_3)(PointF[], Rectangle, WarpStyles) | Initialise une nouvelle instance de la classe `WarpSettings`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | Obtient ou définit les limites de l'image warp |
| [GridSize](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/) { get; set; } | Obtient ou définit la taille de la grille warp. La valeur par défaut est 1. |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | Points de maillage Photoshop |
| [RenderQuality](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/) { get; set; } | Obtient ou définit la valeur de la qualité de rendu warp - entre vitesse et qualité |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | Obtient ou définit la valeur de rotation |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | Obtient ou définit le style du warp |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | Obtient ou définit la valeur du warp |

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


