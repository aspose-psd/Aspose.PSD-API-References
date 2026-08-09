---
title: "TiffRational"
second_title: "Java için Aspose.PSD API Referansı"
description: "tiff rasyonel türü."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

tiff rasyonel türü.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffRational()](#TiffRational--) | TiffRational sınıfının yeni bir örneğini başlatır. |
| [TiffRational(long value)](#TiffRational-long-) | TiffRational sınıfının yeni bir örneğini başlatır. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | TiffRational sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Epsilon](#Epsilon) | Kesir hesaplaması için epsilon |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximateFraction(float value)](#approximateFraction-float-) | Sağlanan değeri bir kesire yaklaştırır. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Sağlanan değeri bir kesire yaklaştırır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen Nesnenin bu örnekle eşit olup olmadığını belirler. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Paydayı alır. |
| [getNominator()](#getNominator--) | Payı alır. |
| [getValue()](#getValue--) | Kayan nokta değerini alır. |
| [getValueD()](#getValueD--) | Double değerini alır. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu örneği temsil eden bir  System.String  döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


TiffRational sınıfının yeni bir örneğini başlatır.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


TiffRational sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | long | Pay değeri. |

Pay, belirtilen değer olarak kullanılacak ve payda 1'e eşit olacaktır. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


TiffRational sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pay | long | Pay. |
| payda | long | Payda. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


Kesir hesaplaması için epsilon

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Sağlanan değeri bir kesire yaklaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Paydayı alır.

Değer: Payda.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Payı alır.

Değer: Pay.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Kayan nokta değerini alır.

Değer: Float değeri.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Double değerini alır.

Değer: Double değeri.

**Returns:**
double
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




### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir  System.String  döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir System.String.
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

