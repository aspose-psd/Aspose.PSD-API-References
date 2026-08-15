---
title: "GraphicsPath Sınıfı"
type: docs
weight: 1570
url: /tr/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır. |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır. |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır. |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Nesnenin sınırlarını alır veya ayarlar. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Yol şekillerini alır. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir [FillMode](/psd/python-net/aspose.psd/fillmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Yeni bir şekil ekler. |
| [add_figures(figures)](#add_figures_figures_2) | Yeni şekiller ekler. |
| [add_path(adding_path)](#add_path_adding_path_3) | Belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bu yola ekler. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bu yola ekler. |
| [deep_clone()](#deep_clone__5) | Bu grafik yolunun derin bir kopyasını oluşturur. |
| flatten() | Bu yoldaki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [flatten(matrix)](#flatten_matrix_6) | Belirtilen dönüşümü uygular ve ardından bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Nesnenin sınırlarını alır. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir. |
| [is_visible(point)](#is_visible_point_18) | Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(point)](#is_visible_point_19) | Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y)](#is_visible_x_y_22) | Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y)](#is_visible_x_y_23) | Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Belirtilen noktanın, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Belirtilen noktanın, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir. |
| [remove_figure(figure)](#remove_figure_figure_26) | Bir şekil kaldırır. |
| [remove_figures(figures)](#remove_figures_figures_27) | Şekilleri kaldırır. |
| reset() | Grafik yolunu boşaltır ve [FillMode](/psd/python-net/aspose.psd/fillmode/) değerini [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) olarak ayarlar. |
| reverse() | Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içindeki her şeklin figür, şekil ve nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_28) | Belirtilen dönüşümü şekle uygular. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular. |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular. |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular. |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular. |
| [widen(pen)](#widen_pen_33) | Yola ek bir dış hat ekler. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine ek bir dış hat ekler. |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yerine, bu yol belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrileri koyar. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır.

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Başlatılacak figürler. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Başlatılacak figürler. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Doldurma modu. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Yeni bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Doldurma modu. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Yeni bir şekil ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Eklenecek figür. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Yeni şekiller ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Eklenecek figürler. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bu yola ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Eklenecek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Belirtilen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bu yola ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Eklenecek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| bağlan | bool | Eklenen yoldaki ilk şeklin bu yoldaki son şeklin bir parçası olup olmadığını belirten Boolean değer. true değeri, eklenen yoldaki ilk şeklin bu yoldaki son şeklin bir parçası olduğunu belirtir. false değeri, eklenen yoldaki ilk şeklin bu yoldaki son şekilden ayrı olduğunu belirtir. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Bu grafik yolunun derin bir kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Grafik yolunun derin bir klonu. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Belirtilen dönüşümü uygular ve ardından bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Düzleştirmeden önce bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dönüştürmek için kullanılacak bir [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Düzleştirmeden önce bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dönüştürmek için kullanılacak bir [Matrix](/psd/python-net/aspose.psd/matrix/). |
| düzlük | float | Eğri ile düzleştirilmiş yaklaşımı arasındaki izin verilen maksimum hatayı belirtir. Varsayılan değer 0.25'tir. Düzlük değerini azaltmak, yaklaşımdaki çizgi segmenti sayısını artırır. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sınırların öncesinde uygulanacak matris hesaplanacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Tahmini nesne sınırları. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sınırların öncesinde uygulanacak matris hesaplanacaktır. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Tahmini nesne sınırları. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek konumu belirten bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Test edilecek konumu belirten bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek konumu belirten bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının (altında) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Test edilecek konumu belirten bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının (altında) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının (altında) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Belirtilen noktanın, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile ve belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) kullanılarak çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Test edilecek [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta, belirtilen [Pen](/psd/python-net/aspose.psd/pen/) ile çizildiğinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dış hattının (altında) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek noktayı temsil eden bir [PointF](/psd/python-net/aspose.psd/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Test edilecek noktayı temsil eden bir [PointF](/psd/python-net/aspose.psd/pointf/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Test edilecek noktayı temsil eden bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Test edilecek noktayı temsil eden bir [PointF](/psd/python-net/aspose.psd/pointf/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Belirtilen noktanın bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Belirtilen noktanın, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Belirtilen noktanın, belirtilen [Graphics](/psd/python-net/aspose.psd/graphics/) görünür kırpma bölgesinde bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Görünürlük testi yapılacak [Graphics](/psd/python-net/aspose.psd/graphics/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu yöntem, belirtilen nokta bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) içinde yer alıyorsa true; aksi takdirde false döndürür. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Bir şekil kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Kaldırılacak şekil. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Şekilleri kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Kaldırılacak şekiller. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Uygulanacak dönüşüm. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, <paramref name="srcRect" /> ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ-alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Paralelkenar <paramref name="destPoints" /> ile tanımlanan dikdörtgene dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, <paramref name="srcRect" /> ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ-alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Paralelkenar <paramref name="destPoints" /> ile tanımlanan dikdörtgene dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, <paramref name="srcRect" /> ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ-alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Paralelkenar <paramref name="destPoints" /> ile tanımlanan dikdörtgene dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir [Matrix](/psd/python-net/aspose.psd/matrix/). |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Bu bükme işleminin perspektif mi yoksa bilineer mod mu kullandığını belirten bir [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumarasyonu. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Bir dikdörtgen ve paralelkenar ile tanımlanan bir bükülme dönüşümünü bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, <paramref name="srcRect" /> ile tanımlanan dikdörtgenin dönüştürüleceği paralelkenarı tanımlar. Dizi üç veya dört öğe içerebilir. Dizi üç öğe içeriyorsa, paralelkenarın sağ-alt köşesi ilk üç nokta ile ima edilir. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Paralelkenar <paramref name="destPoints" /> ile tanımlanan dikdörtgene dönüştürülen dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir [Matrix](/psd/python-net/aspose.psd/matrix/). |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Bu bükme işleminin perspektif mi yoksa bilineer mod mu kullandığını belirten bir [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumarasyonu. |
| flatness | float | 0 ile 1 arasında bir değer, ortaya çıkan yolun ne kadar düz olduğunu belirtir. Daha fazla bilgi için [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) yöntemlerine bakın. |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Yola ek bir dış hat ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Bu yöntemin oluşturduğu yeni dış hat ile yolun orijinal dış hattı arasındaki genişliği belirten bir [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) üzerine ek bir dış hat ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Bu yöntemin oluşturduğu yeni dış hat ile yolun orijinal dış hattı arasındaki genişliği belirten bir [Pen](/psd/python-net/aspose.psd/pen/). |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Genişletmeden önce yola uygulanacak dönüşümü belirten bir [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Bu [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yerine, bu yol belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrileri koyar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Bu yöntemin oluşturduğu yeni dış hat ile yolun orijinal dış hattı arasındaki genişliği belirten bir [Pen](/psd/python-net/aspose.psd/pen/). |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Genişletmeden önce yola uygulanacak dönüşümü belirten bir [Matrix](/psd/python-net/aspose.psd/matrix/). |
| düzlük | float | Eğriler için düzlüğü belirten bir değer. |

