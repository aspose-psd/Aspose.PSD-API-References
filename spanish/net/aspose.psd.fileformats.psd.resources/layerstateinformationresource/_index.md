---
title: "Clase LayerStateInformationResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Resources.LayerStateInformationResource. Recurso de información del estado de capa"
type: docs
weight: 4280
url: /es/net/aspose.psd.fileformats.psd.resources/layerstateinformationresource/
---
{{< psd/tize >}}
## LayerStateInformationResource class

Recurso de información del estado de capa

```csharp
public sealed class LayerStateInformationResource : ResourceBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerStateInformationResource](layerstateinformationresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layerstateinformationresource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| [LayerIndex](../../aspose.psd.fileformats.psd.resources/layerstateinformationresource/layerindex/) { get; set; } | Obtiene o establece el índice de la capa. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layerstateinformationresource/minimalversion/) { get; } | Obtiene la versión mínima requerida del PSD. |
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


