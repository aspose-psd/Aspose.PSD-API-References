---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LayerResourcesRegistry. Obtient le premier descripteur d'ouverture pris en charge."
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Obtient le premier descripteur d'ouvreur pris en charge.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| psdVersion | Int32 | La version PSD. |

### Valeur de retour

Le descripteur de chargeur de ressource de couche ou null si aucun descripteur de chargeur n'est pris en charge pour ce flux.

## Remarques

Le premier chargeur sera en fait le dernier enregistré.

### Voir aussi

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


