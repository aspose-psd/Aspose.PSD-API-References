---
title: "PathGradientBrush"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir Aspose.Imaging.Brush nesnesini bir degrade ile kapsüller."
type: docs
weight: 14
url: /tr/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Bir Aspose.Imaging.Brush nesnesini bir degrade ile kapsüller. Bu sınıf kalıtılamaz.

Merkez rengi varsayılan olarak beyazdır. Bir kullanıcı bu değeri daha sonra istediği zaman değiştirebilir.

Çevre renkleri dizisi varsayılan olarak beyaz renk içeren tek bir öğe ile başlatılır. Çevre renkleri daha sonra değiştirilebilir, ancak çevre renklerini ayarlarken en az bir öğe gereklidir.

Başlatması hakkında daha fazla ayrıntı için  Blend  bölümüne bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Belirtilen noktalarla  PathGradientBrush  sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Belirtilen noktalar ve sarma modu ile  PathGradientBrush  sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Belirtilen noktalarla  PathGradientBrush  sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Belirtilen noktalar ve sarma modu ile  PathGradientBrush  sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Belirtilen yol ile  PathGradientBrush  sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Mevcut Brush'ın yeni bir derin kopyasını oluşturur. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend alır. |
| [getCenterColor()](#getCenterColor--) | Yol gradyanının merkezindeki rengi alır. |
| [getCenterPoint()](#getCenterPoint--) | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFocusScales()](#getFocusScales--) | Gradyan düşüşü için odak noktasını alır. |
| [getGraphicsPath()](#getGraphicsPath--) | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| [getInterpolationColors()](#getInterpolationColors--) | Çok renkli bir lineer gradyanı tanımlayan bir com.aspose.psd.ColorBlend alır. |
| [getOpacity()](#getOpacity--) | Fırça opaklığını alır. |
| [getPathPoints()](#getPathPoints--) | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| [getSurroundColors()](#getSurroundColors--) | Bu  PathGradientBrush  tarafından doldurulan yol içindeki noktalara karşılık gelen renklerin bir dizisini alır. |
| [getTransform()](#getTransform--) | Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar. |
| [getWrapMode()](#getWrapMode--) | Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend ayarlar. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Bir merkez rengi ve tek bir çevre rengine doğru lineer bir düşüşe sahip bir gradyan oluşturur. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Bir merkez rengi ve her bir çevre rengine doğru lineer bir düşüşe sahip bir gradyan oluşturur. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Yol gradyanının merkezindeki rengi ayarlar. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Yol gradyanının merkez noktasını alır veya ayarlar. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Gradyan düşüşü için odak noktasını alır veya ayarlar. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Çok renkli doğrusal bir gradyan tanımlayan bir com.aspose.psd.ColorBlend ayarlar. |
| [setOpacity(float value)](#setOpacity-float-) | Fırça opaklığını ayarlar. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradient fırça oluşturur. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradient fırça oluşturur. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Bu  PathGradientBrush  doldurduğu yol üzerindeki noktalara karşılık gelen renklerin bir dizisini ayarlar. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla ve belirtilen sırada çevirir. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Belirtilen noktalarla  PathGradientBrush  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Yolun köşelerini oluşturan noktaları temsil eden Aspose.Imaging.PointF yapılarının bir dizisi. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Belirtilen noktalar ve sarma modu ile  PathGradientBrush  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Yolun köşelerini oluşturan noktaları temsil eden Aspose.Imaging.PointF yapılarının bir dizisi. |
| wrapMode | int | Bu  PathGradientBrush  ile çizilen doldurmaların nasıl döşeneceğini belirten bir Aspose.Imaging.WrapMode. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Belirtilen noktalarla  PathGradientBrush  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Yolun köşelerini oluşturan noktaları temsil eden Aspose.Imaging.Point yapılarının bir dizisi. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Belirtilen noktalar ve sarma modu ile  PathGradientBrush  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Yolun köşelerini oluşturan noktaları temsil eden Aspose.Imaging.Point yapılarının bir dizisi. |
| wrapMode | int | Bu  PathGradientBrush  ile çizilen doldurmaların nasıl döşeneceğini belirten bir Aspose.Imaging.WrapMode. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Belirtilen yol ile  PathGradientBrush  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Bu  PathGradientBrush  tarafından doldurulan alanı tanımlayan GraphicsPath. |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir Aspose.Imaging.Blend alır.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Yol gradyanının merkezindeki rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Yol gradyanının merkez noktasını alır veya ayarlar.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Gradyan düşüşü için odak noktasını alır.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Bu fırçanın üzerine inşa edildiği grafik yolunu alır.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Çok renkli bir lineer gradyanı tanımlayan bir com.aspose.psd.ColorBlend alır.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Fırça opaklığını alır. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**Returns:**
float - Fırça opaklık değeri.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Bu fırçanın üzerine inşa edildiği yol noktalarını alır.

**Returns:**
com.aspose.psd.PointF[] - Yol noktaları.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Bu  PathGradientBrush  tarafından doldurulan yol içindeki noktalara karşılık gelen renklerin bir dizisini alır.

**Returns:**
com.aspose.psd.Color[] - Bu PathGradientBrush'ın doldurduğu yol üzerindeki her noktaya ilişkin renkleri temsil eden com.aspose.psd.Color yapıların bir dizisi.
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


Bir merkez rengi ve tek bir çevre rengine doğru lineer bir düşüşe sahip bir gradyan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | Yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirten 0 ile 1 arasında bir değer. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Bir merkez rengi ve her bir çevre rengine doğru lineer bir düşüşe sahip bir gradyan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | Yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirten 0 ile 1 arasında bir değer. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |
| ölçek | float | Sınır rengiyle karışan merkez renginin maksimum yoğunluğunu belirten 0 ile 1 arasında bir değer. 1 değeri merkez renginin mümkün olan en yüksek yoğunluğunu sağlar ve bu varsayılan değerdir. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Yol gradyanının merkezindeki rengi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Yol gradientinin merkezindeki rengi temsil eden bir com.aspose.psd.Color. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Yol gradyanının merkez noktasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Yol gradyanının merkez noktasını temsil eden bir Aspose.Imaging.PointF. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Gradyan düşüşü için odak noktasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Gradyan düşüşü için odak noktasını temsil eden bir Aspose.Imaging.PointF. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Çok renkli doğrusal bir gradyan tanımlayan bir com.aspose.psd.ColorBlend ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Çok renkli doğrusal bir gradyan tanımlayan bir com.aspose.psd.ColorBlend. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Fırça opaklığını ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Fırça opaklık değeri. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradient fırça oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | Yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirten 0 ile 1 arasında bir değer. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradient fırça oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | Yolun merkezinden yolun sınırına kadar herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirten 0 ile 1 arasında bir değer. 1 değeri (varsayılan) en yüksek yoğunluğu yolun merkezine yerleştirir. |
| ölçek | float | Sınır rengiyle karışan merkez renginin maksimum yoğunluğunu belirten 0 ile 1 arasında bir değer. 1 değeri merkez renginin mümkün olan en yüksek yoğunluğunu sağlar ve bu varsayılan değerdir. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Bu  PathGradientBrush  doldurduğu yol üzerindeki noktalara karşılık gelen renklerin bir dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Bu PathGradientBrush'ın doldurduğu yol üzerindeki her noktaya ilişkin renkleri temsil eden com.aspose.psd.Color yapıların bir dizisi. |

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

