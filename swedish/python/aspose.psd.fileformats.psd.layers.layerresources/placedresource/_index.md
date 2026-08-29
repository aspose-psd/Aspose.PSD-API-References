---
title: "PlacedResource-klass"
type: docs
weight: 830
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| anti_alias_policy | int | r/w | Hämtar eller anger anti‑alias‑policyn för det placerade lagret i PSD‑bilden. |
| nedre | double | r/w | Hämtar eller anger den nedre positionen för det placerade lagret i PSD‑bilden. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| horizontal_mesh_points | double | r/w | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| is_custom | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instanss warp‑stil är anpassad.<br/>            Om true innehåller den nätpunkter. Om false raderas nätpunkterna. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Hämtar eller anger warp‑objekten. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| vänster | double | r/w | Hämtar eller anger den vänstra positionen för det placerade lagret i PSD‑filen. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| page_number | int | r/w | Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen. |
| perspective | double | r/w | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| perspective_other | double | r/w | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Hämtar eller anger typen för det placerade lagret i PSD‑filen. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| höger | double | r/w | Hämtar eller anger den högra positionen för det placerade lagret i PSD‑filen. |
| signatur | int | r | Hämtar signaturen. |
| övre | double | r/w | Hämtar eller anger den övre positionen för det placerade lagret i PSD‑bilden. |
| total_pages | int | r/w | Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen. |
| transform_matrix | double | r/w | Hämtar eller anger transformmatrisen för det placerade lagret i PSD-filen. |
| u_order | int | r/w | Hämtar eller anger U-ordningsvärdet för det placerade lagret i PSD-filen. |
| unique_id | Guid | r/w | Hämtar eller anger det globala unika identifieraren för det placerade lagret i PSD-bilden. |
| v_order | int | r/w | Hämtar eller anger V-ordningsvärdet för det placerade lagret i PSD-filen. |
| värde | double | r/w | Hämtar eller anger warp‑värdet för det placerade lagret i PSD-bilden. |
| version | int | r | Hämtar versionen för det placerade lagret i PSD-filen, vanligtvis 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Hämtar eller anger måttenheten för de vertikala maskpunkterna. |
| vertical_mesh_points | double | r/w | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

