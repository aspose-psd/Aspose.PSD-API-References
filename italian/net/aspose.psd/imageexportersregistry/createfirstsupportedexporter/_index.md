---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: Aspose.PSD per riferimento API .NET
description: ImageExportersRegistry metodo. Crea il primo esportatore trovato adatto alle opzioni di salvataggio e allimmagine specificate.
type: docs
weight: 30
url: /it/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Image | L'immagine da esportare. |
| options | ImageOptionsBase | Le opzioni di salvataggio da utilizzare per l'esportazione. |

### Valore di ritorno

L'esportatore che supporta l'immagine specificata e salva le opzioni o null se non viene trovato tale esportatore.

### Osservazioni

Il primo esportatore sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* spazio dei nomi [Aspose.PSD](../../imageexportersregistry/)
* assemblea [Aspose.PSD](../../../)


