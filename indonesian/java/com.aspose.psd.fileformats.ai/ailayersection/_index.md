---
title: "AiLayerSection"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Bagian Lapisan format Ai"
type: docs
weight: 15
url: /id/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Bagian Lapisan format Ai
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Menambahkan gambar raster. |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Mendapatkan atau mengatur komponen warna biru. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Mendapatkan atau mengatur indeks warna. |
| [getColorNumber()](#getColorNumber--) | Mendapatkan atau mengatur nomor warna. |
| [getData()](#getData--) | Mendapatkan data string. |
| [getDimValue()](#getDimValue--) | Mendapatkan atau mengatur nilai redup sebagai persentase. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getGreen()](#getGreen--) | Mendapatkan atau mengatur komponen warna hijau. |
| [getName()](#getName--) | Mendapatkan atau mengatur nama lapisan. |
| [getRasterImages()](#getRasterImages--) | Mendapatkan gambar raster. |
| [getRed()](#getRed--) | Mendapatkan atau mengatur komponen warna merah. |
| [getStream_internalized()](#getStream-internalized--) | Mendapatkan aliran dalam |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilayer. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini redup. |
| [isLocked()](#isLocked--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini terkunci. |
| [isPreview()](#isPreview--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini pratinjau. |
| [isPrinted()](#isPrinted--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dicetak. |
| [isShown()](#isShown--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini ditampilkan. |
| [isTemplate()](#isTemplate--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini merupakan lapisan templat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Mendapatkan atau mengatur komponen warna biru. |
| [setColorIndex(int value)](#setColorIndex-int-) | Mendapatkan atau mengatur indeks warna. |
| [setColorNumber(int value)](#setColorNumber-int-) | Mendapatkan atau mengatur nomor warna. |
| [setDimValue(int value)](#setDimValue-int-) | Mendapatkan atau mengatur nilai redup sebagai persentase. |
| [setGreen(int value)](#setGreen-int-) | Mendapatkan atau mengatur komponen warna hijau. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini redup. |
| [setLocked(boolean value)](#setLocked-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini terkunci. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilayer. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama lapisan. |
| [setPreview(boolean value)](#setPreview-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini pratinjau. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dicetak. |
| [setRed(int value)](#setRed-int-) | Mendapatkan atau mengatur komponen warna merah. |
| [setShown(boolean value)](#setShown-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini ditampilkan. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini merupakan lapisan templat. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Menambahkan gambar raster.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | Gambar raster. |

### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |
| properti | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Mendapatkan atau mengatur komponen warna biru.

Nilai: Komponen warna biru.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Mendapatkan atau mengatur indeks warna. Argumen ini dapat mengambil nilai antara \\u20131 dan 26. Setiap integer mewakili warna yang dapat diberikan ke lapisan untuk tujuan identifikasi pengguna.

Nilai: Indeks warna.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Mendapatkan atau mengatur nomor warna. -1 adalah nilai warna kustom dari properti Merah, Hijau, Biru. Menentukan pengaturan warna lapisan\\u2019s.

Nilai: Nomor warna.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Mendapatkan data string.

**Returns:**
java.lang.String - Data string dari bagian
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Mendapatkan atau mengatur nilai redup sebagai persentase. Mengurangi intensitas gambar terkait dan gambar bitmap yang terdapat dalam lapisan ke persentase yang ditentukan.

Nilai: Nilai redup sebagai persentase.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Mendapatkan atau mengatur komponen warna hijau.

Nilai: Komponen warna hijau.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur nama lapisan. Menentukan nama item sebagaimana muncul di panel Lapisan.

Nilai: Nama lapisan.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Mendapatkan gambar raster.

Nilai: Gambar raster.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Mendapatkan atau mengatur komponen warna merah.

Nilai: Komponen warna merah.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Mendapatkan aliran dalam

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilayer.

Nilai:  true  jika instance ini memiliki masker multilayer; jika tidak,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini redup. Mengurangi intensitas gambar terkait dan gambar bitmap yang terdapat dalam lapisan.

Nilai:  true  jika lapisan ini redup; jika tidak,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini terkunci. Mencegah perubahan pada item.

Nilai:  true  jika lapisan ini terkunci; jika tidak,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dalam pratinjau. Menampilkan karya seni yang terdapat dalam lapisan dengan warna alih-alih sebagai garis luar.

Nilai:  true  jika lapisan ini dalam pratinjau; jika tidak,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dicetak. Membuat karya seni yang terdapat dalam lapisan dapat dicetak jika true.

Nilai:  true  jika lapisan ini dicetak; jika tidak,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini ditampilkan. Menampilkan semua karya seni yang terdapat dalam lapisan pada papan gambar jika true.

Nilai:  true  jika lapisan ini ditampilkan; jika tidak,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini merupakan lapisan templat.

Nilai:  true  jika lapisan ini adalah templat; jika tidak,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Mendapatkan atau mengatur komponen warna biru.

Nilai: Komponen warna biru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Mendapatkan atau mengatur indeks warna. Argumen ini dapat mengambil nilai antara \\u20131 dan 26. Setiap integer mewakili warna yang dapat diberikan ke lapisan untuk tujuan identifikasi pengguna.

Nilai: Indeks warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Mendapatkan atau mengatur nomor warna. -1 adalah nilai warna kustom dari properti Merah, Hijau, Biru. Menentukan pengaturan warna lapisan\\u2019s.

Nilai: Nomor warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Mendapatkan atau mengatur nilai redup sebagai persentase. Mengurangi intensitas gambar terkait dan gambar bitmap yang terdapat dalam lapisan ke persentase yang ditentukan.

Nilai: Nilai redup sebagai persentase.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Mendapatkan atau mengatur komponen warna hijau.

Nilai: Komponen warna hijau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini redup. Mengurangi intensitas gambar terkait dan gambar bitmap yang terdapat dalam lapisan.

Nilai:  true  jika lapisan ini redup; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini terkunci. Mencegah perubahan pada item.

Nilai:  true  jika lapisan ini terkunci; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilayer.

Nilai:  true  jika instance ini memiliki masker multilayer; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mendapatkan atau mengatur nama lapisan. Menentukan nama item sebagaimana muncul di panel Lapisan.

Nilai: Nama lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dalam pratinjau. Menampilkan karya seni yang terdapat dalam lapisan dengan warna alih-alih sebagai garis luar.

Nilai:  true  jika lapisan ini dalam pratinjau; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dicetak. Membuat karya seni yang terdapat dalam lapisan dapat dicetak jika true.

Nilai:  true  jika lapisan ini dicetak; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Mendapatkan atau mengatur komponen warna merah.

Nilai: Komponen warna merah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini ditampilkan. Menampilkan semua karya seni yang terdapat dalam lapisan pada papan gambar jika true.

Nilai:  true  jika lapisan ini ditampilkan; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini merupakan lapisan templat.

Nilai:  true  jika lapisan ini adalah templat; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

