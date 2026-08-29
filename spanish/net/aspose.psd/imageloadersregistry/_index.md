---
title: "Clase ImageLoadersRegistry"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageLoadersRegistry. Representa el registro de cargadores de imágenes"
type: docs
weight: 5270
url: /es/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Representa el registro de cargadores de imágenes.

```csharp
public static class ImageLoadersRegistry
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Obtiene los descriptores registrados. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Obtiene los formatos de carga de imágenes registrados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Crea el primer cargador encontrado que sea adecuado para el *stream* especificado y, opcionalmente, para los *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Obtiene el primer descriptor compatible encontrado que sea adecuado para el *stream* especificado y, opcionalmente, para los *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Obtiene el primer formato de archivo compatible por su nombre de tipo. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registra el descriptor de cargador de imágenes especificado. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registra el cargador. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Anula el registro del cargador. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


