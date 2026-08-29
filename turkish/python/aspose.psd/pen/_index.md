---
title: "Pen Sınıfı"
type: docs
weight: 3360
url: /tr/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Belirtilen [Pen.brush](/psd/python-net/aspose.psd/pen/) ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır. |
| [Pen(brush, width)](#Pen_brush_width_2) | Belirtilen [Pen.brush](/psd/python-net/aspose.psd/pen/) ve [Pen.width](/psd/python-net/aspose.psd/pen/) ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır. |
| [Pen(color)](#Pen_color_3) | Belirtilen renk ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır. |
| [Pen(color, width)](#Pen_color_width_4) | Belirtilen [Pen.color](/psd/python-net/aspose.psd/pen/) ve [Pen.width](/psd/python-net/aspose.psd/pen/) özellikleri ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) için hizalamayı alır veya ayarlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) öğesinin özelliklerini belirleyen [Pen.brush](/psd/python-net/aspose.psd/pen/) değerini alır veya ayarlar. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) öğesinin rengini alır veya ayarlar. |
| compound_array | float | r/w | Bir bileşik kalemi tanımlayan değerler dizisini alır veya ayarlar. Bileşik kalem, paralel çizgiler ve boşluklardan oluşan bir bileşik çizgi çizer. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen çizgilerin ucunda kullanılacak özel bir kapak alır veya ayarlar. |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak alır veya ayarlar. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen kesikli çizgileri oluşturan tirelerin ucunda kullanılan kapak stilini alır veya ayarlar. |
| dash_offset | float | r/w | Bir çizginin başlangıcından tire deseninin başlangıcına olan mesafeyi alır veya ayarlar. |
| dash_pattern | float | r/w | Özel tireler ve boşluklardan oluşan bir dizi alır veya ayarlar. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen kesikli çizgilerde kullanılan stili alır veya ayarlar. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen çizgilerin ucunda kullanılan kapak stilini alır veya ayarlar. |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen iki ardışık çizginin uçları için birleşim stilini alır veya ayarlar. |
| miter_limit | float | r/w | Miter köşesindeki birleşimin kalınlık sınırını alır veya ayarlar. |
| opaklık | float | r/w | Nesnenin opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri nesnenin tamamen görünür olduğu, 1 değeri ise nesnenin tamamen opak olduğu anlamına gelir. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen çizgilerin stilini alır. |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen çizgilerin başlangıcında kullanılan kapak stilini alır veya ayarlar. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) için geometrik dönüşümün bir kopyasını alır veya ayarlar. |
| width | float | r/w | Bu [Pen](/psd/python-net/aspose.psd/pen/) genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Bu [Pen](/psd/python-net/aspose.psd/pen/) için dönüşüm matrisini belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile çarpar. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Bu [Pen](/psd/python-net/aspose.psd/pen/) için dönüşüm matrisini belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | Bu [Pen](/psd/python-net/aspose.psd/pen/) için geometrik dönüşüm matrisini birim matrise sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem dönüşüme rotasyonu ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Yerel geometrik dönüşümü belirtilen açıyla, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ek olarak ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendirir. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Bu [Pen](/psd/python-net/aspose.psd/pen/) tarafından çizilen satırların sonlandırılmasında kullanılan kap stilini belirleyen değerleri ayarlar. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ek olarak ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Belirtilen [Pen.brush](/psd/python-net/aspose.psd/pen/) ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Bu [Pen](/psd/python-net/aspose.psd/pen/) için doldurma özelliklerini belirleyen bir [Pen.brush](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Belirtilen [Pen.brush](/psd/python-net/aspose.psd/pen/) ve [Pen.width](/psd/python-net/aspose.psd/pen/) ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Bu [Pen](/psd/python-net/aspose.psd/pen/) özelliklerini belirleyen bir [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| width | float | Yeni [Pen](/psd/python-net/aspose.psd/pen/) genişliği. |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Belirtilen renk ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Bu [Pen](/psd/python-net/aspose.psd/pen/) rengini gösteren bir [Pen.color](/psd/python-net/aspose.psd/pen/) yapısı. |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Belirtilen [Pen.color](/psd/python-net/aspose.psd/pen/) ve [Pen.width](/psd/python-net/aspose.psd/pen/) özellikleri ile yeni bir [Pen](/psd/python-net/aspose.psd/pen/) sınıfı örneği başlatılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Bu [Pen](/psd/python-net/aspose.psd/pen/) rengini gösteren bir [Pen.color](/psd/python-net/aspose.psd/pen/) yapısı. |
| width | float | Bu [Pen](/psd/python-net/aspose.psd/pen/) genişliğini gösteren bir değer. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Bu [Pen](/psd/python-net/aspose.psd/pen/) için dönüşüm matrisini belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Dönüşüm matrisini çarpmak için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/) nesnesi. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Bu [Pen](/psd/python-net/aspose.psd/pen/) için dönüşüm matrisini belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Dönüşüm matrisini çarpmak için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/). |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Çarpma işleminin gerçekleştirileceği sıra. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Rotasyon açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen açıyla, belirtilen sırada döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Rotasyon açısı. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Rotasyon matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ek olarak ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümü x ekseni yönünde ölçeklendirecek faktör. |
| sy | float | Dönüşümü y ekseni yönünde ölçeklendirecek faktör. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümü x ekseni yönünde ölçeklendirecek faktör. |
| sy | float | Dönüşümü y ekseni yönünde ölçeklendirecek faktör. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ölçekleme matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Bu [Pen](/psd/python-net/aspose.psd/pen/) tarafından çizilen satırların sonlandırılmasında kullanılan kap stilini belirleyen değerleri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen satırların başlangıcında kullanılacak kap stilini temsil eden bir [LineCap](/psd/python-net/aspose.psd/linecap/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen satırların sonunda kullanılacak kap stilini temsil eden bir [LineCap](/psd/python-net/aspose.psd/linecap/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Bu [Pen](/psd/python-net/aspose.psd/pen/) ile çizilen kesikli satırların başlangıcında veya sonunda kullanılacak kap stilini temsil eden bir [LineCap](/psd/python-net/aspose.psd/linecap/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ek olarak ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Çevirinin uygulanacağı sıra (başına ekleme veya sona ekleme). |

