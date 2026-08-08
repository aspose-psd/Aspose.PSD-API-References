---
title: "GridAndGuidesResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar rutnät- och guide-resursen."
type: docs
weight: 20
url: /sv/java/com.aspose.psd.fileformats.psd.resources/gridandguidesresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class GridAndGuidesResource extends ResourceBlock
```

Representerar rutnät- och guide-resursen.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GridAndGuidesResource()](#GridAndGuidesResource--) | Initierar en ny instans av klassen [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getGridCycleX()](#getGridCycleX--) | Hämtar eller anger den horisontella rutnätscykeln. |
| [getGridCycleY()](#getGridCycleY--) | Hämtar eller anger den vertikala rutnätscykeln. |
| [getGuideCount()](#getGuideCount--) | Hämtar antalet guide-resursblock. |
| [getGuides()](#getGuides--) | Hämtar eller anger guiderna. |
| [getHeaderVersion()](#getHeaderVersion--) | Hämtar eller anger huvudversionen. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setGridCycleX(int value)](#setGridCycleX-int-) | Hämtar eller anger den horisontella rutnätscykeln. |
| [setGridCycleY(int value)](#setGridCycleY-int-) | Hämtar eller anger den vertikala rutnätscykeln. |
| [setGuides(GuideResource[] value)](#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---) | Hämtar eller anger guiderna. |
| [setHeaderVersion(int value)](#setHeaderVersion-int-) | Hämtar eller anger huvudversionen. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GridAndGuidesResource() {#GridAndGuidesResource--}
```
public GridAndGuidesResource()
```


Initierar en ny instans av klassen [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Resurssignaturen för ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Den vanliga Photoshop-resurssignaturen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Hämtar resursens datastorlek i byte.

Värde: Resursens datastorlek.

**Returns:**
int
### getGridCycleX() {#getGridCycleX--}
```
public final int getGridCycleX()
```


Hämtar eller anger den horisontella rutnätscykeln. Standardvärdet är 576.

Värde: Den horisontella rutnätscykeln.

**Returns:**
int
### getGridCycleY() {#getGridCycleY--}
```
public final int getGridCycleY()
```


Hämtar eller anger den vertikala rutnätscykeln. Standardvärdet är 576.

Värde: Den vertikala rutnätscykeln.

**Returns:**
int
### getGuideCount() {#getGuideCount--}
```
public final int getGuideCount()
```


Hämtar antalet guide-resursblock.

Värde: Antalet guide-resursblock.

**Returns:**
int
### getGuides() {#getGuides--}
```
public final GuideResource[] getGuides()
```


Hämtar eller anger guiderna.

Värde: Guiderna.

**Returns:**
com.aspose.psd.fileformats.psd.resources.GuideResource[]
### getHeaderVersion() {#getHeaderVersion--}
```
public final int getHeaderVersion()
```


Hämtar eller anger huvudversionen. Detta värde ska alltid vara 1.

Värde: Huvudversionen.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Hämtar den minsta erforderliga PSD-versionen.

Värde: Den minsta psd-versionen.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Hämtar resursens signatur. Ska alltid vara '8BIM'.

Värde: Resursens signatur.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar resursblockets storlek i byte inklusive dess data.

Värde: Storleken på resursblocket.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Sparar resursblocket till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

### setGridCycleX(int value) {#setGridCycleX-int-}
```
public final void setGridCycleX(int value)
```


Hämtar eller anger den horisontella rutnätscykeln. Standardvärdet är 576.

Värde: Den horisontella rutnätscykeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGridCycleY(int value) {#setGridCycleY-int-}
```
public final void setGridCycleY(int value)
```


Hämtar eller anger den vertikala rutnätscykeln. Standardvärdet är 576.

Värde: Den vertikala rutnätscykeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGuides(GuideResource[] value) {#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---}
```
public final void setGuides(GuideResource[] value)
```


Hämtar eller anger guiderna.

Värde: Guiderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GuideResource\[\]](../../com.aspose.psd.fileformats.psd.resources/guideresource) |  |

### setHeaderVersion(int value) {#setHeaderVersion-int-}
```
public final void setHeaderVersion(int value)
```


Hämtar eller anger huvudversionen. Detta värde ska alltid vara 1.

Värde: Huvudversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Hämtar eller anger lager- och maskinformation.

Värde: Lager- och maskinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatur | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Hämtar eller anger resursblockets tillstånd.

Värde: Resursblockets tillstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Validerar resursvärdena.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

