---
title: "ResourceEvent"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Berisi dimensi untuk objek yang digambar."
type: docs
weight: 10
url: /id/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Berisi dimensi untuk objek yang digambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Menginisialisasi instance baru dari kelas  ResourceEvent  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Menambahkan kunci yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Mendapatkan aksi. |
| [getActionDate()](#getActionDate--) | Mendapatkan atau mengatur tanggal aksi. |
| [getChanged()](#getChanged--) | Mendapatkan daftar yang dipisahkan dengan titik koma dari bagian-bagian sumber daya yang diubah sejak riwayat peristiwa sebelumnya. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Mendapatkan nilai xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Mendapatkan URI namespace default. |
| [getParameters()](#getParameters--) | Mendapatkan atau mengatur deskripsi tambahan dari aksi. |
| [getPrefix()](#getPrefix--) | Mendapatkan prefiks. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Mendapatkan atau mengatur nama agen perangkat lunak. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Mendapatkan nilai string yang terkandung dalam format XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Mengatur aksi. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Mendapatkan atau mengatur tanggal aksi. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Mengatur daftar yang dipisahkan dengan titik koma dari bagian-bagian sumber daya yang diubah sejak riwayat peristiwa sebelumnya. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Mendapatkan atau mengatur nilai xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Mendapatkan atau mengatur deskripsi tambahan dari aksi. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Mendapatkan atau mengatur nama agen perangkat lunak. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Menginisialisasi instance baru dari kelas  ResourceEvent  .

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Menambahkan kunci yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| nilai | java.lang.Object | Nilai yang akan ditambahkan ke. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Mendapatkan aksi.

Nilai yang didefinisikan adalah: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nilai baru harus berupa kata kerja dalam bentuk lampau.

**Returns:**
java.lang.String - Aksi.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Mendapatkan atau mengatur tanggal aksi.

**Returns:**
java.util.Date - Tanggal aksi.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Mendapatkan daftar yang dipisahkan dengan titik koma dari bagian-bagian sumber daya yang diubah sejak riwayat peristiwa sebelumnya.

**Returns:**
java.lang.String - Daftar yang dipisahkan dengan titik koma dari bagian-bagian sumber daya yang diubah sejak riwayat peristiwa sebelumnya.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Mendapatkan nilai xmpMM:InstanceId.

**Returns:**
java.util.UUID - Nilai dari xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Mendapatkan URI namespace default.

**Returns:**
java.lang.String - URI namespace default.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Mendapatkan atau mengatur deskripsi tambahan dari aksi.

Nilai: Deskripsi tambahan dari aksi.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Mendapatkan prefiks.

**Returns:**
java.lang.String - Prefiks.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Mendapatkan atau mengatur nama agen perangkat lunak.

**Returns:**
java.lang.String - Nama agen perangkat lunak.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Mendapatkan nilai string yang terkandung dalam format XMP.

**Returns:**
java.lang.String - Mengembalikan nilai string yang terkandung dalam format XMP.
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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Mengatur aksi.

Nilai yang didefinisikan adalah: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nilai baru harus berupa kata kerja dalam bentuk lampau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Aksi. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Mendapatkan atau mengatur tanggal aksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date | Tanggal aksi. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Mengatur daftar yang dipisahkan dengan titik koma dari bagian-bagian sumber daya yang diubah sejak riwayat peristiwa sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Daftar yang dipisahkan dengan titik koma dari bagian-bagian sumber daya yang diubah sejak riwayat peristiwa sebelumnya. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Mendapatkan atau mengatur nilai xmpMM:InstanceId.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID | Nilai dari xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Mendapatkan atau mengatur deskripsi tambahan dari aksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Deskripsi tambahan dari aksi. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Mendapatkan atau mengatur nama agen perangkat lunak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nama agen perangkat lunak. |

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

