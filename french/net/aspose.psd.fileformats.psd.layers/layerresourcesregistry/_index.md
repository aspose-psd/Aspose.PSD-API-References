---
title: "Classe LayerResourcesRegistry"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry classe. Définit le registre des ressources de calque pour le chargement des fichiers PSD"
type: docs
weight: 3790
url: /fr/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

Définit le registre des ressources de calque pour le chargement des fichiers PSD.

```csharp
public static class LayerResourcesRegistry
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Obtient les descripteurs enregistrés. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Obtient le premier descripteur d'ouvreur pris en charge. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtient le premier descripteur pris en charge par son nom de type. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Charge [`LayerResource`](../layerresource/) en utilisant le premier ouvreur trouvé adapté au *stream* spécifié. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Enregistre l'ouvreur. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Désenregistre l'ouvreur. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


