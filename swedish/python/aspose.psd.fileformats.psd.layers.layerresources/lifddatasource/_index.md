---
title: "LiFdDataSource-klass"
type: docs
weight: 510
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | Initierar en ny instans av klassen [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Initierar en ny instans av klassen [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst.<br/> Tillgångens låsta tillstånd, för Adobe® Photoshop® СС Libraries‑tillgångar. |
| asset_mod_time | double | r/w | Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® СС Libraries‑tillgångar. |
| child_doc_id | string | r/w | Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen. |
| comp_id | int | r/w | Hämtar eller anger ID för den för närvarande valda compen för underdokumentet, vilket blir -1 om ingen är vald.<br/>            Comps är sammansättningar av en sidlayout som designers kan skapa. Med lager‑comps kan du skapa, hantera och visa flera versioner<br/>            av en layout i en enda Adobe® Photoshop®-fil. En lager‑comp är en ögonblicksbild av ett tillstånd i lagerpanelen. Lager‑comps sparar tre typer av lageralternativ men<br/>            den här egenskapen hämtar identifieraren för lager‑comp‑urvalet för Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Lager‑comps i Smart Objects</see> |
| data | byte | r/w | Hämtar eller anger den inbäddade smartobjektsdatan i PSD-filen. |
| file_creator | string | r/w | Hämtar eller anger filskaparen i PSD-formatet LnkE / Lnk2‑resursen. |
| file_type | string | r/w | Hämtar eller anger typen på den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE‑resursen innehåller eller länkar till. |
| has_file_open_descriptor | bool | r/w | Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId. |
| is_library_link | bool | r | Hämtar ett värde som indikerar om denna PSD‑länkdatas källa länkar till Adobe® Photoshop® СС‑biblioteksposten. |
| längd | long | r | Hämtar länkdatas källa längd i byte. |
| original_comp_id | int | r | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald.<br/>            Denna egenskap hämtar det ursprungliga lager‑Comp‑urvalets identifierare för Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps i Smart Objects</see> |
| original_file_name | string | r | Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkresurs. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Hämtar Adobe® Photoshop® globala länkdatas‑typ som kan vara någon av följande eller ingen:<br/>            Den inbäddade länkade filen liFD som motsvarar PSD Lnk2Resource<br/>            Den externa länkade filen liFE som motsvarar PSD LnkeResource<br/>            Den länkade filaliasen liFA |
| unique_id | Guid | r | Hämtar den globala unika identifieraren för datakällan i PSD link resource. |
| version | int | r | Hämtar versionen av datakällan i PSD LnkE / Lnk2‑resursen. |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

Initierar en ny instans av klassen [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Initierar en ny instans av klassen [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| version | int | Versionen. |
| unique_id | Guid | Den unika identifieraren. |
| original_file_name | string | Namn på den ursprungliga filen. |
| file_type | string | Filens typ. |
| file_creator | string | Filens skapare. |

