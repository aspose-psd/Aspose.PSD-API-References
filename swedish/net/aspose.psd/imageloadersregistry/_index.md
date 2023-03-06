---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageLoadersRegistry klass. Representerar bildladdarens register.
type: docs
weight: 4780
url: /sv/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Representerar bildladdarens register.

```csharp
public static class ImageLoadersRegistry
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Hämtar de registrerade beskrivningarna. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Hämtar de registrerade bildladdningsformaten. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Skapar den första hittade laddaren som är lämplig för den specificerade*stream* och valfritt*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Får den näve som stöds beskrivaren som är lämplig för den angivna*stream* och valfritt*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Hämtar det första filformatet som stöds efter dess typnamn. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Hämtar den första beskrivningen som stöds efter dess typnamn. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registrerar den angivna bildladdningsbeskrivningen. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registrerar laddaren. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Avregistrerar laddaren. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


