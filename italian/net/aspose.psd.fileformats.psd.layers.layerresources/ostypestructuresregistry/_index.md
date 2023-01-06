---
title: OSTypeStructuresRegistry
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Rappresenta ilOSTypeStructure./ostypestructure registro risorse.
type: docs
weight: 2840
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
## OSTypeStructuresRegistry class

Rappresenta il[`OSTypeStructure`](../ostypestructure) registro risorse.

```csharp
public static class OSTypeStructuresRegistry
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors) { get; } | Ottiene i descrittori registrati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor)(Stream) | Ottiene il primo descrittore di apertura supportato. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename)(string) | Ottiene il primo descrittore supportato in base al nome del tipo. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor)(Stream) | Carichi[`OSTypeStructure`](../ostypestructure) utilizzando il primo apri trovato adatto per il specificato*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener)(IOSTypeStructureLoader) | Registra l'apri. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener)(IOSTypeStructureLoader) | Annulla la registrazione dell'apri. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->