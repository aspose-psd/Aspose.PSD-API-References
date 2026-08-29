---
title: "PathGradientBrush Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Belirtilen yol ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Belirtilen noktalar ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Belirtilen noktalar ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Belirtilen noktalar ve sarma modu ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Belirtilen noktalar ve sarma modu ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir [Blend](/psd/python-net/aspose.psd/blend/) alır veya ayarlar. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Yol degrade merkezindeki rengi alır veya ayarlar. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Yol gradyanının merkez noktasını alır veya ayarlar. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gradyan düşüşü için odak noktasını alır veya ayarlar. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Çok renkli doğrusal bir gradyanı tanımlayan bir [ColorBlend](/psd/python-net/aspose.psd/colorblend/) alır veya ayarlar. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini belirten bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| opaklık | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Bu [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) tarafından doldurulan yoldaki noktalara karşılık gelen renk dizisini alır veya ayarlar. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Bu [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) için yerel geometrik dönüşümü tanımlayan bir kopya [Matrix](/psd/python-net/aspose.psd/matrix/) alır veya ayarlar. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Bu [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) için sarma modunu gösteren bir [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enum değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Mevcut [Brush](/psd/python-net/aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Bu [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile ön ekleyerek çarpar. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Bu [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | Kimlik değerine sıfırlar [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) özelliğini. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem dönüşüme rotasyonu ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Yerel geometrik dönüşümü belirtilen miktarlarda ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Yerel geometrik dönüşümü belirtilen miktarlarda, belirtilen sırada ölçeklendirir. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Merkez rengi ve bir çevre rengine doğru lineer azalma ile bir degrade oluşturur. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Merkez rengi ve her çevre rengine doğru lineer azalma ile bir degrade oluşturur. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Yolun merkezinden dış sınırına doğru renk değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Yolun merkezinden dış sınırına doğru renk değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Yerel geometrik dönüşümü belirtilen boyutlarda taşır. Bu yöntem dönüşüme taşıma işlemini ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada taşır. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Belirtilen yol ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Bu [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) tarafından doldurulan alanı tanımlayan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Belirtilen noktalar ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Yolun köşe noktalarını oluşturan noktaları temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapıların bir dizisi. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Belirtilen noktalar ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Yolun köşe noktalarını oluşturan noktaları temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapıların bir dizisi. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Belirtilen noktalar ve sarma modu ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Yolun köşe noktalarını oluşturan noktaları temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapıların bir dizisi. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Bu [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) ile çizilen doldurmaların nasıl döşeneceğini belirten bir [WrapMode](/psd/python-net/aspose.psd/wrapmode/). |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Belirtilen noktalar ve sarma modu ile [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Yolun köşe noktalarını oluşturan noktaları temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapıların bir dizisi. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Bu [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) ile çizilen doldurmaların nasıl döşeneceğini belirten bir [WrapMode](/psd/python-net/aspose.psd/wrapmode/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Mevcut [Brush](/psd/python-net/aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Bu [Brush](/psd/python-net/aspose.psd/brush/) örneğinin derin kopyası olan yeni bir [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Bu [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile ön ekleyerek çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Bu [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/). |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Rotasyon açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Rotasyon açısı. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Rotasyon matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen miktarlarda ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Yerel geometrik dönüşümü belirtilen miktarlarda, belirtilen sırada ölçeklendirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ölçekleme matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Merkez rengi ve bir çevre rengine doğru lineer azalma ile bir degrade oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Merkez rengi ve her çevre rengine doğru lineer azalma ile bir degrade oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |
| scale | float | 0 ile 1 arasında bir değer, merkez renginin sınır rengiyle karıştığı maksimum yoğunluğu belirler. 1 değeri, merkez renginin mümkün olan en yüksek yoğunluğunu sağlar ve bu varsayılan değerdir. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Yolun merkezinden dış sınırına doğru renk değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Yolun merkezinden dış sınırına doğru renk değiştiren bir degrade fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |
| scale | float | 0 ile 1 arasında bir değer, merkez renginin sınır rengiyle karıştığı maksimum yoğunluğu belirler. 1 değeri, merkez renginin mümkün olan en yüksek yoğunluğunu sağlar ve bu varsayılan değerdir. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarda taşır. Bu yöntem dönüşüme taşıma işlemini ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada taşır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Çevirinin uygulanacağı sıra (başına ekleme veya sona ekleme). |

