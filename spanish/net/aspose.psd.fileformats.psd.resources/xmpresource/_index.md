---
title: Class XmpResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Resources.XmpResource clase. Representa el recurso de metadatos XMP.
type: docs
weight: 3990
url: /es/net/aspose.psd.fileformats.psd.resources/xmpresource/
---
## XmpResource class

Representa el recurso de metadatos XMP.

```csharp
public sealed class XmpResource : ResourceBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpResource](xmpresource/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/xmpresource/datasize/) { get; } | Obtiene el tamaño de los datos del recurso en bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtiene o establece el identificador único del recurso. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/xmpresource/minimalversion/) { get; } | Obtiene la versión psd mínima requerida. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea uniforme (un nombre nulo consta de dos bytes de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtiene la firma del recurso. Debe ser siempre '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtiene el tamaño del bloque de recursos en bytes, incluidos sus datos. |
| [XmpData](../../aspose.psd.fileformats.psd.resources/xmpresource/xmpdata/) { get; set; } | Obtener o establecer contenedor de datos XMP |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Guarda el bloque de recursos en el flujo especificado. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valida los valores del recurso. |

### Ver también

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* asamblea [Aspose.PSD](../../)


