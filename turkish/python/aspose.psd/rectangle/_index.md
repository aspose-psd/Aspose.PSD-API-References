---
title: "Rectangle Sınıfı"
type: docs
weight: 3810
url: /tr/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Rectangle sınıfının yeni bir örneğini başlatır |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Belirtilen konum ve boyutla [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının yeni bir örneğini başlatır. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Belirtilen konum ve boyutla [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bottom | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) ve [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Değerleri sıfır olarak ayarlanmış [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) ve [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) olan yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı alır. |
| height | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının yüksekliğini alır veya ayarlar. |
| is_empty | bool | r | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının tüm sayısal özelliklerinin değeri sıfır mı olduğunu gösteren bir değer alır. |
| left | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sol kenarının x koordinatını alır veya ayarlar. |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| right | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) ve [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar. |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının boyutunu alır veya ayarlar. |
| top | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının üst kenarının y koordinatını alır veya ayarlar. |
| width | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının genişliğini alır veya ayarlar. |
| x | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| y | int | r/w | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını, [RectangleF](/psd/python-net/aspose.psd/rectanglef/) değerlerini bir üst tam sayıya yuvarlayarak bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısına dönüştürür. |
| [contains(point)](#contains_point_2) | Belirtilen noktanın bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı içinde olup olmadığını belirler. |
| [contains(rect)](#contains_rect_3) | <paramref name="rect" /> tarafından temsil edilen dikdörtgen bölgenin tamamen bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı içinde olup olmadığını belirler. |
| [contains(x, y)](#contains_x_y_4) | Belirtilen noktanın bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı içinde olup olmadığını belirler. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Belirtilen kenar konumlarıyla bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı oluşturur. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Belirtilen iki noktadan yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) oluşturur. Oluşturulan [Rectangle](/psd/python-net/aspose.psd/rectangle/) iki kenarı, verilen <paramref name="point1" /> ve <paramref name="point2" /> değerlerine eşit olur. Bunlar genellikle karşıt köşeler olur. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Belirtilen [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı değişmeden kalır. |
| [inflate(size)](#inflate_size_8) | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini belirtilen miktarda genişletir. |
| [inflate(width, height)](#inflate_width_height_9) | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini belirtilen miktarda genişletir. |
| [intersect(a, b)](#intersect_a_b_10) | İki diğer [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının kesişimini temsil eden üçüncü bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı döndürür. Kesişme yoksa, boş bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) döndürülür. |
| [intersect(rect)](#intersect_rect_11) | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini, kendisi ile belirtilen [Rectangle](/psd/python-net/aspose.psd/rectangle/) kesişimiyle değiştirir. |
| [intersects_with(rect)](#intersects_with_rect_12) | Bu dikdörtgenin <paramref name="rect" /> ile kesişip kesişmediğini belirler. |
| normalize() | Dikdörtgeni, genişlik ve yüksekliği pozitif yaparak, solun sağdan, üstün ise alttan küçük olmasını sağlayarak normalleştirir. |
| [offset(pos)](#offset_pos_13) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(x, y)](#offset_x_y_14) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [round(value)](#round_value_15) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) değerlerini en yakın tam sayıya yuvarlayarak bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) nesnesine dönüştürür. |
| [truncate(value)](#truncate_value_16) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) değerlerini kırparak bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) nesnesine dönüştürür. |
| [union(a, b)](#union_a_b_17) | İki [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının birleşimini içeren bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı alır. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Rectangle sınıfının yeni bir örneğini başlatır

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Belirtilen konum ve boyutla [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir [Point](/psd/python-net/aspose.psd/point/). |
| size | [Size](/psd/python-net/aspose.psd/size) | Dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eden bir [Size](/psd/python-net/aspose.psd/size/). |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Belirtilen konum ve boyutla [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Dikdörtgenin genişliği. |
| yükseklik | int | Dikdörtgenin yüksekliği. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını, [RectangleF](/psd/python-net/aspose.psd/rectanglef/) değerlerini bir üst tam sayıya yuvarlayarak bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısına dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dönüştürülecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) döndürür. |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Belirtilen noktanın bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Test edilecek [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, <paramref name="point" /> tarafından temsil edilen nokta bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının içinde ise true, aksi takdirde false döndürür. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

<paramref name="rect" /> tarafından temsil edilen dikdörtgen bölgenin tamamen bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Test edilecek [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, <paramref name="rect" /> tarafından temsil edilen dikdörtgen bölge bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının içinde tamamen yer alıyorsa true, aksi takdirde false döndürür. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Belirtilen noktanın bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, <paramref name="x" /> ve <paramref name="y" /> tarafından tanımlanan nokta bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının içinde ise true, aksi takdirde false döndürür. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Belirtilen kenar konumlarıyla bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| left | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sol üst köşesinin x koordinatı. |
| top | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sol üst köşesinin y koordinatı. |
| right | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sağ alt köşesinin x koordinatı. |
| bottom | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının sağ alt köşesinin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu yöntemin oluşturduğu yeni [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Belirtilen iki noktadan yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) oluşturur. Oluşturulan [Rectangle](/psd/python-net/aspose.psd/rectangle/) iki kenarı, verilen <paramref name="point1" /> ve <paramref name="point2" /> değerlerine eşit olur. Bunlar genellikle karşıt köşeler olur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Yeni dikdörtgen için ilk [Point](/psd/python-net/aspose.psd/point/). |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Yeni dikdörtgen için ikinci [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Yeni oluşturulmuş bir [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Belirtilen [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı değişmeden kalır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Başlangıç için kullanılacak [Rectangle](/psd/python-net/aspose.psd/rectangle/). Bu dikdörtgen değiştirilmez. |
| x | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini yatay olarak genişletme miktarı. |
| y | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini dikey olarak genişletme miktarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Genişletilmiş [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini belirtilen miktarda genişletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Bu dikdörtgeni şişirme miktarı. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini belirtilen miktarda genişletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini yatay olarak genişletme miktarı. |
| height | int | Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini dikey olarak genişletme miktarı. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

İki diğer [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının kesişimini temsil eden üçüncü bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı döndürür. Kesişme yoksa, boş bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) döndürülür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kesişmek için birinci dikdörtgen. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kesişmek için ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | <paramref name="a" /> ve <paramref name="b" /> kesişimini temsil eden bir [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Bu [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini, kendisi ile belirtilen [Rectangle](/psd/python-net/aspose.psd/rectangle/) kesişimiyle değiştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kesişmek için kullanılacak [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Bu dikdörtgenin <paramref name="rect" /> ile kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Test edilecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, herhangi bir kesişim varsa true, aksi takdirde false döndürür. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Konumu kaydırma miktarı. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Yatay kaydırma. |
| y | int | Dikey kaydırma. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) değerlerini en yakın tam sayıya yuvarlayarak bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) nesnesine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dönüştürülecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) değerlerini kırparak bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) nesnesine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dönüştürülecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

İki [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının birleşimini içeren bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Birinci birleştirilecek dikdörtgen. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İkinci birleştirilecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | İki [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısının birleşimini sınırlayan bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı. |


