---
title: "LiFeDataSource-klass"
type: docs
weight: 520
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | Initierar en ny instans av [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klassen. |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Initierar en ny instans av [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| adobe_stock_id | string | r/w | Hämtar eller anger grafikbibliotekets AdobeStockId, för Adobe® Photoshop® CC Libraries. |
| adobe_stock_license_state | string | r | Hämtar tillståndet för adobe stock-licensen om den är tillgänglig, för Adobe® Photoshop® CC libraries. |
| asset_locked_state | bool | r/w | Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst.<br/> Tillgångens låsta tillstånd, för Adobe® Photoshop® СС Libraries‑tillgångar. |
| asset_mod_time | double | r/w | Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® СС Libraries‑tillgångar. |
| child_doc_id | string | r/w | Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen. |
| comp_id | int | r/w | Hämtar eller anger ID för den för närvarande valda compen för underdokumentet, vilket blir -1 om ingen är vald.<br/>            Comps är sammansättningar av en sidlayout som designers kan skapa. Med lager‑comps kan du skapa, hantera och visa flera versioner<br/>            av en layout i en enda Adobe® Photoshop®-fil. En lager‑comp är en ögonblicksbild av ett tillstånd i lagerpanelen. Lager‑comps sparar tre typer av lageralternativ men<br/>            den här egenskapen hämtar identifieraren för lager‑comp‑urvalet för Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Lager‑comps i Smart Objects</see> |
| date | datetime | r/w | Hämtar eller anger det senaste skrivdatumet och -tiden för den externa filen i LiFE-datakällan för PSD LnkE‑resursen. |
| element_name | string | r/w | Hämtar eller anger grafikbibliotekets elementnamn, för Adobe® Photoshop® CC Libraries. |
| element_ref | string | r/w | Hämtar eller anger grafikbibliotekets elementreferens, för Adobe® Photoshop® CC Libraries. |
| file_creator | string | r/w | Hämtar eller anger filskaparen i PSD-formatet LnkE / Lnk2‑resursen. |
| file_name | string | r/w | Hämtar eller anger namnet på den externa eller inbäddade filen i PSD link resource. |
| file_size | long | r/w | Hämtar eller anger storleken på den externa filen i LiFE‑datakällan för PSD LnkE‑resursen. |
| file_type | string | r/w | Hämtar eller anger typen på den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE‑resursen innehåller eller länkar till. |
| full_path | string | r/w | Hämtar eller anger den fullständiga sökvägen för den externa filen i LiFE‑datakällan för PSD LnkE‑resursen. |
| has_file_open_descriptor | bool | r/w | Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId. |
| is_library_link | bool | r | Hämtar ett värde som indikerar om denna PSD‑länkdatas källa länkar till Adobe® Photoshop® СС‑biblioteksposten. |
| längd | long | r | Hämtar länkdatas källa längd i byte. |
| original_comp_id | int | r | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald.<br/>            Denna egenskap hämtar det ursprungliga lager‑Comp‑urvalets identifierare för Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps i Smart Objects</see> |
| original_file_name | string | r | Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkresurs. |
| relative_path | string | r/w | Hämtar eller anger den relativa sökvägen för den externa filen i LiFE‑datakällan för PSD LnkE‑resursen. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Hämtar Adobe® Photoshop® globala länkdatas‑typ som kan vara någon av följande eller ingen:<br/>            Den inbäddade länkade filen liFD som motsvarar PSD Lnk2Resource<br/>            Den externa länkade filen liFE som motsvarar PSD LnkeResource<br/>            Den länkade filaliasen liFA |
| unique_id | Guid | r | Hämtar den globala unika identifieraren för datakällan i PSD link resource. |
| version | int | r | Hämtar versionen av datakällan i PSD LnkE / Lnk2‑resursen. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

Initierar en ny instans av [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klassen.

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Initierar en ny instans av [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| version | int | Versionen. |
| unique_id | Guid | Den unika identifieraren. |
| original_file_name | string | Namn på den ursprungliga filen. |
| file_type | string | Filens typ. |
| file_creator | string | Filens skapare. |

