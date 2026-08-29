---
title: "Cache"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Contiene la configuración de caché."
type: docs
weight: 14
url: /es/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contiene la configuración de caché.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Obtiene la cantidad de bytes de disco asignados. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Obtiene la cantidad de bytes en memoria asignados. |
| [getCacheFolder()](#getCacheFolder--) | Obtiene la carpeta de caché. |
| [getCacheType()](#getCacheType--) | Obtiene o establece el esquema de caché utilizado. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Obtiene un valor que indica si la reasignación debe ser exacta o no. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Obtiene el espacio máximo disponible en disco para la caché. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Obtiene la memoria máxima disponible para la caché en memoria. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Establece la carpeta de caché. |
| [setCacheType(int value)](#setCacheType-int-) | Establece el esquema de caché utilizado. |
| [setDefaults()](#setDefaults--) | Establece la configuración de la Caché a los valores predeterminados. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Establece un valor que indica si la reasignación debe ser exacta o no. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Establece el espacio máximo disponible en disco para la caché. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Establece la memoria máxima disponible para la caché en memoria. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Obtiene la cantidad de bytes de disco asignados.

**Returns:**
long - La cantidad de bytes de disco asignados.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Obtiene la cantidad de bytes en memoria asignados.

**Returns:**
long - La cantidad de bytes en memoria asignados.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Obtiene la carpeta de caché.

**Returns:**
java.lang.String - La carpeta de caché.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Obtiene o establece el esquema de caché utilizado.

**Returns:**
int - El esquema de caché utilizado.
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


Obtiene un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

**Returns:**
boolean -  true  si la reasignación es exacta; de lo contrario,  false .

La reasignación exacta realizará la reasignación de memoria adicional solo hasta el límite superior especificado. Al pasar el límite superior para la memoria en RAM durante la reasignación, los datos en caché se copiarán al disco si es posible. Al pasar el límite superior para la memoria en disco durante la reasignación, se lanzará la excepción correspondiente. El rendimiento debería ser mayor si esta opción está desactivada, ya que no se realizará copia adicional si es posible; sin embargo, esto también puede llevar a superar los límites superiores especificados para la memoria o el disco.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Obtiene el espacio máximo disponible en disco para la caché. El valor especificado es la cantidad de megabytes.

**Returns:**
int - El espacio máximo disponible en disco para la caché.

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Obtiene la memoria máxima disponible para la caché en memoria. El valor especificado es la cantidad de megabytes.

**Returns:**
int - La memoria máxima para la caché.

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior.
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


Establece la carpeta de caché.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La carpeta de caché. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Establece el esquema de caché utilizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El esquema de caché utilizado. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Establece la configuración de la Caché a los valores predeterminados.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true si la reasignación es exacta; de lo contrario, false. |

La reasignación exacta realizará la reasignación de memoria adicional solo hasta el límite superior especificado. Al pasar el límite superior para la memoria en RAM durante la reasignación, los datos en caché se copiarán al disco si es posible. Al pasar el límite superior para la memoria en disco durante la reasignación, se lanzará la excepción apropiada. El rendimiento debería ser mayor si esta opción está desactivada, ya que no se realizará copia adicional si es posible; sin embargo, esto también puede llevar a superar los límites superiores especificados para memoria o disco. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Establece el espacio máximo disponible en disco para la caché. El valor especificado es la cantidad de megabytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El espacio máximo disponible en disco para la caché. |

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Establece la memoria máxima disponible para la caché en memoria. El valor especificado es la cantidad de megabytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La memoria máxima para la caché. |

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior. |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

