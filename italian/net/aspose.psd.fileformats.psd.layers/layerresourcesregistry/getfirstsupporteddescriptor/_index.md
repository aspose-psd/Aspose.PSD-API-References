---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD per riferimento API .NET
description: LayerResourcesRegistry metodo. Ottiene il primo descrittore di apertura supportato.
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Ottiene il primo descrittore di apertura supportato.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| psdVersion | Int32 | La versione PSD. |

### Valore di ritorno

Il descrittore del caricatore di risorse del livello o null se nessun descrittore del caricatore è supportato per tale flusso.

### Osservazioni

Il primo caricatore sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* assemblea [Aspose.PSD](../../../)


