---
title: "Clase SoLdResource"
type: docs
weight: 930
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---

**Summary:** Defines the SoLdResource class that contains information about a smart object layer in a PSD file.<br/>            Is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLdResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SoLdResource()](#SoLdResource__1) | Inicializa una nueva instancia de la clase [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/).<br/>            Este constructor predeterminado está diseñado para ser usado por [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/).<br/>            Use [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) para crear clases SoLdResource. |
| [SoLdResource(unique_id, is_custom, has_comp_info)](#SoLdResource_unique_id_is_custom_has_comp_info_2) | Inicializa una nueva instancia de la clase [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/).<br/>            Es necesario establecer la propiedad Items o llamar a InitializeItems() para obtener una instancia lista.<br/>            Este constructor está diseñado para ser usado por [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            y en pruebas unitarias.<br/>            Use [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) para crear clases SoLdResource. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo: 'SoLd'. |
| anti_alias_policy | int | r/w | Obtiene o establece la política de antialiasing de los datos de capa de objeto inteligente en la imagen PSD. |
| inferior | double | r/w | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| comp | int | r/w | Obtiene o establece el valor de comp de los datos de capa de objeto inteligente en el archivo PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Composiciones de capa en objetos inteligentes</see> |
| comp_id | int | r/w | Obtiene o establece el ID del comp actualmente seleccionado para el documento hijo, que será -1 si no hay ninguno seleccionado.<br/>            Los comps son composiciones de un diseño de página que los diseñadores pueden crear. Usando composiciones de capa, puedes crear, gestionar y ver múltiples versiones<br/>            de un diseño en un solo archivo Adobe® Photoshop®. Un comp de capa es una instantánea del estado del panel Capas. Las composiciones de capa guardan tres tipos de opciones de capa pero<br/>            esta propiedad obtiene el identificador de selección de Layer Comp para la capa de objeto inteligente en el archivo PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Composiciones de capa en objetos inteligentes</see> |
| crop | int | r/w | Obtiene o establece el recorte de los datos de capa de objeto inteligente en la imagen PSD. |
| duration_denominator | int | r/w | Obtiene o establece el denominador de la duración. |
| duration_numerator | int | r/w | Obtiene o establece el numerador de la duración. |
| frame_count | int | r/w | Obtiene o establece el recuento de fotogramas de los datos de la capa de objeto inteligente en el archivo PSD. |
| frame_step_denominator | int | r/w | Obtiene o establece el denominador del paso de fotograma. |
| frame_step_numerator | int | r/w | Obtiene o establece el numerador del paso de fotograma. |
| altura | double | r/w | Obtiene o establece la altura. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtiene o establece la unidad de medida de los puntos de malla horizontal. |
| horizontal_mesh_points | double | r/w | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| is_custom | bool | r/w | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado.<br/>            Si es verdadero contiene puntos de malla. Si se establece en falso elimina los puntos de malla. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtiene o establece los elementos del descriptor de los datos de la capa de objeto inteligente en el archivo PSD. |
| key | int | r | Obtiene la clave del recurso de capa. |
| left | double | r/w | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| longitud | int | r | Obtiene la longitud del recurso de objeto inteligente en bytes. |
| non_affine_transform_matrix | double | r/w | Obtiene o establece la matriz de transformación no afín de los datos de la capa de objeto inteligente en el archivo PSD. |
| original_comp_id | int | r | Obtiene el ID original del Comp actualmente seleccionado para el documento hijo, que será -1 si no se selecciona ninguno.<br/>            Esta propiedad obtiene el identificador de selección del Comp de capa original para la capa de objeto inteligente en el archivo PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Compuestos de capa en objetos inteligentes</see> |
| page_number | int | r/w | Obtiene o establece el número de página de los datos de la capa de objeto inteligente en el archivo PSD. |
| perspective | double | r/w | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| perspective_other | double | r/w | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| placed_id | Guid | r/w | Obtiene o establece el identificador único de estos datos de capa de objeto inteligente en la imagen PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Obtiene o establece el tipo de los datos de la capa de objeto inteligente en el archivo PSD. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| resolution | double | r/w | Obtiene o establece la resolución de los datos de la capa de objeto inteligente en el archivo PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtiene o establece la unidad de medida de la resolución de los datos de la capa de objeto inteligente en el archivo PSD. |
| right | double | r/w | Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD. |
| signature | int | r | Obtiene la firma. |
| top | double | r/w | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| total_pages | int | r/w | Obtiene o establece el número total de páginas de los datos de la capa de objeto inteligente en el archivo PSD. |
| transform_matrix | double | r/w | Obtiene o establece la matriz de transformación de los datos de la capa de objeto inteligente en el archivo PSD. |
| u_order | int | r/w | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| unique_id | Guid | r/w | Obtiene o establece el identificador único global de los datos de la capa de objeto inteligente [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) en la imagen PSD. |
| v_order | int | r/w | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| value | double | r/w | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| version | int | r | Obtiene la versión de la capa colocada en el archivo PSD, usualmente 3-5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| vertical_mesh_points | double | r/w | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| width | double | r/w | Obtiene o establece el ancho. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso de objeto inteligente en el contenedor de flujo especificado. |


### Constructor: SoLdResource() {#SoLdResource__1}


```
 SoLdResource() 
```

Inicializa una nueva instancia de la clase [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/).<br/>            Este constructor predeterminado está diseñado para ser usado por [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/).<br/>            Use [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) para crear clases SoLdResource.

### Constructor: SoLdResource(unique_id, is_custom, has_comp_info) {#SoLdResource_unique_id_is_custom_has_comp_info_2}


```
 SoLdResource(unique_id, is_custom, has_comp_info) 
```

Inicializa una nueva instancia de la clase [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/).<br/>            Es necesario establecer la propiedad Items o llamar a InitializeItems() para obtener una instancia lista.<br/>            Este constructor está diseñado para ser usado por [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            y en pruebas unitarias.<br/>            Use [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) para crear clases SoLdResource.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| unique_id | Guid | El identificador único de los datos de la capa de objeto inteligente [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |
| is_custom | bool | si se establece en <c>true</c> [es personalizado]. |
| has_comp_info | bool | si se establece en <c>true</c> [tiene información de composición]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda el recurso de objeto inteligente en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

