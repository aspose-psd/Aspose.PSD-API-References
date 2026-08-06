---
title: "Cache"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Contient les paramètres du cache."
type: docs
weight: 14
url: /fr/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contient les paramètres du cache.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Obtient le nombre d'octets disque alloués. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Obtient le nombre d'octets en mémoire alloués. |
| [getCacheFolder()](#getCacheFolder--) | Obtient le dossier du cache. |
| [getCacheType()](#getCacheType--) | Obtient ou définit le schéma de cache utilisé. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Obtient une valeur indiquant si la réallocation doit être exacte ou non. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Obtient l'espace disque maximal disponible pour le cache. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Obtient la mémoire maximale disponible pour le cache en mémoire. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Définit le dossier du cache. |
| [setCacheType(int value)](#setCacheType-int-) | Définit le schéma de cache utilisé. |
| [setDefaults()](#setDefaults--) | Définit les paramètres du cache aux valeurs par défaut. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Définit une valeur indiquant si la réallocation doit être exacte ou non. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Définit l'espace disque maximal disponible pour le cache. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Définit la mémoire maximale disponible pour le cache en mémoire. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Obtient le nombre d'octets disque alloués.

**Returns:**
long - Le nombre d'octets disque alloués.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Obtient le nombre d'octets en mémoire alloués.

**Returns:**
long - Le nombre d'octets en mémoire alloués.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Obtient le dossier du cache.

**Returns:**
java.lang.String - Le dossier du cache.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Obtient ou définit le schéma de cache utilisé.

**Returns:**
int - Le schéma de cache utilisé.
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


Obtient une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures.

**Returns:**
boolean -  true  si la réallocation est exacte ; sinon,  false .

La réallocation exacte effectuera la réallocation de mémoire supplémentaire uniquement jusqu'à la limite supérieure spécifiée. Lors du passage de la limite supérieure pour la mémoire en cours d'exécution pendant la réallocation, les données mises en cache seront copiées sur le disque si possible. Lors du passage de la limite supérieure pour la mémoire disque pendant la réallocation, l'exception appropriée est levée. Les performances devraient être supérieures si cette option est désactivée, car aucune copie supplémentaire ne sera effectuée si possible ; cependant, cela peut également entraîner le dépassement des limites supérieures spécifiées pour la mémoire ou le disque.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Obtient l'espace disque maximal disponible pour le cache. La valeur spécifiée est le nombre de mégaoctets.

**Returns:**
int - L'espace disque maximal disponible pour le cache.

Une valeur de 0 consommera toute la mémoire disponible et constitue l'absence de limite supérieure.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Obtient la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée est le nombre de mégaoctets.

**Returns:**
int - La mémoire maximale pour le cache.

Une valeur de 0 consommera toute la mémoire disponible et constitue l'absence de limite supérieure.
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


Définit le dossier du cache.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le dossier du cache. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Définit le schéma de cache utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le schéma de cache utilisé. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Définit les paramètres du cache aux valeurs par défaut.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | booléen | true si la réallocation est exacte ; sinon, false. |

La réallocation exacte effectuera la réallocation de mémoire supplémentaire uniquement jusqu'à la limite supérieure spécifiée. Lors du passage de la limite supérieure pour la mémoire en cours lors de la réallocation, les données mises en cache seront copiées sur le disque si possible. Lors du passage de la limite supérieure pour la mémoire disque lors de la réallocation, l'exception appropriée est levée. Les performances devraient être supérieures si cette option est désactivée, car aucune copie supplémentaire ne sera effectuée si possible, cependant cela peut également entraîner le dépassement des limites supérieures spécifiées pour la mémoire ou le disque. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Définit l'espace disque maximal disponible pour le cache. La valeur spécifiée correspond au nombre de mégaoctets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | L'espace disque maximal disponible pour le cache. |

Une valeur de 0 consommera toute la mémoire disponible et sert de limite supérieure inexistante. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée correspond au nombre de mégaoctets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La mémoire maximale pour le cache. |

Une valeur de 0 consommera toute la mémoire disponible et sert de limite supérieure inexistante. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

