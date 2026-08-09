---
title: "RectangleF"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan nokta sayısı setini depolar."
type: docs
weight: 89
url: /tr/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört kayan nokta sayısı setini depolar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Belirtilen konum ve boyut ile **com.aspose.psd.RectangleF** yapısının yeni bir örneğini başlatır. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Belirtilen konum ve boyut ile **com.aspose.psd.RectangleF** yapısının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Belirtilen noktanın bu **com.aspose.psd.RectangleF** yapısı içinde olup olmadığını belirler. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | rect tarafından temsil edilen dikdörtgen bölgenin tamamen bu **com.aspose.psd.RectangleF** yapısı içinde olup olmadığını belirler. |
| [contains(float x, float y)](#contains-float-float-) | Belirtilen noktanın bu **com.aspose.psd.RectangleF** yapısı içinde olup olmadığını belirler. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Mevcut dikdörtgen değerlerini bölerek matrisin dikey ve yatay ölçek değerlerini dönüştürür ve sonuç değerleriyle yeni bir [RectangleF](../../com.aspose.psd/rectanglef) örneği döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | obj'nin bu **com.aspose.psd.RectangleF** ile aynı konum ve boyuta sahip bir **com.aspose.psd.RectangleF** olup olmadığını test eder. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Belirtilen konumlardaki sol üst köşe ve sağ alt köşe ile **com.aspose.psd.RectangleF** yapısını oluşturur. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Belirtilen iki noktadan yeni bir Rectangle oluşturur. |
| [getBottom()](#getBottom--) | Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.Y** ve **com.aspose.psd.RectangleF.Height** toplamı olan y koordinatını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Sıfıra ayarlanmış **com.aspose.psd.RectangleF.X**, **com.aspose.psd.RectangleF.Y**, **com.aspose.psd.RectangleF.Width** ve **com.aspose.psd.RectangleF.Height** değerlerine sahip **com.aspose.psd.RectangleF** yapısının yeni bir örneğini alır. |
| [getHeight()](#getHeight--) | Bu **com.aspose.psd.RectangleF** yapısının yüksekliğini alır veya ayarlar. |
| [getLeft()](#getLeft--) | Bu **com.aspose.psd.RectangleF** yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [getLocation()](#getLocation--) | Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe koordinatlarını alır veya ayarlar. |
| [getRight()](#getRight--) | Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.X** ve **com.aspose.psd.RectangleF.Width** toplamı olan x koordinatını alır veya ayarlar. |
| [getSize()](#getSize--) | Bu **com.aspose.psd.RectangleF** yapısının boyutunu alır veya ayarlar. |
| [getTop()](#getTop--) | Bu **com.aspose.psd.RectangleF** yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [getWidth()](#getWidth--) | Bu **com.aspose.psd.RectangleF** yapısının genişliğini alır veya ayarlar. |
| [getX()](#getX--) | Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe x koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe y koordinatını alır veya ayarlar. |
| [hashCode()](#hashCode--) | Bu  com.aspose.psd.RectangleF  yapısı için karma kodunu alır. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Belirtilen  com.aspose.psd.RectangleF  yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Bu  com.aspose.psd.RectangleF  öğesini belirtilen miktarda şişirir. |
| [inflate(float x, float y)](#inflate-float-float-) | Bu  com.aspose.psd.RectangleF  yapısını belirtilen miktarda şişirir. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Bu  com.aspose.psd.RectangleF  yapısını, kendisi ile belirtilen  com.aspose.psd.RectangleF  yapısının kesişimiyle değiştirir. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | İki dikdörtgenin kesişimini temsil eden bir  com.aspose.psd.RectangleF  yapısını döndürür. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Bu dikdörtgenin  rect  ile kesişip kesişmediğini belirler. |
| [isEmpty()](#isEmpty--) | Bu  com.aspose.psd.RectangleF  öğesinin  com.aspose.psd.RectangleF.Width  veya  com.aspose.psd.RectangleF.Height  özelliğinin sıfır olup olmadığını gösteren bir değer alır. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Mevcut dikdörtgen değerlerini çarparak matrisin dikey ve yatay ölçek değerlerini dönüştürür ve sonuç değerleriyle yeni bir [RectangleF](../../com.aspose.psd/rectanglef) örneği döndürür. |
| [normalize()](#normalize--) | Dikdörtgeni, genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(float x, float y)](#offset-float-float-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | / operatörünü uygular. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | İki  com.aspose.psd.RectangleF  yapısının konum ve boyutunun eşit olup olmadığını test eder. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | İki  com.aspose.psd.RectangleF  yapısının konum veya boyutta farklı olup olmadığını test eder. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | \* operatörünü uygular. |
| [setBottom(float value)](#setBottom-float-) | Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.Y** ve **com.aspose.psd.RectangleF.Height** toplamı olan y koordinatını alır veya ayarlar. |
| [setHeight(float value)](#setHeight-float-) | Bu **com.aspose.psd.RectangleF** yapısının yüksekliğini alır veya ayarlar. |
| [setLeft(float value)](#setLeft-float-) | Bu **com.aspose.psd.RectangleF** yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe koordinatlarını alır veya ayarlar. |
| [setRight(float value)](#setRight-float-) | Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.X** ve **com.aspose.psd.RectangleF.Width** toplamı olan x koordinatını alır veya ayarlar. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Bu **com.aspose.psd.RectangleF** yapısının boyutunu alır veya ayarlar. |
| [setTop(float value)](#setTop-float-) | Bu **com.aspose.psd.RectangleF** yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [setWidth(float value)](#setWidth-float-) | Bu **com.aspose.psd.RectangleF** yapısının genişliğini alır veya ayarlar. |
| [setX(float value)](#setX-float-) | Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe x koordinatını alır veya ayarlar. |
| [setY(float value)](#setY-float-) | Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe y koordinatını alır veya ayarlar. |
| [toRectangle_internalized()](#toRectangle-internalized--) | [RectangleF](../../com.aspose.psd/rectanglef) öğesini, kesilmiş dikdörtgen değerleriyle bir [Rectangle](../../com.aspose.psd/rectangle) yapısına dönüştürür. |
| [toString()](#toString--) | Bu  com.aspose.psd.RectangleF  öğesinin özelliklerini insan tarafından okunabilir bir dizeye dönüştürür. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Belirtilen  com.aspose.psd.Rectangle  yapısını bir  com.aspose.psd.RectangleF  yapısına dönüştürür. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Birleşim oluşturan iki dikdörtgeni de içerebilecek en küçük üçüncü dikdörtgeni oluşturur. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Belirtilen konum ve boyut ile **com.aspose.psd.RectangleF** yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Dikdörtgenin genişliği. |
| height | float | Dikdörtgenin yüksekliği. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Belirtilen konum ve boyut ile **com.aspose.psd.RectangleF** yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Bir  com.aspose.psd.PointF  nesnesi, dikdörtgen bölgenin sol üst köşesini temsil eder. |
| size | [SizeF](../../com.aspose.psd/sizef) | Bir  com.aspose.psd.SizeF  nesnesi, dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eder. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Belirtilen noktanın bu **com.aspose.psd.RectangleF** yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Test edilecek  com.aspose.psd.PointF . |

**Returns:**
boolean - Bu yöntem,  point  parametresiyle temsil edilen nokta bu  com.aspose.psd.RectangleF  yapısının içinde yer alıyorsa true, aksi takdirde false döndürür.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


rect tarafından temsil edilen dikdörtgen bölgenin tamamen bu **com.aspose.psd.RectangleF** yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Test edilecek  com.aspose.psd.RectangleF . |

**Returns:**
boolean - Bu yöntem,  rect  ile temsil edilen dikdörtgen bölge bu  com.aspose.psd.RectangleF  tarafından temsil edilen dikdörtgen bölgenin tamamen içinde yer alıyorsa true, aksi takdirde false döndürür.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Belirtilen noktanın bu **com.aspose.psd.RectangleF** yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem,  x  ve  y  ile tanımlanan nokta bu  com.aspose.psd.RectangleF  yapısının içinde yer alıyorsa true, aksi takdirde false döndürür.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Mevcut dikdörtgen değerlerini bölerek matrisin dikey ve yatay ölçek değerlerini dönüştürür ve sonuç değerleriyle yeni bir [RectangleF](../../com.aspose.psd/rectanglef) örneği döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transformMatrix | double[] | Katman dönüşüm matrisi. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj'nin bu **com.aspose.psd.RectangleF** ile aynı konum ve boyuta sahip bir **com.aspose.psd.RectangleF** olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek  System.Object . |

**Returns:**
boolean - Bu yöntem,  obj  bir  com.aspose.psd.RectangleF  ise ve onun X, Y, Width ve Height özellikleri bu  com.aspose.psd.RectangleF  nesnesinin ilgili özelliklerine eşitse true, aksi takdirde false döndürür.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Belirtilen konumlardaki sol üst köşe ve sağ alt köşe ile **com.aspose.psd.RectangleF** yapısını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | float | Dikdörtgen bölgenin sol-üst köşesinin x koordinatı. |
| top | float | Dikdörtgen bölgenin sol-üst köşesinin y koordinatı. |
| right | float | Dikdörtgen bölgenin sağ-alt köşesinin x koordinatı. |
| bottom | float | Dikdörtgen bölgenin sağ-alt köşesinin y koordinatı. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Belirtilen iki noktadan yeni bir  Rectangle  oluşturur. Oluşturulan  Rectangle  nesnesinin iki köşesi verilen  point1  ve  point2  değerlerine eşit olur. Bunlar genellikle karşıt köşelerdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Yeni dikdörtgen için ilk  Point . |
| point2 | [PointF](../../com.aspose.psd/pointf) | Yeni dikdörtgen için ikinci  Point . |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.Y** ve **com.aspose.psd.RectangleF.Height** toplamı olan y koordinatını alır veya ayarlar.

**Returns:**
float - Bu  com.aspose.psd.RectangleF  yapısının  com.aspose.psd.RectangleF.Y  ve  com.aspose.psd.RectangleF.Height  toplamı olan y koordinatı.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Sıfıra ayarlanmış **com.aspose.psd.RectangleF.X**, **com.aspose.psd.RectangleF.Y**, **com.aspose.psd.RectangleF.Width** ve **com.aspose.psd.RectangleF.Height** değerlerine sahip **com.aspose.psd.RectangleF** yapısının yeni bir örneğini alır.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Bu **com.aspose.psd.RectangleF** yapısının yüksekliğini alır veya ayarlar.

**Returns:**
float - Bu  com.aspose.psd.RectangleF  yapısının yüksekliği.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Bu **com.aspose.psd.RectangleF** yapısının sol kenarının x koordinatını alır veya ayarlar.

**Returns:**
float - Bu  com.aspose.psd.RectangleF  yapısının sol kenarının x koordinatı.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe koordinatlarını alır veya ayarlar.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.X** ve **com.aspose.psd.RectangleF.Width** toplamı olan x koordinatını alır veya ayarlar.

**Returns:**
float - Bu com.aspose.psd.RectangleF yapısının com.aspose.psd.RectangleF.X ve com.aspose.psd.RectangleF.Width toplamı olan x koordinatı.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Bu **com.aspose.psd.RectangleF** yapısının boyutunu alır veya ayarlar.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Bu **com.aspose.psd.RectangleF** yapısının üst kenarının y koordinatını alır veya ayarlar.

**Returns:**
float - Bu com.aspose.psd.RectangleF yapısının üst kenarının y koordinatı.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Bu **com.aspose.psd.RectangleF** yapısının genişliğini alır veya ayarlar.

**Returns:**
float - Bu com.aspose.psd.RectangleF yapısının genişliği.
### getX() {#getX--}
```
public float getX()
```


Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe x koordinatını alır veya ayarlar.

**Returns:**
float - Bu com.aspose.psd.RectangleF yapısının sol üst köşesinin x koordinatı.
### getY() {#getY--}
```
public float getY()
```


Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe y koordinatını alır veya ayarlar.

**Returns:**
float - Bu com.aspose.psd.RectangleF yapısının sol üst köşesinin y koordinatı.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu  com.aspose.psd.RectangleF  yapısı için karma kodunu alır.

**Returns:**
int - Bu com.aspose.psd.RectangleF için hash kodu.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Belirtilen com.aspose.psd.RectangleF yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya belirtilen miktarda şişirilir. Orijinal dikdörtgen değişmeden kalır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Kopyalanacak com.aspose.psd.RectangleF. Bu dikdörtgen değiştirilmez. |
| x | float | Dikdörtgenin kopyasını yatay olarak şişirme miktarı. |
| y | float | Dikdörtgenin kopyasını dikey olarak şişirme miktarı. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Bu  com.aspose.psd.RectangleF  öğesini belirtilen miktarda şişirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Bu dikdörtgeni şişirme miktarı. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Bu  com.aspose.psd.RectangleF  yapısını belirtilen miktarda şişirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Bu com.aspose.psd.RectangleF yapısını yatay olarak şişirme miktarı. |
| y | float | Bu com.aspose.psd.RectangleF yapısını dikey olarak şişirme miktarı. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Bu  com.aspose.psd.RectangleF  yapısını, kendisi ile belirtilen  com.aspose.psd.RectangleF  yapısının kesişimiyle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Kesişecek dikdörtgen. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


İki dikdörtgenin kesişimini temsil eden bir com.aspose.psd.RectangleF yapısı döndürür. Kesişim yoksa boş bir com.aspose.psd.RectangleF döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Kesişecek ilk dikdörtgen. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Kesişecek ikinci dikdörtgen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bu dikdörtgenin  rect  ile kesişip kesişmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Test edilecek dikdörtgen. |

**Returns:**
boolean - Bu yöntem herhangi bir kesişim varsa true döndürür.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu  com.aspose.psd.RectangleF  öğesinin  com.aspose.psd.RectangleF.Width  veya  com.aspose.psd.RectangleF.Height  özelliğinin sıfır olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu özellik, bu com.aspose.psd.RectangleF'in com.aspose.psd.RectangleF.Width veya com.aspose.psd.RectangleF.Height özelliği sıfır değerine sahipse true döndürür; aksi takdirde false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Mevcut dikdörtgen değerlerini çarparak matrisin dikey ve yatay ölçek değerlerini dönüştürür ve sonuç değerleriyle yeni bir [RectangleF](../../com.aspose.psd/rectanglef) örneği döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transformMatrix | double[] | Katman dönüşüm matrisi. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


Dikdörtgeni, genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Konumu kaydırma miktarı. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Konumu yatay olarak kaydırma miktarı. |
| y | float | Konumu dikey olarak kaydırma miktarı. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


/ operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Bu dikdörtgen. |
| bölücü | float | Bölücü. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


İki  com.aspose.psd.RectangleF  yapısının konum ve boyutunun eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Eşitlik operatörünün solunda bulunan com.aspose.psd.RectangleF yapısı. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Eşitlik operatörünün sağında bulunan com.aspose.psd.RectangleF yapısı. |

**Returns:**
boolean - Bu operatör, belirtilen iki com.aspose.psd.RectangleF yapısının com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width ve com.aspose.psd.RectangleF.Height özelliklerinin eşit olması durumunda true döndürür.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


İki  com.aspose.psd.RectangleF  yapısının konum veya boyutta farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Eşitsizlik operatörünün solunda bulunan com.aspose.psd.RectangleF yapısı. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Eşitsizlik operatörünün sağında bulunan com.aspose.psd.RectangleF yapısı. |

**Returns:**
boolean - Bu operatör, iki com.aspose.psd.RectangleF yapısının com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width veya com.aspose.psd.RectangleF.Height özelliklerinden herhangi biri eşit olmadığında true döndürür; aksi takdirde false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


\* operatörünü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Bu dikdörtgen. |
| çarpan | float | Çarpan. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.Y** ve **com.aspose.psd.RectangleF.Height** toplamı olan y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının yüksekliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının sol kenarının x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe koordinatlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının **com.aspose.psd.RectangleF.X** ve **com.aspose.psd.RectangleF.Width** toplamı olan x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Bu **com.aspose.psd.RectangleF** yapısının boyutunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının üst kenarının y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının genişliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Bu **com.aspose.psd.RectangleF** yapısının sol üst köşe y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


[RectangleF](../../com.aspose.psd/rectanglef) öğesini, kesilmiş dikdörtgen değerleriyle bir [Rectangle](../../com.aspose.psd/rectangle) yapısına dönüştürür.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Bu  com.aspose.psd.RectangleF  öğesinin özelliklerini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu com.aspose.psd.RectangleF yapısının konumunu, genişliğini ve yüksekliğini içeren bir dize.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Belirtilen  com.aspose.psd.Rectangle  yapısını bir  com.aspose.psd.RectangleF  yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Dönüştürülecek com.aspose.psd.Rectangle yapısı. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Birleşim oluşturan iki dikdörtgeni de içerebilecek en küçük üçüncü dikdörtgeni oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Birleşecek ilk dikdörtgen. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Birleşecek ikinci dikdörtgen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

