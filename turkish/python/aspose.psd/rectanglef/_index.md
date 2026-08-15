---
title: "RectangleF Sınıfı"
type: docs
weight: 3830
url: /tr/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | RectangleF sınıfının yeni bir örneğini başlatır |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Belirtilen konum ve boyutla [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının yeni bir örneğini başlatır. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Belirtilen konum ve boyutla [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bottom | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) ve [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) toplamı olan y koordinatını alır veya ayarlar. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Değerleri sıfır olan [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) ve [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) içeren yeni bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı örneği alır. |
| height | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının yüksekliğini alır veya ayarlar. |
| is_empty | bool | r | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) veya [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) özelliğinin değeri sıfır olup olmadığını gösteren bir değer alır. |
| left | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının sol kenarının x koordinatını alır veya ayarlar. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| right | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) ve [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) toplamı olan x koordinatını alır veya ayarlar. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının boyutunu alır veya ayarlar. |
| top | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının üst kenarının y koordinatını alır veya ayarlar. |
| width | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının genişliğini alır veya ayarlar. |
| x | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| y | float | r/w | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [contains(point)](#contains_point_1) | Belirtilen noktanın bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde olup olmadığını belirler. |
| [contains(rect)](#contains_rect_2) | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde, <paramref name="rect" /> tarafından temsil edilen dikdörtgen bölgenin tamamen içerilip içerilmediğini belirler. |
| [contains(x, y)](#contains_x_y_3) | Belirtilen noktanın bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde olup olmadığını belirler. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Belirtilen konumlardaki sol üst köşe ve sağ alt köşe ile bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı oluşturur. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Belirtilen iki noktadan yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) oluşturur. Oluşturulan [Rectangle](/psd/python-net/aspose.psd/rectangle/) iki köşesi, verilen <paramref name="point1" /> ve <paramref name="point2" /> değerlerine eşit olacaktır. Bunlar genellikle karşıt köşeler olur. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır. |
| [inflate(size)](#inflate_size_7) | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını belirtilen miktarda şişirir. |
| [inflate(x, y)](#inflate_x_y_8) | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını belirtilen miktarda şişirir. |
| [intersect(a, b)](#intersect_a_b_9) | İki dikdörtgenin kesişimini temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı döndürür. Kesişme yoksa, boş bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) döndürülür. |
| [intersect(rect)](#intersect_rect_10) | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını, kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının kesişimiyle değiştirir. |
| [intersects_with(rect)](#intersects_with_rect_11) | Bu dikdörtgenin <paramref name="rect" /> ile kesişip kesişmediğini belirler. |
| normalize() | Dikdörtgeni, genişlik ve yüksekliği pozitif yaparak, solun sağdan, üstün ise alttan küçük olmasını sağlayarak normalleştirir. |
| [offset(pos)](#offset_pos_12) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(x, y)](#offset_x_y_13) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [union(a, b)](#union_a_b_14) | Birleşim oluşturan iki dikdörtgeni içerebilecek en küçük üçüncü dikdörtgeni oluşturur. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

RectangleF sınıfının yeni bir örneğini başlatır

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Belirtilen konum ve boyutla [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Dikdörtgen bölgenin genişlik ve yüksekliğini temsil eden bir [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Belirtilen konum ve boyutla [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Dikdörtgenin genişliği. |
| yükseklik | float | Dikdörtgenin yüksekliği. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Belirtilen noktanın bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek [PointF](/psd/python-net/aspose.psd/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, <paramref name="point" /> parametresiyle temsil edilen nokta bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde bulunuyorsa true, aksi takdirde false döndürür. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde, <paramref name="rect" /> tarafından temsil edilen dikdörtgen bölgenin tamamen içerilip içerilmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Test edilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, <paramref name="rect" /> tarafından temsil edilen dikdörtgen bölgenin bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) tarafından temsil edilen dikdörtgen bölge içinde tamamen bulunuyorsa true, aksi takdirde false döndürür. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Belirtilen noktanın bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, <paramref name="x" /> ve <paramref name="y" /> ile tanımlanan nokta bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı içinde yer alıyorsa true döndürür; aksi takdirde false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Belirtilen konumlardaki sol üst köşe ve sağ alt köşe ile bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sol | float | Dikdörtgen bölgenin sol üst köşesinin x koordinatı. |
| üst | float | Dikdörtgen bölgenin sol üst köşesinin y koordinatı. |
| sağ | float | Dikdörtgen bölgenin sağ alt köşesinin x koordinatı. |
| alt | float | Dikdörtgen bölgenin sağ alt köşesinin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu yöntemin oluşturduğu yeni [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Belirtilen iki noktadan yeni bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) oluşturur. Oluşturulan [Rectangle](/psd/python-net/aspose.psd/rectangle/) iki köşesi, verilen <paramref name="point1" /> ve <paramref name="point2" /> değerlerine eşit olacaktır. Bunlar genellikle karşıt köşeler olur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Yeni dikdörtgen için ilk [Point](/psd/python-net/aspose.psd/point/). |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Yeni dikdörtgen için ikinci [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Yeni oluşturulmuş bir [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kopyalanacak [RectangleF](/psd/python-net/aspose.psd/rectanglef/). Bu dikdörtgen değiştirilmeyecek. |
| x | float | Dikdörtgenin kopyasını yatay olarak şişirme miktarı. |
| y | float | Dikdörtgenin kopyasını dikey olarak şişirme miktarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Şişirilmiş [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını belirtilen miktarda şişirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Bu dikdörtgeni şişirme miktarı. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını belirtilen miktarda şişirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını yatay olarak şişirme miktarı. |
| y | float | Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını dikey olarak şişirme miktarı. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

İki dikdörtgenin kesişimini temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı döndürür. Kesişme yoksa, boş bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) döndürülür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kesişmek için birinci dikdörtgen. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kesişmek için ikinci dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Belirtilen iki dikdörtgenin çakışan alanını temsil eden boyuta sahip üçüncü bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Bu [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısını, kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının kesişimiyle değiştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kesişmek için dikdörtgen. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Bu dikdörtgenin <paramref name="rect" /> ile kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Test edilecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, herhangi bir kesişme varsa true döndürür. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | Konumu ofsetleme miktarı. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Konumu yatay olarak ofsetleme miktarı. |
| y | float | Konumu dikey olarak ofsetleme miktarı. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Birleşim oluşturan iki dikdörtgeni içerebilecek en küçük üçüncü dikdörtgeni oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Birinci birleştirilecek dikdörtgen. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | İkinci birleştirilecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Birleştirmeyi oluşturan iki dikdörtgeni içeren üçüncü bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |


