---
title: Class LinkResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource clase. Define la clase LinkResource que contiene información sobre archivos vinculados o incrustados en la imagen en formato PSD. El recurso de vínculo puede contener variosLinkDataSource instancias a las que pueden acceder los indexadores en cualquier clase derivada.
type: docs
weight: 2710
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Define la clase LinkResource que contiene información sobre archivos vinculados o incrustados en la imagen en formato PSD. El recurso de vínculo puede contener varios[`LinkDataSource`](../linkdatasource/) instancias a las que pueden acceder los indexadores en cualquier clase derivada.

```csharp
public abstract class LinkResource : LayerResource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtiene el recuento de orígenes de datos de vínculos a los que puede acceder el indexador. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtiene un valor que indica si esta instancia de recurso de enlace está vacía. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Obtiene el[`LinkDataSource`](../linkdatasource/) en el índice especificado que es el identificador único de la fuente de datos del vínculo... |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtiene la longitud del recurso de enlace global PSD en bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Obtiene la versión en formato PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Obtiene la firma del recurso de enlace global PSD. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Guarda los datos del bloque de recursos. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


