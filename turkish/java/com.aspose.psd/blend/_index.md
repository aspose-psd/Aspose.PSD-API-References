---
title: "Blend"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir karışım deseni tanımlar."
type: docs
weight: 11
url: /tr/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Bir karışım deseni tanımlar. Bu sınıf kalıtılamaz.

Tipik blend sınıfı kullanımı, fırça için bir blend deseni tanımlamaktır. Bu nedenle blend özellikleri dikkatlice başlatılmalıdır. Null dizilerine izin verilmez. Blend faktörleri veya konum dizisi boşsa ya da uzunlukları aynı değilse fırça uygun istisnayı fırlatır. Konum dizisinde iki veya daha fazla öğe varsa, ilk öğe 0 ve son öğe 1 olmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Blend()](#Blend--) | Blend sınıfının yeni bir örneğini başlatır. |
| [Blend(int count)](#Blend-int-) | Blend sınıfının belirtilen faktör ve konum sayısıyla yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin com.aspose.psd.Blend sınıfı olup olmadığını ve bu com.aspose.psd.Blend sınıfına eşit olup olmadığını test eder. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Gradyan için karışım çarpanları dizisini alır. |
| [getPositions()](#getPositions--) | Gradyan için karışım konumları dizisini alır. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Gradyan için karışım çarpanları dizisini ayarlar. |
| [setPositions(float[] value)](#setPositions-float---) | Gradyan için karışım konumları dizisini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Blend sınıfının yeni bir örneğini başlatır. Çarpan ve karışım dizilerindeki öğe sayısı 1 olacaktır.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Blend sınıfının belirtilen faktör ve konum sayısıyla yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| count | int | Çarpan ve konum dizilerindeki öğe sayısı. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin com.aspose.psd.Blend sınıfı olup olmadığını ve bu com.aspose.psd.Blend sınıfına eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek nesne. |

**Returns:**
boolean - obj bir com.aspose.psd.Blend sınıfı ise bu com.aspose.psd.Blend sınıfına eşdeğer ise true; aksi takdirde false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Gradyan için karışım çarpanları dizisini alır.

**Returns:**
float[] - İlgili konumda kullanılacak başlangıç ve bitiş renginin yüzde oranlarını belirten karışım çarpanları dizisi.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Gradyan için karışım konumları dizisini alır.

**Returns:**
float[] - Gradyan çizgisi boyunca mesafenin yüzde oranlarını belirten karışım konumları dizisi.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygun.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Gradyan için karışım çarpanları dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | İlgili konumda kullanılacak başlangıç ve bitiş renginin yüzde oranlarını belirten karışım çarpanları dizisi. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Gradyan için karışım konumları dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | Gradyan çizgisi boyunca mesafenin yüzde oranlarını belirten karışım konumları dizisi. |

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

