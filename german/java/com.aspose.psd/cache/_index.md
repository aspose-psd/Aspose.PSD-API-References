---
title: "Cache"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Enthält Cache-Einstellungen."
type: docs
weight: 14
url: /de/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Enthält Cache-Einstellungen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Liefert die Anzahl der zugewiesenen Festplattenbytes. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Liefert die Anzahl der zugewiesenen In-Memory-Bytes. |
| [getCacheFolder()](#getCacheFolder--) | Liefert den Cache-Ordner. |
| [getCacheType()](#getCacheType--) | Liefert oder setzt das verwendete Cache-Schema. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Liefert einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Liefert den maximal verfügbaren Festplattenspeicher für den Cache. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Liefert den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Setzt den Cache-Ordner. |
| [setCacheType(int value)](#setCacheType-int-) | Setzt das verwendete Cache-Schema. |
| [setDefaults()](#setDefaults--) | Setzt die Cache-Einstellungen auf die Standardwerte. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Setzt einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Setzt den maximal verfügbaren Festplattenspeicher für den Cache. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Setzt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Liefert die Anzahl der zugewiesenen Festplattenbytes.

**Returns:**
long - Die zugewiesene Festplattenbyte-Anzahl.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Liefert die Anzahl der zugewiesenen In-Memory-Bytes.

**Returns:**
long - Die zugewiesene In-Memory-Byte-Anzahl.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Liefert den Cache-Ordner.

**Returns:**
java.lang.String - Der Cache-Ordner.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Liefert oder setzt das verwendete Cache-Schema.

**Returns:**
int - Das verwendete Cache-Schema.
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


Gibt einen Wert zurück, der angibt, ob die Neuallokierung exakt sein soll oder nicht. Wenn die Neuallokierung nicht exakt ist, sollte die Leistung höher sein.

**Returns:**
boolean -  true  wenn die Neuallokierung exakt ist; andernfalls  false .

Die exakte Neuallokierung führt die Neuallokierung zusätzlichen Speichers nur bis zum angegebenen oberen Grenzwert durch. Beim Übergeben eines oberen Grenzwerts für den In‑Memory‑Speicher während der Neuallokierung werden die zwischengespeicherten Daten nach Möglichkeit auf die Festplatte kopiert. Beim Übergeben eines oberen Grenzwerts für den Festplattenspeicher während der Neuallokierung wird die entsprechende Ausnahme ausgelöst. Die Leistung sollte höher sein, wenn diese Option deaktiviert ist, da keine zusätzlichen Kopiervorgänge durchgeführt werden, sofern möglich; dies kann jedoch dazu führen, dass die angegebenen oberen Grenzwerte für Speicher oder Festplatte überschritten werden.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Gibt den maximal verfügbaren Festplattenspeicher für den Cache zurück. Der angegebene Wert ist die Megabyte‑Anzahl.

**Returns:**
int - Der maximal verfügbare Festplattenspeicher für den Cache.

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als kein oberer Grenzwert.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Gibt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher zurück. Der angegebene Wert ist die Megabyte‑Anzahl.

**Returns:**
int - Der maximale Speicher für den Cache.

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als kein oberer Grenzwert.
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


Setzt den Cache-Ordner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Cache‑Ordner. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Setzt das verwendete Cache-Schema.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das verwendete Cache‑Schema. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Setzt die Cache-Einstellungen auf die Standardwerte.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Legt einen Wert fest, der angibt, ob die Neuallokierung exakt sein soll oder nicht. Wenn die Neuallokierung nicht exakt ist, sollte die Leistung höher sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true  wenn die Neuallokierung exakt ist; andernfalls  false . |

Die exakte Neuallokierung führt die Neuallokierung zusätzlichen Speichers nur bis zum angegebenen oberen Grenzwert durch. Beim Übergeben eines oberen Grenzwerts für den In‑Memory‑Speicher während der Neuallokierung werden die zwischengespeicherten Daten nach Möglichkeit auf die Festplatte kopiert. Beim Übergeben eines oberen Grenzwerts für den Festplattenspeicher während der Neuallokierung wird die entsprechende Ausnahme ausgelöst. Die Leistung sollte höher sein, wenn diese Option deaktiviert ist, da keine zusätzlichen Kopiervorgänge durchgeführt werden, sofern möglich; dies kann jedoch dazu führen, dass die angegebenen oberen Grenzwerte für Speicher oder Festplatte überschritten werden. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Legt den maximal verfügbaren Festplattenspeicher für den Cache fest. Der angegebene Wert ist die Megabyte‑Anzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der maximal verfügbare Festplattenspeicher für den Cache. |

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als kein oberer Grenzwert. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Legt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher fest. Der angegebene Wert ist die Megabyte‑Anzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der maximale Speicher für den Cache. |

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als kein oberer Grenzwert. |

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

