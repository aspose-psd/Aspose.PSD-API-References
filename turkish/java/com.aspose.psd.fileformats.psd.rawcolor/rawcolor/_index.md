---
title: "RawColor"
second_title: "Java için Aspose.PSD API Referansı"
description: "Raw Color Sınıfı, herhangi bir kanal sayısı, herhangi bir renk modu ve herhangi bir bit derinliğine sahip renkleri depolamaya yardımcı olur. Lütfen bazı iç sınıfların RawColor'ı yerel formatına dönüştürmede sorun yaşayabileceğini unutmayın; bu nedenle API size CMYK rengi sağlıyorsa, sağlanan formatı kullanmak daha güvenilirdir."
type: docs
weight: 11
url: /tr/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color Sınıfı, herhangi bir kanal sayısı, herhangi bir renk modu ve herhangi bir bit derinliğine sahip renkleri depolamaya yardımcı olur. Lütfen bazı iç sınıfların RawColor'ı yerel formatına dönüştürmede sorun yaşayabileceğini unutmayın; bu nedenle API size CMYK rengi sağlıyorsa, sağlanan formatı kullanmak daha güvenilirdir. Ayrıca, Raw Color'ın dönüştürülebileceği bazı durumlar da olabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Yeni bir [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) sınıfı örneği başlatır. |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Önceden tanımlı renk modlarını kullanarak piksel veri formatından yeni bir [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler. |
| [getAsInt()](#getAsInt--) | Rengi mümkünse int olarak alır. |
| [getAsLong()](#getAsLong--) | Rengi mümkünse long olarak alır. |
| [getBitDepth()](#getBitDepth--) | Raw Color'ın bit derinliğini alır. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Rengin takip edeceği mod. |
| [getColorModeName()](#getColorModeName--) | Renk modunun adını alır. |
| [getComponents()](#getComponents--) | Rengin bileşenlerini alır. |
| [hashCode()](#hashCode--) | Geçerli nesnenin hash kodunu al. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | == operatörünü uygular. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | != operatörünü uygular. |
| [setAsInt(int value)](#setAsInt-int-) | Mümkünse int argümandan tüm kanallara veriyi ayarlar. |
| [setAsLong(long value)](#setAsLong-long-) | Mümkünse int argümandan tüm kanallara veriyi ayarlar. |
| [setColorMode(short value)](#setColorMode-short-) | Rengin takip edeceği mod. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Yeni bir [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Özel renk bileşenleri. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Önceden tanımlı renk modlarını kullanarak piksel veri formatından yeni bir [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Piksel veri biçimi. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak Object. |

**Returns:**
boolean -  true  eğer belirtilen Object bu örnek ile eşitse; aksi takdirde,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Rengi mümkünse int olarak alır.

**Returns:**
int - Kanalların int içinde depolanması
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Rengi mümkünse long olarak alır.

**Returns:**
long - Kanalların Int içinde depolanması
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Raw Color'ın bit derinliğini alır. Örneğin, kanal/bileşen başına 8 bit olan ARGB rengi için toplam 32 bit derinlik, kanal/bileşen başına 16 bit olan tam ARGB rengi için ise 64 bit derinliktir. Bit derinliği, kanalların bit derinliklerinin toplamından elde edilir. Farklı kanalların farklı bit derinliklerine sahip olması mümkündür.

**Returns:**
int - Tüm kanalların bit derinliklerinin toplamı
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Rengin takip edeceği mod.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Renk modunun adını alır. Renk modu adı, kanalların/bileşenlerin adlarından türetilir.

**Returns:**
java.lang.String - Renk modu adını içeren dize
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Renk bileşenlerini alır. Her bileşen ayrı bir kanaldır ve popüler olmayan bir renk şeması kullanıyorsanız, her kanalla ayrı ayrı çalışmak daha iyidir.

Değer: Renk bileşenleri

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin hash kodunu al.

**Returns:**
int - Karma kodu.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


== operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | İlk RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | İkinci RawColor. |

**Returns:**
boolean - Operatörün sonucu.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


!= operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | İlk RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | İkinci RawColor. |

**Returns:**
boolean - Operatörün sonucu.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Mümkünse int argümandan tüm kanallara veriyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bileşen verilerini içeren int değeri |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Mümkünse int argümandan tüm kanallara veriyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Bileşen verilerini içeren int değeri |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Rengin takip edeceği mod.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

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

