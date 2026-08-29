---
title: "Classe OSTypeStructuresRegistry"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry. Représente le registre des ressources OSTypeStructure"
type: docs
weight: 3200
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

Représente le registre des ressources [`OSTypeStructure`](../ostypestructure/).

```csharp
public static class OSTypeStructuresRegistry
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | Obtient les descripteurs enregistrés. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | Obtient le premier descripteur d'ouvreur pris en charge. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtient le premier descripteur pris en charge par son nom de type. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | Charge [`OSTypeStructure`](../ostypestructure/) en utilisant le premier ouvreur trouvé adapté au *stream* spécifié. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | Enregistre l'ouvreur. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | Désenregistre l'ouvreur. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


