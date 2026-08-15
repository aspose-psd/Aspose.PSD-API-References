---
title: "LinkDataSource Klasse"
type: docs
weight: 530
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---

**Summary:** Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Haalt op of stelt een waarde in die aangeeft of het PSD‑asset vergrendeld is.<br/>
            De vergrendelde status van het asset, voor Adobe® Photoshop® CC Libraries assets. |
| asset_mod_time | double | r/w | Haalt of stelt de gewijzigde tijd van het asset in, voor Adobe® Photoshop® СС Libraries assets. |
| child_doc_id | string | r/w | Haalt of stelt de identifier van het onderliggende document in de liFE- of liFD-gegevensbron van de Lnk2 / LnkE Adobe® Photoshop® resource in. |
| comp_id | int | r/w | Haalt of stelt de ID van de momenteel geselecteerde comp voor het onderliggende document in, die -1 zal zijn als er geen is geselecteerd.<br/>            Comps zijn composities van een paginalay-out die ontwerpers kunnen maken. Met laag‑comps kun je meerdere versies<br/>            van een lay-out in één Adobe® Photoshop®‑bestand creëren, beheren en bekijken. Een laag‑comp is een momentopname van een toestand van het Layers‑paneel. Laag‑comps slaan drie soorten laagopties op, maar<br/>            deze eigenschap haalt de selectie‑identifier van de Layer Comp op voor Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| file_creator | string | r/w | Haalt of stelt de maker van het bestand in de PSD‑formaat LnkE / Lnk2‑resource in. |
| file_type | string | r/w | Haalt of stelt het type van het ingesloten of externe bestand in dat de Adobe® Photoshop® Lnk2 / LnkE‑resource bevat of waarnaar wordt gelinkt. |
| has_file_open_descriptor | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze koppelings‑gegevensbron de bestands‑open‑descriptor heeft: CompId en OriginalCompId. |
| is_library_link | bool | r | Haalt een waarde op die aangeeft of deze PSD‑koppelings‑gegevensbron linkt naar het Adobe® Photoshop® СС Library‑item. |
| lengte | long | r | Haalt de lengte van de link-gegevensbron op in bytes. |
| original_comp_id | int | r | Haalt de originele ID op van de momenteel geselecteerde Comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd.<br/>            Deze eigenschap haalt de originele laag‑Comp‑selectie‑identifier op voor Smart Objects.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Haalt de originele bestandsnaam op van de gegevensbron in de Adobe® Photoshop® globale link‑resource. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Haalt het type van de Adobe® Photoshop® globale link‑gegevensbron op, dat een van de volgende kan zijn of geen:<br/>            Het ingebedde gekoppelde bestand liFD dat overeenkomt met de PSD Lnk2Resource<br/>            Het externe gekoppelde bestand liFE dat overeenkomt met de PSD LnkeResource<br/>            Het gekoppelde bestand‑alias liFA |
| unique_id | Guid | r | Haalt de globale unieke identifier op van de gegevensbron in de PSD‑link‑resource. |
| version | int | r | Haalt de versie op van de gegevensbron in de PSD LnkE / Lnk2‑resource. |


