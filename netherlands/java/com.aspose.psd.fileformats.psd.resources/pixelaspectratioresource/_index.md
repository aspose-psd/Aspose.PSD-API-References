---
title: "PixelAspectRatioResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Resource voor pixelverhouding"
type: docs
weight: 29
url: /nl/java/com.aspose.psd.fileformats.psd.resources/pixelaspectratioresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PixelAspectRatioResource extends ResourceBlock
```

Resource voor pixelverhouding
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PixelAspectRatioResource()](#PixelAspectRatioResource--) | Initialiseert een nieuw exemplaar van de klasse [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | De resourcesignatuur van ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | De reguliere Photoshop-resourcesignatuur. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Haalt of stelt de beeldverhouding in. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Haalt de grootte van de resourcegegevens op in bytes. |
| [getID()](#getID--) | Haalt of stelt de unieke identifier voor de resource in. |
| [getMinimalVersion()](#getMinimalVersion--) | Haalt de minimaal vereiste PSD-versie op. |
| [getName()](#getName--) | Haalt of stelt de resource‑naam in. |
| [getSignature()](#getSignature--) | Haalt de resourcesignatuur op. |
| [getSize()](#getSize--) | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| [getVersion()](#getVersion--) | Haalt of stelt de versie in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Slaat het resource‑blok op naar de opgegeven stream. |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Haalt of stelt de beeldverhouding in. |
| [setID(short value)](#setID-short-) | Haalt of stelt de unieke identifier voor de resource in. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Haalt of stelt de laag‑ en maskerinformatie in. |
| [setName(String value)](#setName-java.lang.String-) | Haalt of stelt de resource‑naam in. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Haalt of stelt de status van het resource‑blok in. |
| [setVersion(int value)](#setVersion-int-) | Haalt of stelt de versie in. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valideert de resource‑waarden. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelAspectRatioResource() {#PixelAspectRatioResource--}
```
public PixelAspectRatioResource()
```


Initialiseert een nieuw exemplaar van de klasse [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

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
### getAspectRatio() {#getAspectRatio--}
```
public final double getAspectRatio()
```


Haalt of stelt de beeldverhouding in.

Waarde: De beeldverhouding.

**Returns:**
double
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt of stelt de versie in.

Waarde: De versie.

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

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public final void setAspectRatio(double value)
```


Haalt of stelt de beeldverhouding in.

Waarde: De beeldverhouding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

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

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Haalt of stelt de versie in.

Waarde: De versie.

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

