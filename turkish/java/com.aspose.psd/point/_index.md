---
title: "Point"
second_title: "Java için Aspose.PSD API Referansı"
description: "İki boyutlu bir düzlemde bir noktayı tanımlayan tamsayı x ve y koordinatlarından oluşan sıralı bir çifti temsil eder."
type: docs
weight: 82
url: /tr/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

İki boyutlu bir düzlemde bir noktayı tanımlayan tamsayı x ve y koordinatlarından oluşan sıralı bir çifti temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Belirtilen koordinatlarla Aspose.Imaging.Point yapısının yeni bir örneğini başlatır. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Aspose.Imaging.Size yapısından Aspose.Imaging.Point yapısının yeni bir örneğini başlatır. |
| [Point(int dw)](#Point-int-) | Tam sayı değeriyle belirtilen koordinatları kullanarak Aspose.Imaging.Point yapısının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Nokta biçimini temsil eder. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Belirtilen Aspose.Imaging.Size'ı belirtilen Aspose.Imaging.Point'a ekler. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Belirtilen Aspose.Imaging.PointF değerlerini bir üst tam sayıya yuvarlayarak Aspose.Imaging.Point'a dönüştürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu Aspose.Imaging.Point nesnesinin belirtilen System.Object ile aynı koordinatları içerip içermediğini belirtir. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Aspose.Imaging.Point.X ve Aspose.Imaging.Point.Y değerleri sıfıra ayarlanmış Aspose.Imaging.Point yapısının yeni bir örneğini alır. |
| [getX()](#getX--) | Bu Aspose.Imaging.Point nesnesinin x-koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu Aspose.Imaging.Point nesnesinin y-koordinatını alır veya ayarlar. |
| [hashCode()](#hashCode--) | Bu Aspose.Imaging.Point nesnesi için bir karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Bu Aspose.Imaging.Point nesnesinin boş olup olmadığını gösteren bir değer alır. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Bu Aspose.Imaging.Point nesnesini belirtilen Aspose.Imaging.Point ile kaydırır. |
| [offset(int dx, int dy)](#offset-int-int-) | Bu Aspose.Imaging.Point nesnesini belirtilen miktarda kaydırır. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Bir Aspose.Imaging.Point nesnesini verilen Aspose.Imaging.Size ile kaydırır. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | İki Aspose.Imaging.Point nesnesini karşılaştırır. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | İki Aspose.Imaging.Point nesnesini karşılaştırır. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Bir Aspose.Imaging.Point nesnesini verilen Aspose.Imaging.Size'ın negatifine göre kaydırır. |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Belirtilen Aspose.Imaging.PointF nesnesini, Aspose.Imaging.Point değerlerini en yakın tam sayıya yuvarlayarak bir Aspose.Imaging.Point nesnesine dönüştürür. |
| [setX(int value)](#setX-int-) | Bu Aspose.Imaging.Point nesnesinin x-koordinatını alır veya ayarlar. |
| [setY(int value)](#setY-int-) | Bu Aspose.Imaging.Point nesnesinin y-koordinatını alır veya ayarlar. |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Belirtilen Aspose.Imaging.Point nesnesinden belirtilen Aspose.Imaging.Size değerini çıkarmanın sonucunu döndürür. |
| [toString()](#toString--) | Bu Aspose.Imaging.Point nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Belirtilen Point yapısını PointF yapısına dönüştürür. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Belirtilen Aspose.Imaging.Point yapısını bir Aspose.Imaging.Size yapısına dönüştürür. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Belirtilen Aspose.Imaging.PointF nesnesini, Aspose.Imaging.Point değerlerini kırparak bir Aspose.Imaging.Point nesnesine dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Belirtilen koordinatlarla Aspose.Imaging.Point yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Noktanın yatay konumu. |
| y | int | Noktanın dikey konumu. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Aspose.Imaging.Size yapısından Aspose.Imaging.Point yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Yeni nokta koordinatlarını içerir. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Tam sayı değeriyle belirtilen koordinatları kullanarak Aspose.Imaging.Point yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dw | int | Yeni nokta için koordinatları belirten 32 bitlik bir tam sayı. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Nokta biçimini temsil eder.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Belirtilen Aspose.Imaging.Size'ı belirtilen Aspose.Imaging.Point'a ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Eklenecek Aspose.Imaging.Point nesnesi. |
| size | [Size](../../com.aspose.psd/size) | Noktaya eklenecek Aspose.Imaging.Size. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Belirtilen Aspose.Imaging.PointF değerlerini bir üst tam sayıya yuvarlayarak Aspose.Imaging.Point'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Dönüştürülecek Aspose.Imaging.PointF. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu Aspose.Imaging.Point nesnesinin belirtilen System.Object ile aynı koordinatları içerip içermediğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek  System.Object . |

**Returns:**
boolean - obj bir Aspose.Imaging.Point ise ve bu Aspose.Imaging.Point ile aynı koordinatlara sahipse True.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Aspose.Imaging.Point.X ve Aspose.Imaging.Point.Y değerleri sıfıra ayarlanmış Aspose.Imaging.Point yapısının yeni bir örneğini alır.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Bu Aspose.Imaging.Point nesnesinin x-koordinatını alır veya ayarlar.

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Bu Aspose.Imaging.Point nesnesinin y-koordinatını alır veya ayarlar.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu Aspose.Imaging.Point nesnesi için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygun.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu Aspose.Imaging.Point nesnesinin boş olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Aspose.Imaging.Point.X ve Aspose.Imaging.Point.Y ikisi de 0 ise True; aksi takdirde false.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Bu Aspose.Imaging.Point nesnesini belirtilen Aspose.Imaging.Point ile kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Bu Aspose.Imaging.Point'ı ofsetlemek için kullanılan Aspose.Imaging.Point. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Bu Aspose.Imaging.Point nesnesini belirtilen miktarda kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | int | x koordinatını ofsetlemek için miktar. |
| dy | int | y koordinatını ofsetlemek için miktar. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Bir Aspose.Imaging.Point nesnesini verilen Aspose.Imaging.Size ile kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Çevrilecek Aspose.Imaging.Point. |
| size | [Size](../../com.aspose.psd/size) | Koordinatlarına eklenecek sayı çiftini belirten bir Aspose.Imaging.Size. |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


İki Aspose.Imaging.Point nesnesini karşılaştırır. Sonuç, iki Aspose.Imaging.Point nesnesinin Aspose.Imaging.Point.X ve Aspose.Imaging.Point.Y özelliklerinin değerlerinin eşit olup olmadığını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Karşılaştırılacak ilk Aspose.Imaging.Point. |
| point2 | [Point](../../com.aspose.psd/point) | Karşılaştırılacak ikinci Aspose.Imaging.Point. |

**Returns:**
boolean - point1 ve point2'nin Aspose.Imaging.Point.X ve Aspose.Imaging.Point.Y değerleri eşitse True; aksi takdirde false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


İki Aspose.Imaging.Point nesnesini karşılaştırır. Sonuç, iki Aspose.Imaging.Point nesnesinin Aspose.Imaging.Point.X veya Aspose.Imaging.Point.Y özelliklerinin değerlerinin eşit olmaması durumunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Karşılaştırılacak ilk Aspose.Imaging.Point. |
| point2 | [Point](../../com.aspose.psd/point) | Karşılaştırılacak ikinci Aspose.Imaging.Point. |

**Returns:**
boolean - point1 ve point2'nin Aspose.Imaging.Point.X veya Aspose.Imaging.Point.Y özelliklerinin değerlerinden herhangi biri farklıysa True; aksi takdirde false.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Bir Aspose.Imaging.Point nesnesini verilen Aspose.Imaging.Size'ın negatifine göre kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Çevrilecek Aspose.Imaging.Point. |
| size | [Size](../../com.aspose.psd/size) | Koordinatlarından çıkarılacak sayı çiftini belirten bir Aspose.Imaging.Size. |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Belirtilen Aspose.Imaging.PointF nesnesini, Aspose.Imaging.Point değerlerini en yakın tam sayıya yuvarlayarak bir Aspose.Imaging.Point nesnesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Dönüştürülecek Aspose.Imaging.PointF. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Bu Aspose.Imaging.Point nesnesinin x-koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Bu Aspose.Imaging.Point nesnesinin y-koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Belirtilen Aspose.Imaging.Point nesnesinden belirtilen Aspose.Imaging.Size değerini çıkarmanın sonucunu döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Çıkarma işleminin yapılacağı Aspose.Imaging.Point. |
| size | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Point'tan çıkarılacak Aspose.Imaging.Size. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Bu Aspose.Imaging.Point nesnesini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir System.String.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Belirtilen Point yapısını PointF yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Dönüştürülecek Point. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Belirtilen Aspose.Imaging.Point yapısını bir Aspose.Imaging.Size yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Dönüştürülecek Aspose.Imaging.Point. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Belirtilen Aspose.Imaging.PointF nesnesini, Aspose.Imaging.Point değerlerini kırparak bir Aspose.Imaging.Point nesnesine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Dönüştürülecek Aspose.Imaging.PointF. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

