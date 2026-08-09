---
title: "Boyut"
second_title: "Java için Aspose.PSD API Referansı"
description: "Boyutu temsil eder."
type: docs
weight: 98
url: /tr/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Boyutu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | Belirtilen Aspose.Imaging.Point'tan yeni bir Aspose.Imaging.Size yapısı örneği başlatır. |
| [Size(int width, int height)](#Size-int-int-) | Belirtilen boyutlardan yeni bir Aspose.Imaging.Size yapısı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | Bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğini başka bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğine ekler. |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | Belirtilen Aspose.Imaging.SizeF yapısını, Aspose.Imaging.Size yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak Aspose.Imaging.Size yapısına dönüştürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bu Aspose.Imaging.Size ile aynı boyutlarda bir Aspose.Imaging.Size olup olmadığını test eder. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Aspose.Imaging.Size.Width ve Aspose.Imaging.Size.Height değerleri sıfır olarak ayarlanmış yeni bir Aspose.Imaging.Size yapısı örneğini alır. |
| [getHeight()](#getHeight--) | Bu Aspose.Imaging.Size'ın dikey bileşenini alır veya ayarlar. |
| [getWidth()](#getWidth--) | Bu Aspose.Imaging.Size'ın yatay bileşenini alır veya ayarlar. |
| [hashCode()](#hashCode--) | Bu Aspose.Imaging.Size yapısı için bir hash kodu döndürür. |
| [isEmpty()](#isEmpty--) | Bu Aspose.Imaging.Size'ın genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değer alır. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | Bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğini başka bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğine ekler. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | İki  Aspose.Imaging.Size  yapısının eşit olup olmadığını test eder. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | İki  Aspose.Imaging.Size  yapısının farklı olup olmadığını test eder. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | Bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğini, başka bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğinden çıkarır. |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | Belirtilen  Aspose.Imaging.SizeF  yapısını,  Aspose.Imaging.SizeF  yapısının değerlerini en yakın tam sayıya yuvarlayarak bir  Aspose.Imaging.Size  yapısına dönüştürür. |
| [setHeight(int value)](#setHeight-int-) | Bu Aspose.Imaging.Size'ın dikey bileşenini alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Bu Aspose.Imaging.Size'ın yatay bileşenini alır veya ayarlar. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | Bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğini, başka bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğinden çıkarır. |
| [toString()](#toString--) | Bu  Aspose.Imaging.Size  nesnesini temsil eden insan tarafından okunabilir bir dize oluşturur. |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | Belirtilen  Aspose.Imaging.Size  değerini bir  Aspose.Imaging.Point  nesnesine dönüştürür. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | Belirtilen  Aspose.Imaging.Size  değerini bir  Aspose.Imaging.SizeF  nesnesine dönüştürür. |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | Belirtilen  Aspose.Imaging.SizeF  yapısının değerlerini bir alt tam sayıya kırparak bir  Aspose.Imaging.Size  yapısına dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


Belirtilen Aspose.Imaging.Point'tan yeni bir Aspose.Imaging.Size yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Bu  Aspose.Imaging.Size  nesnesini başlatmak için kullanılacak  Aspose.Imaging.Point . |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Belirtilen boyutlardan yeni bir Aspose.Imaging.Size yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Yeni  Aspose.Imaging.Size  nesnesinin genişlik bileşeni. |
| height | int | Yeni  Aspose.Imaging.Size  nesnesinin yükseklik bileşeni. |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


Bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğini başka bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Eklenecek ilk  Aspose.Imaging.Size . |
| size2 | [Size](../../com.aspose.psd/size) | Eklenecek ikinci  Aspose.Imaging.Size . |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


Belirtilen Aspose.Imaging.SizeF yapısını, Aspose.Imaging.Size yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak Aspose.Imaging.Size yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Dönüştürülecek  Aspose.Imaging.SizeF  yapısı. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bu Aspose.Imaging.Size ile aynı boyutlarda bir Aspose.Imaging.Size olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek  System.Object . |

**Returns:**
boolean - Eğer  obj  bir  Aspose.Imaging.Size  ise ve bu  Aspose.Imaging.Size  ile aynı genişlik ve yüksekliğe sahipse doğru; aksi takdirde yanlış.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Aspose.Imaging.Size.Width ve Aspose.Imaging.Size.Height değerleri sıfır olarak ayarlanmış yeni bir Aspose.Imaging.Size yapısı örneğini alır.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu Aspose.Imaging.Size'ın dikey bileşenini alır veya ayarlar.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu Aspose.Imaging.Size'ın yatay bileşenini alır veya ayarlar.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu Aspose.Imaging.Size yapısı için bir hash kodu döndürür.

**Returns:**
int - Bu  Aspose.Imaging.Size  yapısı için bir karma (hash) değeri belirten tam sayı değeri.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu Aspose.Imaging.Size'ın genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değer alır.

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğini başka bir Aspose.Imaging.Size yapısının genişlik ve yüksekliğine ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Eklenecek ilk  Aspose.Imaging.Size . |
| size2 | [Size](../../com.aspose.psd/size) | Eklenecek ikinci  Aspose.Imaging.Size . |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


İki  Aspose.Imaging.Size  yapısının eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Eşitlik operatörünün sol tarafındaki  Aspose.Imaging.Size  yapısı. |
| size2 | [Size](../../com.aspose.psd/size) | Eşitlik operatörünün sağ tarafındaki  Aspose.Imaging.Size  yapısı. |

**Returns:**
boolean - Eğer  size1  ve  size2  aynı genişlik ve yüksekliğe sahipse doğru; aksi takdirde yanlış.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


İki  Aspose.Imaging.Size  yapısının farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Eşitsizlik operatörünün sol tarafındaki  Aspose.Imaging.Size  yapısı. |
| size2 | [Size](../../com.aspose.psd/size) | Eşitsizlik operatörünün sağ tarafındaki  Aspose.Imaging.Size  yapısı. |

**Returns:**
boolean - Eğer  size1  ve  size2  genişlik ya da yükseklikte farklıysa doğru;  size1  ve  size2  eşitse yanlış.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğini, başka bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Çıkarma operatörünün sol tarafındaki  Aspose.Imaging.Size  yapısı. |
| size2 | [Size](../../com.aspose.psd/size) | Çıkarma operatörünün sağ tarafındaki  Aspose.Imaging.Size  yapısı. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


Belirtilen  Aspose.Imaging.SizeF  yapısını,  Aspose.Imaging.SizeF  yapısının değerlerini en yakın tam sayıya yuvarlayarak bir  Aspose.Imaging.Size  yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Dönüştürülecek  Aspose.Imaging.SizeF  yapısı. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Bu Aspose.Imaging.Size'ın dikey bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Bu Aspose.Imaging.Size'ın yatay bileşenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğini, başka bir  Aspose.Imaging.Size  yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Çıkarma operatörünün sol tarafındaki  Aspose.Imaging.Size  yapısı. |
| size2 | [Size](../../com.aspose.psd/size) | Çıkarma operatörünün sağ tarafındaki  Aspose.Imaging.Size  yapısı. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Bu  Aspose.Imaging.Size  nesnesini temsil eden insan tarafından okunabilir bir dize oluşturur.

**Returns:**
java.lang.String - Bu  Aspose.Imaging.Size  nesnesini temsil eden bir dize.
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


Belirtilen  Aspose.Imaging.Size  değerini bir  Aspose.Imaging.Point  nesnesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | The Aspose.Imaging.Size'ı dönüştürmek için. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


Belirtilen  Aspose.Imaging.Size  değerini bir  Aspose.Imaging.SizeF  nesnesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | The Aspose.Imaging.Size'ı dönüştürmek için. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


Belirtilen  Aspose.Imaging.SizeF  yapısının değerlerini bir alt tam sayıya kırparak bir  Aspose.Imaging.Size  yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Dönüştürülecek  Aspose.Imaging.SizeF  yapısı. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

