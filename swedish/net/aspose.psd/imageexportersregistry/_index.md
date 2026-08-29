---
title: "Klass ImageExportersRegistry"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageExportersRegistry klass. Representerar registret för bildexportörer"
type: docs
weight: 5100
url: /sv/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Representerar registret för bildexportörer.

```csharp
public static class ImageExportersRegistry
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Hämtar de registrerade exportörsbeskrivningarna. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Hämtar de registrerade exportformaten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Hämtar den först hittade stödjade descriptor som är lämplig för de angivna sparalternativen och bilden. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Registrerar den angivna bildexportör descriptorn. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Registrerar exportören. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Avregistrerar exportören. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


