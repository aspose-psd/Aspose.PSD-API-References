---
title: "Cache"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Bevat cache-instellingen."
type: docs
weight: 14
url: /nl/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Bevat cache-instellingen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Haalt het aantal toegewezen schijfbytes op. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Haalt het aantal toegewezen in‑memory bytes op. |
| [getCacheFolder()](#getCacheFolder--) | Haalt de cachemap op. |
| [getCacheType()](#getCacheType--) | Haalt het gebruikte cacheschema op of stelt het in. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Haalt een waarde op die aangeeft of herallocatie exact moet zijn of niet. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Haalt de maximaal beschikbare schijfruimte voor de cache op. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Haalt het maximaal beschikbare geheugen voor de cache in het geheugen op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Stelt de cachemap in. |
| [setCacheType(int value)](#setCacheType-int-) | Stelt het gebruikte cacheschema in. |
| [setDefaults()](#setDefaults--) | Stelt de cache‑instellingen in op de standaardwaarden. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Stelt een waarde in die aangeeft of herallocatie exact moet zijn of niet. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Stelt de maximaal beschikbare schijfruimte voor de cache in. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Stelt het maximaal beschikbare geheugen voor de cache in het geheugen in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Haalt het aantal toegewezen schijfbytes op.

**Returns:**
long - Het toegewezen aantal schijfbytes.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Haalt het aantal toegewezen in‑memory bytes op.

**Returns:**
long - Het toegewezen aantal in‑memory bytes.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Haalt de cachemap op.

**Returns:**
java.lang.String - De cachemap.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Haalt het gebruikte cacheschema op of stelt het in.

**Returns:**
int - Het gebruikte cacheschema.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


Haalt een waarde op die aangeeft of herallocatie exact moet zijn of niet. Als herallocatie niet exact is, zou de prestaties hoger moeten zijn.

**Returns:**
boolean -  true  als herallocatie exact is; anders,  false .

De exacte herallocatie zal extra geheugen alleen tot de opgegeven bovengrens heralloceren. Bij het doorgeven van een bovengrens voor in‑memory tijdens herallocatie wordt de gecachte data, indien mogelijk, naar de schijf gekopieerd. Bij het doorgeven van een bovengrens voor schijfgeheugen tijdens herallocatie wordt de juiste uitzondering gegooid. De prestaties zouden hoger moeten zijn als deze optie is uitgeschakeld, omdat er geen extra kopiëren wordt uitgevoerd indien mogelijk; dit kan echter ook leiden tot het overschrijden van de opgegeven limieten voor geheugen of schijf.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Haalt de maximaal beschikbare schijfruimte voor de cache op. De opgegeven waarde is het aantal megabytes.

**Returns:**
int - De maximale beschikbare schijfruimte voor cache.

Een waarde van 0 zal al het beschikbare geheugen verbruiken en fungeert als geen bovengrens.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Haalt het maximale beschikbare geheugen voor cache in het geheugen op. De opgegeven waarde is het aantal megabytes.

**Returns:**
int - Het maximale geheugen voor cache.

Een waarde van 0 zal al het beschikbare geheugen verbruiken en fungeert als geen bovengrens.
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




### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Stelt de cachemap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De cachemap. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Stelt het gebruikte cacheschema in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Het gebruikte cacheschema. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Stelt de cache‑instellingen in op de standaardwaarden.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Stelt een waarde in die aangeeft of herallocatie exact moet zijn of niet. Als herallocatie niet exact is, zou de prestaties hoger moeten zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  als herallocatie exact is; anders,  false . |

De exacte herallocatie zal extra geheugen alleen tot de opgegeven bovengrens heralloceren. Bij het doorgeven van een bovengrens voor in-memory tijdens herallocatie wordt de gecachte data, indien mogelijk, naar de schijf gekopieerd. Bij het doorgeven van een bovengrens voor schijfgeheugen tijdens herallocatie wordt de juiste uitzondering gegooid. De prestaties zouden hoger moeten zijn als deze optie is uitgeschakeld, omdat er geen extra kopiëren wordt uitgevoerd indien mogelijk, maar dit kan er ook toe leiden dat de opgegeven bovengrenzen voor geheugen of schijf worden overschreden. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Stelt de maximale beschikbare schijfruimte voor cache in. De opgegeven waarde is het aantal megabytes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De maximale beschikbare schijfruimte voor cache. |

Een waarde van 0 zal al het beschikbare geheugen verbruiken en fungeert als geen bovengrens. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Stelt het maximale beschikbare geheugen voor cache in het geheugen in. De opgegeven waarde is het aantal megabytes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Het maximale geheugen voor cache. |

Een waarde van 0 zal al het beschikbare geheugen verbruiken en fungeert als geen bovengrens. |

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

