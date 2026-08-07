---
title: "LiFdDataSource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die liFD-Datenquellenklasse in einer PSD-Datei, die Informationen über eine eingebettete Datei enthält."
type: docs
weight: 10
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFdDataSource extends LinkDataSource
```

Definiert die liFD-Datenquellenklasse in PSD File, die Informationen über eine eingebettete Datei enthält. Dies ist Teil der PSD File Format Manipulation API, die beim Ändern von Adobe® Photoshop®‑Dateien hilft.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LiFdDataSource()](#LiFdDataSource--) | Initialisiert eine neue Instanz der Klasse [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource). |
| [LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | Die Deskriptor-Version. |
| [LatestVersion_internalized](#LatestVersion-internalized) | Die neueste verfügbare Version der Link-Datenquelle |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Der unerwartete Typwert der Link-Datenquelle |
| [ZeroChar_internalized](#ZeroChar-internalized) | Das Nullzeichen |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Liest oder setzt einen Wert, der angibt, ob das PSD-Asset gesperrt ist. |
| [getAssetModTime()](#getAssetModTime--) | Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® \\u0421\\u0421 Libraries-Assets. |
| [getChildDocId()](#getChildDocId--) | Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE- oder liFD-Datenquelle der Lnk2 / LnkE Adobe® Photoshop®-Ressource. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Liest oder setzt die Ressourcenklassen-ID. |
| [getClassName_internalized()](#getClassName-internalized--) | Liest oder setzt den Namen der Ressourcenklasse. |
| [getCompId()](#getCompId--) | Liest oder setzt die ID der aktuell ausgewählten Komponente für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Liest oder setzt die ContentID-Eigenschaft. |
| [getData()](#getData--) | Liest oder setzt die eingebetteten Smart‑Object‑Daten in einer PSD‑Datei. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Liest die Länge der eingebetteten Daten. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Liest die Länge der Link-Quellendaten. |
| [getFileCreator()](#getFileCreator--) | Liest oder setzt den Dateiersteller in der PSD-Format LnkE / Lnk2-Ressource. |
| [getFileType()](#getFileType--) | Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE-Ressource enthält oder verlinkt. |
| [getItems_internalized()](#getItems-internalized--) | Liest oder setzt das OSTypeStructure-Array, das Ressourceneigenschaften definiert. |
| [getLength()](#getLength--) | Liest die Länge der Link-Datenquelle in Bytes. |
| [getOriginalCompId()](#getOriginalCompId--) | Liest die ursprüngliche ID der aktuell ausgewählten Comp für das Unterdokument, die -1 ist, wenn keine ausgewählt ist. |
| [getOriginalFileName()](#getOriginalFileName--) | Liest den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop® Global Link-Ressource. |
| [getType()](#getType--) | Liest den Adobe® Photoshop® Global Link-Datenquellentyp, der einer der folgenden sein kann oder keiner: Die eingebettete verknüpfte Datei liFD, die dem PSD Lnk2Resource entspricht; Die externe verknüpfte Datei liFE, die dem PSD LnkeResource entspricht; Der verknüpfte Datei-Alias liFA. |
| [getUniqueId()](#getUniqueId--) | Liest den globalen eindeutigen Bezeichner der Datenquelle in der PSD-Link-Ressource. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Liest oder setzt die unbekannten Daten, die vor den Eigenschaften von Items OSTypeStructures stehen. |
| [getVersion()](#getVersion--) | Liest die Version der Datenquelle in der PSD LnkE / Lnk2-Ressource. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Liest oder setzt einen Wert, der angibt, ob diese Link-Datenquelle den Datei-Öffnungsdeskriptor hat: CompId und OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Liest einen Wert, der angibt, ob diese PSD-Link-Datenquelle mit dem Adobe® Photoshop® \\u0421\\u0421 Bibliothekselement verknüpft ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Speichert die Blockdaten der Link-Datenquelle. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Liest oder setzt einen Wert, der angibt, ob das PSD-Asset gesperrt ist. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® \\u0421\\u0421 Libraries-Assets. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE- oder liFD-Datenquelle der Lnk2 / LnkE Adobe® Photoshop®-Ressource. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Liest oder setzt die Ressourcenklassen-ID. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Liest oder setzt den Namen der Ressourcenklasse. |
| [setCompId(int value)](#setCompId-int-) | Liest oder setzt die ID der aktuell ausgewählten Komponente für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Liest oder setzt die ContentID-Eigenschaft. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt die eingebetteten Smart‑Object‑Daten in einer PSD‑Datei. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Liest oder setzt den Dateiersteller in der PSD-Format LnkE / Lnk2-Ressource. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Link-Datenquelle den Datei-Öffnungsdeskriptor hat: CompId und OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE-Ressource enthält oder verlinkt. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Liest oder setzt das OSTypeStructure-Array, das Ressourceneigenschaften definiert. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Liest einen Wert, der angibt, ob diese PSD-Link-Datenquelle mit dem Adobe® Photoshop® \\u0421\\u0421 Bibliothekselement verknüpft ist. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Liest die ursprüngliche ID der aktuell ausgewählten Comp für das Unterdokument, die -1 ist, wenn keine ausgewählt ist. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Liest den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop® Global Link-Ressource. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Setzt den Eigenschaftswert nach Typstruktur. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Liest den globalen eindeutigen Bezeichner der Datenquelle in der PSD-Link-Ressource. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Liest oder setzt die unbekannten Daten, die vor den Eigenschaften von Items OSTypeStructures stehen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFdDataSource() {#LiFdDataSource--}
```
public LiFdDataSource()
```


Initialisiert eine neue Instanz der Klasse [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource).

### LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Initialisiert eine neue Instanz der Klasse [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| version | int | Die Version. |
| uniqueId | java.util.UUID | Der eindeutige Bezeichner. |
| originalFileName | java.lang.String | Name der Originaldatei. |
| fileType | java.lang.String | Typ der Datei. |
| fileCreator | java.lang.String | Der Dateiersteller. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


Die Deskriptor-Version.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


Die neueste verfügbare Version der Link-Datenquelle

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Der unerwartete Typwert der Link-Datenquelle

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Das Nullzeichen

### create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFdDataSource create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| version | int |  |
| guid | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource)
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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Liest oder setzt einen Wert, der angibt, ob das PSD-Asset gesperrt ist. Der gesperrte Zustand des Assets für Adobe® Photoshop® \u0421\u0421 Libraries-Assets.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® \\u0421\\u0421 Libraries-Assets.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE- oder liFD-Datenquelle der Lnk2 / LnkE Adobe® Photoshop®-Ressource.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Liest oder setzt die Ressourcenklassen-ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Liest oder setzt den Namen der Ressourcenklasse.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Liest oder setzt die ID der aktuell ausgewählten Comp für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Comps sind Zusammensetzungen eines Seitenlayouts, die Designer erstellen können. Mit Layer‑Comps können Sie mehrere Versionen eines Layouts in einer einzigen Adobe® Photoshop®‑Datei erstellen, verwalten und anzeigen. Ein Layer‑Comp ist ein Schnappschuss eines Zustands des Layers‑Panels. Layer‑Comps speichern drei Arten von Layer‑Optionen, aber diese Eigenschaft liefert die Auswahl‑Kennung des Layer‑Comp für Smart Objects.  Layer‑Comps in Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Liest oder setzt die ContentID‑Eigenschaft. Der Wert dieser Eigenschaft wird nur gelesen und gespeichert, wenn Version >= 8 ist.

**Returns:**
java.lang.String
### getData() {#getData--}
```
public final byte[] getData()
```


Liest oder setzt die eingebetteten Smart‑Object‑Daten in einer PSD‑Datei.

Wert: Die eingebetteten Smart-Objektdaten.

**Returns:**
byte[]
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Liest die Länge der eingebetteten Daten.

Wert: Die Länge der eingebetteten Daten.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Liest die Länge der Link-Quellendaten.

**Returns:**
long – Die Länge der Quelldaten.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Liest oder setzt den Dateiersteller in der PSD-Format LnkE / Lnk2-Ressource.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE-Ressource enthält oder verlinkt.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Liest oder setzt das OSTypeStructure-Array, das Ressourceneigenschaften definiert.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Liest die Länge der Link-Datenquelle in Bytes.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Liest die ursprüngliche ID der aktuell ausgewählten Comp für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Diese Eigenschaft liefert die ursprüngliche Auswahl‑Kennung des Layer‑Comp für Smart Objects.  Layer‑Comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Liest den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop® Global Link-Ressource.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Liest den Adobe® Photoshop® Global Link-Datenquellentyp, der einer der folgenden sein kann oder keiner: Die eingebettete verknüpfte Datei liFD, die dem PSD Lnk2Resource entspricht; Die externe verknüpfte Datei liFE, die dem PSD LnkeResource entspricht; Der verknüpfte Datei-Alias liFA.

Wert: Der PSD‑Link‑Datenquellentyp.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Liest den globalen eindeutigen Bezeichner der Datenquelle in der PSD-Link-Ressource.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Liest oder setzt die unbekannten Daten, die vor den Eigenschaften von Items OSTypeStructures stehen.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liest die Version der Datenquelle in der PSD LnkE / Lnk2-Ressource.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Liest oder setzt einen Wert, der angibt, ob diese Link-Datenquelle den Datei-Öffnungsdeskriptor hat: CompId und OriginalCompId.

Wert:  true  wenn diese Instanz einen offenen Dateideskriptor hat; andernfalls  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Liest einen Wert, der angibt, ob diese PSD-Link-Datenquelle mit dem Adobe® Photoshop® \\u0421\\u0421 Bibliothekselement verknüpft ist.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Speichert die Blockdaten der Link-Datenquelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob das PSD-Asset gesperrt ist. Der gesperrte Zustand des Assets für Adobe® Photoshop® \u0421\u0421 Libraries-Assets.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Liest oder setzt die Änderungszeit des Assets, für Adobe® Photoshop® \\u0421\\u0421 Libraries-Assets.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Liest oder setzt die Kennung des untergeordneten Dokuments in der liFE- oder liFD-Datenquelle der Lnk2 / LnkE Adobe® Photoshop®-Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Liest oder setzt die Ressourcenklassen-ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Liest oder setzt den Namen der Ressourcenklasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Liest oder setzt die ID der aktuell ausgewählten Comp für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Comps sind Zusammensetzungen eines Seitenlayouts, die Designer erstellen können. Mit Layer‑Comps können Sie mehrere Versionen eines Layouts in einer einzigen Adobe® Photoshop®‑Datei erstellen, verwalten und anzeigen. Ein Layer‑Comp ist ein Schnappschuss eines Zustands des Layers‑Panels. Layer‑Comps speichern drei Arten von Layer‑Optionen, aber diese Eigenschaft liefert die Auswahl‑Kennung des Layer‑Comp für Smart Objects.  Layer‑Comps in Smart Objects

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Liest oder setzt die ContentID‑Eigenschaft. Der Wert dieser Eigenschaft wird nur gelesen und gespeichert, wenn Version >= 8 ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Liest oder setzt die eingebetteten Smart‑Object‑Daten in einer PSD‑Datei.

Wert: Die eingebetteten Smart-Objektdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Liest oder setzt den Dateiersteller in der PSD-Format LnkE / Lnk2-Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Link-Datenquelle den Datei-Öffnungsdeskriptor hat: CompId und OriginalCompId.

Wert:  true  wenn diese Instanz einen offenen Dateideskriptor hat; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Liest oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2 / LnkE-Ressource enthält oder verlinkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Liest oder setzt das OSTypeStructure-Array, das Ressourceneigenschaften definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Liest einen Wert, der angibt, ob diese PSD-Link-Datenquelle mit dem Adobe® Photoshop® \\u0421\\u0421 Bibliothekselement verknüpft ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Liest die ursprüngliche ID der aktuell ausgewählten Comp für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Diese Eigenschaft liefert die ursprüngliche Auswahl‑Kennung des Layer‑Comp für Smart Objects.  Layer‑Comps in Smart Objects

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Liest den ursprünglichen Dateinamen der Datenquelle in der Adobe® Photoshop® Global Link-Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Setzt den Eigenschaftswert nach Typstruktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Die Struktur. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Liest den globalen eindeutigen Bezeichner der Datenquelle in der PSD-Link-Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Liest oder setzt die unbekannten Daten, die vor den Eigenschaften von Items OSTypeStructures stehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

