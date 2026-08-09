---
title: "Matrix"
second_title: "Java için Aspose.PSD API Referansı"
description: "GDI Matrix'ini değiştirir."
type: docs
weight: 69
url: /tr/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

GDI+ Matrix'i değiştirir.

Çoğu algoritma Sun'un AffineTransform.java dosyasından alınmıştır. Java'nın matris elemanları için kullanılan adlar dahili olarak kullanılır. Java adlarının .net karşılıklarına ve açıklamalarına harita: m00 M11 Ölçek X m10 M12 Kaydırma Y m01 M21 Kaydırma X m11 M22 Ölçek Y m02 M31 Çevirme X m12 M32 Çevirme Y
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix sınıfının yeni bir örneğini birim matris olarak başlatır. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Matrix sınıfının yeni bir örneğini başlatır. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Matrix sınıfının bir kopyasını oluşturur. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Aspose.Imaging.Matrix sınıfının yeni bir örneğini, belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme başlatır. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Aspose.Imaging.Matrix sınıfının yeni bir örneğini, belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, normalde sağ el koordinat sistemini sol el sistemine değiştiren bir eksen etrafında ayna görüntüsü çevirmesi yaptığını gösterir. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, rastgele bir açıyla döndürme yaptığını gösterir. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Genel bir ölçek, dik vektörler arasındaki açıyı değiştirmeden, x ve y yönlerinde vektörlerin uzunluğunu farklı miktarlarda çarpar. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Bu sabit, bu nesne tarafından tanımlanan dönüşümün giriş koordinatlarının rastgele bir dönüşümünü gerçekleştirdiğini gösterir. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Bir birim dönüşüm, çıktı koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu dönüşümdür. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Bu sabit, döndürme bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, 90 derecenin katlarıyla bir bölge döndürmesi yaptığını gösterir. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Bir çevirme, vektörlerin uzunluğunu veya açısını değiştirmeden, x ve y eksenlerinde koordinatları sabit bir miktar hareket ettirir. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Bir eşit ölçek, vektörlerin uzunluğunu x ve y yönlerinde aynı miktarda çarpar ve vektörler arasındaki açıyı değiştirmez. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen  System.Object  bu örnek ile eşit olup olmadığını belirler. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Matris elemanlarının bir kopyasını alır. |
| [getM11()](#getM11--) | İlk satırın ilk sütunundaki matris elemanını alır. |
| [getM12()](#getM12--) | İlk satırın ikinci sütunundaki matris elemanını alır. |
| [getM21()](#getM21--) | İkinci satırın ilk sütunundaki matris elemanını alır. |
| [getM22()](#getM22--) | İkinci satırın ikinci sütunundaki matris elemanını alır. |
| [getM31()](#getM31--) | Üçüncü satırın ilk sütunundaki matris elemanını alır. |
| [getM32()](#getM32--) | Üçüncü satırın ilk sütunundaki matris elemanını alır. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | İki matrisin eşit olup olmadığını belirler. |
| [isIdentity()](#isIdentity--) | Bu `AffineTransform` bir birim dönüşümse `true` döndürür. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Bu Matrix'i birim matrisin elemanlarına sahip olacak şekilde sıfırlar. |
| [rotate(float angle)](#rotate-float-) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir döndürme uygular, orijinde (sıfır x ve y koordinatları) varsayılan (Prepend) sırada. |
| [rotate(float angle, int order)](#rotate-float-int-) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir döndürme uygular, orijinde (sıfır x ve y koordinatları) belirtilen sırada. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Belirtilen nokta etrafında saat yönünde bir döndürme uygular, bu Matrix'i varsayılan (Prepend) sırada. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Belirtilen nokta etrafında saat yönünde bir döndürme uygular, bu Matrix'i belirtilen sırada. |
| [scale(float sx, float sy)](#scale-float-float-) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e belirtilen sırayı kullanarak uygular. |
| [toString()](#toString--) | Bu örneği temsil eden bir  System.String  döndürür. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Bu Matrix tarafından temsil edilen geometrik dönüşümü belirtilen bir nokta dizisine uygular. |
| [translate(float tx, float ty)](#translate-float-float-) | Belirtilen çeviri vektörünü bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Belirtilen çeviri vektörünü bu Matrix'e belirtilen sırada uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix sınıfının yeni bir örneğini birim matris olarak başlatır.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Matrix sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 X Eğimi |
| m22 | float | m11 M22 Y Ölçeği |
| m31 | float | m02 M31 X Çevirme |
| m32 | float | m12 M32 Y Çevirme |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Matrix sınıfının bir kopyasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | kopyalama için temel matris |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Aspose.Imaging.Matrix sınıfının yeni bir örneğini, belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Dönüştürülecek dikdörtgeni temsil eden bir Aspose.Imaging.RectangleF yapısı. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç adet Aspose.Imaging.PointF yapısından oluşan bir dizi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Aspose.Imaging.Matrix sınıfının yeni bir örneğini, belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Dönüştürülecek dikdörtgeni temsil eden bir Aspose.Imaging.Rectangle yapısı. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Üç adet Aspose.Imaging.Point yapısından oluşan bir dizi, dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eder. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, normalde sağ el koordinat sistemini sol el sistemine değiştiren bir eksen etrafında ayna yansıtması (flip) yaptığını gösterir. Sağ el koordinat sistemi, pozitif X ekseninin pozitif Y eksenini örtmek üzere saat yönünün tersine döndüğü, başparmağınıza baktığınızda sağ elinizin parmaklarının kıvrıldığı yönle benzer bir sistemdir. Sol el koordinat sistemi ise pozitif X ekseninin pozitif Y eksenini örtmek üzere saat yönünde döndüğü, sol elinizin parmaklarının kıvrıldığı yönle benzer bir sistemdir. Uygun bir ayarlama dönüşü sağlandığında tüm flip açıları aynı olduğu için orijinal yansıtma veya ayna dönüşümünün açısını belirlemenin matematiksel bir yolu yoktur. NOT: TypeFlip, GENERAL\_TRANSFORM genel kullanıma sunulduktan sonra eklendi ve bayrak bitleri dış kodlarda ikili uyumsuzluk yaratmadan yeniden numaralandırılamadı.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, keyfi bir açıyla döndürme yaptığını gösterir. Döndürme, vektörün uzunluğunu değiştirmeden, vektörün orijinal yönünden bağımsız olarak vektörlerin açılarını aynı miktarda değiştirir. Bu bayrak biti, şununla karşılıklı olarak dışlayıcıdır.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Genel bir ölçek, dik vektörler arasındaki açıyı değiştirmeden, vektörlerin uzunluğunu x ve y yönlerinde farklı miktarlarda çarpar. Bu bayrak biti, TypeUniformScale bayrağı ile karşılıklı olarak dışlayıcıdır.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Bu sabit, bu nesne tarafından tanımlanan dönüşümün girdi koordinatlarını keyfi bir şekilde dönüştürdüğünü gösterir. Eğer bu dönüşüm yukarıdaki sabitlerden biriyle sınıflandırılabiliyorsa, tür ya TypeIdentity sabiti ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Bir kimlik dönüşümü, çıktı koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu dönüşümdür. Bu dönüşüm kimlik dönüşümü dışında bir şey ise, tür ya GENERAL\_TRANSFORM sabiti ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Bu sabit, döndürme bayrak bitlerinden herhangi biri için bir bit maskesidir.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, 90 derecenin katları kadar bir çeyrek dönüşüm (quadrant rotation) yaptığını gösterir. Döndürme, vektörün uzunluğunu değiştirmeden, vektörün orijinal yönünden bağımsız olarak vektörlerin açılarını aynı miktarda değiştirir. Bu bayrak biti, TypeGeneralRotation bayrağı ile karşılıklı olarak dışlayıcıdır.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Bir çevirme, vektörlerin uzunluğunu veya açısını değiştirmeden, x ve y eksenlerinde koordinatları sabit bir miktar hareket ettirir.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Tekdüzen bir ölçek, vektörlerin uzunluğunu x ve y yönlerinde aynı miktarda çarpar ve vektörler arasındaki açıyı değiştirmez. Bu bayrak biti, TypeGeneralScale bayrağı ile karşılıklı olarak dışlayıcıdır.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen  System.Object  bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak System.Object. |

**Returns:**
boolean - belirtilen System.Object bu örnek ile eşitse true; aksi takdirde false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Matris elemanlarının bir kopyasını alır.

**Returns:**
float[] - Bir matris öğesi kopyası.
### getM11() {#getM11--}
```
public float getM11()
```


İlk satır ilk sütundaki matris öğesini alır. X ekseni boyunca ölçeği temsil eder.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


İlk satır ikinci sütundaki matris öğesini alır. Y ekseni boyunca kaydırmayı (eğimi) temsil eder.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


İkinci satır birinci sütundaki matris elemanını alır. X ekseni boyunca kayma temsil eder.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


İkinci satır ikinci sütundaki matris elemanını alır. Y ekseni boyunca ölçekleme temsil eder.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Üçüncü satır birinci sütundaki matris elemanını alır. X ekseni boyunca çevirme temsil eder.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Üçüncü satır birinci sütundaki matris elemanını alır. Y ekseni boyunca çevirme temsil eder.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygun.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


İki matrisin eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | Karşılaştırılacak ilk matris. |
| b | [Matrix](../../com.aspose.psd/matrix) | Karşılaştırılacak ikinci matris. |

**Returns:**
boolean - Matrisler eşitse True.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Bu `AffineTransform` bir birim dönüşümse `true` döndürür.

**Returns:**
boolean - `true` eğer bu `AffineTransform` bir birim dönüşümse; aksi takdirde `false`.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Çarpma yapılacak matris. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | tx. tx. tx. |
| order | int | Sıra. Sıra. Sıra. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Bu Matrix'i birim matrisin elemanlarına sahip olacak şekilde sıfırlar.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir döndürme uygular, orijinde (sıfır x ve y koordinatları) varsayılan (Prepend) sırada.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Döndürme açısı. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir döndürme uygular, orijinde (sıfır x ve y koordinatları) belirtilen sırada.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Döndürme açısı. |
| order | int | Matris sırası. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Belirtilen nokta etrafında saat yönünde bir döndürme uygular, bu Matrix'i varsayılan (Prepend) sırada.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Açı. |
| point | [PointF](../../com.aspose.psd/pointf) | Nokta. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Belirtilen nokta etrafında saat yönünde bir döndürme uygular, bu Matrix'i belirtilen sırada.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Açı. |
| point | [PointF](../../com.aspose.psd/pointf) | Nokta. |
| order | int | Sıra. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e belirtilen sırayı kullanarak uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float | X ölçeği. |
| scaleY | float | Y ölçeği. |
| order | int | Sıra. |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir  System.String  döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir System.String.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Bu Matrix tarafından temsil edilen geometrik dönüşümü belirtilen bir nokta dizisine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Belirtilen çeviri vektörünü bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Belirtilen çeviri vektörünü bu Matrix'e belirtilen sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| offsetX | float | Offset X. |
| offsetY | float | Offset Y. |
| order | int | Sıra. |

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

