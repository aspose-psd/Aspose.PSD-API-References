---
title: "Clase ColorHalftoneInformationResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Resources.ColorHalftoneInformationResource. Recurso de tramado"
type: docs
weight: 4130
url: /es/net/aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/
---
{{< psd/tize >}}
## ColorHalftoneInformationResource class

Recurso Halftoning

```csharp
public sealed class ColorHalftoneInformationResource : ResourceBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ColorHalftoneInformationResource](colorhalftoneinformationresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [HalftoneData](../../aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/halftonedata/) { get; set; } | Obtiene o establece los datos de tramado. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/minimalversion/) { get; } | Obtiene la versión mínima requerida del PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consta de dos bytes de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtiene la firma del recurso. Siempre debe ser '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Guarda el bloque de recurso en el flujo especificado. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valida los valores del recurso. |

### Ver también

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


