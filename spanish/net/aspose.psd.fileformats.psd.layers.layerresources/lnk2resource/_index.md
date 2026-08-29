---
title: "Clase Lnk2Resource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource. Define la clase que contiene información sobre archivos incrustados en la imagen con formato PSD. El recurso de enlace puede contener varias instancias de LiFdDataSource que pueden ser accedidas mediante el indexador."
type: docs
weight: 3030
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

Define la clase que contiene información sobre archivos incrustados en la imagen con formato PSD. El recurso de enlace puede contener varias instancias de [`LiFdDataSource`](../lifddatasource/) que pueden ser accedidas mediante el indexador.

```csharp
public class Lnk2Resource : LinkResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | Inicializa una nueva instancia de la clase `Lnk2Resource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtiene el recuento de fuentes de datos de enlace que pueden accederse mediante el indexador. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtiene un valor que indica si esta instancia del recurso de enlace está vacía. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Obtiene el [`LiFdDataSource`](../lifddatasource/) en el índice especificado. (2 indexadores) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtiene la longitud del recurso de enlace global PSD en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Guarda los datos del bloque de recursos. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


