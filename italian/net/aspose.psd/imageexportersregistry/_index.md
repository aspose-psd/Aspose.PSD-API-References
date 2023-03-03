---
title: Class ImageExportersRegistry
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageExportersRegistry classe. Rappresenta il registro degli esportatori di immagini.
type: docs
weight: 4630
url: /it/net/aspose.psd/imageexportersregistry/
---
## ImageExportersRegistry class

Rappresenta il registro degli esportatori di immagini.

```csharp
public static class ImageExportersRegistry
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Ottiene i descrittori dell'esportatore registrato. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Ottiene i formati di esportazione registrati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Ottiene il primo descrittore supportato adatto per le opzioni di salvataggio e l'immagine specificate. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Registra il descrittore dell'esportatore di immagini specificato. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Registra l'esportatore. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Annulla la registrazione dell'esportatore. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


