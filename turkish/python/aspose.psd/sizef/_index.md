---
title: "SizeF Sınıfı"
type: docs
weight: 4090
url: /tr/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SizeF()](#SizeF__1) | SizeF sınıfının yeni bir örneğini başlatır |
| [SizeF(point)](#SizeF_point_2) | Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesinden yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği oluşturur. |
| [SizeF(size)](#SizeF_size_3) | Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinden yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği oluşturur. |
| [SizeF(width, height)](#SizeF_width_height_4) | Belirtilen boyutlardan yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği oluşturur. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Sıfır olarak ayarlanmış [SizeF.width](/psd/python-net/aspose.psd/sizef/) ve [SizeF.height](/psd/python-net/aspose.psd/sizef/) değerlerine sahip yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği alır. |
| height | float | r/w | Bu [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinin dikey bileşenini alır veya ayarlar. |
| is_empty | bool | r | Bu [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinin sıfır genişlik ve yüksekliğe sahip olup olmadığını gösteren bir değer alır. |
| width | float | r/w | Bu [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinin yatay bileşenini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğine ekler. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğinden çıkarır. |
| [to_point_f()](#to_point_f__3) | [SizeF](/psd/python-net/aspose.psd/sizef/) öğesini bir [PointF](/psd/python-net/aspose.psd/pointf/) öğesine dönüştürür. |
| [to_size()](#to_size__4) | [SizeF](/psd/python-net/aspose.psd/sizef/) öğesini kesilmiş boyut değerlerine sahip bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

SizeF sınıfının yeni bir örneğini başlatır

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) öğesinden yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Bu [SizeF](/psd/python-net/aspose.psd/sizef/) öğesini başlatmak için kullanılacak [PointF](/psd/python-net/aspose.psd/pointf/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinden yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) oluşturmak için kullanılacak [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Belirtilen boyutlardan yeni bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | float | Yeni [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinin genişlik bileşeni. |
| height | float | Yeni [SizeF](/psd/python-net/aspose.psd/sizef/) öğesinin yükseklik bileşeni. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğine ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Eklemek için ilk [SizeF](/psd/python-net/aspose.psd/sizef/). |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Eklemek için ikinci [SizeF](/psd/python-net/aspose.psd/sizef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Toplama işleminin sonucu olan bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğini başka bir [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Çıkarma operatörünün sol tarafındaki [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Çıkarma operatörünün sağ tarafındaki [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Çıkarma işleminin sonucu olan [SizeF](/psd/python-net/aspose.psd/sizef/). |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

[SizeF](/psd/python-net/aspose.psd/sizef/) öğesini bir [PointF](/psd/python-net/aspose.psd/pointf/) öğesine dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısını döndürür. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

[SizeF](/psd/python-net/aspose.psd/sizef/) öğesini kesilmiş boyut değerlerine sahip bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) yapısını döndürür. |


