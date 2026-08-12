---
title: "Klass ImageLoadersRegistry"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageLoadersRegistry-klass. Representerar registret för bildladdare"
type: docs
weight: 5270
url: /sv/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Representerar registret för bildladdare.

```csharp
public static class ImageLoadersRegistry
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Hämtar de registrerade beskrivarna. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Hämtar de registrerade bildladdningsformaten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Skapar den första hittade laddaren som är lämplig för den angivna *stream* och eventuellt *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Hämtar den första hittade stödjade beskrivaren som är lämplig för den angivna *stream* och eventuellt *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Hämtar det första stödjade filformatet efter dess typnamn. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Hämtar den första stödda beskrivaren efter dess typnamn. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registrerar den angivna bildladdar-beskrivaren. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registrerar laddaren. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Avregistrerar laddaren. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


