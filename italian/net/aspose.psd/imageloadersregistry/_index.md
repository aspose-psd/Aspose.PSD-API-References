---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageLoadersRegistry classe. Rappresenta il registro dei caricatori di immagini.
type: docs
weight: 4780
url: /it/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Rappresenta il registro dei caricatori di immagini.

```csharp
public static class ImageLoadersRegistry
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Ottiene i descrittori registrati. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Ottiene i formati di caricamento delle immagini registrati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Crea il primo caricatore trovato adatto per l'oggetto specificato*stream* e facoltativamente il*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Ottiene il primo descrittore supportato trovato adatto per l'elemento specificato*stream* e facoltativamente il*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Ottiene il primo formato di file supportato in base al nome del tipo. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Ottiene il primo descrittore supportato in base al relativo nome del tipo. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registra il descrittore del caricatore di immagini specificato. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registra il caricatore. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Annulla la registrazione del caricatore. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


