---
title: "Classe GrdmResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource. Classe GrdmResource. Contient des informations sur le calque GradientMap"
type: docs
weight: 2770
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

Classe GrdmResource. Contient des informations sur le calque Gradient-Map.

```csharp
public class GrdmResource : AdjustmentLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GrdmResource](grdmresource/)(int) | Initialise une nouvelle instance de la classe `GrdmResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | Modèle de couleur. Lorsque le 'Gradient type' = 'Noise', nous pouvons assigner le 'Color Model' à RGB/SHB/LAB (3/4/6). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | Obtient ou définit les points de couleur. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | Le dégradé est dithérisé. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | Nombre d'expansion ( = 2 pour Photoshop 6.0). |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | Le mode pour ce dégradé détermine 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | Nom du dégradé : chaîne Unicode, remplie. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | Interpolation. Détermine la douceur lorsque le 'Gradient Type' = 'Solid' (GradientMode = 0). |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/) { get; set; } | Obtient ou définit la méthode d'interpolation du dégradé. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; set; } | Couleur maximale du format PixelDataFormat.Rgba64Bpp. La couleur possède des canaux ARGB, chaque canal étant sur 16 bits. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; set; } | Couleur minimale du format PixelDataFormat.Rgba64Bpp. La couleur possède des canaux ARGB, chaque canal étant sur 16 bits. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour cette ressource. La version 3 est nécessaire lorsque la méthode d'interpolation est stockée explicitement. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | Le dégradé est inversé. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | Le seed du nombre aléatoire utilisé pour générer les couleurs du dégradé Noise. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | Facteur de rugosité. Lorsque le 'Gradient type' = 'Noise', nous pouvons assigner la 'Roughness' (0 - 2048). |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | Indicateur d'affichage de la transparence. Lorsque le 'Gradient type' = 'Noise', nous pouvons définir 'Add transparency' sur vrai. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | Obtient ou définit les points de transparence. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | Indicateur d'utilisation de la couleur vectorielle. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | Enregistre les données de la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant démontre la prise en charge de la ressource GrdmResource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // vérifier les valeurs actuelles
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Couleur rouge pour le deuxième point de couleur du dégradé
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // vérifier les valeurs modifiées
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Voir aussi

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


