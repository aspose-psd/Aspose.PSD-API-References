---
title: "Clase LrXxResource"
type: docs
weight: 630
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/
---

**Summary:** The lrXX resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LrXxResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| key | int | r | Obtiene la clave del recurso de capa. |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | r/w | Obtiene o establece las capas. |
| longitud | int | r | Obtiene la longitud del recurso para la versión del encabezado PSD de la imagen. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el registro de capa. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda el registro de capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| psd_version | int | La versión psd. |

