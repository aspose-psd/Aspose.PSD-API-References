---
title: "Clase ResolutionInfoResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource. El recurso de información de resolución"
type: docs
weight: 4350
url: /es/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
{{< psd/tize >}}
## ResolutionInfoResource class

El recurso de información de resolución

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | DPI horizontal. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Obtiene o establece la unidad de visualización de altura. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Unidades de visualización para la resolución horizontal. Esto solo afecta la interfaz de usuario; la resolución sigue almacenada en el archivo PSD como píxeles/pulgada. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Obtiene la versión mínima requerida del PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consta de dos bytes de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtiene la firma del recurso. Siempre debe ser '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | DPI vertical. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Unidades de visualización para la resolución vertical. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Obtiene o establece la unidad de visualización del ancho. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Guarda el bloque de recurso en el flujo especificado. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valida los valores del recurso. |

### Ver también

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


