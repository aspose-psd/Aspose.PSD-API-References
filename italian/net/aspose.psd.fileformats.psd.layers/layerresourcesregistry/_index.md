---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry classe. Definisce il registro delle risorse del layer per il caricamento dei file PSD.
type: docs
weight: 3390
url: /it/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Definisce il registro delle risorse del layer per il caricamento dei file PSD.

```csharp
public static class LayerResourcesRegistry
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Ottiene i descrittori registrati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Ottiene il primo descrittore di apertura supportato. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Ottiene il primo descrittore supportato in base al relativo nome del tipo. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Carichi[`LayerResource`](../layerresource/) utilizzando il primo dispositivo di apertura trovato adatto allo specificato*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Registra l'apri. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Annulla la registrazione dell'apri. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assemblea [Aspose.PSD](../../)


