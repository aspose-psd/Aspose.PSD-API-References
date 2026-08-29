---
title: "Klasse ImageExportersRegistry"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageExportersRegistry‑Klasse. Stellt das Registry der Bildexporteure dar"
type: docs
weight: 5100
url: /de/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Stellt das Register der Bild-Exportierer dar.

```csharp
public static class ImageExportersRegistry
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Liefert die registrierten Exporter‑Deskriptoren. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Liefert die registrierten Exportformate. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Liefert den zuerst gefundenen unterstützten Deskriptor, der für die angegebenen Speicheroptionen und das Bild geeignet ist. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Registriert den angegebenen Bildexporter‑Deskriptor. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Registriert den Exporter. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Meldet den Exporter ab. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


