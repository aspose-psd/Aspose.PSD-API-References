---
title: "SmartObjectProvider"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert den Smart-Object-Provider, der das Abrufen/Setzen von Datenquellen aus globalen Link-Ressourcen der PSD-Datei und deren Inhalte ermöglicht."
type: docs
weight: 17
url: /de/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Definiert den Smart-Object-Provider, der das Abrufen/Setzen von Datenquellen aus globalen Link-Ressourcen der PSD-Datei und deren Inhalte ermöglicht.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Konvertiert Ebenen in ein eingebettetes Smart‑Object. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Konvertiert Ebenen in ein eingebettetes Smart‑Object. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Initialisiert eine neue Instanz der Klasse [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Bettet alle verknüpften Smart‑Objects im Bild ein. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Ermittelt den Typ des Inhalts der Smart‑Object‑Ebene. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Ermittelt die eingebetteten oder verknüpften Dateiinhalte. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Ermittelt die Link‑Datenquelle anhand der eindeutigen ID. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Lädt die Inhalte. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Erstellt eine neue Smart‑Object‑Ebene, indem die Quell‑Ebene kopiert wird. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Entfernt Datenquellen aus eingebetteten und externen Ressourcen, die nicht in der bereitgestellten Liste gültiger GUIDs vorhanden sind. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Ersetzt die Datenquelle in den globalen Ressourcen durch die bereitgestellten Inhalte zum Einbetten. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Ersetzt die Datenquelle in einer globalen LinkResource‑Ressource durch die neu erstellte Datenquelle aus einer externen Datei. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Setzt die eingebetteten oder externen Dateiinhalte. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Setzt (ersetzt oder fügt hinzu) die Link‑Datenquelle in der globalen Link‑Ressource. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Aktualisiert den Inhalt aller modifizierten Smart‑Objects im Bild. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Aktualisiert alle Smart‑Object‑Ebenen im Container, deren  UniqueId  mit  oldGuid  übereinstimmt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Konvertiert Ebenen in ein eingebettetes Smart‑Object.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebenen. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Konvertiert Ebenen in ein eingebettetes Smart‑Object.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerNumbers | int[] | Die Ebenennummern. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Initialisiert eine neue Instanz der Klasse [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Der Container. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Bettet alle verknüpften Smart‑Objects im Bild ein.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


Ermittelt den Typ des Inhalts der Smart‑Object‑Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Der eindeutige Bezeichner. |

**Returns:**
int – Der Typ des Inhalts der Smart‑Object‑Ebene.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Ermittelt die eingebetteten oder verknüpften Dateiinhalte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Der eindeutige Bezeichner der verknüpften Datenquelle. |

**Returns:**
byte[] - Der  byte[]  Inhalt.
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Ermittelt die Link‑Datenquelle anhand der eindeutigen ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Der eindeutige Bezeichner. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


Lädt die Inhalte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Der eindeutige Bezeichner. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Erstellt eine neue Smart‑Object‑Ebene, indem die Quell‑Ebene kopiert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Die Quellschicht. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


Entfernt Datenquellen aus eingebetteten und externen Ressourcen, die nicht in der bereitgestellten Liste gültiger GUIDs vorhanden sind. Diese Methode bereinigt verwaiste Datenquellen, indem sie sie mit den aktuellen gültigen Datenquellenkennungen vergleicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | Die Liste der gültigen Datenquellen-GUIDs, die beibehalten werden sollen. Datenquellen, die nicht in dieser Liste enthalten sind, werden entfernt. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Ersetzt die Datenquelle in den globalen Ressourcen durch die bereitgestellten Inhalte zum Einbetten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | Der eindeutige Bezeichner der bestehenden Datenquelle. |
| contents | byte[] | Die Daten für eine neue Datenquelle. |

**Returns:**
com.aspose.ms.System.Guid - Der eindeutige Bezeichner der erstellten eingebetteten Datenquelle.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Ersetzt die Datenquelle in einer globalen LinkResource‑Ressource durch die neu erstellte Datenquelle aus einer externen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Die platzierte Ressource. |
| linkedPath | java.lang.String | Der absolute Pfad zur verknüpften Datei. |
| isReplaceOnlyThis | boolean | Wenn true, dann wird die Datenquelle in globalen Ressourcen nicht entfernt. |

**Returns:**
com.aspose.ms.System.Guid - Der eindeutige Bezeichner Guid der erstellten verknüpften Datenquelle. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Setzt die eingebetteten oder externen Dateiinhalte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Der eindeutige Bezeichner der verknüpften Datenquelle. |
| Daten | byte[] | Die Daten. |
| fileType | java.lang.String | Der Datendateityp. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Setzt (ersetzt oder fügt hinzu) die Link‑Datenquelle in der globalen Link‑Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Die verknüpfte Datenquelle. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


Aktualisiert den Inhalt aller modifizierten Smart‑Objects im Bild.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Aktualisiert alle Smart-Object-Ebenen innerhalb des Containers, deren  UniqueId  mit  oldGuid  übereinstimmt. Die passenden Ebenen‑UniqueId werden auf  newGuid  neu zugewiesen und ihr Inhalt wird aktualisiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | Der eindeutige Bezeichner der ursprünglichen Smart-Object-Datenquelle, die ersetzt werden soll. |
| newGuid | com.aspose.ms.System.Guid | Der eindeutige Bezeichner der neuen Smart-Object-Datenquelle, die zuzuweisen ist. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Die Auflösungseinstellungen, die beim Aktualisieren des Inhalts angewendet werden sollen. Wenn null, wird die Bildauflösung verwendet. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

