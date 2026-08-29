---
title: "Clase LinkResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource class. Define la clase LinkResource que contiene información sobre archivos vinculados o incrustados en la imagen de formato PSD. El recurso de enlace puede contener varias instancias de LinkDataSource que pueden ser accedidas mediante indexadores en cualquier clase derivada."
type: docs
weight: 3010
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Define la clase LinkResource que contiene información sobre archivos vinculados o incrustados en la imagen de formato PSD. El recurso de enlace puede contener varias instancias de [`LinkDataSource`](../linkdatasource/) que pueden ser accedidas mediante indexadores en cualquier clase derivada.

```csharp
public abstract class LinkResource : LayerResource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtiene el recuento de fuentes de datos de enlace que pueden accederse mediante el indexador. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtiene un valor que indica si esta instancia del recurso de enlace está vacía. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Obtiene el [`LinkDataSource`](../linkdatasource/) en el índice especificado, que es el identificador único de la fuente de datos del enlace. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtiene la longitud del recurso de enlace global PSD en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Guarda los datos del bloque de recursos. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


