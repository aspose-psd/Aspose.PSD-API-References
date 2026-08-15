---
title: "Clase GdFlResource"
type: docs
weight: 330
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Inicializa una nueva instancia de la clase GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| align_with_layer | bool | r/w | Obtiene o establece un valor que indica si [alinear con capa]. |
| ángulo | double | r/w | Obtiene o establece el ángulo. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene el color del RGB. |
| color_model | string | r/w | Modelo de color - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Obtiene los puntos de color. |
| dither | bool | r/w | Obtiene o establece un valor que indica si este [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) está dither. |
| gradient_interval | double | r/w | Obtiene o establece el intervalo del gradiente. |
| gradient_mode | string | r/w | Modo para este gradiente.<br/>            Determina 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| gradient_name | string | r/w | Obtiene o establece el nombre del degradado. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Obtiene o establece el tipo del degradado. |
| horizontal_offset | double | r/w | Obtiene o establece el desplazamiento horizontal. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Color máximo de PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Color mínimo de PixelDataFormat. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| reverse | bool | r/w | Obtiene o establece un valor que indica si este [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) está invertido. |
| rnd_number_seed | int | r/w | La semilla del número aleatorio utilizada para generar colores para el gradiente Noise. |
| roughness | int | r/w | Factor de rugosidad. |
| scale | int | r/w | Obtiene o establece la escala. |
| show_transparency | bool | r/w | Indicador para mostrar transparencia. |
| signature | int | r | Obtiene la firma. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Obtiene los puntos de transparencia. |
| use_vector_color | bool | r/w | Indicador para usar color vectorial. |
| vertical_offset | double | r/w | Obtiene o establece el desplazamiento vertical. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Inicializa una nueva instancia de la clase GdFlResource

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

