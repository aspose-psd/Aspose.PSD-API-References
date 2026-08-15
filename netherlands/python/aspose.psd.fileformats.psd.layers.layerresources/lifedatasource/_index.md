---
title: "LiFeDataSource Klasse"
type: docs
weight: 520
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | Initialiseert een nieuw exemplaar van de [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klasse. |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Initialiseert een nieuw exemplaar van de [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| adobe_stock_id | string | r/w | Haalt op of stelt de grafische bibliotheek AdobeStockId in, voor Adobe® Photoshop® CC Libraries. |
| adobe_stock_license_state | string | r | Haalt de status van de Adobe Stock-licentie op indien beschikbaar, voor Adobe® Photoshop® CC libraries. |
| asset_locked_state | bool | r/w | Haalt op of stelt een waarde in die aangeeft of het PSD‑asset vergrendeld is.<br/>
            De vergrendelde status van het asset, voor Adobe® Photoshop® CC Libraries assets. |
| asset_mod_time | double | r/w | Haalt of stelt de gewijzigde tijd van het asset in, voor Adobe® Photoshop® СС Libraries assets. |
| child_doc_id | string | r/w | Haalt of stelt de identifier van het onderliggende document in de liFE- of liFD-gegevensbron van de Lnk2 / LnkE Adobe® Photoshop® resource in. |
| comp_id | int | r/w | Haalt of stelt de ID van de momenteel geselecteerde comp voor het onderliggende document in, die -1 zal zijn als er geen is geselecteerd.<br/>            Comps zijn composities van een paginalay-out die ontwerpers kunnen maken. Met laag‑comps kun je meerdere versies<br/>            van een lay-out in één Adobe® Photoshop®‑bestand creëren, beheren en bekijken. Een laag‑comp is een momentopname van een toestand van het Layers‑paneel. Laag‑comps slaan drie soorten laagopties op, maar<br/>            deze eigenschap haalt de selectie‑identifier van de Layer Comp op voor Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| date | datetime | r/w | Haalt of stelt de laatste schrijf‑datum en -tijd van het externe bestand in de LiFE‑gegevensbron van de PSD LnkE‑resource in. |
| element_name | string | r/w | Haalt of stelt de naam van het grafische bibliotheek‑element in, voor Adobe® Photoshop® CC Libraries. |
| element_ref | string | r/w | Haalt of stelt de referentie van het grafische bibliotheek‑element in, voor Adobe® Photoshop® CC Libraries. |
| file_creator | string | r/w | Haalt of stelt de maker van het bestand in de PSD‑formaat LnkE / Lnk2‑resource in. |
| file_name | string | r/w | Haalt of stelt de naam van het externe of ingesloten bestand in de PSD‑koppelingsresource in. |
| file_size | long | r/w | Haalt of stelt de grootte van het externe bestand in de LiFE‑gegevensbron van de PSD LnkE‑resource in. |
| file_type | string | r/w | Haalt of stelt het type van het ingesloten of externe bestand in dat de Adobe® Photoshop® Lnk2 / LnkE‑resource bevat of waarnaar wordt gelinkt. |
| full_path | string | r/w | Haalt of stelt het volledige pad van het externe bestand in de LiFE‑gegevensbron van de PSD LnkE‑resource in. |
| has_file_open_descriptor | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze koppelings‑gegevensbron de bestands‑open‑descriptor heeft: CompId en OriginalCompId. |
| is_library_link | bool | r | Haalt een waarde op die aangeeft of deze PSD‑koppelings‑gegevensbron linkt naar het Adobe® Photoshop® СС Library‑item. |
| lengte | long | r | Haalt de lengte van de link-gegevensbron op in bytes. |
| original_comp_id | int | r | Haalt de originele ID op van de momenteel geselecteerde Comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd.<br/>            Deze eigenschap haalt de originele laag‑Comp‑selectie‑identifier op voor Smart Objects.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Haalt de originele bestandsnaam op van de gegevensbron in de Adobe® Photoshop® globale link‑resource. |
| relative_path | string | r/w | Haalt het relatieve pad op of stelt het in van het externe bestand in de LiFE‑gegevensbron van de PSD LnkE‑resource. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Haalt het type van de Adobe® Photoshop® globale link‑gegevensbron op, dat een van de volgende kan zijn of geen:<br/>            Het ingebedde gekoppelde bestand liFD dat overeenkomt met de PSD Lnk2Resource<br/>            Het externe gekoppelde bestand liFE dat overeenkomt met de PSD LnkeResource<br/>            Het gekoppelde bestand‑alias liFA |
| unique_id | Guid | r | Haalt de globale unieke identifier op van de gegevensbron in de PSD‑link‑resource. |
| version | int | r | Haalt de versie op van de gegevensbron in de PSD LnkE / Lnk2‑resource. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

Initialiseert een nieuw exemplaar van de [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klasse.

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Initialiseert een nieuw exemplaar van de [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| version | int | De versie. |
| unique_id | Guid | De unieke identifier. |
| original_file_name | string | Naam van het originele bestand. |
| file_type | string | Type van het bestand. |
| file_creator | string | De maker van het bestand. |

