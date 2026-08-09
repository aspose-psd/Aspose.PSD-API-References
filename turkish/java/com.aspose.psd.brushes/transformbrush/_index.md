---
title: "TransformBrush"
second_title: "Java için Aspose.PSD API Referansı"
description: "Dönüştürme yeteneklerine sahip bir fırça."
type: docs
weight: 19
url: /tr/java/com.aspose.psd.brushes/transformbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public abstract class TransformBrush extends Brush
```

Dönüştürme yeteneklerine sahip bir  Brush .
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Mevcut Brush'ın yeni bir derin kopyasını oluşturur. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getOpacity()](#getOpacity--) | Fırça opaklığını alır. |
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
| [setOpacity(float value)](#setOpacity-float-) | Fırça opaklığını ayarlar. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Bu TransformBrush için yerel geometrik dönüşümü tanımlayan bir kopya Aspose.Imaging.Matrix'i alır veya ayarlar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Bu TransformBrush için sarma modunu gösteren bir Aspose.Imaging.WrapMode enum değerini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla ve belirtilen sırada çevirir. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


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
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Fırça opaklığını alır. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**Returns:**
float - Fırça opaklık değeri.
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

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Fırça opaklığını ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Fırça opaklık değeri. |

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

