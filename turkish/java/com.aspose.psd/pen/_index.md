---
title: "Pen"
second_title: "Java için Aspose.PSD API Referansı"
description: "Çizgileri, eğrileri ve şekilleri çizmeye kullanılan bir nesneyi tanımlar."
type: docs
weight: 77
url: /tr/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Çizgileri, eğrileri ve şekilleri çizmek için kullanılan bir nesneyi tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Belirtilen renk ile  Pen  sınıfının yeni bir örneğini başlatır. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Belirtilen  Color  ve  Pen.Width  özellikleriyle  Pen  sınıfının yeni bir örneğini başlatır. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Belirtilen  Brush  ile  Pen  sınıfının yeni bir örneğini başlatır . |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Belirtilen  Brush  ve  Pen.Width  ile  Pen  sınıfının yeni bir örneğini başlatır . |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Bu  Pen  için hizalamayı alır . |
| [getBrush()](#getBrush--) | Bu  Pen  nesnesinin özelliklerini belirleyen  Brush  öğesini alır . |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Bu  Pen  nesnesinin rengini alır . |
| [getCompoundArray()](#getCompoundArray--) | Bileşik bir kalemi belirten değerlerin bir dizisini alır . |
| [getCustomEndCap()](#getCustomEndCap--) | Bu  Pen  ile çizilen çizgilerin sonunda kullanılacak özel bir kapak alır . |
| [getCustomStartCap()](#getCustomStartCap--) | Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak alır . |
| [getDashCap()](#getDashCap--) | Bu  Pen  ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini alır . |
| [getDashOffset()](#getDashOffset--) | Bir çizginin başlangıcından tire deseninin başlangıcına olan mesafeyi alır . |
| [getDashPattern()](#getDashPattern--) | Özel tireler ve boşluklardan oluşan bir dizi alır . |
| [getDashStyle()](#getDashStyle--) | Bu  Pen  ile çizilen kesikli çizgiler için kullanılan stili alır . |
| [getEndCap()](#getEndCap--) | Bu  Pen  ile çizilen çizgilerin sonunda kullanılan kapak stilini alır . |
| [getLineJoin()](#getLineJoin--) | Bu  Pen  ile çizilen iki ardışık çizginin uçları için birleştirme stilini alır . |
| [getMiterLimit()](#getMiterLimit--) | Köşe birleşiminde eklemenin kalınlık sınırını alır . |
| [getOpacity()](#getOpacity--) | Nesnenin opaklığını alır. |
| [getPenType()](#getPenType--) | Bu  Pen  ile çizilen çizgilerin stilini alır . |
| [getStartCap()](#getStartCap--) | Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılan kapak stilini alır . |
| [getTransform()](#getTransform--) | Bu  Pen  için geometrik dönüşümün bir kopyasını alır . |
| [getWidth()](#getWidth--) | Çizim için kullanılan Graphics nesnesinin birimlerinde bu  Pen  genişliğini alır . |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Bu  Pen  için dönüşüm matrisini belirtilen  Matrix  ile çarpar . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Bu  Pen  için dönüşüm matrisini belirtilen  Matrix  ile belirtilen sırada çarpar . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Bu  Pen  için geometrik dönüşüm matrisini birim (identity) haline getirir . |
| [rotateTransform(float angle)](#rotateTransform-float-) | Yerel geometrik dönüşümü belirtilen açıyla döndürür . |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür . |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir . |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen faktörlerle, belirtilen sırada ölçeklendirir. |
| [setAlignment(int value)](#setAlignment-int-) | Bu  Pen  için hizalamayı ayarlar. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Bu  Pen  özelliklerini belirleyen  Brush  öğesini ayarlar. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Bu  Pen  rengini ayarlar. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Bir bileşik kalemi belirten değerler dizisini ayarlar. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Bu  Pen  ile çizilen çizgilerin sonunda kullanılacak özel bir kapak ayarlar. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak ayarlar. |
| [setDashCap(int value)](#setDashCap-int-) | Bu  Pen  ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini ayarlar. |
| [setDashOffset(float value)](#setDashOffset-float-) | Bir çizginin başlangıcından tire deseninin başına olan mesafeyi ayarlar. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Özel tireler ve boşluklardan oluşan bir dizi ayarlar. |
| [setDashStyle(int value)](#setDashStyle-int-) | Bu  Pen  ile çizilen kesikli çizgiler için kullanılan stili ayarlar. |
| [setEndCap(int value)](#setEndCap-int-) | Bu  Pen  ile çizilen çizgilerin sonunda kullanılan kapak stilini ayarlar. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Bu  Pen  tarafından çizilen çizgileri sonlandırmak için kullanılan kapak stilini belirleyen değerleri ayarlar. |
| [setLineJoin(int value)](#setLineJoin-int-) | Bu  Pen  ile çizilen iki ardışık çizginin uçları için birleştirme stilini ayarlar. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Köşe birleşiminde eklem kalınlığının sınırını ayarlar. |
| [setOpacity(float value)](#setOpacity-float-) | Nesnenin opaklığını ayarlar. |
| [setStartCap(int value)](#setStartCap-int-) | Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılan kapak stilini ayarlar. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Bu  Pen  için geometrik dönüşümün bir kopyasını ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Çizim için kullanılan Graphics nesnesinin birimlerinde, bu  Pen  genişliğini ayarlar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Belirtilen renk ile  Pen  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Bu  Pen  rengini gösteren bir  Color  yapısı. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Belirtilen  Color  ve  Pen.Width  özellikleriyle  Pen  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Bu  Pen  rengini gösteren bir  Color  yapısı. |
| width | float | Bu  Pen  genişliğini belirten bir değer. |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Belirtilen  Brush  ile  Pen  sınıfının yeni bir örneğini başlatır .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Bu  Pen  doldurma özelliklerini belirleyen bir  Brush . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Belirtilen  Brush  ve  Pen.Width  ile  Pen  sınıfının yeni bir örneğini başlatır .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Bu  Pen  özelliklerini belirleyen bir  Brush . |
| width | float | Yeni  Pen  genişliği. |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Bu  Pen  için hizalamayı alır .

**Returns:**
int - Bir  PenAlignment  bu  Pen  için hizalamayı temsil eder.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Bu  Pen  nesnesinin özelliklerini belirleyen  Brush  öğesini alır .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Bu  Pen  nesnesinin rengini alır .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Bir bileşik kalemi belirten değerler dizisini alır. Bir bileşik kalem, paralel çizgiler ve boşluklardan oluşan bir bileşik çizgi çizer.

**Returns:**
float[] - Bileşik diziyi belirten gerçek sayılar dizisi. Dizideki elemanlar artan sırada olmalı, 0'dan küçük olmamalı ve 1'den büyük olmamalıdır.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Bu  Pen  ile çizilen çizgilerin sonunda kullanılacak özel bir kapak alır .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak alır .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Bu  Pen  ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini alır .

**Returns:**
int - Bu  Pen  ile çizilen kesikli çizgileri oluşturan tirelerin başlangıç ve bitişinde kullanılan kap stilini temsil eden  DashCap  değerlerinden biri.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Bir çizginin başlangıcından tire deseninin başlangıcına olan mesafeyi alır .

**Returns:**
float - Bir çizginin başlangıcından tire deseninin başlangıcına olan mesafe.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Özel tireler ve boşluklardan oluşan bir dizi alır .

**Returns:**
float[] - Kesikli çizgilerde alternatif tire ve boşluk uzunluklarını belirten gerçek sayılar dizisi.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Bu  Pen  ile çizilen kesikli çizgiler için kullanılan stili alır .

**Returns:**
int - Bu  Pen  ile çizilen kesikli çizgilerde kullanılan stili temsil eden bir  DashStyle  .
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Bu  Pen  ile çizilen çizgilerin sonunda kullanılan kapak stilini alır .

**Returns:**
int - Bu  Pen  ile çizilen çizgilerin sonunda kullanılan kap stilini temsil eden  LineCap  değerlerinden biri.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Bu  Pen  ile çizilen iki ardışık çizginin uçları için birleştirme stilini alır .

**Returns:**
int - Bu  Pen  ile çizilen iki ardışık çizginin uçlarındaki birleşim stilini temsil eden bir  LineJoin  .
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Köşe birleşiminde eklemenin kalınlık sınırını alır .

**Returns:**
float - Keskin köşedeki birleşimin kalınlık sınırı.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Nesnenin opaklığını alır. Değer 0 ile 1 arasında olmalıdır. 0 değeri nesnenin tamamen görünür olduğu, 1 değeri nesnenin tamamen opak olduğu anlamına gelir.

**Returns:**
float - Opaklık değeri.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Bu  Pen  ile çizilen çizgilerin stilini alır .

**Returns:**
int - Bu  Pen  ile çizilen çizgilerin stilini belirten bir  PenType  enum'ı.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılan kapak stilini alır .

**Returns:**
int - Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılan kap stilini temsil eden  LineCap  değerlerinden biri.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Bu  Pen  için geometrik dönüşümün bir kopyasını alır .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Çizim için kullanılan Graphics nesnesinin birimlerinde bu  Pen  genişliğini alır .

**Returns:**
float - Bu  Pen  genişliği.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Bu  Pen  için dönüşüm matrisini belirtilen  Matrix  ile çarpar .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Dönüşüm matrisini çarpmak için kullanılan  Matrix  nesnesi. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Bu  Pen  için dönüşüm matrisini belirtilen  Matrix  ile belirtilen sırada çarpar .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Dönüşüm matrisini çarpmak için kullanılan  Matrix  . |
| order | int | Çarpma işleminin gerçekleştirileceği sıra. |

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


Bu  Pen  için geometrik dönüşüm matrisini birim (identity) haline getirir .

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönüşüm açısı. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönüşüm açısı. |
| order | int | Rotasyon matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir  MatrixOrder  . |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümü x ekseni yönünde ölçeklendirecek faktör. |
| sy | float | Dönüşümü y ekseni yönünde ölçeklendirecek faktör. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Yerel geometrik dönüşümü belirtilen faktörlerle, belirtilen sırada ölçeklendirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümü x ekseni yönünde ölçeklendirecek faktör. |
| sy | float | Dönüşümü y ekseni yönünde ölçeklendirecek faktör. |
| order | int | Ölçekleme matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir  MatrixOrder  . |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Bu  Pen  için hizalamayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  Pen  için hizalamayı temsil eden bir  PenAlignment  . |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Bu  Pen  özelliklerini belirleyen  Brush  öğesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Bu  Pen  özelliklerini belirleyen bir  Brush  . |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Bu  Pen  rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Bu  Pen  rengini temsil eden bir  Color  yapısı. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Bir bileşik kalemi belirten değerler dizisini ayarlar. Bir bileşik kalem, paralel çizgiler ve boşluklardan oluşan bir bileşik çizgi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | Bileşik diziyi belirten gerçek sayılardan oluşan bir dizi. Dizideki öğeler artan sırada olmalı, 0'dan küçük olmamalı ve 1'den büyük olmamalıdır. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Bu  Pen  ile çizilen çizgilerin sonunda kullanılacak özel bir kapak ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Bu Pen ile çizilen çizgilerin sonunda kullanılan ucu temsil eden bir  CustomLineCap . |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılacak özel bir kapak ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Bu Pen ile çizilen çizgilerin başlangıcında kullanılan ucu temsil eden bir  CustomLineCap . |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Bu  Pen  ile çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan kapak stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu Pen ile çizilen kesikli çizgileri oluşturan tirelerin başlangıç ve bitişinde kullanılan kap stilini temsil eden  DashCap  değerlerinden biri. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Bir çizginin başlangıcından tire deseninin başına olan mesafeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bir çizginin başlangıcından tire deseninin başlangıcına olan mesafe. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Özel tireler ve boşluklardan oluşan bir dizi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] | Kesikli çizgilerde dönüşümlü tire ve boşluk uzunluklarını belirten gerçek sayılardan oluşan bir dizi. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Bu  Pen  ile çizilen kesikli çizgiler için kullanılan stili ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu Pen ile çizilen kesikli çizgilerde kullanılan stili temsil eden bir  DashStyle . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Bu  Pen  ile çizilen çizgilerin sonunda kullanılan kapak stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu Pen ile çizilen çizgilerin sonunda kullanılan kap stilini temsil eden  LineCap  değerlerinden biri. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Bu  Pen  tarafından çizilen çizgileri sonlandırmak için kullanılan kapak stilini belirleyen değerleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startCap | int | Bu Pen ile çizilen çizgilerin başlangıcında kullanılacak kap stilini temsil eden bir  LineCap . |
| endCap | int | Bu Pen ile çizilen çizgilerin sonunda kullanılacak kap stilini temsil eden bir  LineCap . |
| dashCap | int | Bu Pen ile çizilen kesikli çizgilerin başlangıç veya sonunda kullanılacak kap stilini temsil eden bir  LineCap . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Bu  Pen  ile çizilen iki ardışık çizginin uçları için birleştirme stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu Pen ile çizilen iki ardışık çizginin uçlarındaki birleşim stilini temsil eden bir  LineJoin . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Köşe birleşiminde eklem kalınlığının sınırını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Köşeli bir köşedeki birleşimin kalınlık sınırı. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Nesnenin opaklığını ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri nesnenin tamamen görünür olduğu, 1 değeri nesnenin tamamen opak olduğu anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Opaklık değeri. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Bu  Pen  ile çizilen çizgilerin başlangıcında kullanılan kapak stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu Pen ile çizilen çizgilerin başlangıcında kullanılan kap stilini temsil eden  LineCap  değerlerinden biri. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Bu  Pen  için geometrik dönüşümün bir kopyasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Bu Pen için geometrik dönüşümü temsil eden bir  Matrix  kopyası. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Çizim için kullanılan Graphics nesnesinin birimlerinde, bu  Pen  genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu  Pen  genişliği. |

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


Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşümün başına ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir.

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

