---
title: "TextureBrush Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Belirtilen görüntüyü kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Belirtilen görüntü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Belirtilen görüntü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Belirtilen görüntü, sınırlayıcı dikdörtgen ve görüntü özniteliklerini kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Belirtilen görüntü, sınırlayıcı dikdörtgen ve görüntü özniteliklerini kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Belirtilen görüntü ve sarma modunu kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Belirtilen görüntü, sarma modu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Belirtilen görüntü, sarma modu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesiyle ilişkili [Image](/psd/python-net/aspose.psd/image/) nesnesini alır. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ile ilişkili [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) öğesini alır. |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ile ilişkili [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini alır. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini belirten bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Bu özellik GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir. |
| opaklık | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri fırçanın tamamen opak olduğu anlamına gelir. |
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
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Yerel geometrik dönüşümü belirtilen boyutlarda taşır. Bu yöntem dönüşüme taşıma işlemini ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada taşır. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Belirtilen görüntüyü kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Belirtilen görüntü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Belirtilen görüntü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Belirtilen görüntü, sınırlayıcı dikdörtgen ve görüntü özniteliklerini kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bu [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) nesnesi, bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi tarafından kullanılan görüntü hakkında ek bilgi içerir. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Belirtilen görüntü, sınırlayıcı dikdörtgen ve görüntü özniteliklerini kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bu [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) nesnesi, bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi tarafından kullanılan görüntü hakkında ek bilgi içerir. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Belirtilen görüntü ve sarma modunu kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Bu [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enum, bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin nasıl döşeneceğini belirtir. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Belirtilen görüntü, sarma modu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Bu [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enum, bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin nasıl döşeneceğini belirtir. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Belirtilen görüntü, sarma modu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin iç kısımları doldurmak için kullandığı [Image](/psd/python-net/aspose.psd/image/) nesnesi. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Bu [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enum, bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesinin nasıl döşeneceğini belirtir. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Bu [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarda taşır. Bu yöntem dönüşüme taşıma işlemini ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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

