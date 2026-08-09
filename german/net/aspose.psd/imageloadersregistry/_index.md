---
title: "Klasse ImageLoadersRegistry"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageLoadersRegistry Klasse. Stellt das Registrierungsverzeichnis der Bildlader dar"
type: docs
weight: 5270
url: /de/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Stellt das Register der Bild‑Lader dar.

```csharp
public static class ImageLoadersRegistry
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Ermittelt die registrierten Deskriptoren. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Liest die registrierten Bildladeformate. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Erstellt den zuerst gefundenen Loader, der für den angegebenen *stream* geeignet ist und optional die *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für den angegebenen *stream* geeignet ist und optional die *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Ruft das erste unterstützte Dateiformat anhand seines Typnamens ab. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Ermittelt den ersten unterstützten Deskriptor anhand seines Typnamens. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registriert den angegebenen Bildlader-Deskriptor. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registriert den Lader. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Meldet den Lader ab. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


