---
title: "ResolutionInfoResource-klasse"
type: docs
weight: 230
url: /nl/python-net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Summary:** The resolution info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ResolutionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ResolutionInfoResource()](#ResolutionInfoResource__1) | Initialiseert een nieuw exemplaar van de ResolutionInfoResource-klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | De resourcesignatuur van ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | De reguliere Photoshop-resourcesignatuur. |
| data_size | int | r | Haalt de grootte van de resourcegegevens op in bytes. |
| h_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | Horizontale DPI. |
| h_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | Weergave-eenheden voor horizontale resolutie.  Dit beïnvloedt alleen de<br/>            gebruikersinterface; de resolutie wordt nog steeds opgeslagen in het PSD‑bestand<br/>            als pixels/inch. |
| height_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Haalt of stelt de hoogte‑weergave‑eenheid in. |
| id | short | r/w | Haalt de unieke identifier van de resource op of stelt deze in. |
| minimal_version | int | r | Haalt de minimaal vereiste PSD-versie op. |
| name | string | r/w | Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een nul‑naam bestaat uit twee bytes van 0). |
| signature | int | r | Haalt de resourcesignatuur op. Zou altijd '8BIM' moeten zijn. |
| grootte | int | r | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| v_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | Verticale DPI. |
| v_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | Weergave-eenheden voor verticale resolutie. |
| width_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Haalt of stelt de breedte‑weergave‑eenheid in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream)](#save_stream_1) | Slaat het resource‑blok op in de opgegeven stream. |
| validate_values() | Valideert de resource‑waarden. |


### Constructor: ResolutionInfoResource() {#ResolutionInfoResource__1}


```
 ResolutionInfoResource() 
```

Initialiseert een nieuw exemplaar van de ResolutionInfoResource-klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Slaat het resource‑blok op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De stream waarin het resource‑blok moet worden opgeslagen. |

