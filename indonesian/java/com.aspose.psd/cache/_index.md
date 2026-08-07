---
title: "Cache"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Berisi pengaturan cache."
type: docs
weight: 14
url: /id/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Berisi pengaturan cache.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Mendapatkan jumlah byte disk yang dialokasikan. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Mendapatkan jumlah byte memori dalam (in-memory) yang dialokasikan. |
| [getCacheFolder()](#getCacheFolder--) | Mendapatkan folder cache. |
| [getCacheType()](#getCacheType--) | Mendapatkan atau mengatur skema cache yang digunakan. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Mendapatkan nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Mendapatkan ruang disk maksimum yang tersedia untuk cache. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Mendapatkan memori maksimum yang tersedia untuk cache di memori. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Mengatur folder cache. |
| [setCacheType(int value)](#setCacheType-int-) | Mengatur skema cache yang digunakan. |
| [setDefaults()](#setDefaults--) | Mengatur pengaturan  Cache  ke nilai default. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Mengatur nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Mengatur ruang disk maksimum yang tersedia untuk cache. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Mengatur memori maksimum yang tersedia untuk cache di memori. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Mendapatkan jumlah byte disk yang dialokasikan.

**Returns:**
long - Jumlah byte disk yang dialokasikan.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Mendapatkan jumlah byte memori dalam (in-memory) yang dialokasikan.

**Returns:**
long - Jumlah byte memori dalam yang dialokasikan.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Mendapatkan folder cache.

**Returns:**
java.lang.String - Folder cache.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Mendapatkan atau mengatur skema cache yang digunakan.

**Returns:**
int - Skema cache yang digunakan.
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


Mendapatkan nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. Jika alokasi ulang tidak tepat, kinerja harus lebih tinggi.

**Returns:**
boolean -  true  jika alokasi ulang tepat; sebaliknya,  false .

Alokasi ulang yang tepat akan melakukan alokasi ulang memori tambahan hanya hingga batas atas yang ditentukan. Saat memberikan batas atas untuk memori dalam selama alokasi ulang, data yang di-cache akan disalin ke disk jika memungkinkan. Saat memberikan batas atas untuk memori disk selama alokasi ulang, pengecualian yang sesuai akan dilemparkan. Kinerja harus lebih tinggi jika opsi ini dimatikan karena tidak ada penyalinan tambahan yang akan dilakukan jika memungkinkan, namun hal ini juga dapat menyebabkan melewati batas atas yang ditentukan untuk memori atau disk.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Mendapatkan ruang disk maksimum yang tersedia untuk cache. Nilai yang ditentukan adalah jumlah megabyte.

**Returns:**
int - Ruang disk maksimum yang tersedia untuk cache.

Nilai 0 akan menggunakan semua memori yang tersedia dan berfungsi sebagai tanpa batas atas.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Mendapatkan memori maksimum yang tersedia untuk cache di memori. Nilai yang ditentukan adalah jumlah megabyte.

**Returns:**
int - Memori maksimum untuk cache.

Nilai 0 akan menggunakan semua memori yang tersedia dan berfungsi sebagai tanpa batas atas.
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


Mengatur folder cache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Folder cache. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Mengatur skema cache yang digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Skema cache yang digunakan. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Mengatur pengaturan  Cache  ke nilai default.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Mengatur nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. Jika alokasi ulang tidak tepat, kinerja seharusnya lebih tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  jika alokasi ulang tepat; sebaliknya,  false . |

Alokasi ulang yang tepat hanya akan melakukan alokasi ulang memori tambahan hingga batas atas yang ditentukan. Saat memberikan batas atas untuk memori dalam proses alokasi ulang, data yang di-cache akan disalin ke disk jika memungkinkan. Saat memberikan batas atas untuk memori disk selama alokasi ulang, pengecualian yang sesuai akan dilempar. Kinerja seharusnya lebih tinggi jika opsi ini dimatikan karena tidak ada penyalinan tambahan yang akan dilakukan jika memungkinkan, namun hal ini juga dapat menyebabkan melewati batas atas yang ditentukan untuk memori atau disk. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Mengatur ruang disk maksimum yang tersedia untuk cache. Nilai yang ditentukan adalah jumlah megabyte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Ruang disk maksimum yang tersedia untuk cache. |

Nilai 0 akan menggunakan semua memori yang tersedia dan berfungsi sebagai tanpa batas atas. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Mengatur memori maksimum yang tersedia untuk cache di memori. Nilai yang ditentukan adalah jumlah megabyte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Memori maksimum untuk cache. |

Nilai 0 akan menggunakan semua memori yang tersedia dan berfungsi sebagai tanpa batas atas. |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

