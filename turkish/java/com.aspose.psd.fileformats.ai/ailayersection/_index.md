---
title: "AiLayerSection"
second_title: "Java için Aspose.PSD API Referansı"
description: "Ai formatı Katman Bölümü"
type: docs
weight: 15
url: /tr/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Ai formatı Katman Bölümü
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Raster görüntüyü ekler. |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Mavi renk bileşenini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Renk indeksini alır veya ayarlar. |
| [getColorNumber()](#getColorNumber--) | Renk numarasını alır veya ayarlar. |
| [getData()](#getData--) | Dize verisini alır. |
| [getDimValue()](#getDimValue--) | Karartma değerini yüzde olarak alır veya ayarlar. |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getGreen()](#getGreen--) | Yeşil renk bileşenini alır veya ayarlar. |
| [getName()](#getName--) | Katman adını alır veya ayarlar. |
| [getRasterImages()](#getRasterImages--) | Raster görüntüleri alır. |
| [getRed()](#getRed--) | Kırmızı renk bileşenini alır veya ayarlar. |
| [getStream_internalized()](#getStream-internalized--) | İç akışı alır |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Bu katmanın karartılıp karartılmadığını gösteren bir değeri alır veya ayarlar. |
| [isLocked()](#isLocked--) | Bu katmanın kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isPreview()](#isPreview--) | Bu katmanın önizleme olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isPrinted()](#isPrinted--) | Bu katmanın yazdırılıp yazdırılmadığını gösteren bir değeri alır veya ayarlar. |
| [isShown()](#isShown--) | Bu katmanın gösterilip gösterilmediğini gösteren bir değeri alır veya ayarlar. |
| [isTemplate()](#isTemplate--) | Bu katmanın şablon katmanı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Mavi renk bileşenini alır veya ayarlar. |
| [setColorIndex(int value)](#setColorIndex-int-) | Renk indeksini alır veya ayarlar. |
| [setColorNumber(int value)](#setColorNumber-int-) | Renk numarasını alır veya ayarlar. |
| [setDimValue(int value)](#setDimValue-int-) | Karartma değerini yüzde olarak alır veya ayarlar. |
| [setGreen(int value)](#setGreen-int-) | Yeşil renk bileşenini alır veya ayarlar. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Bu katmanın karartılıp karartılmadığını gösteren bir değeri alır veya ayarlar. |
| [setLocked(boolean value)](#setLocked-boolean-) | Bu katmanın kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Katman adını alır veya ayarlar. |
| [setPreview(boolean value)](#setPreview-boolean-) | Bu katmanın önizleme olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Bu katmanın yazdırılıp yazdırılmadığını gösteren bir değeri alır veya ayarlar. |
| [setRed(int value)](#setRed-int-) | Kırmızı renk bileşenini alır veya ayarlar. |
| [setShown(boolean value)](#setShown-boolean-) | Bu katmanın gösterilip gösterilmediğini gösteren bir değeri alır veya ayarlar. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Bu katmanın şablon katmanı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Raster görüntüyü ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | Raster görüntüsü. |

### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |
| özellikler | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Mavi renk bileşenini alır veya ayarlar.

Değer: Mavi renk bileşeni.

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


Renk indeksini alır veya ayarlar. Bu argüman \\u20131 ile 26 arasında değer alabilir. Her tam sayı, katmana kullanıcı tanımlama amacıyla atanabilecek bir rengi temsil eder.

Değer: Renk indeksi.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Renk numarasını alır veya ayarlar. -1, Kırmızı, Yeşil, Mavi özelliklerinden gelen özel renk değeridir. Katmanın\\u2019s renk ayarını belirtir.

Değer: Renk numarası.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Dize verisini alır.

**Returns:**
java.lang.String - Bölümün dize verisi
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Karartma değerini yüzde olarak alır veya ayarlar. Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu belirtilen yüzdeye düşürür.

Değer: Yüzde olarak karartma değeri.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Yeşil renk bileşenini alır veya ayarlar.

Değer: Yeşil renk bileşeni.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Katman adını alır veya ayarlar. Öğenin Katmanlar panelinde göründüğü adı belirtir.

Değer: Katman adı.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Raster görüntüleri alır.

Değer: Raster görüntüler.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Kırmızı renk bileşenini alır veya ayarlar.

Değer: Kırmızı renk bileşeni.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


İç akışı alır

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek çok katmanlı maskelere sahipse; aksi takdirde,  false .

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


Bu katmanın karartılıp karartılmadığını gösteren bir değeri alır veya ayarlar. Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu azaltır.

Değer:  true  bu katman karartılmışsa; aksi takdirde,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Bu katmanın kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. Öğenin değişikliklerini engeller.

Değer:  true  bu katman kilitli ise; aksi takdirde,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Bu katmanın önizleme olup olmadığını gösteren bir değeri alır veya ayarlar. Katmanda bulunan sanat eserini kontur yerine renkle gösterir.

Değer:  true  bu katman önizleme ise; aksi takdirde,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Bu katmanın yazdırılıp yazdırılmayacağını gösteren bir değeri alır veya ayarlar. Katmanda bulunan sanat eserini true ise yazdırılabilir yapar.

Değer:  true  eğer bu katman yazdırılıyorsa; aksi takdirde,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Bu katmanın gösterilip gösterilmeyeceğini belirten bir değeri alır veya ayarlar. Katmanda bulunan tüm sanat eserlerini true ise çalışma tahtasında gösterir.

Değer:  true  eğer bu katman gösteriliyorsa; aksi takdirde,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Bu katmanın şablon katmanı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer bu katman bir şablon ise; aksi takdirde,  false .

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


Mavi renk bileşenini alır veya ayarlar.

Değer: Mavi renk bileşeni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Renk indeksini alır veya ayarlar. Bu argüman \\u20131 ile 26 arasında değer alabilir. Her tam sayı, katmana kullanıcı tanımlama amacıyla atanabilecek bir rengi temsil eder.

Değer: Renk indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Renk numarasını alır veya ayarlar. -1, Kırmızı, Yeşil, Mavi özelliklerinden gelen özel renk değeridir. Katmanın\\u2019s renk ayarını belirtir.

Değer: Renk numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Karartma değerini yüzde olarak alır veya ayarlar. Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu belirtilen yüzdeye düşürür.

Değer: Yüzde olarak karartma değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Yeşil renk bileşenini alır veya ayarlar.

Değer: Yeşil renk bileşeni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Bu katmanın karartılıp karartılmadığını gösteren bir değeri alır veya ayarlar. Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu azaltır.

Değer:  true  bu katman karartılmışsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Bu katmanın kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. Öğenin değişikliklerini engeller.

Değer:  true  bu katman kilitli ise; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek çok katmanlı maskelere sahipse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Katman adını alır veya ayarlar. Öğenin Katmanlar panelinde göründüğü adı belirtir.

Değer: Katman adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Bu katmanın önizleme olup olmadığını gösteren bir değeri alır veya ayarlar. Katmanda bulunan sanat eserini kontur yerine renkle gösterir.

Değer:  true  bu katman önizleme ise; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Bu katmanın yazdırılıp yazdırılmayacağını gösteren bir değeri alır veya ayarlar. Katmanda bulunan sanat eserini true ise yazdırılabilir yapar.

Değer:  true  eğer bu katman yazdırılıyorsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Kırmızı renk bileşenini alır veya ayarlar.

Değer: Kırmızı renk bileşeni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Bu katmanın gösterilip gösterilmeyeceğini belirten bir değeri alır veya ayarlar. Katmanda bulunan tüm sanat eserlerini true ise çalışma tahtasında gösterir.

Değer:  true  eğer bu katman gösteriliyorsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Bu katmanın şablon katmanı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer bu katman bir şablon ise; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

