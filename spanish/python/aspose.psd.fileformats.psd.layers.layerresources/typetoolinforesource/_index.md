---
title: "Clase TypeToolInfoResource"
type: docs
weight: 1000
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Inicializa una nueva instancia de la clase TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| a_component | short | r/w | Obtiene o establece un componente. |
| b_component | short | r/w | Obtiene o establece el componente b. |
| character_count | int | r/w | Obtiene o establece el recuento de caracteres. |
| color_space_value | short | r/w | Obtiene o establece el valor del espacio de color. |
| font_version | short | r/w | Obtiene o establece la versión de la fuente. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Obtiene o establece las fuentes. |
| fonts_count | short | r | Obtiene el recuento de fuentes. |
| g_component | short | r/w | Obtiene o establece el componente g. |
| horizontal_placement | int | r/w | Obtiene o establece la posición horizontal. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| line_count | short | r | Obtiene el recuento de líneas. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Obtiene o establece las líneas. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| r_component | short | r/w | Obtiene o establece el componente r. |
| scale_factor | int | r/w | Obtiene o establece el factor de escala. |
| selection_end | int | r/w | Obtiene o establece el final de la selección. |
| selection_start | int | r/w | Obtiene o establece el inicio de la selección. |
| signature | int | r | Obtiene la firma. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Obtiene o establece los estilos de fuente. |
| styles_count | short | r | Obtiene el recuento de estilos. |
| transform_matrix | double | r/w | Obtiene o establece la matriz de transformación. |
| type_value | short | r/w | Obtiene o establece el valor de tipo. |
| version | short | r/w | Obtiene o establece la versión. |
| vertical_placement | int | r/w | Obtiene o establece la ubicación vertical. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el contenedor de flujo especificado. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Inicializa una nueva instancia de la clase TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| psd_version | int | La versión PSD. |

