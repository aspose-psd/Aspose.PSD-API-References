---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD per riferimento API .NET
description: ImageExportersRegistry metodo. Ottiene il primo descrittore supportato adatto per le opzioni di salvataggio e limmagine specificate.
type: docs
weight: 40
url: /it/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Ottiene il primo descrittore supportato adatto per le opzioni di salvataggio e l'immagine specificate.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Image | L'immagine da esportare. |
| options | ImageOptionsBase | Le opzioni. |

### Valore di ritorno

Il descrittore dell'esportatore che supporta l'immagine specificata e salva le opzioni o null se non viene trovato tale descrittore.

### Osservazioni

Il descrittore del primo esportatore sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* spazio dei nomi [Aspose.PSD](../../imageexportersregistry/)
* assemblea [Aspose.PSD](../../../)


