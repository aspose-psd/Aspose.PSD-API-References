---
title: "LiFdDataSource Klasse"
type: docs
weight: 510
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | Initialisiert eine neue Instanz der Klasse [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Initialisiert eine neue Instanz der Klasse [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das PSD-Asset gesperrt ist.<br/>            Der gesperrte Zustand des Assets, für Adobe® Photoshop® СС Libraries Assets. |
| asset_mod_time | double | r/w | Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® СС Libraries Assets. |
| child_doc_id | string | r/w | Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE- oder liFD-Datenquelle der Lnk2 / LnkE Adobe® Photoshop® Ressource. |
| comp_id | int | r/w | Liest oder setzt die ID der aktuell ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist.<br/>            Kompositionen sind Zusammenstellungen eines Seitenlayouts, die Designer erstellen können. Mit Layer‑Kompositionen können Sie mehrere Versionen eines Layouts in einer einzigen Adobe® Photoshop® Datei erstellen, verwalten und anzeigen. Eine Layer‑Komposition ist ein Schnappschuss eines Zustands des Ebenen‑Panels. Layer‑Kompositionen speichern drei Arten von Ebenenoptionen, aber diese Eigenschaft liefert die Auswahl‑Kennung der Layer‑Komposition für Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| data | byte | r/w | Liest oder setzt die eingebetteten Smart-Object-Daten in einer PSD-Datei. |
| file_creator | string | r/w | Liest oder setzt den Ersteller der Datei im PSD-Format der LnkE / Lnk2 Ressource. |
| file_type | string | r/w | Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE Ressource enthält oder verlinkt. |
| has_file_open_descriptor | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Link‑Datenquelle den Datei‑Öffnungs‑Deskriptor hat: CompId und OriginalCompId. |
| is_library_link | bool | r | Liest einen Wert, der angibt, ob diese PSD‑Link‑Datenquelle mit dem Adobe® Photoshop® СС‑Bibliothekselement verknüpft ist. |
| Länge | long | r | Liest die Länge der Link‑Datenquelle in Bytes. |
| original_comp_id | int | r | Liest die ursprüngliche ID des aktuell ausgewählten Comp für das Unterdokument, die -1 ist, wenn kein Comp ausgewählt ist.<br/>            Diese Eigenschaft liest den ursprünglichen Layer‑Comp‑Auswahl‑Identifikator für Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Liest den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop®‑globalen Link‑Ressource. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Liest den Typ der Adobe® Photoshop®‑globalen Link‑Datenquelle, der einer der folgenden sein kann oder keiner:<br/>            Die eingebettete verknüpfte Datei liFD, die dem PSD Lnk2Resource entspricht<br/>            Die externe verknüpfte Datei liFE, die dem PSD LnkeResource entspricht<br/>            Der Alias der verknüpften Datei liFA |
| unique_id | Guid | r | Liest die global eindeutige Kennung der Datenquelle in der PSD‑Link‑Ressource. |
| version | int | r | Liest die Version der Datenquelle in der PSD‑LnkE‑/‑Lnk2‑Ressource. |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

Initialisiert eine neue Instanz der Klasse [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Initialisiert eine neue Instanz der Klasse [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| version | int | Die Version. |
| unique_id | Guid | Der eindeutige Bezeichner. |
| original_file_name | string | Name der Originaldatei. |
| file_type | string | Typ der Datei. |
| file_creator | string | Der Dateiersteller. |

