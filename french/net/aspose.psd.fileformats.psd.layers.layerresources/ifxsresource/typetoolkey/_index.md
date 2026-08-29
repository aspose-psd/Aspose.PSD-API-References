---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "IfxsResource champ. La clé d'information de l'outil de type"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

La clé d'information de l'outil de type.

```csharp
public const int TypeToolKey;
```

## Exemples

Le code suivant montre la prise en charge de IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // L'exemple comporte 2 calques de groupe avec effets
    // Calque de groupe avec un effet
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Calque de groupe avec plusieurs effets
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Obtenez le nombre d'effets et vérifiez leur quantité
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Un effet dans le calque de groupe se trouve dans la ressource 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Deux effets ou plus dans un calque de groupe se trouvent dans la ressource 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Ajoutez une troisième ombre à un calque de groupe avec plusieurs effets
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Voir aussi

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


