---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageLoadersRegistry klas. Vertegenwoordigt het register voor het laden van afbeeldingen.
type: docs
weight: 4780
url: /nl/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Vertegenwoordigt het register voor het laden van afbeeldingen.

```csharp
public static class ImageLoadersRegistry
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Haalt de geregistreerde descriptors op. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Haalt de geregistreerde indelingen voor het laden van afbeeldingen op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Creëert de eerst gevonden loader die geschikt is voor de gespecificeerde*stream* en eventueel de*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Haalt de eerste gevonden ondersteunde descriptor op die geschikt is voor de gespecificeerde*stream* en eventueel de*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Haalt het eerste ondersteunde bestandsformaat op door zijn typenaam. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Haalt de eerste ondersteunde descriptor op met zijn typenaam. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registreert de opgegeven afbeeldingsladerdescriptor. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registreert de lader. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Registreert de lader. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


