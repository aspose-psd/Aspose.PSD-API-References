---
title: LinkedLayersManager.LinkLayers
second_title: Référence de l'API Aspose.PSD pour .NET
description: LinkedLayersManager méthode. Lie les couches dentrée et renvoie LingGroupId.
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
## LinkedLayersManager.LinkLayers method

Lie les couches d'entrée et renvoie LingGroupId.

```csharp
public short LinkLayers(Layer[] layers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| layers | Layer[] | Les couches. |

### Return_Value

L'identifiant du groupe de liens.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Les calques sont nuls. |
| ArgumentException | Le nombre de couches doit être supérieur à 1. |
| ArgumentException | Le conteneur de chaque calque doit être le même que le PsdImage actuel. |

### Exemples

L'exemple suivant montre comment vous pouvez manipuler des calques liés dans Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // lie toutes les couches dans un groupe lié
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // obtient l'identifiant d'une couche
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // obtient toutes les couches liées par l'identifiant du groupe de liens.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // dissocie chaque calque du groupe
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // récupère NULL pour un ID de groupe de liens qui n'a pas de couches dans le groupe.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Voir également

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* Assemblée [Aspose.PSD](../../../)


