---
title: "Clase BlncResource"
type: docs
weight: 80
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Inicializa una nueva instancia de la clase [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| highlights_cyan_red_balance | short | r/w | Obtiene o establece el Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Obtiene o establece el Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Obtiene o establece el Highlights Yellow Blue Balance. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| midtones_cyan_red_balance | short | r/w | Obtiene o establece el Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Obtiene o establece el Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Obtiene o establece el Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Obtiene o establece un valor que indica si este [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) conserva la luminosidad. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| shadows_cyan_red_balance | short | r/w | Obtiene o establece el Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Obtiene o establece el Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Obtiene o establece el Shadows Yellow Blue Balance. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Inicializa una nueva instancia de la clase [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

