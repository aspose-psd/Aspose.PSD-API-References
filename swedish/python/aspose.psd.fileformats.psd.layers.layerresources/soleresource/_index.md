---
title: "SoLeResource-klass"
type: docs
weight: 940
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/
---

**Summary:** Defines the SoLeResource class that contains information about a smart object layer in a PSD file.<br/>            Is is used to support smart object layers with external file links in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLeResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SoLeResource()](#SoLeResource__1) | Initierar en ny instans av [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) klassen. |
| [SoLeResource(unique_id, is_custom, has_comp_info)](#SoLeResource_unique_id_is_custom_has_comp_info_2) | Initierar en ny instans av [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinfo-nyckeln: 'SoLE'. |
| anti_alias_policy | int | r/w | Hämtar eller anger anti-alias-policy för smartobjektlagrets data i PSD-bilden. |
| nedre | double | r/w | Hämtar eller anger den nedre positionen för det placerade lagret i PSD‑bilden. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| comp | int | r/w | Hämtar eller anger comp‑värdet för smartobjektlagrets data i PSD‑filen.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps i Smart Objects</see> |
| comp_id | int | r/w | Hämtar eller anger ID för den för närvarande valda comp‑en för underdokumentet, vilket blir -1 om ingen är vald.<br/>            Comps är sammansättningar av en sidlayout som designers kan skapa. Med hjälp av lager‑comps kan du skapa, hantera och visa flera versioner<br/>            av en layout i en enda Adobe Photoshop‑fil. En lager‑comp är en ögonblicksbild av ett tillstånd i Lager‑panelen. Lager‑comps sparar tre typer av lageralternativ men<br/>            den här egenskapen hämtar identifieraren för lager‑comp‑urvalet för smartobjektlagret i PSD‑filen.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps i Smart Objects</see> |
| crop | int | r/w | Hämtar eller anger crop för smartobjektlagrets data i PSD‑bilden. |
| duration_denominator | int | r/w | Hämtar eller anger varaktighetens nämnare. |
| duration_numerator | int | r/w | Hämtar eller anger varaktighetens täljare. |
| frame_count | int | r/w | Hämtar eller anger antalet bildrutor för smartobjektlagrets data i PSD‑filen. |
| frame_step_denominator | int | r/w | Hämtar eller anger bildrutsstegets nämnare. |
| frame_step_numerator | int | r/w | Hämtar eller anger bildrutsstegets täljare. |
| height | double | r/w | Hämtar eller anger höjden. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| horizontal_mesh_points | double | r/w | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| is_custom | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instanss warp‑stil är anpassad.<br/>            Om true innehåller den nätpunkter. Om false raderas nätpunkterna. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Hämtar eller anger deskriptorelementen för smartobjektlagrets data i PSD‑filen. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| vänster | double | r/w | Hämtar eller anger den vänstra positionen för det placerade lagret i PSD‑filen. |
| längd | int | r | Hämtar smartobjektresursens längd i byte. |
| non_affine_transform_matrix | double | r/w | Hämtar eller anger den icke‑affina transformationsmatrisen för smartobjektlagrets data i PSD‑filen. |
| original_comp_id | int | r | Hämtar det ursprungliga ID‑t för den för närvarande valda Comp‑en för underdokumentet, vilket blir -1 om ingen är vald.<br/>            Den här egenskapen hämtar det ursprungliga lager‑Comp‑urvalsidentifieraren för smartobjektlagret i PSD‑filen.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps i Smart Objects</see> |
| page_number | int | r/w | Hämtar eller anger sidnumret för smartobjektlagrets data i PSD-filen. |
| perspective | double | r/w | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| perspective_other | double | r/w | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| placed_id | Guid | r/w | Hämtar eller anger det unika identifieraren för detta smartobjektlagrets data i PSD-bilden. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Hämtar eller anger typen av smartobjektlagrets data i PSD-filen. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| resolution | double | r/w | Hämtar eller anger upplösningen för smartobjektlagrets data i PSD-filen. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Hämtar eller anger måttenheten för upplösning av smartobjektlagrets data i PSD-filen. |
| höger | double | r/w | Hämtar eller anger den högra positionen för det placerade lagret i PSD‑filen. |
| signatur | int | r | Hämtar signaturen. |
| övre | double | r/w | Hämtar eller anger den övre positionen för det placerade lagret i PSD‑bilden. |
| total_pages | int | r/w | Hämtar eller anger det totala antalet sidor för smartobjektlagrets data i PSD-filen. |
| transform_matrix | double | r/w | Hämtar eller anger transformmatrisen för smartobjektlagrets data i PSD-filen. |
| u_order | int | r/w | Hämtar eller anger U-ordningsvärdet för det placerade lagret i PSD-filen. |
| unique_id | Guid | r/w | Hämtar eller anger det globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) i PSD-bilden. |
| v_order | int | r/w | Hämtar eller anger V-ordningsvärdet för det placerade lagret i PSD-filen. |
| värde | double | r/w | Hämtar eller anger warp‑värdet för det placerade lagret i PSD-bilden. |
| version | int | r | Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3‑5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Hämtar eller anger måttenheten för de vertikala maskpunkterna. |
| vertical_mesh_points | double | r/w | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| width | double | r/w | Hämtar eller anger bredden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar smartobjektresursen till den angivna strömbehållaren. |


### Constructor: SoLeResource() {#SoLeResource__1}


```
 SoLeResource() 
```

Initierar en ny instans av [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) klassen.

### Constructor: SoLeResource(unique_id, is_custom, has_comp_info) {#SoLeResource_unique_id_is_custom_has_comp_info_2}


```
 SoLeResource(unique_id, is_custom, has_comp_info) 
```

Initierar en ny instans av [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| unique_id | Guid | Det unika identifieraren för den placerade lagerdatan [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |
| is_custom | bool | om den är satt till <c>true</c> [är anpassad]. |
| has_comp_info | bool | om den är satt till <c>true</c> [har kompositionsinformation]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar smartobjektresursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

