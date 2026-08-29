---
title: "PointF Sınıfı"
type: docs
weight: 3550
url: /tr/python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PointF()](#PointF__1) | PointF sınıfının yeni bir örneğini başlatır |
| [PointF(x, y)](#PointF_x_y_2) | Belirtilen koordinatlarla yeni bir [PointF](/psd/python-net/aspose.psd/pointf/) yapısı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | Sıfır değerine ayarlanmış [PointF.x](/psd/python-net/aspose.psd/pointf/) ve [PointF.y](/psd/python-net/aspose.psd/pointf/) değerlerine sahip yeni bir [PointF](/psd/python-net/aspose.psd/pointf/) yapısı örneği alır. |
| is_empty | bool | r | Bu [PointF](/psd/python-net/aspose.psd/pointf/) nesnesinin boş olup olmadığını gösteren değeri alır. |
| x | float | r/w | Bu [PointF](/psd/python-net/aspose.psd/pointf/) nesnesinin x koordinatını alır veya ayarlar. |
| y | float | r/w | Bu [PointF](/psd/python-net/aspose.psd/pointf/) nesnesinin y koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Belirtilen [Size](/psd/python-net/aspose.psd/size/) ile verilen bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır. |
| [add(point, size)](#add_point_size_2) | Belirtilen [Size](/psd/python-net/aspose.psd/size/) ile verilen bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır. |
| [subtract(point, size)](#subtract_point_size_3) | Belirtilen bir boyutun negatifine göre bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır. |
| [subtract(point, size)](#subtract_point_size_4) | Belirtilen bir boyutun negatifine göre bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır. |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

PointF sınıfının yeni bir örneğini başlatır

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

Belirtilen koordinatlarla yeni bir [PointF](/psd/python-net/aspose.psd/pointf/) yapısı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Noktanın yatay konumu. |
| y | float | Noktanın dikey konumu. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Belirtilen [Size](/psd/python-net/aspose.psd/size/) ile verilen bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilecek [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [Size](/psd/python-net/aspose.psd/size) | Koordinatlarına <paramref name="point" /> eklemek için sayıları belirten [Size](/psd/python-net/aspose.psd/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilen [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

Belirtilen [Size](/psd/python-net/aspose.psd/size/) ile verilen bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilecek [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Koordinatlarına <paramref name="point" /> eklemek için sayıları belirten [Size](/psd/python-net/aspose.psd/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilen [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

Belirtilen bir boyutun negatifine göre bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilecek [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [Size](/psd/python-net/aspose.psd/size) | Koordinatlarından <paramref name="point" /> çıkarmak için sayıları belirten [Size](/psd/python-net/aspose.psd/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilen [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

Belirtilen bir boyutun negatifine göre bir [PointF](/psd/python-net/aspose.psd/pointf/) kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilecek [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Koordinatlarından <paramref name="point" /> çıkarmak için sayıları belirten [Size](/psd/python-net/aspose.psd/size/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Çevrilen [PointF](/psd/python-net/aspose.psd/pointf/). |


