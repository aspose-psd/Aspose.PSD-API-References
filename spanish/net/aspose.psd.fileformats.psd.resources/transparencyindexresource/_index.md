---
title: "Clase TransparencyIndexResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.TransparencyIndexResource class. El bloque de recurso de índice de transparencia"
type: docs
weight: 4390
url: /es/net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---
{{< psd/tize >}}
## TransparencyIndexResource class

El bloque de recurso de índice de transparencia.

```csharp
public sealed class TransparencyIndexResource : ResourceBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TransparencyIndexResource](transparencyindexresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/minimalversion/) { get; } | Obtiene la versión mínima requerida de PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consta de dos bytes de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtiene la firma del recurso. Siempre debe ser '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [TransparencyIndex](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/transparencyindex/) { get; set; } | Obtiene o establece el índice de color de transparencia. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Guarda el bloque de recurso en el flujo especificado. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valida los valores del recurso. |

### Ver también

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


