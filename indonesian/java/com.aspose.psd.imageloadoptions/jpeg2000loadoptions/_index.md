---
title: "Jpeg2000LoadOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi pemuatan JPEG2000"
type: docs
weight: 10
url: /id/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

Opsi pemuatan JPEG2000
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Menginisialisasi instance baru dari kelas  Jpeg2000LoadOptions  . |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Sumber font khusus |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Mendapatkan Warna latar belakang Gambar. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Mendapatkan mode pemulihan data. |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | Mendapatkan waktu dekode maksimum default. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Mendapatkan nilai yang menunjukkan apakah [ignore after load]. |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Mendapatkan waktu dekode maksimum dalam detik (opsi ini dapat digunakan pada mesin dengan memori sangat lambat untuk mencegah proses menggantung pada gambar sangat besar - resolusi lebih dari 5500x6500 piksel). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Mendapatkan waktu dekode maksimum untuk ubin. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan penangan peristiwa kemajuan. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Mendapatkan nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Ini adalah bagian dari pola lisensi ventura. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Mengatur Warna latar belakang Image. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Mengatur mode pemulihan data. |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | Mengatur waktu dekode maksimum default. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Mengatur nilai yang menunjukkan apakah [ignore after load]. |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Mengatur waktu dekode maksimum dalam detik (opsi ini dapat digunakan pada mesin dengan memori sangat lambat untuk mencegah proses menggantung pada gambar sangat besar - resolusi lebih dari 5500x6500 piksel). |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Mengatur waktu dekode maksimum untuk ubin. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Mendapatkan atau mengatur MGR memori. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mengatur penangan peristiwa kemajuan. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Mengatur nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Ini adalah bagian dari pola lisensi ventura. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Menginisialisasi instance baru dari kelas  Jpeg2000LoadOptions  .

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Sumber font khusus

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Returns:**
int - petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Mendapatkan Warna latar belakang Gambar.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Biasanya warna latar belakang diatur setiap kali nilai piksel tidak dapat dipulihkan karena korupsi data.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Mendapatkan mode pemulihan data.

**Returns:**
int - Mode pemulihan data.
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


Mendapatkan waktu dekode maksimum default.

**Returns:**
int - Waktu dekode maksimum default.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Mendapatkan nilai yang menunjukkan apakah [ignore after load].

**Returns:**
boolean - true jika [ignore after load]; sebaliknya, false.
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Mendapatkan waktu dekode maksimum dalam detik (opsi ini dapat digunakan pada mesin dengan memori sangat lambat untuk mencegah proses menggantung pada gambar sangat besar - resolusi lebih dari 5500x6500 piksel).

**Returns:**
int - Waktu dekode maksimum.
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Mendapatkan waktu dekode maksimum untuk ubin.

Nilai: Waktu dekode maksimum untuk ubin.

**Returns:**
int - waktu dekode maksimum untuk ubin.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Mendapatkan penangan peristiwa kemajuan.

Nilai: Penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Mendapatkan nilai yang menunjukkan apakah konversi profil ICC harus diterapkan.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Ini adalah bagian dari pola lisensi ventura. Nilai ini akan diatur oleh VentureLicenser jika ventura memberikan kami objek LoadOptions.

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Mengatur Warna latar belakang Image.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Warna latar belakang. |

Biasanya warna latar belakang diatur setiap kali nilai piksel tidak dapat dipulihkan karena korupsi data. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Mengatur mode pemulihan data.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Mode pemulihan data. |

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


Mengatur waktu dekode maksimum default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Waktu dekode maksimum default. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Mengatur nilai yang menunjukkan apakah [ignore after load].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true jika [ignore after load]; selainnya, false. |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Mengatur waktu dekode maksimum dalam detik (opsi ini dapat digunakan pada mesin dengan memori sangat lambat untuk mencegah proses menggantung pada gambar sangat besar - resolusi lebih dari 5500x6500 piksel).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Waktu dekoding maksimum. |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Mengatur waktu dekode maksimum untuk ubin.

Nilai: Waktu dekode maksimum untuk ubin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | waktu dekoding maksimum untuk ubin. |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Mendapatkan atau mengatur MGR memori.

Nilai: Manajer memori MGR.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Mengatur penangan peristiwa kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | penangkap peristiwa kemajuan. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Mengatur nilai yang menunjukkan apakah konversi profil ICC harus diterapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Ini adalah bagian dari pola lisensi ventura. Nilai ini akan diatur oleh VentureLicenser jika ventura memberikan kami objek LoadOptions.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

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

