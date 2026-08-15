---
title: "Size Sınıfı"
type: docs
weight: 4080
url: /tr/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Size()](#Size__1) | Yeni bir Size sınıfının örneğini başlatır |
| [Size(point)](#Size_point_2) | Belirtilen [Point](/psd/python-net/aspose.psd/point/) üzerinden yeni bir [Size](/psd/python-net/aspose.psd/size/) yapısının bir örneğini başlatır. |
| [Size(width, height)](#Size_width_height_3) | Belirtilen boyutlardan yeni bir [Size](/psd/python-net/aspose.psd/size/) yapısının bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | [Size.width](/psd/python-net/aspose.psd/size/) ve [Size.height](/psd/python-net/aspose.psd/size/) değerleri sıfıra ayarlanmış yeni bir [Size](/psd/python-net/aspose.psd/size/) yapısını alır. |
| height | int | r/w | Bu [Size](/psd/python-net/aspose.psd/size/) öğesinin dikey bileşenini alır veya ayarlar. |
| is_empty | bool | r | Bu [Size](/psd/python-net/aspose.psd/size/) öğesinin genişlik ve yüksekliğinin 0 olup olmadığını gösteren bir değeri alır. |
| width | int | r/w | Bu [Size](/psd/python-net/aspose.psd/size/) öğesinin yatay bileşenini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğini başka bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğine ekler. |
| [ceiling(size)](#ceiling_size_2) | Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) yapısını, [Size](/psd/python-net/aspose.psd/size/) yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür. |
| [round(size)](#round_size_3) | Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) yapısını, [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının değerlerini en yakın tam sayıya yuvarlayarak bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğini, başka bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğinden çıkarır. |
| [truncate(size)](#truncate_size_5) | Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) yapısını, [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının değerlerini bir alt tam sayıya kırparak bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Yeni bir Size sınıfının örneğini başlatır

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Belirtilen [Point](/psd/python-net/aspose.psd/point/) üzerinden yeni bir [Size](/psd/python-net/aspose.psd/size/) yapısının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Bu [Size](/psd/python-net/aspose.psd/size/) nesnesini başlatmak için kullanılacak [Point](/psd/python-net/aspose.psd/point/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Belirtilen boyutlardan yeni bir [Size](/psd/python-net/aspose.psd/size/) yapısının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Yeni [Size](/psd/python-net/aspose.psd/size/) nesnesinin genişlik bileşeni. |
| height | int | Yeni [Size](/psd/python-net/aspose.psd/size/) nesnesinin yükseklik bileşeni. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğini başka bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğine ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Eklenecek ilk [Size](/psd/python-net/aspose.psd/size/). |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Eklenecek ikinci [Size](/psd/python-net/aspose.psd/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Toplama işleminin sonucu olan bir [Size](/psd/python-net/aspose.psd/size/) yapısı. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) yapısını, [Size](/psd/python-net/aspose.psd/size/) yapısının değerlerini bir sonraki üst tam sayıya yuvarlayarak bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Dönüştürülecek [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Bu yöntemin dönüştürdüğü [Size](/psd/python-net/aspose.psd/size/) yapısı. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) yapısını, [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının değerlerini en yakın tam sayıya yuvarlayarak bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Dönüştürülecek [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Bu yöntemin dönüştürdüğü [Size](/psd/python-net/aspose.psd/size/) yapısı. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğini, başka bir [Size](/psd/python-net/aspose.psd/size/) yapısının genişlik ve yüksekliğinden çıkarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Çıkarma operatörünün sol tarafındaki [Size](/psd/python-net/aspose.psd/size/) yapısı. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Çıkarma operatörünün sağ tarafındaki [Size](/psd/python-net/aspose.psd/size/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Çıkarma işleminin sonucu olan [Size](/psd/python-net/aspose.psd/size/). |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Belirtilen [SizeF](/psd/python-net/aspose.psd/sizef/) yapısını, [SizeF](/psd/python-net/aspose.psd/sizef/) yapısının değerlerini bir alt tam sayıya kırparak bir [Size](/psd/python-net/aspose.psd/size/) yapısına dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Dönüştürülecek [SizeF](/psd/python-net/aspose.psd/sizef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Bu yöntemin dönüştürdüğü [Size](/psd/python-net/aspose.psd/size/) yapısı. |


