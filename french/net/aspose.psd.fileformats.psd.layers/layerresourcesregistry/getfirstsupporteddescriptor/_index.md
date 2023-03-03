---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerResourcesRegistry méthode. Obtient le premier descripteur douverture pris en charge.
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Obtient le premier descripteur d'ouverture pris en charge.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| psdVersion | Int32 | La version PSD. |

### Return_Value

Le descripteur de chargeur de ressource de couche ou null si aucun descripteur de chargeur n'est pris en charge pour ce flux.

### Remarques

Le premier chargeur sera en fait le dernier enregistré.

### Voir également

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* Assemblée [Aspose.PSD](../../../)


