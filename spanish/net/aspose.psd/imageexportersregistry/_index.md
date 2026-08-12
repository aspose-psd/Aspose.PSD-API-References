---
title: "Clase ImageExportersRegistry"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageExportersRegistry. Representa el registro de exportadores de imágenes"
type: docs
weight: 5100
url: /es/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Representa el registro de exportadores de imágenes.

```csharp
public static class ImageExportersRegistry
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Obtiene los descriptores de exportador registrados. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Obtiene los formatos de exportación registrados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Crea el primer exportador encontrado que sea adecuado para las opciones de guardado e imagen especificadas. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Obtiene el primer descriptor compatible encontrado que sea adecuado para las opciones de guardado e imagen especificadas. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Registra el descriptor de exportador de imágenes especificado. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Registra el exportador. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Anula el registro del exportador. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


