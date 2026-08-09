---
title: "PsdImage.AddLayerGroup"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Ajoute le groupe de calques"
type: docs
weight: 400
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

Ajoute le groupe de calques.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| groupName | String | Nom du groupe. |
| index | Int32 | L'index du calque après lequel insérer. |
| startBehaviour | Booléen | si défini sur `true` [start behaviour] alors le groupe sera en état ouvert au démarrage, sinon en état minimisé. |

### Valeur de retour

Ouverture du groupe de calques

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | L'index doit être dans les limites du nombre de calques |

### Voir aussi

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


