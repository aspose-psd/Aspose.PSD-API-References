---
title: "Clase PhflResource"
type: docs
weight: 790
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| density | int | r/w | Obtiene o establece la densidad. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| preserve_luminosity | bool | r/w | Obtiene o establece un valor que indica si [preserve luminosity]. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| version | short | r | Obtiene la versión. El valor predeterminado es 2 o 3 |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Obtiene el color del RGB. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Guarda el recurso en el contenedor de flujo especificado. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Establece el color RGB. |


### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Obtiene el color del RGB.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | El color RGB |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Establece el color RGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | El color RGB. |

