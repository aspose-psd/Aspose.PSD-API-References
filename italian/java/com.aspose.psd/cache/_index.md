---
title: "Cache"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Contiene le impostazioni della cache."
type: docs
weight: 14
url: /it/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contiene le impostazioni della cache.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Ottiene il conteggio dei byte su disco allocati. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Ottiene il conteggio dei byte in memoria allocati. |
| [getCacheFolder()](#getCacheFolder--) | Ottiene la cartella della cache. |
| [getCacheType()](#getCacheType--) | Ottiene o imposta lo schema della cache utilizzato. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Ottiene un valore che indica se la riallocazione deve essere esatta o meno. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Ottiene lo spazio su disco massimo disponibile per la cache. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Ottiene la memoria massima disponibile per la cache in memoria. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Imposta la cartella della cache. |
| [setCacheType(int value)](#setCacheType-int-) | Imposta lo schema della cache utilizzato. |
| [setDefaults()](#setDefaults--) | Imposta le impostazioni della  Cache  ai valori predefiniti. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Imposta un valore che indica se la riallocazione deve essere esatta o meno. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Imposta lo spazio su disco massimo disponibile per la cache. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Imposta la memoria massima disponibile per la cache in memoria. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Ottiene il conteggio dei byte su disco allocati.

**Returns:**
long - Il conteggio dei byte su disco allocati.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Ottiene il conteggio dei byte in memoria allocati.

**Returns:**
long - Il conteggio dei byte in memoria allocati.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Ottiene la cartella della cache.

**Returns:**
java.lang.String - La cartella della cache.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Ottiene o imposta lo schema della cache utilizzato.

**Returns:**
int - Lo schema della cache utilizzato.
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


Ottiene un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori.

**Returns:**
boolean -  true  se la riallocazione è esatta; altrimenti,  false .

La riallocazione esatta eseguirà la riallocazione della memoria aggiuntiva solo fino al limite superiore specificato. Quando si passa il limite superiore per la memoria in RAM durante la riallocazione, i dati nella cache verranno copiati su disco se possibile. Quando si passa il limite superiore per la memoria su disco durante la riallocazione, viene sollevata l'eccezione appropriata. Le prestazioni dovrebbero essere superiori se questa opzione è disattivata, poiché non verrà eseguita alcuna copia aggiuntiva se possibile, tuttavia ciò potrebbe anche portare a superare i limiti superiori specificati per la memoria o il disco.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Ottiene lo spazio su disco massimo disponibile per la cache. Il valore specificato è il conteggio dei megabyte.

**Returns:**
int - Lo spazio su disco massimo disponibile per la cache.

Il valore 0 consumerà tutta la memoria disponibile e fungerà da limite superiore inesistente.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Restituisce la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.

**Returns:**
int - La memoria massima per la cache.

Il valore 0 consumerà tutta la memoria disponibile e fungerà da limite superiore inesistente.
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


Imposta la cartella della cache.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La cartella della cache. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Imposta lo schema della cache utilizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Lo schema della cache utilizzato. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Imposta le impostazioni della  Cache  ai valori predefiniti.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta le prestazioni dovrebbero essere superiori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  se la riallocazione è esatta; altrimenti,  false . |

La riallocazione esatta effettuerà la riallocazione della memoria aggiuntiva solo fino al limite superiore specificato. Quando si passa il limite superiore per la memoria in RAM durante la riallocazione, i dati memorizzati nella cache verranno copiati su disco, se possibile. Quando si passa il limite superiore per la memoria su disco durante la riallocazione, viene sollevata l'eccezione appropriata. Le prestazioni dovrebbero essere superiori se questa opzione è disattivata, poiché non verrà eseguita alcuna copia aggiuntiva, se possibile; tuttavia ciò potrebbe anche portare a superare i limiti superiori specificati per la memoria o il disco. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Imposta lo spazio su disco massimo disponibile per la cache. Il valore specificato è il conteggio dei megabyte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Lo spazio su disco massimo disponibile per la cache. |

Il valore 0 consumerà tutta la memoria disponibile e fungerà da limite superiore inesistente. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La memoria massima per la cache. |

Il valore 0 consumerà tutta la memoria disponibile e fungerà da limite superiore inesistente. |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

