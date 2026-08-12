---
title: "Clase ShmdResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ShmdResource. Clase ShmdResource. Configuraciones de metadatos"
type: docs
weight: 3330
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---
{{< psd/tize >}}
## ShmdResource class

Clase ShmdResource. Configuración de metadatos

```csharp
public class ShmdResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ShmdResource](shmdresource/#constructor)() | Inicializa una nueva instancia de la clase `ShmdResource`. |
| [ShmdResource](shmdresource/#constructor_1)(byte[]) | Inicializa una nueva instancia de la clase `ShmdResource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| [LayerCreatedDateTime](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/layercreateddatetime/) { get; set; } | Obtiene o establece la hora de creación de la capa. Si la hora de creación de la capa no se especifica, devuelve new DateTime(0) |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |
| [SubResources](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/) { get; } | Obtiene los subrecursos del recurso shmd. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/save/)(StreamContainer, int) | Guarda el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [SubResourceHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresourceheaderlength/) | La longitud del encabezado del subrecurso |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


