---
title: "PsdLoadOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi pemuatan Psd"
type: docs
weight: 12
url: /id/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Opsi pemuatan Psd
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Menginisialisasi instance baru dari kelas [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Sumber font khusus |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Mendapatkan Warna latar belakang Gambar. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Mendapatkan mode pemulihan data. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Mendapatkan nilai yang menunjukkan apakah [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada eksekusi operasi UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [load effects resource] (secara default sumber daya tidak dimuat). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan penangan peristiwa kemajuan. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Mendapatkan atau mengatur mode baca-saja yang digunakan saat memuat gambar PSD. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use disk for load effects resource] (secara default menggunakan disk untuk memuat sumber daya efek, tetapi dapat menggunakan memori jika cukup dengan mengatur nilai ini ke false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Mendapatkan nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Ini adalah bagian dari pola lisensi ventura. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Mengatur Warna latar belakang Image. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Mengatur mode pemulihan data. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Mengatur nilai yang menunjukkan apakah [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada eksekusi operasi UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [load effects resource] (secara default sumber daya tidak dimuat). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Mendapatkan atau mengatur MGR memori. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mengatur penangan peristiwa kemajuan. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Mendapatkan atau mengatur mode baca-saja yang digunakan saat memuat gambar PSD. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use disk for load effects resource] (secara default menggunakan disk untuk memuat sumber daya efek, tetapi dapat menggunakan memori jika cukup dengan mengatur nilai ini ke false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Mengatur nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Ini adalah bagian dari pola lisensi ventura. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Menginisialisasi instance baru dari kelas [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi.

Nilai: true untuk mempertahankan piksel asli dari lapisan yang tidak berubah; selainnya, false.

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp.

Nilai: true untuk merender gambar dengan transformasi warp; false.

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
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Mendapatkan nilai yang menunjukkan apakah [ignore after load].

**Returns:**
boolean - true jika [ignore after load]; sebaliknya, false.
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [ignore alpha channel].

Nilai: true jika [ignore alpha channel]; selainnya, false.

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada eksekusi operasi UpdateText.

Nilai: true jika [ignore text layer width]; selainnya, false.

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [load effects resource] (secara default sumber daya tidak dimuat). Ketika opsi ini diatur, hanya efek yang didukung yang akan dirender ke gambar gabungan akhir.

Nilai: true jika [load effects resource]; selainnya, false.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Mendapatkan penangan peristiwa kemajuan.

Nilai: Penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [use read only mode]. Ini adalah mode baca-saja, didukung untuk kompatibilitas identik dengan Adobe Photoshop. Ketika opsi ini diatur, semua perubahan yang diterapkan pada lapisan tidak akan disimpan ke gambar akhir. Semua data diambil dari bagian ImageData, sehingga identik dengan Photoshop. Secara default semua gambar yang dimuat tidak kompatibel identik dengan Adobe Photoshop.

Nilai: true jika [use photoshop compatibility mode]; selainnya, false.

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Mendapatkan atau mengatur mode baca-saja yang digunakan saat memuat gambar PSD.

Nilai: Salah satu nilai ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)).

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [use disk for load effects resource] (secara default menggunakan disk untuk memuat sumber daya efek, tetapi dapat menggunakan memori jika cukup dengan mengatur nilai ini ke false).

Nilai: true jika [use disk for load effects resource]; selainnya, false.

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi.

Nilai: true untuk mempertahankan piksel asli dari lapisan yang tidak berubah; selainnya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp.

Nilai: true untuk merender gambar dengan transformasi warp; false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Mengatur nilai yang menunjukkan apakah [ignore after load].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true jika [ignore after load]; selainnya, false. |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [ignore alpha channel].

Nilai: true jika [ignore alpha channel]; selainnya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada eksekusi operasi UpdateText.

Nilai: true jika [ignore text layer width]; selainnya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [load effects resource] (secara default sumber daya tidak dimuat). Ketika opsi ini diatur, hanya efek yang didukung yang akan dirender ke gambar gabungan akhir.

Nilai: true jika [load effects resource]; selainnya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [use read only mode]. Ini adalah mode baca-saja, didukung untuk kompatibilitas identik dengan Adobe Photoshop. Ketika opsi ini diatur, semua perubahan yang diterapkan pada lapisan tidak akan disimpan ke gambar akhir. Semua data diambil dari bagian ImageData, sehingga identik dengan Photoshop. Secara default semua gambar yang dimuat tidak kompatibel identik dengan Adobe Photoshop.

Nilai: true jika [use photoshop compatibility mode]; selainnya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Mendapatkan atau mengatur mode baca-saja yang digunakan saat memuat gambar PSD.

Nilai: Salah satu nilai ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)).

 *  
 *  
 *  

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [use disk for load effects resource] (secara default menggunakan disk untuk memuat sumber daya efek, tetapi dapat menggunakan memori jika cukup dengan mengatur nilai ini ke false).

Nilai: true jika [use disk for load effects resource]; selainnya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

