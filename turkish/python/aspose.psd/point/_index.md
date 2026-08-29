---
title: "Point Sınıfı"
type: docs
weight: 3530
url: /tr/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Point()](#Point__1) | Point sınıfının yeni bir örneğini başlatır. |
| [Point(dw)](#Point_dw_2) | Koordinatları bir tamsayı değeriyle belirtilen yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısını başlatır. |
| [Point(size)](#Point_size_3) | [Size](/psd/python-net/aspose.psd/size/) yapısından yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısını başlatır. |
| [Point(x, y)](#Point_x_y_4) | Belirtilen koordinatlarla yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısını başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | [Point.x](/psd/python-net/aspose.psd/point/) ve [Point.y](/psd/python-net/aspose.psd/point/) değerleri sıfıra ayarlanmış yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısının bir örneğini alır. |
| is_empty | bool | r | Bu [Point](/psd/python-net/aspose.psd/point/) nesnesinin boş olup olmadığını gösteren bir değer alır. |
| x | int | r/w | Bu [Point](/psd/python-net/aspose.psd/point/) nesnesinin x koordinatını alır veya ayarlar. |
| y | int | r/w | Bu [Point](/psd/python-net/aspose.psd/point/) nesnesinin y koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Belirtilen [Size](/psd/python-net/aspose.psd/size/) değerini belirtilen [Point](/psd/python-net/aspose.psd/point/) değerine ekler. |
| [ceiling(point)](#ceiling_point_2) | Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesini, [PointF](/psd/python-net/aspose.psd/pointf/) değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Point](/psd/python-net/aspose.psd/point/) öğesine dönüştürür. |
| [offset(dx, dy)](#offset_dx_dy_3) | Bu [Point](/psd/python-net/aspose.psd/point/) öğesini belirtilen miktarda kaydırır. |
| [offset(point)](#offset_point_4) | Bu [Point](/psd/python-net/aspose.psd/point/) öğesini belirtilen [Point](/psd/python-net/aspose.psd/point/) ile kaydırır. |
| [round(point)](#round_point_5) | Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesini, [Point](/psd/python-net/aspose.psd/point/) değerlerini en yakın tam sayıya yuvarlayarak bir [Point](/psd/python-net/aspose.psd/point/) nesnesine dönüştürür. |
| [subtract(point, size)](#subtract_point_size_6) | Belirtilen [Point](/psd/python-net/aspose.psd/point/) öğesinden belirtilen [Size](/psd/python-net/aspose.psd/size/) öğesini çıkarmanın sonucunu döndürür. |
| [truncate(point)](#truncate_point_7) | Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesini, [Point](/psd/python-net/aspose.psd/point/) değerlerini kırparak bir [Point](/psd/python-net/aspose.psd/point/) öğesine dönüştürür. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Point sınıfının yeni bir örneğini başlatır.

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Koordinatları bir tamsayı değeriyle belirtilen yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısını başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dw | int | Yeni noktanın koordinatlarını belirten 32 bitlik bir tam sayı. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

[Size](/psd/python-net/aspose.psd/size/) yapısından yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısını başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Yeni nokta koordinatlarını içerir. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Belirtilen koordinatlarla yeni bir [Point](/psd/python-net/aspose.psd/point/) yapısını başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Noktanın yatay konumu. |
| y | int | Noktanın dikey konumu. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Belirtilen [Size](/psd/python-net/aspose.psd/size/) değerini belirtilen [Point](/psd/python-net/aspose.psd/point/) değerine ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Eklenecek [Point](/psd/python-net/aspose.psd/point/) öğesi. |
| size | [Size](/psd/python-net/aspose.psd/size) | <paramref name="point" /> öğesine eklenecek [Size](/psd/python-net/aspose.psd/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Toplama işleminin sonucu olan [Point](/psd/python-net/aspose.psd/point/) öğesi. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesini, [PointF](/psd/python-net/aspose.psd/pointf/) değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Point](/psd/python-net/aspose.psd/point/) öğesine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Dönüştürülecek [PointF](/psd/python-net/aspose.psd/pointf/) öğesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Bu yöntemin dönüştürdüğü [Point](/psd/python-net/aspose.psd/point/) öğesi. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Bu [Point](/psd/python-net/aspose.psd/point/) öğesini belirtilen miktarda kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | int | x koordinatını ofsetlemek için miktar. |
| dy | int | y koordinatını ofsetlemek için miktar. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Bu [Point](/psd/python-net/aspose.psd/point/) öğesini belirtilen [Point](/psd/python-net/aspose.psd/point/) ile kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Bu [Point](/psd/python-net/aspose.psd/point/) öğesini ofsetlemek için kullanılan [Point](/psd/python-net/aspose.psd/point/) öğesi. |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesini, [Point](/psd/python-net/aspose.psd/point/) değerlerini en yakın tam sayıya yuvarlayarak bir [Point](/psd/python-net/aspose.psd/point/) nesnesine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Dönüştürülecek [PointF](/psd/python-net/aspose.psd/pointf/) öğesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Bu yöntemin dönüştürdüğü [Point](/psd/python-net/aspose.psd/point/) öğesi. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Belirtilen [Point](/psd/python-net/aspose.psd/point/) öğesinden belirtilen [Size](/psd/python-net/aspose.psd/size/) öğesini çıkarmanın sonucunu döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Çıkarma işleminin yapılacağı [Point](/psd/python-net/aspose.psd/point/) öğesi. |
| size | [Size](/psd/python-net/aspose.psd/size) | <paramref name="point" /> öğesinden çıkarılacak [Size](/psd/python-net/aspose.psd/size/) öğesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Çıkarma işleminin sonucu olan [Point](/psd/python-net/aspose.psd/point/) öğesi. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesini, [Point](/psd/python-net/aspose.psd/point/) değerlerini kırparak bir [Point](/psd/python-net/aspose.psd/point/) öğesine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Dönüştürülecek [PointF](/psd/python-net/aspose.psd/pointf/) öğesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Bu yöntemin dönüştürdüğü [Point](/psd/python-net/aspose.psd/point/) öğesi. |


