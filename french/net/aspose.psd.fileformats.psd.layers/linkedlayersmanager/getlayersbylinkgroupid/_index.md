---
title: "LinkedLayersManager.GetLayersByLinkGroupId"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LinkedLayersManager. Obtient les calques par identifiant de groupe de liaison"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLayersByLinkGroupId method

Obtient les calques par identifiant de groupe de liens.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| linkGroupId | Int16 | L'identifiant du groupe de liaison. |

### Valeur de retour

Le tableau de calques.

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


