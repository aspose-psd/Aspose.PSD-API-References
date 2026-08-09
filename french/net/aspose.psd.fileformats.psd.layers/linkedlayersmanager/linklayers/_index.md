---
title: "LinkedLayersManager.LinkLayers"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LinkedLayersManager. Lie les calques d'entrée et renvoie LingGroupId"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
{{< psd/tize >}}
## LinkedLayersManager.LinkLayers method

Lie les calques d'entrée et renvoie LingGroupId.

```csharp
public short LinkLayers(Layer[] layers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| layers | Layer[] | Les calques. |

### Valeur de retour

L'identifiant du groupe de liaison.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Les calques sont nuls. |
| ArgumentException | Le nombre de calques doit être supérieur à 1. |
| ArgumentException | Le conteneur de chaque calque doit être le même que le PsdImage actuel. |

## Exemples

L'exemple suivant montre comment vous pouvez manipuler les calques liés dans Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Chargez une image existante dans une instance de la classe PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // lier tous les calques dans un groupe lié
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // obtient l'ID d'un calque
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // obtient tous les calques liés par identifiant de groupe de liens.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // délier chaque calque du groupe
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // renvoie NULL pour un ID de groupe de liens qui n'a aucun calque dans le groupe.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Voir aussi

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


