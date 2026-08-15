---
title: "Clase GrdmResource"
type: docs
weight: 340
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Inicializa una nueva instancia de la clase [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| color_model | short | r/w | Modelo de color.<br/>            Cuando 'Gradient type' = 'Noise', podemos asignar 'Color Model' a RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Obtiene o establece los puntos de color. |
| dither | bool | r/w | El degradado está dithered. |
| expansion_count | short | r/w | Recuento de expansión ( = 2 para Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Modo para este degradado<br/>            Determina 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Nombre del degradado: cadena Unicode, con relleno. |
| interpolación | short | r/w | Interpolación. Determina la suavidad, cuando 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Color máximo del formato PixelDataFormat.Rgba64Bpp.<br/>            El color tiene canales ARGB, cada canal es de 16 bits. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Color mínimo del formato PixelDataFormat.Rgba64Bpp.<br/>            El color tiene canales ARGB, cada canal es de 16 bits. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| reverse | bool | r/w | El degradado está invertido. |
| rnd_number_seed | int | r/w | La semilla del número aleatorio utilizada para generar colores para el gradiente Noise. |
| roughness | int | r/w | Factor de rugosidad<br/>            Cuando 'Gradient type' = 'Noise', podemos asignar 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Indicador para mostrar transparencia<br/>            Cuando 'Gradient type' = 'Noise', podemos asignar 'Add transparency' a true. |
| signature | int | r | Obtiene la firma. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Obtiene o establece los puntos de transparencia. |
| use_vector_color | short | r/w | Indicador para usar color vectorial. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda los datos del recurso en el contenedor de flujo especificado. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Inicializa una nueva instancia de la clase [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| psd_version | int | La versión psd del recurso. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda los datos del recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| psd_version | int | La versión PSD. |

