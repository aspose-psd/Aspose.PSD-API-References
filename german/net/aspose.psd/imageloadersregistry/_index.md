---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ImageLoadersRegistry klas. Repräsentiert die ImageLoaderRegistrierung.
type: docs
weight: 4780
url: /de/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Repräsentiert die Image-Loader-Registrierung.

```csharp
public static class ImageLoadersRegistry
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Ruft die registrierten Deskriptoren ab. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Ruft die registrierten Bildladeformate ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Erstellt den ersten gefundenen Lader, der für die angegebenen geeignet ist*stream* und optional die*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Ruft den ersten gefundenen unterstützten Deskriptor ab, der für den angegebenen geeignet ist*stream* und optional die*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Ruft das erste unterstützte Dateiformat anhand seines Typnamens ab. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Ruft den ersten unterstützten Deskriptor anhand seines Typnamens ab. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registriert den angegebenen Image-Loader-Deskriptor. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registriert den Loader. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Hebt die Registrierung des Loaders auf. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


