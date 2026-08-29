---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LayerResourcesRegistry. Charge LayerResource en utilisant le premier ouvreur trouvé adapté au flux spécifié."
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Charge [`LayerResource`](../../layerresource/) en utilisant le premier ouvreur trouvé adapté au *flux* spécifié.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| psdVersion | Int32 | La version PSD. |

### Valeur de retour

Le [`LayerResource`](../../layerresource/) chargé ou null si aucun ouvreur n'est trouvé.

## Remarques

Le premier ouvreur sera en fait le dernier enregistré.

### Voir aussi

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


