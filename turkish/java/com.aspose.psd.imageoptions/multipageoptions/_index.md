---
title: "MultiPageOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "Birden fazla sayfayı destekleyen formatlar için temel sınıf."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Birden fazla sayfayı destekleyen formatlar için temel sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | MultiPageOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Dışa aktarma alanını alır veya ayarlar. |
| [getMergeLayers()](#getMergeLayers--) | Katmanların birleştirileceğini gösteren bir değeri alır [katmanları birleştir]. |
| [getMode()](#getMode--) | Modu alır veya ayarlar. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için). |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Sayfa rasterleştirme seçeneklerini alır. |
| [getPageTitles()](#getPageTitles--) | Sayfa başlıklarını alır veya ayarlar. |
| [getPages()](#getPages--) | Sayfaları alır veya ayarlar. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Zaman aralığını alır. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Sayfaları aralıklar dizisinden başlatır |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Dışa aktarma alanını alır veya ayarlar. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Bir değeri ayarlar, [merege layers] olup olmadığını gösterir. |
| [setMode(int value)](#setMode-int-) | Modu alır veya ayarlar. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için). |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Sayfa rasterleştirme seçeneklerini ayarlar. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Sayfa başlıklarını alır veya ayarlar. |
| [setPages(int[] value)](#setPages-int---) | Sayfaları alır veya ayarlar. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Zaman aralığını ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfalar | int[] | Sayfalar. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfalar | int[] | Sayfalar dizisi. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sayfa başlıkları. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sayfa başlıkları. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Bu IntRange. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Bu IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Bu IntRange. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Bu IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Dışa aktarma alanı. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | int | Sayfa indeksi. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


MultiPageOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | int | Sayfa indeksi. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Dışa aktarma alanı. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Dışa aktarma alanını alır veya ayarlar.

Değer: Dışa aktarma alanı.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Katmanların birleştirileceğini gösteren bir değeri alır [katmanları birleştir].

Değer: true eğer [merege layers]; aksi takdirde, false.

**Returns:**
boolean - [merege layers] olup olmadığını gösteren bir değer.
### getMode() {#getMode--}
```
public int getMode()
```


Modu alır veya ayarlar.

Değer: Mod.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için).

Değer: Çıktı katmanları adları.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Sayfa rasterleştirme seçeneklerini alır.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - sayfa rasterleştirme seçenekleri.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Sayfa başlıklarını alır veya ayarlar.

Değer: Sayfa başlıkları.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Sayfaları alır veya ayarlar.

Değer: Sayfalar.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Zaman aralığını alır.

Değer: Zaman aralığı.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Sayfaları aralıklar dizisinden başlatır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Aralıklar. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Dışa aktarma alanını alır veya ayarlar.

Değer: Dışa aktarma alanı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Bir değeri ayarlar, [merege layers] olup olmadığını gösterir.

Değer: true eğer [merege layers]; aksi takdirde, false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Bir değer, [merege layers] olup olmadığını gösterir. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Modu alır veya ayarlar.

Değer: Mod.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Çıktı katman adlarını alır veya ayarlar (Dışa aktarma formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için).

Değer: Çıktı katmanları adları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Sayfa rasterleştirme seçeneklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | sayfa rasterleştirme seçenekleri. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Sayfa başlıklarını alır veya ayarlar.

Değer: Sayfa başlıkları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Sayfaları alır veya ayarlar.

Değer: Sayfalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Zaman aralığını ayarlar.

Değer: Zaman aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | zaman aralığı. |

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

