---
title: "GridAndGuidesResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Vertegenwoordigt de raster‑ en hulplijnen‑resource."
type: docs
weight: 20
url: /nl/java/com.aspose.psd.fileformats.psd.resources/gridandguidesresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class GridAndGuidesResource extends ResourceBlock
```

Vertegenwoordigt de raster‑ en hulplijnen‑resource.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GridAndGuidesResource()](#GridAndGuidesResource--) | Initialiseert een nieuw exemplaar van de [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | De resourcesignatuur van ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | De reguliere Photoshop-resourcesignatuur. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Haalt de grootte van de resourcegegevens op in bytes. |
| [getGridCycleX()](#getGridCycleX--) | Haalt op of stelt de horizontale rastercyclus in. |
| [getGridCycleY()](#getGridCycleY--) | Haalt op of stelt de verticale rastercyclus in. |
| [getGuideCount()](#getGuideCount--) | Haalt het aantal gidsresourceblokken op. |
| [getGuides()](#getGuides--) | Haalt op of stelt de gidsen in. |
| [getHeaderVersion()](#getHeaderVersion--) | Haalt op of stelt de headerversie in. |
| [getID()](#getID--) | Haalt of stelt de unieke identifier voor de resource in. |
| [getMinimalVersion()](#getMinimalVersion--) | Haalt de minimaal vereiste PSD-versie op. |
| [getName()](#getName--) | Haalt of stelt de resource‑naam in. |
| [getSignature()](#getSignature--) | Haalt de resourcesignatuur op. |
| [getSize()](#getSize--) | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Slaat het resource‑blok op naar de opgegeven stream. |
| [setGridCycleX(int value)](#setGridCycleX-int-) | Haalt op of stelt de horizontale rastercyclus in. |
| [setGridCycleY(int value)](#setGridCycleY-int-) | Haalt op of stelt de verticale rastercyclus in. |
| [setGuides(GuideResource[] value)](#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---) | Haalt op of stelt de gidsen in. |
| [setHeaderVersion(int value)](#setHeaderVersion-int-) | Haalt op of stelt de headerversie in. |
| [setID(short value)](#setID-short-) | Haalt of stelt de unieke identifier voor de resource in. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Haalt of stelt de laag‑ en maskerinformatie in. |
| [setName(String value)](#setName-java.lang.String-) | Haalt of stelt de resource‑naam in. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Haalt of stelt de status van het resource‑blok in. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valideert de resource‑waarden. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GridAndGuidesResource() {#GridAndGuidesResource--}
```
public GridAndGuidesResource()
```


Initialiseert een nieuw exemplaar van de [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource) klasse.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


De resourcesignatuur van ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


De reguliere Photoshop-resourcesignatuur.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de grootte van de resourcegegevens op in bytes.

Waarde: De grootte van de resourcegegevens.

**Returns:**
int
### getGridCycleX() {#getGridCycleX--}
```
public final int getGridCycleX()
```


Haalt op of stelt de horizontale rastercyclus in. Standaard is 576.

Waarde: De horizontale rastercyclus.

**Returns:**
int
### getGridCycleY() {#getGridCycleY--}
```
public final int getGridCycleY()
```


Haalt op of stelt de verticale rastercyclus in. Standaard is 576.

Waarde: De verticale rastercyclus.

**Returns:**
int
### getGuideCount() {#getGuideCount--}
```
public final int getGuideCount()
```


Haalt het aantal gidsresourceblokken op.

Waarde: Het aantal gidsresourceblokken.

**Returns:**
int
### getGuides() {#getGuides--}
```
public final GuideResource[] getGuides()
```


Haalt op of stelt de gidsen in.

Waarde: De gidsen.

**Returns:**
com.aspose.psd.fileformats.psd.resources.GuideResource[]
### getHeaderVersion() {#getHeaderVersion--}
```
public final int getHeaderVersion()
```


Haalt op of stelt de headerversie in. Deze waarde moet altijd 1 zijn.

Waarde: De headerversie.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Haalt of stelt de unieke identifier voor de resource in.

Waarde: De unieke identifier voor de resource.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Haalt de minimaal vereiste PSD-versie op.

Waarde: De minimale PSD-versie.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een null‑naam bestaat uit twee bytes van 0).

Waarde: De resource‑naam.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Haalt de resourcehandtekening op. Zou altijd '8BIM' moeten zijn.

Waarde: De resourcehandtekening.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens.

Waarde: De grootte van het resourceblok.

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


Slaat het resource‑blok op naar de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream om het resourceblok op te slaan. |

### setGridCycleX(int value) {#setGridCycleX-int-}
```
public final void setGridCycleX(int value)
```


Haalt op of stelt de horizontale rastercyclus in. Standaard is 576.

Waarde: De horizontale rastercyclus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGridCycleY(int value) {#setGridCycleY-int-}
```
public final void setGridCycleY(int value)
```


Haalt op of stelt de verticale rastercyclus in. Standaard is 576.

Waarde: De verticale rastercyclus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGuides(GuideResource[] value) {#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---}
```
public final void setGuides(GuideResource[] value)
```


Haalt op of stelt de gidsen in.

Waarde: De gidsen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [GuideResource\[\]](../../com.aspose.psd.fileformats.psd.resources/guideresource) |  |

### setHeaderVersion(int value) {#setHeaderVersion-int-}
```
public final void setHeaderVersion(int value)
```


Haalt op of stelt de headerversie in. Deze waarde moet altijd 1 zijn.

Waarde: De headerversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Haalt of stelt de unieke identifier voor de resource in.

Waarde: De unieke identifier voor de resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Haalt of stelt de laag‑ en maskerinformatie in.

Waarde: De laag‑ en maskerinformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een null‑naam bestaat uit twee bytes van 0).

Waarde: De resource‑naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| handtekening | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Haalt of stelt de status van het resource‑blok in.

Waarde: De status van het resourceblok.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


Valideert de resource‑waarden.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

