---
title: "Cache"
second_title: "Aspose.PSD för Java API-referens"
description: "Innehåller cacheinställningar."
type: docs
weight: 14
url: /sv/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Innehåller cacheinställningar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Hämtar antalet tilldelade diskbyte. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Hämtar antalet tilldelade minnesbyte. |
| [getCacheFolder()](#getCacheFolder--) | Hämtar cache-mappen. |
| [getCacheType()](#getCacheType--) | Hämtar eller anger det använda cache‑schemat. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Hämtar ett värde som indikerar om omallokering ska vara exakt eller inte. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Hämtar det maximala tillgängliga diskutrymmet för cache. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Hämtar det maximala tillgängliga minnet för cache i minnet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Anger cache-mappen. |
| [setCacheType(int value)](#setCacheType-int-) | Anger det använda cache‑schemat. |
| [setDefaults()](#setDefaults--) | Anger cache‑inställningarna till standardvärden. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Anger ett värde som indikerar om omallokering ska vara exakt eller inte. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Anger det maximala tillgängliga diskutrymmet för cache. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Anger det maximala tillgängliga minnet för cache i minnet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Hämtar antalet tilldelade diskbyte.

**Returns:**
long - Det tilldelade antalet diskbyte.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Hämtar antalet tilldelade minnesbyte.

**Returns:**
long - Det tilldelade antalet minnesbyte.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Hämtar cache-mappen.

**Returns:**
java.lang.String - Cache-mappen.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Hämtar eller anger det använda cache‑schemat.

**Returns:**
int - Det använda cache‑schemat.
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


Hämtar ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokering inte är exakt bör prestandan vara högre.

**Returns:**
boolean -  true  om omallokeringen är exakt; annars,  false .

Den exakta omallokeringen kommer endast att omallokera ytterligare minne upp till den angivna övre gränsen. När den övre gränsen för minne i RAM anges under omallokeringen kopieras den cachade datan till disk om möjligt. När den övre gränsen för diskmemory anges under omallokeringen kastas lämpligt undantag. Prestandan bör vara högre om detta alternativ är avstängt eftersom ingen ytterligare kopiering kommer att utföras om möjligt, men detta kan också leda till att de angivna övre gränserna för minne eller disk överskrids.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Hämtar det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte.

**Returns:**
int - Det maximala tillgängliga diskutrymmet för cache.

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Hämtar det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte.

**Returns:**
int - Det maximala minnet för cache.

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns.
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


Anger cache-mappen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Cache‑mappen. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Anger det använda cache‑schemat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Det använda cache‑schemat. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Anger cache‑inställningarna till standardvärden.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Ställer in ett värde som indikerar om omallokeringen ska vara exakt eller inte. Om omallokeringen inte är exakt bör prestandan vara högre.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  om omallokeringen är exakt; annars,  false . |

Den exakta omallokeringen kommer endast att omallokera ytterligare minne upp till den angivna övre gränsen. När den övre gränsen för minne i RAM anges under omallokeringen kopieras den cachade datan till disk om möjligt. När den övre gränsen för diskmemory anges under omallokeringen kastas lämpligt undantag. Prestandan bör vara högre om detta alternativ är avstängt eftersom ingen ytterligare kopiering kommer att utföras om möjligt, men detta kan också leda till att de angivna övre gränserna för minne eller disk överskrids. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Ställer in det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Det maximala tillgängliga diskutrymmet för cache. |

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Ställer in det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Det maximala minnet för cache. |

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns. |

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

