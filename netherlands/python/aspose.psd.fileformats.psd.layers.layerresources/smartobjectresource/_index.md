---
title: "SmartObjectResource Klasse"
type: docs
weight: 900
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| anti_alias_policy | int | r/w | Haalt of stelt het anti‑aliasbeleid van de smart object‑lagengegevens in de PSD‑afbeelding in. |
| bottom | double | r/w | Haalt de onderkant‑locatie op van de geplaatste laag in de PSD‑afbeelding of stelt deze in. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Haalt de grenzen op van de geplaatste laag in het PSD‑bestand of stelt ze in. |
| comp | int | r/w | Haalt of stelt de comp‑waarde van de smart object‑lagengegevens in het PSD‑bestand in.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| comp_id | int | r/w | Haalt of stelt de ID van de momenteel geselecteerde comp voor het onderliggende document in, die -1 is als er geen is geselecteerd.<br/>            Comps zijn composities van een paginalay-out die ontwerpers kunnen maken. Met layer comps kun je meerdere versies van een lay-out maken, beheren en bekijken<br/>            in één Adobe® Photoshop®‑bestand. Een layer comp is een momentopname van een toestand van het Layers‑paneel. Layer comps slaan drie soorten laagopties op, maar<br/>            deze eigenschap haalt de selectie‑identifier van de Layer Comp op voor de smart object‑laag in het PSD‑bestand.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| crop | int | r/w | Haalt of stelt de bijsnijding van de smart object‑lagengegevens in de PSD‑afbeelding in. |
| duration_denominator | int | r/w | Geeft of stelt de duurnoemer in. |
| duration_numerator | int | r/w | Geeft of stelt de duurteller in. |
| frame_count | int | r/w | Geeft of stelt het frame‑aantal van de smart object‑laaggegevens in het PSD‑bestand in. |
| frame_step_denominator | int | r/w | Geeft of stelt de frame‑stapnoemer in. |
| frame_step_numerator | int | r/w | Geeft of stelt de frame‑stapteller in. |
| hoogte | double | r/w | Haalt de hoogte op of stelt deze in. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Haalt of stelt de meeteenheid van de horizontale rasterpunten in. |
| horizontal_mesh_points | double | r/w | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD‑bestand in. |
| is_custom | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze instantie van warp‑stijl aangepast is.<br/>            Als true bevat het rasterpunten. Als false wist het rasterpunten. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Geeft of stelt de descriptor‑items van de smart object‑laaggegevens in het PSD‑bestand in. |
| key | int | r | Haalt de laagresource key op. |
| left | double | r/w | Haalt of stelt de linkerlokatie van de geplaatste laag in het PSD‑bestand in. |
| lengte | int | r | Geeft de lengte van de smart object‑resource in bytes. |
| non_affine_transform_matrix | double | r/w | Geeft of stelt de niet‑affiene transformatie‑matrix van de smart object‑laaggegevens in het PSD‑bestand in. |
| original_comp_id | int | r | Geeft de oorspronkelijke ID van de momenteel geselecteerde Comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd.<br/>            Deze eigenschap geeft de oorspronkelijke laag‑Comp‑selectie‑identifier voor de smart object‑laag in het PSD‑bestand.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| page_number | int | r/w | Geeft of stelt het paginanummer van de smart object‑laaggegevens in het PSD‑bestand in. |
| perspective | double | r/w | Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD‑bestand in. |
| perspective_other | double | r/w | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD‑bestand in. |
| placed_id | Guid | r/w | Geeft of stelt de unieke identifier van deze smart object‑laaggegevens in de PSD‑afbeelding in. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Geeft of stelt het type van de smart object‑laaggegevens in het PSD‑bestand in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| resolution | double | r/w | Geeft of stelt de resolutie van de smart object‑laaggegevens in het PSD‑bestand in. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Geeft of stelt de meeteenheid van de resolutie van de smart object‑laaggegevens in het PSD‑bestand in. |
| right | double | r/w | Haalt of stelt de rechterlokatie van de geplaatste laag in het PSD‑bestand in. |
| signature | int | r | Haalt de handtekening op. |
| boven | double | r/w | Haalt of stelt de bovenlokatie van de geplaatste laag in de PSD‑afbeelding in. |
| total_pages | int | r/w | Geeft of stelt het totale aantal pagina's van de smart object‑laaggegevens in het PSD‑bestand in. |
| transform_matrix | double | r/w | Geeft of stelt de transformatie‑matrix van de smart object‑laaggegevens in het PSD‑bestand in. |
| u_order | int | r/w | Haalt of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| unique_id | Guid | r/w | Geeft of stelt de globale unieke identifier van de smart object‑laaggegevens [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) in de PSD‑afbeelding in. |
| v_order | int | r/w | Haalt of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| value | double | r/w | Haalt of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in. |
| version | int | r | Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Haalt of stelt de meeteenheid van de verticale rasterpunten in. |
| vertical_mesh_points | double | r/w | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD‑bestand in. |
| width | double | r/w | Haalt de breedte op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de smart object resource op in de opgegeven streamcontainer. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de smart object resource op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

