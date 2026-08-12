---
title: "Clase LayerGroupInformationResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Resources.LayerGroupInformationResource. Recurso de información del grupo de capas."
type: docs
weight: 4250
url: /es/net/aspose.psd.fileformats.psd.resources/layergroupinformationresource/
---
{{< psd/tize >}}
## LayerGroupInformationResource class

Recurso de información de grupo de capas

```csharp
public sealed class LayerGroupInformationResource : ResourceBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerGroupInformationResource](layergroupinformationresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [Groups](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/groups/) { get; set; } | Obtiene o establece los grupos. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/minimalversion/) { get; } | Obtiene la versión mínima requerida del PSD. |
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


