---
title: "Clase VstkResource"
type: docs
weight: 40
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Inicializa una nueva instancia de la clase VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| fill_enabled | bool | r/w | Obtiene o establece un valor que indica si el relleno Stroke está habilitado. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Obtiene o establece la configuración de Relleno del trazo. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| stroke_enabled | bool | r/w | Obtiene o establece un valor que indica si el efecto de trazo está habilitado. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Obtiene o establece el modo de fusión Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Obtiene o establece la entidad Stroke. La propiedad determina la configuración de relleno del trazo. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Obtiene o establece la alineación de línea del estilo de trazo. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Obtiene o establece el tipo de la tapa de línea del estilo de trazo. |
| stroke_style_line_cap_width | double | r/w | Obtiene o establece el ancho de la tapa de línea Stroke. |
| stroke_style_line_dash_offset | int | r/w | Obtiene o establece el desplazamiento de guión de línea del estilo de trazo. |
| stroke_style_line_dash_set | double | r/w | Obtiene o establece la matriz de guiones de línea. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Obtiene o establece el tipo de unión de línea del estilo Stroke. |
| stroke_style_line_width | double | r/w | Obtiene o establece el ancho de línea Stroke. |
| stroke_style_miter_limit | double | r/w | Obtiene o establece el límite de inglete del estilo de trazo. |
| stroke_style_opacity | int | r/w | Obtiene o establece la opacidad del estilo Stroke (0-100%). |
| stroke_style_resolution | double | r/w | Obtiene o establece la resolución del estilo de trazo. |
| stroke_style_scale_lock | bool | r/w | Obtiene o establece el bloqueo de escala del estilo de trazo. |
| stroke_style_stroke_adjust | bool | r/w | Obtiene o establece el ajuste del trazo. |
| stroke_style_version | int | r/w | Obtiene o establece la versión del estilo de trazo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Inicializa una nueva instancia de la clase VstkResource

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

