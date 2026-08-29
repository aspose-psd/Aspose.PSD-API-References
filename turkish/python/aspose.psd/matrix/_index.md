---
title: "Matrix Sınıfı"
type: docs
weight: 3000
url: /tr/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Matrix()](#Matrix__1) | Matrix sınıfının yeni bir örneğini birim matris olarak başlatır. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Yeni bir [Matrix](/psd/python-net/aspose.psd/matrix/) sınıf örneği başlatır. |
| [Matrix(origin)](#Matrix_origin_3) | [Matrix](/psd/python-net/aspose.psd/matrix/) sınıfının bir kopyasını oluşturur. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Yeni bir [Matrix](/psd/python-net/aspose.psd/matrix/) sınıf örneğini belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme başlatır. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Yeni bir [Matrix](/psd/python-net/aspose.psd/matrix/) sınıf örneğini belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a mirror image flip about some axis which changes the<br/>            normally right handed coordinate system into a left handed<br/>            system in addition to the conversions indicated by other flag bits.<br/>            A right handed coordinate system is one where the positive X<br/>            axis rotates counterclockwise to overlay the positive Y axis<br/>            similar to the direction that the fingers on your right hand<br/>            curl when you stare end on at your thumb.<br/>            A left handed coordinate system is one where the positive X<br/>            axis rotates clockwise to overlay the positive Y axis similar<br/>            to the direction that the fingers on your left hand curl.<br/>            There is no mathematical way to determine the angle of the<br/>            original flipping or mirroring transformation since all angles<br/>            of flip are identical given an appropriate adjusting rotation.<br/>            NOTE: TypeFlip was added after GENERAL_TRANSFORM was in public<br/>            circulation and the flag bits could no longer be conveniently<br/>            renumbered without introducing binary incompatibility in outside<br/>            code. |
| TYPE_GENERAL_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a rotation by an arbitrary angle in addition to the<br/>            conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the |
| TYPE_GENERAL_SCALE [static] | int | r | A general scale multiplies the length of vectors by different<br/>            amounts in the x and y directions without changing the angle<br/>            between perpendicular vectors.<br/>            This flag bit is mutually exclusive with the TypeUniformScale flag. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | This constant indicates that the transform defined by this object<br/>            performs an arbitrary conversion of the input coordinates.<br/>            If this transform can be classified by any of the above constants,<br/>            the type will either be the constant TypeIdentity or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_IDENTITY [static] | int | r | An identity transform is one in which the output coordinates are<br/>            always the same as the input coordinates.<br/>            If this transform is anything other than the identity transform,<br/>            the type will either be the constant GENERAL_TRANSFORM or a<br/>            combination of the appropriate flag bits for the various coordinate<br/>            conversions that this transform performs. |
| TYPE_MASK_ROTATION [static] | int | r | This constant is a bit mask for any of the rotation flag bits. |
| TYPE_MASK_SCALE [static] | int | r | This constant is a bit mask for any of the scale flag bits. |
| TYPE_QUADRANT_ROTATION [static] | int | r | This flag bit indicates that the transform defined by this object<br/>            performs a quadrant rotation by some multiple of 90 degrees in<br/>            addition to the conversions indicated by other flag bits.<br/>            A rotation changes the angles of vectors by the same amount<br/>            regardless of the original direction of the vector and without<br/>            changing the length of the vector.<br/>            This flag bit is mutually exclusive with the TypeGeneralRotation flag. |
| TYPE_TRANSLATION [static] | int | r | A translation moves the coordinates by a constant amount in x<br/>            and y without changing the length or angle of vectors. |
| TYPE_UNIFORM_SCALE [static] | int | r | Bir eşit ölçek, vektörlerin uzunluğunu aynı miktarda çarpar<br/>            hem x hem de y yönlerinde açıları değiştirmeden<br/>            vektörler arasındaki.<br/>            Bu bayrak biti, TypeGeneralScale bayrağıyla karşılıklı olarak birbirini dışlar. |
| elements | float | r | Bu [Matrix](/psd/python-net/aspose.psd/matrix/) öğesinin elemanlarını temsil eden kayan nokta değerlerinden oluşan bir dizi alır. |
| m11 | float | r | İlk satırın ilk sütunundaki matris elemanını alır. X ekseni boyunca ölçeği temsil eder. |
| m12 | float | r | İlk satırın ikinci sütunundaki matris elemanını alır. Y ekseni boyunca kaymayı temsil eder. |
| m21 | float | r | İkinci satırın ilk sütunundaki matris elemanını alır. X ekseni boyunca kaymayı temsil eder. |
| m22 | float | r | İkinci satırın ikinci sütunundaki matris elemanını alır. Y ekseni boyunca ölçeği temsil eder. |
| m31 | float | r | Üçüncü satırın ilk sütunundaki matris elemanını alır. X ekseni boyunca çeviriyi temsil eder. |
| m32 | float | r | Üçüncü satırın ilk sütunundaki matris elemanını alır. Y ekseni boyunca çeviriyi temsil eder. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_elements()](#get_elements__1) | Matris elemanlarının bir kopyasını alır. |
| [multiply(tx)](#multiply_tx_2) | Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar. |
| [multiply(tx, order)](#multiply_tx_order_3) | Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar. |
| reset() | Bu Matrix'i, birim matrisin elemanlarına sahip olacak şekilde sıfırlar. |
| [rotate(angle)](#rotate_angle_4) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşü, orijinde (sıfır x ve y koordinatları) varsayılan (Prepend) sırada uygular. |
| [rotate(angle, order)](#rotate_angle_order_5) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşü, orijinde (sıfır x ve y koordinatları) belirtilen sırada uygular. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Belirtilen nokta etrafında saat yönünde bir dönüşü, bu Matrix'e varsayılan (Prepend) sırada uygular. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Belirtilen nokta etrafında saat yönünde bir dönüşü, bu Matrix'e belirtilen sırada uygular. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu [Matrix](/psd/python-net/aspose.psd/matrix/) üzerine belirtilen sırayı kullanarak uygular. |
| [scale(sx, sy)](#scale_sx_sy_9) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular. |
| [transform_points(points)](#transform_points_points_10) | Bu [Matrix](/psd/python-net/aspose.psd/matrix/) tarafından temsil edilen geometrik dönüşümü, belirtilen bir nokta dizisine uygular. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Belirtilen çeviri vektörünü bu Matris'e belirtilen sırada uygular. |
| [translate(tx, ty)](#translate_tx_ty_12) | Belirtilen çeviri vektörünü bu [Matris](/psd/python-net/aspose.psd/matrix/) (varsayılan) Ön ekleme sırasını kullanarak uygular. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Matrix sınıfının yeni bir örneğini birim matris olarak başlatır.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Yeni bir [Matrix](/psd/python-net/aspose.psd/matrix/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| m11 | float | m00     M11     Ölçek X |
| m12 | float | m10     M12     Kaydırma Y |
| m21 | float | m01     M21     Kaydırma X |
| m22 | float | m11     M22     Ölçek Y |
| m31 | float | m02     M31     Çevirme X |
| m32 | float | m12     M32     Çevirme Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) sınıfının bir kopyasını oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Kopyalama için temel matris |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Yeni bir [Matrix](/psd/python-net/aspose.psd/matrix/) sınıf örneğini belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Üst‑sol, üst‑sağ ve alt‑sol köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bir dizisi. Paralelkenarın alt‑sağ köşesi ilk üç köşe tarafından ima edilir. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Yeni bir [Matrix](/psd/python-net/aspose.psd/matrix/) sınıf örneğini belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Üst‑sol, üst‑sağ ve alt‑sol köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](/psd/python-net/aspose.psd/pointf/) yapısının bir dizisi. Paralelkenarın alt‑sağ köşesi ilk üç köşe tarafından ima edilir. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Matris elemanlarının bir kopyasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Bir matris öğesi kopyası. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Çarpma yapılacak matris. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Tx. Tx. Tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sıra. Sıra. Sıra. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşü, orijinde (sıfır x ve y koordinatları) varsayılan (Prepend) sırada uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Döndürme açısı. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşü, orijinde (sıfır x ve y koordinatları) belirtilen sırada uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Döndürme açısı. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Matris sırası. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Belirtilen nokta etrafında saat yönünde bir dönüşü, bu Matrix'e varsayılan (Prepend) sırada uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Açı. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Nokta. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Belirtilen nokta etrafında saat yönünde bir dönüşü, bu Matrix'e belirtilen sırada uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Açı. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Nokta. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sıra. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Belirtilen ölçek vektörünü (scaleX ve scaleY) bu [Matrix](/psd/python-net/aspose.psd/matrix/) üzerine belirtilen sırayı kullanarak uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scale_x | float | Ölçek X. |
| scale_y | float | Ölçek Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sıra. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Bu [Matrix](/psd/python-net/aspose.psd/matrix/) tarafından temsil edilen geometrik dönüşümü, belirtilen bir nokta dizisine uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Noktalar. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Belirtilen çeviri vektörünü bu Matris'e belirtilen sırada uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| offset_x | float | X ofseti. |
| offset_y | float | Y ofseti. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sıra. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Belirtilen çeviri vektörünü bu [Matris](/psd/python-net/aspose.psd/matrix/) (varsayılan) Ön ekleme sırasını kullanarak uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tx | float | Tx. Tx. Tx. |
| ty | float | ty. ty. ty. |

