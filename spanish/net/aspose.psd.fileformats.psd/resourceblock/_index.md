---
title: "Clase ResourceBlock"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.ResourceBlock. El bloque de recursos"
type: docs
weight: 4070
url: /es/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
## ResourceBlock class

El bloque de recursos.

```csharp
public abstract class ResourceBlock
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Obtiene la versión mínima requerida del PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consta de dos bytes de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtiene la firma del recurso. Siempre debe ser '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Guarda el bloque de recurso en el flujo especificado. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valida los valores del recurso. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | La firma de recurso de ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | La firma de recurso regular de Photoshop. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | Representa el estado del bloque de recursos. |

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


