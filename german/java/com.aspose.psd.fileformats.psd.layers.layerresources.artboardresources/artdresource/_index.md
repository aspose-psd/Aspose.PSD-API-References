---
title: "ArtDResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Artboard-Info-Daten für PsdImage.GlobalLayerResources/."
type: docs
weight: 12
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtDResource extends BaseArtboardInfoResource
```

Die Artboard-Info-Daten für PsdImage.GlobalLayerResources ([PsdImage.getGlobalLayerResources](../../com.aspose.psd.fileformats.psd/psdimage\#getGlobalLayerResources)/[PsdImage.setGlobalLayerResources(LayerResource[])](../../com.aspose.psd.fileformats.psd/psdimage\#setGlobalLayerResources-LayerResource---)).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArtDResource()](#ArtDResource--) | Initialisiert eine neue Instanz der [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource)-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Die PSB‑Header‑Version |
| [PsbResourceSignature](#PsbResourceSignature) | Die PSB‑spezifische Ressourcen‑Signatur. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Die PSD‑Header‑Version |
| [ResourceSignature](#ResourceSignature) | Die allgemeine Ressourcen‑Signatur. |
| [TypeToolKey](#TypeToolKey) | Der Typ-Tool-Info-Schlüssel. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Die Venture-Lizenz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtboardCount_internalized()](#getArtboardCount-internalized--) | Ruft die Anzahl der Art-Boards ab oder legt sie fest. |
| [getAutoExpandOffset_internalized()](#getAutoExpandOffset-internalized--) | Ruft den Auto-Expand-Offset ab oder legt ihn fest. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Liest oder setzt die Ressourcenklassen-ID. |
| [getClassName_internalized()](#getClassName-internalized--) | Liest oder setzt den Namen der Ressourcenklasse. |
| [getDocDefaultNewArtboardBackgroundColor_internalized()](#getDocDefaultNewArtboardBackgroundColor-internalized--) | Ruft die DocDefaultNewArtboardBackgroundColor ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundColor_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [getDocDefaultNewArtboardBackgroundType_internalized()](#getDocDefaultNewArtboardBackgroundType-internalized--) | Ruft die DocDefaultNewArtboardBackgroundType ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundType_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)). |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getItems()](#getItems--) | Ruft die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-Elemente ab oder legt sie fest. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLength()](#getLength--) |    |
| [getOriginPoint_internalized()](#getOriginPoint-internalized--) | Ruft den Ursprungspunkt ab oder legt ihn fest. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getVersion_internalized()](#getVersion-internalized--) | Ruft die Ressourcen-Version ab oder legt sie fest. |
| [hashCode()](#hashCode--) |  |
| [isAutoExpandEnabled_internalized()](#isAutoExpandEnabled-internalized--) | Ruft die IsAutoExpandEnabled ab oder legt sie fest ([.isAutoExpandEnabled_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [isAutoNestEnabled_internalized()](#isAutoNestEnabled-internalized--) | Ruft die IsAutoNestEnabled ab oder legt sie fest ([.isAutoNestEnabled_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [isAutoPositionEnabled_internalized()](#isAutoPositionEnabled-internalized--) | Ruft die IsAutoPositionEnabled ab oder legt sie fest ([.isAutoPositionEnabled_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled_internalized(boolean)](../../null/\#setAutoPositionEnabled_internalized-boolean-)). |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [isShrinkwrapOnSaveEnabled_internalized()](#isShrinkwrapOnSaveEnabled-internalized--) | Ruft die IsShrinkwrapOnSaveEnabled ab oder legt sie fest ([.isShrinkwrapOnSaveEnabled_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled_internalized-boolean-)). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert die Ressource im angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setArtboardCount_internalized(int value)](#setArtboardCount-internalized-int-) | Ruft die Anzahl der Art-Boards ab oder legt sie fest. |
| [setAutoExpandEnabled_internalized(boolean value)](#setAutoExpandEnabled-internalized-boolean-) | Ruft die IsAutoExpandEnabled ab oder legt sie fest ([.isAutoExpandEnabled_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [setAutoExpandOffset_internalized(PointF value)](#setAutoExpandOffset-internalized-com.aspose.psd.PointF-) | Ruft den Auto-Expand-Offset ab oder legt ihn fest. |
| [setAutoNestEnabled_internalized(boolean value)](#setAutoNestEnabled-internalized-boolean-) | Ruft die IsAutoNestEnabled ab oder legt sie fest ([.isAutoNestEnabled_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [setAutoPositionEnabled_internalized(boolean value)](#setAutoPositionEnabled-internalized-boolean-) | Ruft die IsAutoPositionEnabled ab oder legt sie fest ([.isAutoPositionEnabled_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled_internalized(boolean)](../../null/\#setAutoPositionEnabled_internalized-boolean-)). |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Liest oder setzt die Ressourcenklassen-ID. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Liest oder setzt den Namen der Ressourcenklasse. |
| [setDocDefaultNewArtboardBackgroundColor_internalized(Color value)](#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-) | Ruft die DocDefaultNewArtboardBackgroundColor ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundColor_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [setDocDefaultNewArtboardBackgroundType_internalized(int value)](#setDocDefaultNewArtboardBackgroundType-internalized-int-) | Ruft die DocDefaultNewArtboardBackgroundType ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundType_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)). |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ruft die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-Elemente ab oder legt sie fest. |
| [setOriginPoint_internalized(PointF value)](#setOriginPoint-internalized-com.aspose.psd.PointF-) | Ruft den Ursprungspunkt ab oder legt ihn fest. |
| [setShrinkwrapOnSaveEnabled_internalized(boolean value)](#setShrinkwrapOnSaveEnabled-internalized-boolean-) | Ruft die IsShrinkwrapOnSaveEnabled ab oder legt sie fest ([.isShrinkwrapOnSaveEnabled_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled_internalized-boolean-)). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Ruft die Ressourcen-Version ab oder legt sie fest. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtDResource() {#ArtDResource--}
```
public ArtDResource()
```


Initialisiert eine neue Instanz der [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource)-Klasse.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Die PSB‑Header‑Version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Die PSB‑spezifische Ressourcen‑Signatur.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Die PSD‑Header‑Version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Die allgemeine Ressourcen‑Signatur.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Der Typ-Tool-Info-Schlüssel.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Die Venture-Lizenz.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. Einige Ressourcen werden derzeit nicht erkannt, aber wir haben eine vollständige Liste von PSB-spezifischen Ressourcen, die ihr Verhalten beim Speichern ändern. Daher müssen wir dies zumindest in UnknownResource überprüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Schlüssel. |

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
### getArtboardCount_internalized() {#getArtboardCount-internalized--}
```
public final int getArtboardCount_internalized()
```


Ruft die Anzahl der Art-Boards ab oder legt sie fest.

**Returns:**
int
### getAutoExpandOffset_internalized() {#getAutoExpandOffset-internalized--}
```
public final PointF getAutoExpandOffset_internalized()
```


Ruft den Auto-Expand-Offset ab oder legt ihn fest.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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
### getDocDefaultNewArtboardBackgroundColor_internalized() {#getDocDefaultNewArtboardBackgroundColor-internalized--}
```
public final Color getDocDefaultNewArtboardBackgroundColor_internalized()
```


Ruft die DocDefaultNewArtboardBackgroundColor ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundColor_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Returns:**
[Color](../../com.aspose.psd/color)
### getDocDefaultNewArtboardBackgroundType_internalized() {#getDocDefaultNewArtboardBackgroundType-internalized--}
```
public final int getDocDefaultNewArtboardBackgroundType_internalized()
```


Ruft die DocDefaultNewArtboardBackgroundType ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundType_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)).

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Ruft die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-Elemente ab oder legt sie fest.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Ermittelt den Schichtressourcen-Schlüssel.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


  

**Returns:**
int
### getOriginPoint_internalized() {#getOriginPoint-internalized--}
```
public final PointF getOriginPoint_internalized()
```


Ruft den Ursprungspunkt ab oder legt ihn fest.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Ermittelt die Präfixlänge. Standardwert ist 12 für 8BIM-Ressourcen und 16 für 8B64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdVersion | int | Die PSD‑Version. |

**Returns:**
int - Die Präfixlänge.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


Ruft die Ressourcen-Version ab oder legt sie fest.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoExpandEnabled_internalized() {#isAutoExpandEnabled-internalized--}
```
public final boolean isAutoExpandEnabled_internalized()
```


Ruft die IsAutoExpandEnabled ab oder legt sie fest ([.isAutoExpandEnabled_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoNestEnabled_internalized() {#isAutoNestEnabled-internalized--}
```
public final boolean isAutoNestEnabled_internalized()
```


Ruft die IsAutoNestEnabled ab oder legt sie fest ([.isAutoNestEnabled_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoPositionEnabled_internalized() {#isAutoPositionEnabled-internalized--}
```
public final boolean isAutoPositionEnabled_internalized()
```


Ruft die IsAutoPositionEnabled ab oder legt sie fest ([.isAutoPositionEnabled_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled_internalized(boolean)](../../null/\#setAutoPositionEnabled_internalized-boolean-)).

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bestimmt, ob die Ressource PSB-spezifisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Ressourcen-Schlüssel. |

**Returns:**
boolean -  true  wenn die Ressource PSB-spezifisch ist; andernfalls  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist.

Wert:  true  wenn diese Instanz ressourcen-PSB-spezifisch ist; andernfalls  false .

**Returns:**
boolean
### isShrinkwrapOnSaveEnabled_internalized() {#isShrinkwrapOnSaveEnabled-internalized--}
```
public final boolean isShrinkwrapOnSaveEnabled_internalized()
```


Ruft die IsShrinkwrapOnSaveEnabled ab oder legt sie fest ([.isShrinkwrapOnSaveEnabled_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled_internalized-boolean-)).

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |
| psdVersion | int | Die PSD‑Version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Speichert den benutzerdefinierten Ressourcen-Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Speichert die Header-Signatur, den Bezeichner und die Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |
| isLengthLong | boolean | wenn auf  true  gesetzt, ist die Länge lang. |

### setArtboardCount_internalized(int value) {#setArtboardCount-internalized-int-}
```
public final void setArtboardCount_internalized(int value)
```


Ruft die Anzahl der Art-Boards ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setAutoExpandEnabled_internalized(boolean value) {#setAutoExpandEnabled-internalized-boolean-}
```
public final void setAutoExpandEnabled_internalized(boolean value)
```


Ruft die IsAutoExpandEnabled ab oder legt sie fest ([.isAutoExpandEnabled_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAutoExpandOffset_internalized(PointF value) {#setAutoExpandOffset-internalized-com.aspose.psd.PointF-}
```
public final void setAutoExpandOffset_internalized(PointF value)
```


Ruft den Auto-Expand-Offset ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setAutoNestEnabled_internalized(boolean value) {#setAutoNestEnabled-internalized-boolean-}
```
public final void setAutoNestEnabled_internalized(boolean value)
```


Ruft die IsAutoNestEnabled ab oder legt sie fest ([.isAutoNestEnabled_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAutoPositionEnabled_internalized(boolean value) {#setAutoPositionEnabled-internalized-boolean-}
```
public final void setAutoPositionEnabled_internalized(boolean value)
```


Ruft die IsAutoPositionEnabled ab oder legt sie fest ([.isAutoPositionEnabled_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled_internalized(boolean)](../../null/\#setAutoPositionEnabled_internalized-boolean-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setDocDefaultNewArtboardBackgroundColor_internalized(Color value) {#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-}
```
public final void setDocDefaultNewArtboardBackgroundColor_internalized(Color value)
```


Ruft die DocDefaultNewArtboardBackgroundColor ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundColor_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDocDefaultNewArtboardBackgroundType_internalized(int value) {#setDocDefaultNewArtboardBackgroundType-internalized-int-}
```
public final void setDocDefaultNewArtboardBackgroundType_internalized(int value)
```


Ruft die DocDefaultNewArtboardBackgroundType ab oder legt sie fest ([.getDocDefaultNewArtboardBackgroundType_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Ruft die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)-Elemente ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setOriginPoint_internalized(PointF value) {#setOriginPoint-internalized-com.aspose.psd.PointF-}
```
public final void setOriginPoint_internalized(PointF value)
```


Ruft den Ursprungspunkt ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setShrinkwrapOnSaveEnabled_internalized(boolean value) {#setShrinkwrapOnSaveEnabled-internalized-boolean-}
```
public final void setShrinkwrapOnSaveEnabled_internalized(boolean value)
```


Ruft die IsShrinkwrapOnSaveEnabled ab oder legt sie fest ([.isShrinkwrapOnSaveEnabled_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled_internalized-boolean-)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Ruft die Ressourcen-Version ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
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

