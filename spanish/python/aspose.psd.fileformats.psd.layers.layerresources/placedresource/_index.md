---
title: "Clase PlacedResource"
type: docs
weight: 830
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| anti_alias_policy | int | r/w | Obtiene o establece la política de antialias del capa colocada en la imagen PSD. |
| inferior | double | r/w | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtiene o establece la unidad de medida de los puntos de malla horizontal. |
| horizontal_mesh_points | double | r/w | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| is_custom | bool | r/w | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado.<br/>            Si es verdadero contiene puntos de malla. Si se establece en falso elimina los puntos de malla. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtiene o establece los elementos de deformación. |
| key | int | r | Obtiene la clave del recurso de capa. |
| left | double | r/w | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| page_number | int | r/w | Obtiene o establece el número de página de la capa colocada en el archivo PSD. |
| perspective | double | r/w | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| perspective_other | double | r/w | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Obtiene o establece el tipo de la capa colocada en el archivo PSD. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| right | double | r/w | Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD. |
| signature | int | r | Obtiene la firma. |
| top | double | r/w | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| total_pages | int | r/w | Obtiene o establece el total de páginas de la capa colocada en el archivo PSD. |
| transform_matrix | double | r/w | Obtiene o establece la matriz de transformación de la capa colocada en el archivo PSD. |
| u_order | int | r/w | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| unique_id | Guid | r/w | Obtiene o establece el identificador único global de la capa colocada en la imagen PSD. |
| v_order | int | r/w | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| value | double | r/w | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| version | int | r | Obtiene la versión de la capa colocada en el archivo PSD, usualmente 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| vertical_mesh_points | double | r/w | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


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

