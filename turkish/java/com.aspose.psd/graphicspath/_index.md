---
title: "GraphicsPath"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bağlantılı çizgi ve eğrilerden oluşan bir seriyi temsil eder."
type: docs
weight: 50
url: /tr/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Bağlantılı çizgiler ve eğriler serisini temsil eder. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) |   GraphicsPath  sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) |   GraphicsPath  sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) |   GraphicsPath  sınıfının yeni bir örneğini başlatır. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) |   GraphicsPath  sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Yeni bir şekil ekler. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Yeni şekiller ekler. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Belirtilen  com.aspose.psd.GraphicsPath  öğesini bu yola ekler. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Belirtilen  com.aspose.psd.GraphicsPath  öğesini bu yola ekler. |
| [deepClone()](#deepClone--) | Bu grafik yolunun derin bir kopyasını oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Bu yoldaki her eğriyi bağlantılı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Belirtilen dönüşümü uygular ve ardından bu  com.aspose.psd.GraphicsPath  içindeki her eğriyi bağlantılı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Bu  com.aspose.psd.GraphicsPath  içindeki her eğriyi bağlantılı çizgi segmentlerinden oluşan bir diziye dönüştürür. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır veya ayarlar. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Nesnenin sınırlarını alır. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Yol figürlerini alır. |
| [getFillMode()](#getFillMode--) | Bu  com.aspose.psd.GraphicsPath  içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir  com.aspose.psd.FillMode  numaralandırmasını alır. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.graphics  görünür kırpma bölgesinde bu  com.aspose.psd.GraphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  içinde olup olmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Bir şekil kaldırır. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Şekilleri kaldırır. |
| [reset()](#reset--) | Grafik yolunu boşaltır ve  com.aspose.psd.FillMode  değerini  F:com.aspose.psd.fillMode.alternate  olarak ayarlar. |
| [reverse()](#reverse--) | Bu com.aspose.psd.graphicsPath içindeki her şeklin figür, şekil ve nokta sırasını tersine çevirir. |
| [setFillMode(int value)](#setFillMode-int-) | Bu com.aspose.psd.GraphicsPath içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir com.aspose.psd.FillMode enum değerini ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular. |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Yola ek bir kontur ekler. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | com.aspose.psd.graphicsPath öğesine ek bir kontur ekler. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Bu com.aspose.psd.GraphicsPath'i, belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


  GraphicsPath  sınıfının yeni bir örneğini başlatır.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


  GraphicsPath  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Başlatılacak figürler. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


  GraphicsPath  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Başlatılacak figürler. |
| fillMode | int | Doldurma modu. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


  GraphicsPath  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillMode | int | Doldurma modu. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Yeni bir şekil ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Eklenecek figür. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Yeni şekiller ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Eklenecek figürler. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Belirtilen  com.aspose.psd.GraphicsPath  öğesini bu yola ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Eklenecek com.aspose.psd.GraphicsPath. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Belirtilen  com.aspose.psd.GraphicsPath  öğesini bu yola ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Eklenecek com.aspose.psd.GraphicsPath. |
| connect | boolean | Eklenen yoldaki ilk figürün bu yoldaki son figürün bir parçası olup olmadığını belirten bir Boolean değer. true değeri, eklenen yoldaki ilk figürün bu yoldaki son figürün bir parçası olduğunu belirtir. false değeri, eklenen yoldaki ilk figürün bu yoldaki son figürden ayrı olduğunu belirtir. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Bu grafik yolunun derin bir kopyasını oluşturur.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


Bu yoldaki her eğriyi bağlantılı çizgi segmentlerinden oluşan bir diziye dönüştürür.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Belirtilen dönüşümü uygular ve ardından bu  com.aspose.psd.GraphicsPath  içindeki her eğriyi bağlantılı çizgi segmentlerinden oluşan bir diziye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Bu com.aspose.psd.GraphicsPath'i düzleştirmeden önce dönüştürmek için kullanılacak bir com.aspose.psd.Matrix. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Bu  com.aspose.psd.GraphicsPath  içindeki her eğriyi bağlantılı çizgi segmentlerinden oluşan bir diziye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Bu com.aspose.psd.GraphicsPath'i düzleştirmeden önce dönüştürmek için kullanılacak bir com.aspose.psd.Matrix. |
| flatness | float | Eğri ile düzleştirilmiş yaklaşımı arasındaki izin verilen maksimum hatayı belirler. Varsayılan değer 0.25'tir. Flatness değerini azaltmak, yaklaşımdaki çizgi segment sayısını artırır. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır veya ayarlar.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](../../com.aspose.psd/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Yol figürlerini alır.

**Returns:**
com.aspose.psd.Figure[] - Yol figürleri.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Bu  com.aspose.psd.GraphicsPath  içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir  com.aspose.psd.FillMode  numaralandırmasını alır.

**Returns:**
int - Doldurma modu. Bu com.aspose.psd.GraphicsPath içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirten bir com.aspose.psd.FillMode enum değeri.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Test edilecek konumu belirten bir com.aspose.psd.Point. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |

**Returns:**
boolean - Belirtilen nokta, belirtilen com.aspose.psd.Pen ile çizildiğinde bu com.aspose.psd.GraphicsPath'in konturu içinde yer alıyorsa true döner; aksi takdirde false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Test edilecek konumu belirten bir com.aspose.psd.Point. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Belirtilen nokta, belirtilen com.aspose.psd.Pen ile çizildiğinde bu com.aspose.psd.GraphicsPath'in konturu içinde yer alıyorsa true döner; aksi takdirde false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Test edilecek konumu belirten bir com.aspose.psd.PointF. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |

**Returns:**
boolean - Belirtilen nokta, belirtilen com.aspose.psd.Pen ile çizildiğinde bu com.aspose.psd.GraphicsPath'in konturu içinde yer alıyorsa true döner; aksi takdirde false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Test edilecek konumu belirten bir com.aspose.psd.PointF. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath'in (belirtilen com.aspose.psd.Pen ile çizilen) dış hatının içinde (altında) bulunması durumunda true döndürür; aksi takdirde false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |

**Returns:**
boolean - Belirtilen nokta, belirtilen com.aspose.psd.Pen ile çizildiğinde bu com.aspose.psd.GraphicsPath'in konturu içinde yer alıyorsa true döner; aksi takdirde false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath'in (belirtilen com.aspose.psd.Pen ile çizilen) dış hatının içinde (altında) bulunması durumunda true döndürür; aksi takdirde false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.pen  ile çizildiğinde bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |

**Returns:**
boolean - Belirtilen nokta, belirtilen com.aspose.psd.Pen ile çizildiğinde bu com.aspose.psd.GraphicsPath'in konturu içinde yer alıyorsa true döner; aksi takdirde false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.Pen  ile çizildiğinde ve belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  dış hattının içinde (altında) olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| pen | [Pen](../../com.aspose.psd/pen) | Test edilecek com.aspose.psd.Pen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Belirtilen nokta, belirtilen com.aspose.psd.Pen ile çizildiğinde bu com.aspose.psd.GraphicsPath'in konturu içinde yer alıyorsa true döner; aksi takdirde false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Test edilecek noktayı temsil eden bir com.aspose.psd.Point. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Test edilecek noktayı temsil eden bir com.aspose.psd.Point. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Test edilecek noktayı temsil eden bir com.aspose.psd.PointF. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Test edilecek noktayı temsil eden bir com.aspose.psd.PointF. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.graphics  görünür kırpma bölgesinde bu  com.aspose.psd.GraphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Belirtilen noktanın bu  com.aspose.psd.graphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.graphics  kullanılarak bu  com.aspose.psd.GraphicsPath  içinde olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Görünürlük testi yapılacak com.aspose.psd.Graphics. |

**Returns:**
boolean - Bu yöntem, belirtilen noktanın bu com.aspose.psd.GraphicsPath içinde bulunması durumunda true döndürür; aksi takdirde false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Bir şekil kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Kaldırılacak şekil. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Şekilleri kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Kaldırılacak şekiller. |

### reset() {#reset--}
```
public void reset()
```


Grafik yolunu boşaltır ve  com.aspose.psd.FillMode  değerini  F:com.aspose.psd.fillMode.alternate  olarak ayarlar.

### reverse() {#reverse--}
```
public void reverse()
```


Bu com.aspose.psd.graphicsPath içindeki her şeklin figür, şekil ve nokta sırasını tersine çevirir.

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Bu com.aspose.psd.GraphicsPath içindeki şekillerin iç kısımlarının nasıl doldurulacağını belirleyen bir com.aspose.psd.FillMode enum değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Doldurma modu. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Belirtilen dönüşümü şekle uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Uygulanacak dönüşüm. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect tarafından tanımlanan dikdörtgenin dönüştürüldüğü paralelkenarı tanımlayan com.aspose.psd.PointF yapılarını içeren bir dizi. Dizi üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir com.aspose.psd.RectangleF. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect tarafından tanımlanan dikdörtgenin dönüştürüldüğü paralelkenarı tanımlayan com.aspose.psd.PointF yapılarını içeren bir dizi. Dizi üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir com.aspose.psd.RectangleF. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir com.aspose.psd.Matrix. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect tarafından tanımlanan dikdörtgenin dönüştürüldüğü paralelkenarı tanımlayan com.aspose.psd.PointF yapılarını içeren bir dizi. Dizi üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir com.aspose.psd.RectangleF. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir com.aspose.psd.Matrix. |
| warpMode | int | Bu warp işleminin perspektif mi yoksa bilineer mod mu kullandığını belirten bir com.aspose.psd.WarpMode enumarasyonu. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Bu com.aspose.psd.graphicsPath üzerine bir dikdörtgen ve paralelkenar ile tanımlanan bir bükme dönüşümü uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | srcRect tarafından tanımlanan dikdörtgenin dönüştürüldüğü paralelkenarı tanımlayan com.aspose.psd.PointF yapılarını içeren bir dizi. Dizi üç veya dört eleman içerebilir. Dizi üç eleman içeriyorsa, paralelkenarın sağ‑alt köşesi ilk üç nokta ile ima edilir. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | destPoints tarafından tanımlanan paralelkenara dönüştürülen dikdörtgeni temsil eden bir com.aspose.psd.RectangleF. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Yola uygulanacak geometrik dönüşümü belirten bir com.aspose.psd.Matrix. |
| warpMode | int | Bu warp işleminin perspektif mi yoksa bilineer mod mu kullandığını belirten bir com.aspose.psd.WarpMode enumarasyonu. |
| flatness | float | 0 ile 1 arasında bir değer, sonuç yolunun ne kadar düz olduğunu belirtir. Daha fazla bilgi için com.aspose.psd.GraphicsPath.flatten yöntemlerine bakın. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Yola ek bir kontur ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Yolun orijinal dış hattı ile bu yöntemin oluşturduğu yeni dış hat arasındaki genişliği belirten bir com.aspose.psd.Pen. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


com.aspose.psd.graphicsPath öğesine ek bir kontur ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Yolun orijinal dış hattı ile bu yöntemin oluşturduğu yeni dış hat arasındaki genişliği belirten bir com.aspose.psd.Pen. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Genişletmeden önce yola uygulanacak dönüşümü belirten bir com.aspose.psd.Matrix. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Bu com.aspose.psd.GraphicsPath'i, belirtilen kalemle çizildiğinde doldurulan alanı çevreleyen eğrilerle değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Yolun orijinal dış hattı ile bu yöntemin oluşturduğu yeni dış hat arasındaki genişliği belirten bir com.aspose.psd.Pen. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Genişletmeden önce yola uygulanacak dönüşümü belirten bir com.aspose.psd.Matrix. |
| flatness | float | Eğrilerin düzlüğünü belirten bir değer. |

