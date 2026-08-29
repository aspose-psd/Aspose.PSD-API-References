---
title: "Klasse LiFdDataSource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource Klasse. Definiert die liFD-Datenquellen‑Klasse in einer PSD‑Datei, die Informationen über eine eingebettete Datei enthält. Dies ist Teil der PSD‑Dateiformat‑Manipulations‑API, die beim Ändern von Adobe‑Photoshop‑Dateien hilft."
type: docs
weight: 2970
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
{{< psd/tize >}}
## LiFdDataSource class

Definiert die liFD-Datenquellklasse in PSD-Datei, die Informationen über eine eingebettete Datei enthält. Dies ist Teil der PSD File Format Manipulation API, die beim Ändern von Adobe® Photoshop®-Dateien hilft.

```csharp
public class LiFdDataSource : LinkDataSource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | Initialisiert eine neue Instanz der `LiFdDataSource`‑Klasse. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | Initialisiert eine neue Instanz der `LiFdDataSource`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das PSD‑Asset gesperrt ist. Der gesperrte Zustand des Assets, für Adobe® Photoshop® CC Libraries‑Assets. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® CC Libraries‑Assets. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE‑ oder liFD‑Datenquelle des Lnk2 / LnkE‑Adobe®‑Photoshop‑Ressource. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Liest oder setzt die ID der aktuell ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Kompositionen (Comps) sind Zusammensetzungen eines Seitenlayouts, die Designer erstellen können. Mit Layer‑Comps können Sie mehrere Versionen eines Layouts in einer einzigen Adobe® Photoshop®‑Datei erstellen, verwalten und anzeigen. Ein Layer‑Comp ist ein Schnappschuss eines Zustands des Ebenen‑Panels. Layer‑Comps speichern drei Arten von Ebenenoptionen, aber diese Eigenschaft liest die Auswahl‑ID des Layer‑Comp für Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | Liest oder setzt die eingebetteten Smart‑Object‑Daten in einer PSD‑Datei. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Liest oder setzt den Dateiersteller in der PSD‑Format‑LnkE / Lnk2‑Ressource. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE‑Ressource enthält oder verlinkt. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Link‑Datenquelle den offenen Dateideskriptor hat: CompId und OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Liest einen Wert, der angibt, ob diese PSD‑Link‑Datenquelle mit dem Adobe® Photoshop® CC‑Bibliothekselement verknüpft ist. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Liest die Länge der Link‑Datenquelle in Bytes. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Liest die ursprüngliche ID der aktuell ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Diese Eigenschaft liest die ursprüngliche Auswahl‑ID des Layer‑Comp für Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Ruft den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop® Global Link-Ressource ab. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Ruft den Adobe® Photoshop® Global Link-Datentyp der Datenquelle ab, der einer der folgenden Werte oder keiner sein kann: Die eingebettete verknüpfte Datei liFD, die der PSD Lnk2Resource entspricht; Die extern verknüpfte Datei liFE, die der PSD LnkeResource entspricht; Der Alias der verknüpften Datei liFA. |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Ruft die global eindeutige Kennung der Datenquelle in der PSD-Link-Ressource ab. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Ruft die Version der Datenquelle in der PSD LnkE / Lnk2-Ressource ab. |

### Siehe auch

* class [LinkDataSource](../linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


