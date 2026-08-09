---
title: "Rectangle"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tam sayı setini depolar."
type: docs
weight: 88
url: /tr/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Bir dikdörtgenin konumunu ve boyutunu temsil eden dört tam sayı setini depolar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Belirtilen konum ve boyutla yeni bir com.aspose.psd.Rectangle yapısı örneği başlatır. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Belirtilen konum ve boyutla yeni bir com.aspose.psd.Rectangle yapısı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Belirtilen com.aspose.psd.RectangleF yapısını, com.aspose.psd.RectangleF değerlerini bir üst tam sayıya yuvarlayarak com.aspose.psd.Rectangle yapısına dönüştürür. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Belirtilen noktanın bu com.aspose.psd.Rectangle yapısı içinde olup olmadığını belirler. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | rect tarafından temsil edilen dikdörtgen bölgenin bu com.aspose.psd.Rectangle yapısı içinde tamamen bulunup bulunmadığını belirler. |
| [contains(int x, int y)](#contains-int-int-) | Belirtilen noktanın bu com.aspose.psd.Rectangle yapısı içinde olup olmadığını belirler. |
| [equals(Object obj)](#equals-java.lang.Object-) | obj'nin bu com.aspose.psd.Rectangle yapısı ile aynı konuma ve boyuta sahip bir com.aspose.psd.Rectangle yapısı olup olmadığını test eder. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Belirtilen kenar konumlarıyla bir com.aspose.psd.Rectangle yapısı oluşturur. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Belirtilen iki noktadan yeni bir Rectangle oluşturur. |
| [getBottom()](#getBottom--) | Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.Y ve com.aspose.psd.Rectangle.Height özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width ve com.aspose.psd.Rectangle.Height değerleri sıfıra ayarlanmış yeni bir com.aspose.psd.Rectangle yapısı örneği alır. |
| [getHeight()](#getHeight--) | Bu com.aspose.psd.Rectangle yapısının yüksekliğini alır veya ayarlar. |
| [getLeft()](#getLeft--) | Bu com.aspose.psd.Rectangle yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [getLocation()](#getLocation--) | Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| [getRight()](#getRight--) | Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.X ve com.aspose.psd.Rectangle.Width özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar. |
| [getSize()](#getSize--) | Bu com.aspose.psd.Rectangle öğesinin boyutunu alır veya ayarlar. |
| [getTop()](#getTop--) | Bu com.aspose.psd.Rectangle yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [getWidth()](#getWidth--) | Bu com.aspose.psd.Rectangle yapısının genişliğini alır. |
| [getX()](#getX--) | Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [getY()](#getY--) | Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
| [hashCode()](#hashCode--) | Bu com.aspose.psd.Rectangle yapısının karma (hash) kodunu döndürür. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Belirtilen com.aspose.psd.Rectangle yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Bu com.aspose.psd.Rectangle'ı belirtilen miktarda şişirir. |
| [inflate(int width, int height)](#inflate-int-int-) | Bu com.aspose.psd.Rectangle'ı belirtilen miktarda şişirir. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Bu com.aspose.psd.Rectangle'ı kendisi ile belirtilen com.aspose.psd.Rectangle'ın kesişimiyle değiştirir. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | İki diğer com.aspose.psd.Rectangle yapısının kesişimini temsil eden üçüncü bir com.aspose.psd.Rectangle yapısını döndürür. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Bu dikdörtgenin  rect  ile kesişip kesişmediğini belirler. |
| [isEmpty()](#isEmpty--) | Bu com.aspose.psd.Rectangle'ın tüm sayısal özelliklerinin sıfır değere sahip olup olmadığını gösteren bir değeri alır. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Bu Rectangle'ın en azından kısmen görünür olup olmadığını gösteren bir değeri alır. |
| [normalize()](#normalize--) | Dikdörtgeni, genişliğini ve yüksekliğini pozitif yaparak, solun sağdan, üstün alttan küçük olmasını sağlayarak normalleştirir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [offset(int x, int y)](#offset-int-int-) | Bu dikdörtgenin konumunu belirtilen miktarda ayarlar. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | İki com.aspose.psd.Rectangle yapısının konum ve boyutlarının eşit olup olmadığını test eder. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | İki com.aspose.psd.Rectangle yapısının konum veya boyutta farklı olup olmadığını test eder. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Belirtilen com.aspose.psd.RectangleF değerlerini en yakın tam sayıya yuvarlayarak bir com.aspose.psd.Rectangle'a dönüştürür. |
| [setBottom(int value)](#setBottom-int-) | Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.Y ve com.aspose.psd.Rectangle.Height özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | Bu com.aspose.psd.Rectangle yapısının yüksekliğini alır veya ayarlar. |
| [setLeft(int value)](#setLeft-int-) | Bu com.aspose.psd.Rectangle yapısının sol kenarının x koordinatını alır veya ayarlar. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin koordinatlarını alır veya ayarlar. |
| [setRight(int value)](#setRight-int-) | Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.X ve com.aspose.psd.Rectangle.Width özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Bu com.aspose.psd.Rectangle öğesinin boyutunu alır veya ayarlar. |
| [setTop(int value)](#setTop-int-) | Bu com.aspose.psd.Rectangle yapısının üst kenarının y koordinatını alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Bu com.aspose.psd.Rectangle yapısının genişliğini ayarlar. |
| [setX(int value)](#setX-int-) | Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin x koordinatını alır veya ayarlar. |
| [setY(int value)](#setY-int-) | Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin y koordinatını alır veya ayarlar. |
| [toString()](#toString--) | Bu com.aspose.psd.Rectangle'ın özniteliklerini insan tarafından okunabilir bir dizeye dönüştürür. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Belirtilen com.aspose.psd.RectangleF değerlerini kırparak bir com.aspose.psd.Rectangle'a dönüştürür. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | İki com.aspose.psd.Rectangle yapısının birleşimini içeren bir com.aspose.psd.Rectangle yapısı alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Belirtilen konum ve boyutla yeni bir com.aspose.psd.Rectangle yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Dikdörtgenin genişliği. |
| height | int | Dikdörtgenin yüksekliği. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Belirtilen konum ve boyutla yeni bir com.aspose.psd.Rectangle yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Dikdörtgen bölgenin sol üst köşesini temsil eden bir  com.aspose.psd.Point . |
| size | [Size](../../com.aspose.psd/size) | Dikdörtgen bölgenin genişliğini ve yüksekliğini temsil eden bir  com.aspose.psd.Size . |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Belirtilen com.aspose.psd.RectangleF yapısını, com.aspose.psd.RectangleF değerlerini bir üst tam sayıya yuvarlayarak com.aspose.psd.Rectangle yapısına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Dönüştürülecek  com.aspose.psd.RectangleF  yapısı. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Belirtilen noktanın bu com.aspose.psd.Rectangle yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Test edilecek  com.aspose.psd.Point . |

**Returns:**
boolean - Bu yöntem,  point  tarafından temsil edilen nokta bu  com.aspose.psd.Rectangle  yapısı içinde bulunuyorsa true döndürür; aksi takdirde false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


rect tarafından temsil edilen dikdörtgen bölgenin bu com.aspose.psd.Rectangle yapısı içinde tamamen bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Test edilecek  com.aspose.psd.Rectangle . |

**Returns:**
boolean - Bu yöntem,  rect  tarafından temsil edilen dikdörtgen bölgesi tamamen bu  com.aspose.psd.Rectangle  yapısı içinde bulunuyorsa true döndürür; aksi takdirde false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Belirtilen noktanın bu com.aspose.psd.Rectangle yapısı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem,  x  ve  y  tarafından tanımlanan nokta bu  com.aspose.psd.Rectangle  yapısı içinde bulunuyorsa true döndürür; aksi takdirde false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj'nin bu com.aspose.psd.Rectangle yapısı ile aynı konuma ve boyuta sahip bir com.aspose.psd.Rectangle yapısı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek  System.Object . |

**Returns:**
boolean - Bu yöntem,  obj  bir  com.aspose.psd.Rectangle  yapısı ise ve onun  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  ve  com.aspose.psd.Rectangle.Height  özellikleri bu  com.aspose.psd.Rectangle  yapısının ilgili özelliklerine eşitse true döndürür; aksi takdirde false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Belirtilen kenar konumlarıyla bir com.aspose.psd.Rectangle yapısı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | int | Bu  com.aspose.psd.Rectangle  yapısının sol üst köşesinin x koordinatı. |
| top | int | Bu  com.aspose.psd.Rectangle  yapısının sol üst köşesinin y koordinatı. |
| right | int | Bu  com.aspose.psd.Rectangle  yapısının sağ alt köşesinin x koordinatı. |
| bottom | int | Bu  com.aspose.psd.Rectangle  yapısının sağ alt köşesinin y koordinatı. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Belirtilen iki noktadan yeni bir  Rectangle  oluşturur. Oluşturulan  Rectangle  nesnesinin iki kenarı, verilen  point1  ve  point2  değerlerine eşit olacaktır. Bunlar genellikle karşıt köşeler olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Yeni dikdörtgen için ilk  Point . |
| point2 | [Point](../../com.aspose.psd/point) | Yeni dikdörtgen için ikinci  Point . |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.Y ve com.aspose.psd.Rectangle.Height özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  nesnesinin  com.aspose.psd.Rectangle.Y  ve  com.aspose.psd.Rectangle.Height  toplamı olan y koordinatı.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width ve com.aspose.psd.Rectangle.Height değerleri sıfıra ayarlanmış yeni bir com.aspose.psd.Rectangle yapısı örneği alır.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu com.aspose.psd.Rectangle yapısının yüksekliğini alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  yapısının yüksekliği.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Bu com.aspose.psd.Rectangle yapısının sol kenarının x koordinatını alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  yapısının sol kenarının x koordinatı.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin koordinatlarını alır veya ayarlar.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.X ve com.aspose.psd.Rectangle.Width özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  nesnesinin  com.aspose.psd.Rectangle.X  ve  com.aspose.psd.Rectangle.Width  toplamı olan x koordinatı.
### getSize() {#getSize--}
```
public Size getSize()
```


Bu com.aspose.psd.Rectangle öğesinin boyutunu alır veya ayarlar.

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Bu com.aspose.psd.Rectangle yapısının üst kenarının y koordinatını alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  yapısının üst kenarının y koordinatı.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu com.aspose.psd.Rectangle yapısının genişliğini alır.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  yapısının genişliği.
### getX() {#getX--}
```
public int getX()
```


Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin x koordinatını alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  yapısının sol üst köşesinin x koordinatı.
### getY() {#getY--}
```
public int getY()
```


Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin y koordinatını alır veya ayarlar.

**Returns:**
int - Bu  com.aspose.psd.Rectangle  yapısının sol üst köşesinin y koordinatı.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu com.aspose.psd.Rectangle yapısının karma (hash) kodunu döndürür.

**Returns:**
int - Bu dikdörtgenin hash kodunu temsil eden bir tamsayı.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Belirtilen  com.aspose.psd.Rectangle  yapısının şişirilmiş bir kopyasını oluşturur ve döndürür. Kopya, belirtilen miktarda şişirilir. Orijinal  com.aspose.psd.Rectangle  yapısı değiştirilmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Başlangıç için kullanılacak  com.aspose.psd.Rectangle . Bu dikdörtgen değiştirilmez. |
| x | int | Bu  com.aspose.psd.Rectangle  nesnesini yatay olarak şişirme miktarı. |
| y | int | Bu  com.aspose.psd.Rectangle  nesnesini dikey olarak şişirme miktarı. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Bu com.aspose.psd.Rectangle'ı belirtilen miktarda şişirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Bu dikdörtgeni şişirme miktarı. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Bu com.aspose.psd.Rectangle'ı belirtilen miktarda şişirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Bu  com.aspose.psd.Rectangle  nesnesini yatay olarak şişirme miktarı. |
| height | int | Bu  com.aspose.psd.Rectangle  nesnesini dikey olarak şişirme miktarı. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Bu com.aspose.psd.Rectangle'ı kendisi ile belirtilen com.aspose.psd.Rectangle'ın kesişimiyle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Kesişmek için kullanılacak  com.aspose.psd.Rectangle  . |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


İki diğer  com.aspose.psd.Rectangle  yapısının kesişimini temsil eden üçüncü bir  com.aspose.psd.Rectangle  yapısını döndürür. Kesişme yoksa, boş bir  com.aspose.psd.Rectangle  döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Kesişecek ilk dikdörtgen. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Kesişecek ikinci dikdörtgen. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bu dikdörtgenin  rect  ile kesişip kesişmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Test edilecek dikdörtgen. |

**Returns:**
boolean - Bu yöntem, herhangi bir kesişme varsa true, aksi takdirde false döndürür.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu com.aspose.psd.Rectangle'ın tüm sayısal özelliklerinin sıfır değere sahip olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - Bu özellik, bu  com.aspose.psd.Rectangle  nesnesinin  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X  ve  com.aspose.psd.Rectangle.Y  özelliklerinin tümünün sıfır değerine sahip olması durumunda true; aksi takdirde false döndürür.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Bu Rectangle'ın en azından kısmen görünür olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean -  true  eğer bu  Rectangle  en azından kısmen görünürse; aksi takdirde  false .
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Konumu kaydırma miktarı. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Bu dikdörtgenin konumunu belirtilen miktarda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Yatay kaydırma. |
| y | int | Dikey kaydırma. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


İki com.aspose.psd.Rectangle yapısının konum ve boyutlarının eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Eşitlik operatörünün solunda bulunan  com.aspose.psd.Rectangle  yapısı. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Eşitlik operatörünün sağında bulunan  com.aspose.psd.Rectangle  yapısı. |

**Returns:**
boolean - Bu operatör, iki  com.aspose.psd.Rectangle  yapısının  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  ve  com.aspose.psd.Rectangle.Height  özelliklerinin eşit olması durumunda true döndürür.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


İki com.aspose.psd.Rectangle yapısının konum veya boyutta farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Eşitsizlik operatörünün solunda bulunan  com.aspose.psd.Rectangle  yapısı. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Eşitsizlik operatörünün sağında bulunan  com.aspose.psd.Rectangle  yapısı. |

**Returns:**
boolean - Bu operatör, iki  com.aspose.psd.Rectangle  yapısının  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  veya  com.aspose.psd.Rectangle.Height  özelliklerinden herhangi biri eşit değilse true; aksi takdirde false döndürür.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Belirtilen com.aspose.psd.RectangleF değerlerini en yakın tam sayıya yuvarlayarak bir com.aspose.psd.Rectangle'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Dönüştürülecek  com.aspose.psd.RectangleF . |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.Y ve com.aspose.psd.Rectangle.Height özellik değerlerinin toplamı olan y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  nesnesinin  com.aspose.psd.Rectangle.Y  ve  com.aspose.psd.Rectangle.Height  toplamı olan y koordinatı. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Bu com.aspose.psd.Rectangle yapısının yüksekliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  yapısının yüksekliği. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Bu com.aspose.psd.Rectangle yapısının sol kenarının x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  yapısının sol kenarının x koordinatı. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin koordinatlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Bu  com.aspose.psd.Rectangle  yapısının sol-üst köşesini temsil eden bir  Point . |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Bu com.aspose.psd.Rectangle yapısının com.aspose.psd.Rectangle.X ve com.aspose.psd.Rectangle.Width özellik değerlerinin toplamı olan x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  nesnesinin  com.aspose.psd.Rectangle.X  ve  com.aspose.psd.Rectangle.Width  toplamı olan x koordinatı. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Bu com.aspose.psd.Rectangle öğesinin boyutunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Bu  com.aspose.psd.Rectangle  yapısının genişlik ve yüksekliğini temsil eden bir  com.aspose.psd.Size . |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Bu com.aspose.psd.Rectangle yapısının üst kenarının y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  yapısının üst kenarının y koordinatı. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Bu com.aspose.psd.Rectangle yapısının genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  yapısının genişliği. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin x koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  yapısının sol üst köşesinin x koordinatı. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Bu com.aspose.psd.Rectangle yapısının sol üst köşesinin y koordinatını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.Rectangle  yapısının sol üst köşesinin y koordinatı. |

### toString() {#toString--}
```
public String toString()
```


Bu com.aspose.psd.Rectangle'ın özniteliklerini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu  com.aspose.psd.Rectangle  yapısının konumunu, genişliğini ve yüksekliğini içeren bir dize.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Belirtilen com.aspose.psd.RectangleF değerlerini kırparak bir com.aspose.psd.Rectangle'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Dönüştürülecek  com.aspose.psd.RectangleF . |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


İki com.aspose.psd.Rectangle yapısının birleşimini içeren bir com.aspose.psd.Rectangle yapısı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Birleşecek ilk dikdörtgen. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Birleşecek ikinci dikdörtgen. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

