---
title: "Classe ImfxResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ImfxResource. Ressource Imfx Multieffects."
type: docs
weight: 2850
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/imfxresource/
---
{{< psd/tize >}}
## ImfxResource class

Ressource Imfx (ressource multi-effets)

```csharp
public sealed class ImfxResource : BaseFxResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImfxResource](imfxresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Obtient la version du descripteur. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/imfxresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant démontre la prise en charge de la ressource multi‑effets.

```csharp
[C#]

// L'image PSD contient 2 effets d'ombre portée.
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // Il rend l'image PSD avec 2 effets d'ombre portée.
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Il ajoute un troisième effet d'ombre portée.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // Il rend l'image PSD avec 3 effets d'ombre portée
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // La ressource imfx est utilisée si le calque contient plusieurs effets du même type.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Il supprime tous les effets
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // Il rend l'image PSD avec 1 effet d'ombre portée (les autres ont été supprimés)
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // La ressource lfx2 est utilisée si le calque ne contient pas plusieurs effets du même type.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Voir aussi

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


