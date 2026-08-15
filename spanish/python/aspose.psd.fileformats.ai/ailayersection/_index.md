---
title: "Clase AiLayerSection"
type: docs
weight: 50
url: /es/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| azul | int | r/w | Obtiene o establece el componente de color azul. |
| color_index | int | r/w | Obtiene o establece el índice del color.<br/>            Este argumento puede tomar valores entre –1 y 26. Cada entero<br/>            representa un color que puede asignarse a la capa para propósitos de identificación del usuario. |
| color_number | int | r/w | Obtiene o establece el número de color. -1 es el valor de color personalizado de las propiedades Rojo, Verde, Azul.<br/>            Especifica la configuración de color de la capa. |
| dim_value | int | r/w | Obtiene o establece el valor de atenuación como porcentaje.<br/>            Reduce la intensidad de las imágenes vinculadas y de los mapas de bits contenidos en la capa al porcentaje especificado. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| verde | int | r/w | Obtiene o establece el componente de color verde. |
| has_multi_layer_masks | bool | r/w | Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer. |
| is_images_dimmed | bool | r/w | Obtiene o establece un valor que indica si esta capa está atenuada.<br/>            Reduce la intensidad de las imágenes vinculadas y de las imágenes de mapa de bits contenidas en la capa. |
| is_locked | bool | r/w | Obtiene o establece un valor que indica si esta capa está bloqueada.<br/>            Impide cambios en el elemento. |
| is_preview | bool | r/w | Obtiene o establece un valor que indica si esta capa es una vista previa.<br/>            Muestra el arte contenido en la capa en color en lugar de como contornos. |
| is_printed | bool | r/w | Obtiene o establece un valor que indica si esta capa se imprime.<br/>            Hace que el arte contenido en la capa sea imprimible si es verdadero. |
| is_shown | bool | r/w | Obtiene o establece un valor que indica si esta capa se muestra.<br/>            Muestra todo el arte contenido en la capa en la mesa de trabajo si es verdadero. |
| is_template | bool | r/w | Obtiene o establece un valor que indica si esta capa es una capa de plantilla. |
| name | string | r/w | Obtiene o establece el nombre de la capa.<br/>            Especifica el nombre del elemento tal como aparece en el panel de Capas. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Obtiene las imágenes raster. |
| rojo | int | r/w | Obtiene o establece el componente de color rojo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Agrega la imagen raster. |
| [get_data()](#get_data__2) | Obtiene los datos de cadena. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Agrega la imagen raster.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | La imagen raster. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Obtiene los datos de cadena.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Los datos de cadena de la sección. |


