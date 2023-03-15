---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD per riferimento API .NET
description: ImageLoadersRegistry metodo. Ottiene il primo descrittore supportato trovato adatto per lelemento specificatostream e facoltativamente illoadOptions .
type: docs
weight: 40
url: /it/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Ottiene il primo descrittore supportato trovato adatto per l'elemento specificato*stream* e facoltativamente il*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| loadOptions | LoadOptions | Le opzioni di caricamento. |

### Valore di ritorno

Il descrittore del caricatore che supporta il file specificato*stream* E*loadOptions* o null se non viene trovato tale descrittore.

### Osservazioni

Il primo descrittore del caricatore sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* spazio dei nomi [Aspose.PSD](../../imageloadersregistry/)
* assemblea [Aspose.PSD](../../../)


