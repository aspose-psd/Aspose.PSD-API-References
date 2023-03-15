---
title: Class ImageLoadersRegistry
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ImageLoadersRegistry clase. Representa el registro de cargadores de imágenes.
type: docs
weight: 4780
url: /es/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Representa el registro de cargadores de imágenes.

```csharp
public static class ImageLoadersRegistry
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Obtiene los descriptores registrados. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Obtiene los formatos de carga de imagen registrados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Crea el primer cargador encontrado adecuado para el especificado*stream* y opcionalmente el*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Obtiene el primer descriptor compatible encontrado adecuado para el especificado*stream* y opcionalmente el*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Obtiene el primer formato de archivo admitido por su nombre de tipo. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtiene el primer descriptor admitido por su nombre de tipo. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Registra el descriptor del cargador de imágenes especificado. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Registra el cargador. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Da de baja el cargador. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


