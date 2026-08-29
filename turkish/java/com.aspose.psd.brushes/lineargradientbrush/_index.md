---
title: "LinearGradientBrush"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir Aspose.Imaging.Brush'ı lineer gradyan ile kapsüller."
type: docs
weight: 11
url: /tr/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Bir Aspose.Imaging.Brush'ı lineer gradyan ile kapsüller. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | LinearGradientBrush sınıfının yeni bir örneğini varsayılan parametrelerle başlatır. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | LinearGradientBrush sınıfının yeni bir örneğini belirtilen noktalar ve renklerle başlatır. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | LinearGradientBrush sınıfının yeni bir örneğini belirtilen noktalar ve renklerle başlatır. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Mevcut Brush'ın yeni bir derin kopyasını oluşturur. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Gradyan açısını alır. |
| [getBlend()](#getBlend--) | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend alır. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getEndColor()](#getEndColor--) | Bitiş gradyan rengini alır. |
| [getGammaCorrection()](#getGammaCorrection--) | Bu LinearGradientBrushBase için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır. |
| [getInterpolationColors()](#getInterpolationColors--) | Çok renkli bir lineer gradyanı tanımlayan bir com.aspose.psd.ColorBlend alır. |
| [getLinearColors()](#getLinearColors--) | Gradyanın başlangıç ve bitiş renklerini alır. |
| [getOpacity()](#getOpacity--) | Fırça opaklığını alır. |
| [getRectangle()](#getRectangle--) | Gradyanın başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölgeyi alır. |
| [getStartColor()](#getStartColor--) | Başlangıç gradyan rengini alır. |
| [getTransform()](#getTransform--) | Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar. |
| [getWrapMode()](#getWrapMode--) | Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Bu LinearGradientBrushBase ile yapılan dönüşümler sırasında LinearGradientBrushBase.Angle'ın değişip değişmediğini gösteren bir değeri alır. |
| [isTransformChanged()](#isTransformChanged--) | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Bu LinearGradientBrush'ın yerel geometrik dönüşümünü temsil eden Aspose.Imaging.Matrix'i, belirtilen Aspose.Imaging.Matrix'i ön ekleyerek çarpar. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Bu LinearGradientBrush'ın yerel geometrik dönüşümünü temsil eden Aspose.Imaging.Matrix'i, belirtilen sırada belirtilen Aspose.Imaging.Matrix ile çarpar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | TransformBrush.Transform özelliğini birim (identity) haline getirir. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Yerel geometrik dönüşümü belirtilen miktarda ve belirtilen sırada döndürür. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Yerel geometrik dönüşümü belirtilen ölçeklerle ölçeklendirir. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen ölçeklerle ve belirtilen sırada ölçeklendirir. |
| [setAngle(float value)](#setAngle-float-) | Gradyan açısını ayarlar. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Bu LinearGradientBrushBase ile yapılan dönüşümler sırasında LinearGradientBrushBase.Angle'ın değişip değişmediğini gösteren bir değeri ayarlar. |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend ayarlar. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Her iki uçta tek bir renge doğru lineer bir düşüş ve merkez rengi olan bir lineer gradyan oluşturur. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Her iki uçta tek bir renge doğru lineer bir düşüş ve merkez rengi olan bir lineer gradyan oluşturur. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Bitiş gradyan rengini ayarlar. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Bu LinearGradientBrushBase için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri ayarlar. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Çok renkli doğrusal bir gradyan tanımlayan bir com.aspose.psd.ColorBlend ayarlar. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Gradyanın başlangıç ve bitiş renklerini ayarlar. |
| [setOpacity(float value)](#setOpacity-float-) | Fırça opaklığını ayarlar. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Gradyanın başlangıç ve bitiş noktalarını tanımlayan bir dikdörtgen bölge ayarlar. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Başlangıç gradyan rengini ayarlar. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla ve belirtilen sırada çevirir. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


LinearGradientBrush sınıfının yeni bir örneğini varsayılan parametrelerle başlatır. Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutundadır.

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


LinearGradientBrush sınıfının yeni bir örneğini belirtilen noktalar ve renklerle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Doğrusal gradyanın başlangıç noktasını temsil eden bir Aspose.Imaging.Point yapısı. |
| point2 | [Point](../../com.aspose.psd/point) | Doğrusal gradyanın bitiş noktasını temsil eden bir Aspose.Imaging.Point yapısı. |
| color1 | [Color](../../com.aspose.psd/color) | Lineer gradyanın başlangıç rengini temsil eden bir com.aspose.psd.Color yapısı. |
| color2 | [Color](../../com.aspose.psd/color) | Lineer gradyanın bitiş rengini temsil eden bir com.aspose.psd.Color yapısı. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


LinearGradientBrush sınıfının yeni bir örneğini belirtilen noktalar ve renklerle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Doğrusal gradyanın başlangıç noktasını temsil eden bir Aspose.Imaging.PointF yapısı. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Doğrusal degrade'nin son noktasını temsil eden bir Aspose.Imaging.PointF yapısı. |
| color1 | [Color](../../com.aspose.psd/color) | Lineer gradyanın başlangıç rengini temsil eden bir com.aspose.psd.Color yapısı. |
| color2 | [Color](../../com.aspose.psd/color) | Lineer gradyanın bitiş rengini temsil eden bir com.aspose.psd.Color yapısı. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Doğrusal degrade'nin sınırlarını belirten bir Aspose.Imaging.RectangleF yapısı. |
| color1 | [Color](../../com.aspose.psd/color) | Gradyan için başlangıç rengini temsil eden bir com.aspose.psd.Color yapısı. |
| color2 | [Color](../../com.aspose.psd/color) | Gradyan için bitiş rengini temsil eden bir com.aspose.psd.Color yapısı. |
| açı | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Doğrusal degrade'nin sınırlarını belirten bir Aspose.Imaging.RectangleF yapısı. |
| color1 | [Color](../../com.aspose.psd/color) | Gradyan için başlangıç rengini temsil eden bir com.aspose.psd.Color yapısı. |
| color2 | [Color](../../com.aspose.psd/color) | Gradyan için bitiş rengini temsil eden bir com.aspose.psd.Color yapısı. |
| açı | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Doğrusal degrade'nin sınırlarını belirten bir Aspose.Imaging.RectangleF yapısı. |
| color1 | [Color](../../com.aspose.psd/color) | Gradyan için başlangıç rengini temsil eden bir com.aspose.psd.Color yapısı. |
| color2 | [Color](../../com.aspose.psd/color) | Gradyan için bitiş rengini temsil eden bir com.aspose.psd.Color yapısı. |
| açı | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| isAngleScalable | boolean | true olarak ayarlanırsa, bu LinearGradientBrush ile dönüşümler sırasında açı değişir. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


LinearGradientBrush sınıfının yeni bir örneğini bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısı temel alarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Doğrusal degrade'nin sınırlarını belirten bir Aspose.Imaging.RectangleF yapısı. |
| color1 | [Color](../../com.aspose.psd/color) | Gradyan için başlangıç rengini temsil eden bir com.aspose.psd.Color yapısı. |
| color2 | [Color](../../com.aspose.psd/color) | Gradyan için bitiş rengini temsil eden bir com.aspose.psd.Color yapısı. |
| açı | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| isAngleScalable | boolean | true olarak ayarlanırsa, bu LinearGradientBrush ile dönüşümler sırasında açı değişir. |

### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Mevcut Brush'ın yeni bir derin kopyasını oluşturur.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


Gradyan açısını alır.

**Returns:**
float - Degrade açısı.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend alır.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Bitiş gradyan rengini alır.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Bu LinearGradientBrushBase için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Değer, bu LinearGradientBrushBase için gama düzeltmesi etkinleştirilmişse true, aksi takdirde false olur.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Çok renkli bir lineer gradyanı tanımlayan bir com.aspose.psd.ColorBlend alır.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Gradyanın başlangıç ve bitiş renklerini alır.

**Returns:**
com.aspose.psd.Color[] - Gradyanın başlangıç ve bitiş renklerini temsil eden iki  Color  yapısının bir dizisi.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Fırça opaklığını alır. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**Returns:**
float - Fırça opaklık değeri.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Gradyanın başlangıç ve bitiş noktalarını tanımlayan dikdörtgen bir bölgeyi alır.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Başlangıç gradyan rengini alır.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar.

**Returns:**
int - Bu TransformBrush ile çizilen doldurmaların nasıl döşeneceğini belirten bir Aspose.Imaging.WrapMode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Bu LinearGradientBrushBase ile yapılan dönüşümler sırasında LinearGradientBrushBase.Angle'ın değişip değişmediğini gösteren bir değeri alır.

**Returns:**
boolean - Bu LinearGradientBrushBase ile yapılan dönüşümler sırasında LinearGradientBrushBase.Angle değiştirildiyse true, aksi takdirde false.
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Dönüşümlerin bir şekilde değiştirildiğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir.

Değer: Dönüşüm değiştirildiyse True, aksi takdirde false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Bu LinearGradientBrush'ın yerel geometrik dönüşümünü temsil eden Aspose.Imaging.Matrix'i, belirtilen Aspose.Imaging.Matrix'i ön ekleyerek çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılacak Aspose.Imaging.Matrix. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Bu LinearGradientBrush'ın yerel geometrik dönüşümünü temsil eden Aspose.Imaging.Matrix'i, belirtilen sırada belirtilen Aspose.Imaging.Matrix ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılacak Aspose.Imaging.Matrix. |
| order | int | İki matrisi hangi sırayla çarpacağını belirten bir Aspose.Imaging.MatrixOrder. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


TransformBrush.Transform özelliğini birim (identity) haline getirir.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönüşüm açısı. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Yerel geometrik dönüşümü belirtilen miktarda ve belirtilen sırada döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönüşüm açısı. |
| order | int | Rotasyon matrisini ekleyecek mi yoksa ön ekleyecek mi belirten bir Aspose.Imaging.MatrixOrder. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Yerel geometrik dönüşümü belirtilen miktarlarda ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Yerel geometrik dönüşümü belirtilen ölçeklerle ve belirtilen sırada ölçeklendirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |
| order | int | Ölçekleme matrisini ekleyecek mi yoksa ön ekleyecek mi belirten bir Aspose.Imaging.MatrixOrder. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Gradyan açısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Gradyan açısı. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Bu LinearGradientBrushBase ile yapılan dönüşümler sırasında LinearGradientBrushBase.Angle'ın değişip değişmediğini gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Bu LinearGradientBrushBase ile dönüşümler sırasında LinearGradientBrushBase.Angle değiştirildiyse true; aksi takdirde false. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Gradyan için özel bir düşüşü temsil eden bir  Aspose.Imaging.Blend . |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Her iki uçta tek bir renge doğru lineer bir düşüş ve merkez rengi olan bir lineer gradyan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, gradyanın merkezini (gradyanın yalnızca bitiş rengiyle oluştuğu nokta) belirler. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Her iki uçta tek bir renge doğru lineer bir düşüş ve merkez rengi olan bir lineer gradyan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, gradyanın merkezini (gradyanın yalnızca bitiş rengiyle oluştuğu nokta) belirler. |
| ölçek | float | 0 ile 1 arasında bir değer, renklerin başlangıç renginden  odak  (bitiş rengi) noktasına ne kadar hızlı düştüğünü belirler. |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Bitiş gradyan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Bitiş gradyan rengi. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Bu LinearGradientBrushBase için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Bu LinearGradientBrushBase için gama düzeltmesi etkinleştirildiyse değer true; aksi takdirde false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Çok renkli doğrusal bir gradyan tanımlayan bir com.aspose.psd.ColorBlend ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Çok renkli doğrusal bir gradyan tanımlayan bir com.aspose.psd.ColorBlend. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Gradyanın başlangıç ve bitiş renklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Gradyanın başlangıç ve bitiş renklerini temsil eden iki  Color  yapısının bir dizisi. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Fırça opaklığını ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Fırça opaklık değeri. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Gradyanın başlangıç ve bitiş noktalarını tanımlayan bir dikdörtgen bölge ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Gradyanın başlangıç ve bitiş noktalarını belirten bir com.aspose.psd.RectangleF yapısı. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, gradyanın merkezini (başlangıç rengi ile bitiş renginin eşit şekilde karıştığı nokta) belirler. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, gradyanın merkezini (gradyanın yalnızca bitiş rengiyle oluştuğu nokta) belirler. |
| ölçek | float | 0 ile 1 arasında bir değer, renklerin  odak  noktasından ne kadar hızlı düştüğünü belirler. |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Başlangıç gradyan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Başlangıç gradyan rengi. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ek olarak ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Yerel geometrik dönüşümü belirtilen boyutlarla ve belirtilen sırada çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| order | int | Çevirinin uygulanacağı sıra (ön ekleme veya ekleme). |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

