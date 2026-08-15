---
title: "PlacedResource‑klasse"
type: docs
weight: 830
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| anti_alias_policy | int | r/w | Haalt het anti‑alias‑beleid op van de geplaatste laag in de PSD‑afbeelding of stelt het in. |
| bottom | double | r/w | Haalt de onderkant‑locatie op van de geplaatste laag in de PSD‑afbeelding of stelt deze in. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Haalt de grenzen op van de geplaatste laag in het PSD‑bestand of stelt ze in. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Haalt of stelt de meeteenheid van de horizontale rasterpunten in. |
| horizontal_mesh_points | double | r/w | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD‑bestand in. |
| is_custom | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze instantie van warp‑stijl aangepast is.<br/>            Als true bevat het rasterpunten. Als false wist het rasterpunten. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Haalt of stelt de warp‑items in. |
| key | int | r | Haalt de laagresource key op. |
| left | double | r/w | Haalt of stelt de linkerlokatie van de geplaatste laag in het PSD‑bestand in. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| page_number | int | r/w | Haalt of stelt het paginanummer van de geplaatste laag in het PSD‑bestand in. |
| perspective | double | r/w | Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD‑bestand in. |
| perspective_other | double | r/w | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD‑bestand in. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Haalt of stelt het type van de geplaatste laag in het PSD‑bestand in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| right | double | r/w | Haalt of stelt de rechterlokatie van de geplaatste laag in het PSD‑bestand in. |
| signature | int | r | Haalt de handtekening op. |
| boven | double | r/w | Haalt of stelt de bovenlokatie van de geplaatste laag in de PSD‑afbeelding in. |
| total_pages | int | r/w | Haalt of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in. |
| transform_matrix | double | r/w | Haalt of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in. |
| u_order | int | r/w | Haalt of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| unique_id | Guid | r/w | Haalt of stelt de globale unieke identifier van de geplaatste laag in de PSD‑afbeelding in. |
| v_order | int | r/w | Haalt of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| value | double | r/w | Haalt of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in. |
| version | int | r | Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Haalt of stelt de meeteenheid van de verticale rasterpunten in. |
| vertical_mesh_points | double | r/w | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD‑bestand in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

