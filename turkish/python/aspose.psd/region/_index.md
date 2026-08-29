---
title: "Region Sınıfı"
type: docs
weight: 3870
url: /tr/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Region()](#Region__1) | Yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır. |
| [Region(path)](#Region_path_2) | Belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ile yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır. |
| [Region(rect)](#Region_rect_3) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısından yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır. |
| [Region(rect)](#Region_rect_4) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısından yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [complement(path)](#complement_path_1) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bölümünü içerecek şekilde günceller. |
| [complement(rect)](#complement_rect_2) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının bölümünü içerecek şekilde günceller. |
| [complement(rect)](#complement_rect_3) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının bölümünü içerecek şekilde günceller. |
| [complement(region)](#complement_region_4) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [Region](/psd/python-net/aspose.psd/region/) bölümünü içerecek şekilde günceller. |
| [deep_clone()](#deep_clone__5) | Bu [Region](/psd/python-net/aspose.psd/region/)'in tam bir derin kopyasını oluşturur. |
| [exclude(path)](#exclude_path_6) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller. |
| [exclude(rect)](#exclude_rect_7) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller. |
| [exclude(rect)](#exclude_rect_8) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller. |
| [exclude(region)](#exclude_region_9) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller. |
| [intersect(path)](#intersect_path_10) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ile kesişimine günceller. |
| [intersect(rect)](#intersect_rect_11) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişimine günceller. |
| [intersect(rect)](#intersect_rect_12) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişimine günceller. |
| [intersect(region)](#intersect_region_13) | Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [Region](/psd/python-net/aspose.psd/region/) ile kesişimine günceller. |
| [is_empty(g)](#is_empty_g_14) | Bu [Region](/psd/python-net/aspose.psd/region/)'in belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder. |
| [is_infinite(g)](#is_infinite_g_15) | Bu [Region](/psd/python-net/aspose.psd/region/)'in belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder. |
| [is_visible(point)](#is_visible_point_16) | Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(point)](#is_visible_point_17) | Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(point, g)](#is_visible_point_g_18) | Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(point, g)](#is_visible_point_g_19) | Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(rect)](#is_visible_rect_20) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(rect)](#is_visible_rect_21) | Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y)](#is_visible_x_y_24) | Belirtilen noktanın bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen noktanın bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen noktanın bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Belirtilen dikdörtgenin herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Belirtilen dikdörtgenin herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder. |
| make_empty() | Bu [Region](/psd/python-net/aspose.psd/region/) içini boş bir iç bölgeye başlatır. |
| make_infinite() | Bu [Region](/psd/python-net/aspose.psd/region/) nesnesini sonsuz bir iç bölgeye başlatır. |
| [transform(matrix)](#transform_matrix_31) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile dönüştürür. |
| [translate(dx, dy)](#translate_dx_dy_32) | Bu [Region](/psd/python-net/aspose.psd/region/) koordinatlarını belirtilen miktarda kaydırır. |
| [translate(dx, dy)](#translate_dx_dy_33) | Bu [Region](/psd/python-net/aspose.psd/region/) koordinatlarını belirtilen miktarda kaydırır. |
| [union(path)](#union_path_34) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) birleşimine günceller. |
| [union(rect)](#union_rect_35) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının birleşimine günceller. |
| [union(rect)](#union_rect_36) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının birleşimine günceller. |
| [union(region)](#union_region_37) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [Region](/psd/python-net/aspose.psd/region/) birleşimine günceller. |
| [xor(path)](#xor_path_38) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) kesişiminin çıkarıldığı birleşime günceller. |
| [xor(rect)](#xor_rect_39) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının kesişiminin çıkarıldığı birleşime günceller. |
| [xor(rect)](#xor_rect_40) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının kesişiminin çıkarıldığı birleşime günceller. |
| [xor(region)](#xor_region_41) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [Region](/psd/python-net/aspose.psd/region/) kesişiminin çıkarıldığı birleşime günceller. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır.

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ile yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Yeni bir [Region](/psd/python-net/aspose.psd/region/) tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısından yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Yeni bir [Region](/psd/python-net/aspose.psd/region/) içini tanımlayan bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısından yeni bir [Region](/psd/python-net/aspose.psd/region/) başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Yeni bir [Region](/psd/python-net/aspose.psd/region/) içini tanımlayan bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini tamamlamak için [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini tamamlamak için [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesini tamamlamak için [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, bu [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen belirtilen [Region](/psd/python-net/aspose.psd/region/) bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Bu [Region](/psd/python-net/aspose.psd/region/) nesnesini tamamlamak için [Region](/psd/python-net/aspose.psd/region/) nesnesi. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'in tam bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | Bu yöntemin oluşturduğu [Region](/psd/python-net/aspose.psd/region/). |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesinden hariç tutulacak [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesinden hariç tutulacak [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesinden hariç tutulacak [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [Region](/psd/python-net/aspose.psd/region/) ile kesişmeyen yalnızca iç kısmının bölümünü içerecek şekilde günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Bu [Region](/psd/python-net/aspose.psd/region/) öğesinden hariç tutulacak [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ile kesişimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Bu [Region](/psd/python-net/aspose.psd/region/) ile kesişecek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [Region](/psd/python-net/aspose.psd/region/) ile kesişecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile kesişimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [Region](/psd/python-net/aspose.psd/region/) ile kesişecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'i, belirtilen [Region](/psd/python-net/aspose.psd/region/) ile kesişimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Bu [Region](/psd/python-net/aspose.psd/region/) ile kesişecek [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'in belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir çizim yüzeyini temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu [Region](/psd/python-net/aspose.psd/region/) içi, <paramref name="g" /> ile ilişkili dönüşüm uygulandığında boş ise doğru; aksi takdirde yanlış. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Bu [Region](/psd/python-net/aspose.psd/region/)'in belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir çizim yüzeyini temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu [Region](/psd/python-net/aspose.psd/region/) içi, <paramref name="g" /> ile ilişkili dönüşüm uygulandığında sonsuz ise doğru; aksi takdirde yanlış. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek [PointF](/psd/python-net/aspose.psd/pointf/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="point" /> bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Test edilecek [PointF](/psd/python-net/aspose.psd/pointf/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="point" /> bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek [PointF](/psd/python-net/aspose.psd/pointf/) yapısı. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="point" /> bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Test edilecek [PointF](/psd/python-net/aspose.psd/pointf/) yapısı. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="point" /> bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Test edilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="rect" />'in herhangi bir kısmı bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Test edilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="rect" />'in herhangi bir kısmı bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Test edilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="rect" /> bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Test edilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <paramref name="rect" /> bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Belirtilen noktanın bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen noktanın bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) ile çizildiğinde, belirtilen noktanın bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen nokta bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Belirtilen dikdörtgenin herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Test edilecek dikdörtgenin genişliği. |
| yükseklik | float | Test edilecek dikdörtgenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen dikdörtgenin herhangi bir kısmı bu [Region](/psd/python-net/aspose.psd/region/) nesnesi içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Belirtilen dikdörtgenin herhangi bir bölümünün bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Test edilecek dikdörtgenin genişliği. |
| yükseklik | int | Test edilecek dikdörtgenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen dikdörtgenin herhangi bir kısmı bu [Region](/psd/python-net/aspose.psd/region/) nesnesi içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Test edilecek dikdörtgenin genişliği. |
| yükseklik | float | Test edilecek dikdörtgenin yüksekliği. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen dikdörtgenin herhangi bir kısmı bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Belirtilen dikdörtgenin herhangi bir bölümünün, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [Region](/psd/python-net/aspose.psd/region/) içinde olup olmadığını test eder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Test edilecek dikdörtgenin genişliği. |
| yükseklik | int | Test edilecek dikdörtgenin yüksekliği. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Bir grafik bağlamını temsil eden [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen dikdörtgenin herhangi bir kısmı bu [Region](/psd/python-net/aspose.psd/region/) içinde yer alıyorsa doğru; aksi takdirde yanlış. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Bu [Region](/psd/python-net/aspose.psd/region/) dönüştürmek için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) koordinatlarını belirtilen miktarda kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | Bu [Region](/psd/python-net/aspose.psd/region/) yatay olarak kaydırma miktarı. |
| dy | float | Bu [Region](/psd/python-net/aspose.psd/region/) dikey olarak kaydırma miktarı. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) koordinatlarını belirtilen miktarda kaydırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | int | Bu [Region](/psd/python-net/aspose.psd/region/) yatay olarak kaydırma miktarı. |
| dy | int | Bu [Region](/psd/python-net/aspose.psd/region/) dikey olarak kaydırma miktarı. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) birleşimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Bu [Region](/psd/python-net/aspose.psd/region/) ile birleştirilecek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının birleşimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [Region](/psd/python-net/aspose.psd/region/) ile birleştirilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının birleşimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [Region](/psd/python-net/aspose.psd/region/) ile birleştirilecek [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini kendisi ile belirtilen [Region](/psd/python-net/aspose.psd/region/) birleşimine günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Bu [Region](/psd/python-net/aspose.psd/region/) ile birleştirilecek [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Bu [Region](/psd/python-net/aspose.psd/region/) ile xor yapılacak [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [Region](/psd/python-net/aspose.psd/region/) ile xor yapılacak [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısının kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [Region](/psd/python-net/aspose.psd/region/) ile xor yapılacak [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Bu [Region](/psd/python-net/aspose.psd/region/) öğesini, kendisi ile belirtilen [Region](/psd/python-net/aspose.psd/region/) kesişiminin çıkarıldığı birleşime günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Bu [Region](/psd/python-net/aspose.psd/region/) ile xor yapılacak [Region](/psd/python-net/aspose.psd/region/). |

