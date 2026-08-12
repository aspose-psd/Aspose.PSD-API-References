---
title: "Clase UnknownResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Resources.UnknownResource. El recurso desconocido. Cuando un bloque de recurso no es reconocido, se crea este bloque de recurso."
type: docs
weight: 4410
url: /es/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
{{< psd/tize >}}
## UnknownResource class

El recurso desconocido. Cuando un bloque de recurso no es reconocido, se crea este bloque de recurso.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Obtiene los datos del recurso. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Obtiene la versión mínima requerida de PSD. |
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


