---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD per riferimento API .NET
description: ImageLoadersRegistry metodo. Crea il primo caricatore trovato adatto per loggetto specificatostream e facoltativamente illoadOptions .
type: docs
weight: 30
url: /it/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Crea il primo caricatore trovato adatto per l'oggetto specificato*stream* e facoltativamente il*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| loadOptions | LoadOptions | Le opzioni di caricamento. |

### Valore di ritorno

Il caricatore che supporta il file specificato*stream* E*loadOptions* o null se non viene trovato alcun caricatore di questo tipo.

### Osservazioni

Il primo caricatore sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* spazio dei nomi [Aspose.PSD](../../imageloadersregistry/)
* assemblea [Aspose.PSD](../../../)


