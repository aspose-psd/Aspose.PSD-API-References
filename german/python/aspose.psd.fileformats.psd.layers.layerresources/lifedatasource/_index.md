---
title: "LiFeDataSource Klasse"
type: docs
weight: 520
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | Initialisiert eine neue Instanz der [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) Klasse. |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Initialisiert eine neue Instanz der [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| adobe_stock_id | string | r/w | Liest oder setzt die Grafikbibliothek AdobeStockId für Adobe® Photoshop® CC Bibliotheken. |
| adobe_stock_license_state | string | r | Ermittelt den Status der Adobe Stock-Lizenz, falls verfügbar, für Adobe® Photoshop® CC Libraries. |
| asset_locked_state | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das PSD-Asset gesperrt ist.<br/>            Der gesperrte Zustand des Assets, für Adobe® Photoshop® СС Libraries Assets. |
| asset_mod_time | double | r/w | Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® СС Libraries Assets. |
| child_doc_id | string | r/w | Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE- oder liFD-Datenquelle der Lnk2 / LnkE Adobe® Photoshop® Ressource. |
| comp_id | int | r/w | Liest oder setzt die ID der aktuell ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist.<br/>            Kompositionen sind Zusammenstellungen eines Seitenlayouts, die Designer erstellen können. Mit Layer‑Kompositionen können Sie mehrere Versionen eines Layouts in einer einzigen Adobe® Photoshop® Datei erstellen, verwalten und anzeigen. Eine Layer‑Komposition ist ein Schnappschuss eines Zustands des Ebenen‑Panels. Layer‑Kompositionen speichern drei Arten von Ebenenoptionen, aber diese Eigenschaft liefert die Auswahl‑Kennung der Layer‑Komposition für Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| date | datetime | r/w | Liest oder setzt das Datum und die Uhrzeit der letzten Schreiboperation der externen Datei in der LiFE-Datenquelle der PSD LnkE Ressource. |
| element_name | string | r/w | Liest oder setzt den Namen des Grafikbibliothekselements, für Adobe® Photoshop® CC Libraries. |
| element_ref | string | r/w | Liest oder setzt die Referenz des Grafikbibliothekselements, für Adobe® Photoshop® CC Libraries. |
| file_creator | string | r/w | Liest oder setzt den Ersteller der Datei im PSD-Format der LnkE / Lnk2 Ressource. |
| file_name | string | r/w | Liest oder setzt den Namen der externen oder eingebetteten Datei in der PSD‑Link‑Ressource. |
| file_size | long | r/w | Liest oder setzt die Größe der externen Datei in der LiFE-Datenquelle der PSD LnkE Ressource. |
| file_type | string | r/w | Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE Ressource enthält oder verlinkt. |
| full_path | string | r/w | Liest oder setzt den vollständigen Pfad der externen Datei in der LiFE-Datenquelle der PSD LnkE Ressource. |
| has_file_open_descriptor | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Link‑Datenquelle den Datei‑Öffnungs‑Deskriptor hat: CompId und OriginalCompId. |
| is_library_link | bool | r | Liest einen Wert, der angibt, ob diese PSD‑Link‑Datenquelle mit dem Adobe® Photoshop® СС‑Bibliothekselement verknüpft ist. |
| Länge | long | r | Liest die Länge der Link‑Datenquelle in Bytes. |
| original_comp_id | int | r | Liest die ursprüngliche ID des aktuell ausgewählten Comp für das Unterdokument, die -1 ist, wenn kein Comp ausgewählt ist.<br/>            Diese Eigenschaft liest den ursprünglichen Layer‑Comp‑Auswahl‑Identifikator für Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Liest den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop®‑globalen Link‑Ressource. |
| relative_path | string | r/w | Liest oder setzt den relativen Pfad der externen Datei in der LiFE‑Datenquelle der PSD‑LnkE‑Ressource. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Liest den Typ der Adobe® Photoshop®‑globalen Link‑Datenquelle, der einer der folgenden sein kann oder keiner:<br/>            Die eingebettete verknüpfte Datei liFD, die dem PSD Lnk2Resource entspricht<br/>            Die externe verknüpfte Datei liFE, die dem PSD LnkeResource entspricht<br/>            Der Alias der verknüpften Datei liFA |
| unique_id | Guid | r | Liest die global eindeutige Kennung der Datenquelle in der PSD‑Link‑Ressource. |
| version | int | r | Liest die Version der Datenquelle in der PSD‑LnkE‑/‑Lnk2‑Ressource. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

Initialisiert eine neue Instanz der [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) Klasse.

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Initialisiert eine neue Instanz der [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| version | int | Die Version. |
| unique_id | Guid | Der eindeutige Bezeichner. |
| original_file_name | string | Name der Originaldatei. |
| file_type | string | Typ der Datei. |
| file_creator | string | Der Dateiersteller. |

