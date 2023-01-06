---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD für .NET-API-Referenz
description: Der Namespace enthält Entitäten im PSDDateiformat die in Layern enthalten sind.
type: docs
weight: 270
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/
---
Der Namespace enthält Entitäten im PSD-Dateiformat, die in Layern enthalten sind.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource) | Basisklasse für Anpassungs-Layer-Ressourcen |
| [AnimatedDataSectionStructure](./animateddatasectionstructure) | Der Abschnitt mit animierten Daten. |
| [BlncResource](./blncresource) | BlncResource-Klasse ist eine Ressource der Farbanpassungsebene. |
| [BlwhResource](./blwhresource) | BlwhResource-Klasse ist eine Ressource der Schwarzweiß-Anpassungsebene. |
| [BooleanResource](./booleanresource) | Klasse BooleanResource. Es ist eine Pseudo-Ressource. Photoshop hat es nicht |
| [BritResource](./britresource) | Klasse BritResource. Ressource der Helligkeits-/Kontrastanpassungsebene |
| [CgEdResource](./cgedresource) | Klasse CgEdResource. Zusatzdaten des Inhaltsgenerators (Photoshop CS5) |
| [ClassID](./classid) | Das PSD-Klassen-ID-Objekt. |
| [ClblResource](./clblresource) | Klasse ClblResource. Diese Ressource enthält Informationen zum Mischen von abgeschnittenen Elementen. |
| [CmlsResource](./cmlsresource) | Klasse CmlsResource. |
| [ColorRangeHsl](./colorrangehsl) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource) hat 6 Farbbereiche, in denen Sie HSV-Parameter ändern können. Jeder Bereich hat 4 Schlüsselpunkte, um Bereichsgrenzen zu identifizieren. Und es ist ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager) | Manager für die Kurvenanpassungsebene, die Kurven manipuliert |
| [CurvesDiscreteManager](./curvesdiscretemanager) | Manager für die Kurvenanpassungsebene, die die Pixelkarte manipuliert |
| [CurvesManager](./curvesmanager) | Basisklasse zum Verwalten von CurvResource |
| [CurvResource](./curvresource) | Klasse CurvResource. Ressource für Kurvenanpassungsebene 1 Byte - 0, wenn Kurven verwendet werden, 1, wenn Pixel auf der Karte verwendet werden , wenn 0, dann: 2 Bytes - kurz. Standard ist 1 4 Bytes - int. Nur letztes Byte für Bit verwendet. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 2 Bytes – Anzahl der kurzen Punkte 4 Bytes * Anzahl der Punkte – Punkte der Kurve 2 kurz: erste Position, zweite Höhe 4 Bytes – Wort „Crv“ 2 Bytes – short Standard ist 4 für Curves 4 Bytes - int. Standard ist 1 4 Bytes - Punktzahl 4 Bytes * Punktzahl - Punkte von Kurve 2 kurz: erste Position, zweite Höhe 0-4 Bytes - Leading to be fold for four wenn 1 dann: 2 Bytes - kurz. Standard ist 1 4 Bytes - int. Nur letztes Byte verwendet. Ein Kanal ist in einem Bit. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 256 * Anzahl der geänderten Kanäle - geordnete Werte des Kanals im Bereich 0 - 255 4 Bytes - Wort "Crv " 2 Bytes - kurz. Standard ist 3 für Pixel auf map 4 Bytes - int Channel count (2 + 256) Bytes - kurz 2 für Kanalindex, 256 sind geordnete Werte des Kanals im Bereich 0 - 255 |
| [CustResource](./custresource) | Klasse CustResource. Diese Ressource enthält Informationen zum Mischen von abgeschnittenen Elementen. |
| [ExpaResource](./exparesource) | Klasse ExpaResource. Ressource der Belichtungsanpassungsebene |
| [FillLayerResource](./filllayerresource) | Basisklasse für Füllschicht-Ressourcen |
| [FilterEffectMaskData](./filtereffectmaskdata) | Die Datenklasse der Filtermaske. |
| [FXidResource](./fxidresource) | Die Ressource „Filtereffekte“ enthält Kanäle, eine Benutzermaske und eine Planmaske für den Smartfilter. |
| [FxrpResource](./fxrpresource) | Klasse FxrpResource. Der Bezugspunkt von layer |
| [GdFlResource](./gdflresource) | Klasse GdFlResource. Diese Ressource enthält Informationen zum Mischen von abgeschnittenen Elementen. |
| [Hue2Resource](./hue2resource) | Klasse Hue2Resource. Ressource der Belichtungsanpassungsebene |
| [InfxResource](./infxresource) | Class InfxResource. Diese Ressource enthält Informationen zum Mischen von abgeschnittenen Elementen. |
| [IopaResource](./ioparesource) | Klasse IopaResource. Diese Ressource enthält Informationen über die Fülldeckkrafteigenschaft aus dem Ebenenstil form |
| [KnkoResource](./knkoresource) | Klasse KnkoResource. Diese Ressource enthält Informationen zum Mischen von abgeschnittenen Elementen. |
| [LayerSectionResource](./layersectionresource) | Die Schichtabschnittsressource. |
| [LclrResource](./lclrresource) | Klasse LclrResource. Diese Ressource enthält Informationen über die Farbe der Ebene in der Liste der Ebenen ist PS. Es ist nur |
| [LevelChannel](./levelchannel) | Klasse zum Arbeiten mit Kanälen in der Ebenenanpassungsebene |
| [LevlResource](./levlresource) | Klasse LevelResource. Ressource der Belichtungsanpassungsebene |
| [Lfx2Resource](./lfx2resource) | Lfx2-Ressource (Effekt-Ressource) |
| [LiFdDataSource](./lifddatasource) | Definiert die liFD-Datenquellenklasse in der PSD-Datei, die Informationen über eine eingebettete Datei enthält. Dies ist Teil der PSD-Dateiformat-Manipulations-API, die hilft, Adobe® Photoshop®-Dateien zu ändern |
| [LiFeDataSource](./lifedatasource) | Definiert die LnkeDataSource-Klasse, die Informationen über extern verknüpfte Dateien enthält. Dies ist Teil der PSD-Dateiformat-Manipulations-API, die hilft, Adobe® Photoshop®-Dateien zu ändern |
| [LinkDataSource](./linkdatasource) | Definiert die LinkDataSource-Klasse, die Informationen zu einer verknüpften Datei oder einem Asset in der PSD-Datei enthält. |
| [LinkResource](./linkresource) | Definiert die LinkResource-Klasse, die Informationen über verknüpfte oder eingebettete Dateien im Bild im PSD-Format enthält. Die Link-Ressource kann mehrere enthalten[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) Instanzen, auf die von Indexern in jeder abgeleiteten Klasse zugegriffen werden kann. |
| [Lnk2Resource](./lnk2resource) | Definiert die Klasse, die Informationen über eingebettete Dateien im Bild im PSD-Format enthält. Die Link-Ressource kann mehrere enthalten[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) Instanzen, auf die der Indexer zugreifen kann. |
| [Lnk3Resource](./lnk3resource) | Definiert die Klasse, die Informationen über eine eingebettete Datei im PSD-Format 32 Bit pro Kanalbild enthält. Die Link-Ressource kann mehrere enthalten[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) Instanzen, auf die per Indexer zugegriffen werden kann. |
| [LnkeResource](./lnkeresource) | Definiert die Klasse LnkeResource, die Informationen über extern verknüpfte Dateien oder Assets im Bild im PSD-Format enthält. Die Link-Ressource kann mehrere enthalten[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource) Instanzen, auf die der Indexer zugreifen kann. Dies ist ein Teil der PSD-Dateiformat-Manipulations-API, die dabei hilft, Adobe® Photoshop®-Dateien programmgesteuert zu ändern |
| [LnsrResource](./lnsrresource) | Klasse lnsrResource. |
| [Lr16Resource](./lr16resource) | Die lr32-Ressource. |
| [Lr32Resource](./lr32resource) | Die lr32-Ressource. |
| [LspfResource](./lspfresource) | Ebenengeschützte Einstellungen |
| [LuniResource](./luniresource) | Schichtname resource |
| [LyidResource](./lyidresource) | Klasse LyidResource. |
| [MixrResource](./mixrresource) | Klasse MixrResource. Ressource der Kanalmixer-Anpassungsebene |
| [MlstResource](./mlstresource) | Die mlst-Ressource. Diese Klasse enthält unter anderem Informationen über die Position der Ebene auf der Zeitleiste. |
| [NvrtResource](./nvrtresource) | Klasse NvrtResource. Ressource für Anpassungsebene umkehren. |
| [OSTypeStructure](./ostypestructure) | Repräsentiert die Typstruktur des Betriebssystems. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry) | steht für die[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) Ressourcenregistrierung. |
| [PattResource](./pattresource) | Klasse PattResource. Ressource mit Muster data |
| [PattResourceData](./pattresourcedata) | Die Klasse zum Speichern der Musterdaten[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource) Ressource. |
| [PhflResource](./phflresource) | Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version ( = 3 ) oder ( = 2 ) 12 Jeweils 4 Byte für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 * 2 Byte Farbkomponente (nur in Version 2) 4 Dichte 1 Leuchtkraft erhalten |
| [PhflResourceVersion2](./phflresourceversion2) | Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version ( = 3 ) oder ( = 2 ) 12 Jeweils 4 Byte für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 * 2 Byte Farbkomponente (nur in Version 2) 4 Dichte 1 Leuchtkraft erhalten |
| [PhflResourceVersion3](./phflresourceversion3) | Klasse PhflResource. Ressource der Belichtungsanpassungsebene 2 Version ( = 3 ) oder ( = 2 ) 12 Jeweils 4 Byte für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 * 2 Byte Farbkomponente (nur in Version 2) 4 Dichte 1 Leuchtkraft erhalten |
| [PlacedResource](./placedresource) | Definiert die PlacedResource-Klasse, die allgemeine Informationen über eine platzierte Ebene oder eine Smart-Objekt-Ebene in der PSD-Datei enthält. Wird verwendet, um Smart-Objekt-Ebenen in den Adobe® Photoshop®-Bildern zu unterstützen. |
| [PlLdResource](./plldresource) | Definiert die PlLdResource-Klasse, die Informationen über eine platzierte Ebene in der PSD-Datei enthält. Wird verwendet, um intelligente Objektebenen in den Adobe® Photoshop®-Bildern zu unterstützen. Sie wurde in Adobe® Photoshop® CS3 durch SoLdResource ersetzt |
| [PtFlResource](./ptflresource) | Klasse PtFlResource. Enthält Musterfüllungs-Layerdaten. |
| [ShmdResource](./shmdresource) | Klasse ShmdResource. Metadateneinstellungen |
| [SmartObjectResource](./smartobjectresource) | Definiert die SmartObjectResource-Klasse, die Informationen zu einer Smart-Objekt-Ebene in einer PSD-Datei enthält. Dies ist die Basisklasse für Sold- und Sole-Ressourcen, die verwendet wird, um Smart-Objekt-Ebenen in den Adobe® Photoshop®-Bildern zu unterstützen. |
| [SmartResourceCreator](./smartresourcecreator) | Definiert die SmartResourceCreator-Klasse, die PlLd-, SoLd- und SoLe-Ressourcen erstellen kann. Wird verwendet, um intelligente Objektebenen in den Adobe® Photoshop®-Bildern zu unterstützen. |
| [SoCoResource](./socoresource) | Klasse SoCoResource. Diese Ressource enthält Informationen zu Farbfüllebenen |
| [SoLdResource](./soldresource) | Definiert die SoLdResource-Klasse, die Informationen zu einer Smart-Objekt-Ebene in einer PSD-Datei enthält. Wird verwendet, um Smart-Objekt-Ebenen in den Adobe® Photoshop®-Bildern zu unterstützen. |
| [SoLeResource](./soleresource) | Definiert die SoLeResource-Klasse, die Informationen über eine Smart-Objekt-Ebene in einer PSD-Datei enthält. Wird verwendet, um Smart-Objekt-Ebenen mit externen Dateiverknüpfungen in den Adobe® Photoshop®-Bildern zu unterstützen. |
| [Txt2Resource](./txt2resource) | Txt2-Ressourcenklasse |
| [TypeToolFontInfo](./typetoolfontinfo) | Enthält Informationen über die Schriftart des Textwerkzeugs. |
| [TypeToolInfo6Resource](./typetoolinfo6resource) | Die Typ-Tool-Informationen. Für PSD-Version höher oder gleich 6.0. |
| [TypeToolInfoResource](./typetoolinforesource) | Die Typ-Tool-Informationen. Für PSD-Version kleiner als 6.0. |
| [TypeToolLineInfo](./typetoollineinfo) | Werkzeugzeileninfo eingeben. |
| [TypeToolStyleInfo](./typetoolstyleinfo) | Informationen zum Werkzeugstil eingeben. |
| [UnknownResource](./unknownresource) | Die unbekannte Ressource. |
| [VectorPathDataResource](./vectorpathdataresource) | Klasse VectorPathDataResource. Diese Ressource enthält Informationen zur Vektorebenenmaske |
| [VibAResource](./vibaresource) | VibA-Ressource. |
| [VmskResource](./vmskresource) | Klasse VmskResource. Diese Ressource enthält Informationen über die Vektorebenenmaske |
| [VogkResource](./vogkresource) | Die Vektorentstehungsdaten-Ressource. |
| [VsmsResource](./vsmsresource) | Klasse VsmsResource. Diese Ressource enthält Informationen über die Vektorebenenmaske |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader) | Die[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) Ressourcenlader. |
| [IPlacedLayerResource](./iplacedlayerresource) | Definiert die IPlacedLayerResource-Schnittstelle, die Informationen über eine platzierte Ebene in der PSD-Datei enthält. Ist eine Markup-Schnittstelle, die verwendet wird, um PlLd-, Verkauft- und Sole-Ressourcen in den Adobe® Photoshop®-Bildern zu kennzeichnen. Wird verwendet, um intelligente Objektebenen zu unterstützen die Adobe® Photoshop®-Bilder. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource) | Definiert die ISmartObjectLayerResource-Schnittstelle, die Informationen über eine Smart-Object-Layer-Ressource in der PSD-Datei enthält. Dies ist auch eine Markup-Schnittstelle, die verwendet wird, um sowohl verkaufte als auch alleinige Ressourcen in den Adobe® Photoshop®-Bildern zu kennzeichnen. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [LayerLockType](./layerlocktype) | Ebenensperroptionen |
| [LayerSectionSubtype](./layersectionsubtype) | Der Abschnitt subtype |
| [LayerSectionType](./layersectiontype) | Der Ebenenabschnitt Typ |
| [LinkDataSourceType](./linkdatasourcetype) | Definiert die LinkDataSourceType-Aufzählung für die Datenquellen in der PSD-Link-Ressource. |
| [LnsrResourceType](./lnsrresourcetype) | Mögliche Lnsr-Ressourcentypen entdeckt |
| [PlacedLayerType](./placedlayertype) | Definiert die PlacedLayerType-Enumeration für die PlLd-Ressource der platzierten Ebene. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum) | Mögliche Farben der Blattfarbeinstellung. Dies ist die dekorative Farbe der Benutzeroberfläche der Ebene in der Ebenenliste in PS |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
