---
title: "Region"
second_title: "Java için Aspose.PSD API Referansı"
description: "Dikdörtgenler ve yollarla oluşturulmuş bir grafik şeklinin iç kısmını tanımlar."
type: docs
weight: 90
url: /tr/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Dikdörtgenler ve yollarla oluşturulmuş bir grafik şeklinin iç kısmını tanımlar. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Region()](#Region--) | Yeni bir  T:Aspose.Imaging.Region  başlatır. |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Belirtilen  T:Aspose.Imaging.RectangleF  yapısından yeni bir  T:Aspose.Imaging.Region  başlatır. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Belirtilen  T:Aspose.Imaging.Rectangle  yapısından yeni bir  T:Aspose.Imaging.Region  başlatır. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Belirtilen  T:Aspose.Imaging.GraphicsPath  ile yeni bir  T:Aspose.Imaging.Region  başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.GraphicsPath  öğesinin bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller. |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.Rectangle  yapısının bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller. |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.RectangleF  yapısının bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.Region  öğesinin bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller. |
| [deepClone()](#deepClone--) | Bu  com.aspose.psd.region  öğesinin tam bir derin kopyasını oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.graphicsPath  ile kesişmeyen iç kısmının yalnızca o bölümünü içerecek şekilde günceller. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.Rectangle  yapısının iç kısmının kesişmeyen yalnızca o bölümünü içerecek şekilde günceller. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.RectangleF  yapısının iç kısmının kesişmeyen yalnızca o bölümünü içerecek şekilde günceller. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.region  ile kesişmeyen iç kısmının yalnızca o bölümünü içerecek şekilde günceller. |
| [getActions_internalized()](#getActions-internalized--) | Bölge eylemlerini alır. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.graphicsPath  ile kesişimi olacak şekilde günceller. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.Rectangle  yapısı ile kesişimi olacak şekilde günceller. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.RectangleF  yapısı ile kesişimi olacak şekilde günceller. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.region  ile kesişimi olacak şekilde günceller. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Bu  com.aspose.psd.Region  nesnesinin, belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Belirtilen  com.aspose.psd.Region  nesnesinin, belirtilen çizim yüzeyinde bu  com.aspose.psd.Region  nesnesiyle aynı olup olmadığını test eder. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Bu  com.aspose.psd.Region  nesnesinin, belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Belirtilen  com.aspose.psd.Point  yapısının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Belirtilen  com.aspose.psd.Point  yapısının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Belirtilen  com.aspose.psd.PointF  yapısının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Belirtilen  com.aspose.psd.PointF  yapısının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Belirtilen  com.aspose.psd.Rectangle  yapısının herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Belirtilen  com.aspose.psd.Rectangle  yapısının herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Belirtilen  com.aspose.psd.RectangleF  yapısının herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Belirtilen  com.aspose.psd.RectangleF  yapısının herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Belirtilen noktanın bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Belirtilen dikdörtgenin herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Belirtilen dikdörtgenin herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Belirtilen noktanın, belirtilen  com.aspose.psd.Graphics  nesnesi kullanılarak çizildiğinde bu  com.aspose.psd.Region  nesnesi içinde bulunup bulunmadığını test eder. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Belirtilen dikdörtgenin herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Belirtilen dikdörtgenin herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder. |
| [makeEmpty()](#makeEmpty--) | Bu  com.aspose.psd.Region  nesnesini boş bir iç kısım ile başlatır. |
| [makeInfinite()](#makeInfinite--) | Bu  com.aspose.psd.Region  nesnesini sonsuz bir iç kısım ile başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Değişiklik olduğunda bölgeyi alır veya ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Bu com.aspose.psd.Region belirtilen com.aspose.psd.matrix ile dönüştürür. |
| [translate(float dx, float dy)](#translate-float-float-) | Bu com.aspose.psd.Region koordinatlarını belirtilen miktar kadar kaydırır. |
| [translate(int dx, int dy)](#translate-int-int-) | Bu com.aspose.psd.Region koordinatlarını belirtilen miktar kadar kaydırır. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.graphicsPath'in birleşimine günceller. |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.Rectangle yapısının birleşimine günceller. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.RectangleF yapısının birleşimine günceller. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.region'in birleşimine günceller. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.graphicsPath'in kesişimini çıkartarak birleşime günceller. |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.Rectangle yapısının kesişimini çıkartarak birleşime günceller. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.RectangleF yapısının kesişimini çıkartarak birleşime günceller. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.region'in kesişimini çıkartarak birleşime günceller. |
### Region() {#Region--}
```
public Region()
```


Yeni bir  T:Aspose.Imaging.Region  başlatır.

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Belirtilen  T:Aspose.Imaging.RectangleF  yapısından yeni bir  T:Aspose.Imaging.Region  başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Yeni T:Aspose.Imaging.Region'in iç kısmını tanımlayan bir T:Aspose.Imaging.RectangleF yapısı. |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Belirtilen  T:Aspose.Imaging.Rectangle  yapısından yeni bir  T:Aspose.Imaging.Region  başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Yeni T:Aspose.Imaging.Region'in iç kısmını tanımlayan bir T:Aspose.Imaging.Rectangle yapısı. |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Belirtilen  T:Aspose.Imaging.GraphicsPath  ile yeni bir  T:Aspose.Imaging.Region  başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Yeni T:Aspose.Imaging.Region'i tanımlayan bir T:Aspose.Imaging.GraphicsPath. |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.GraphicsPath  öğesinin bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Bu com.aspose.psd.region'i tamamlamak için com.aspose.psd.GraphicsPath. |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.Rectangle  yapısının bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Bu com.aspose.psd.region'i tamamlamak için com.aspose.psd.Rectangle yapısı. |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.RectangleF  yapısının bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Bu com.aspose.psd.region'i tamamlamak için com.aspose.psd.RectangleF yapısı. |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.Region  öğesinin bu  com.aspose.psd.region  ile kesişmeyen kısmını içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Bu com.aspose.psd.Region nesnesini tamamlamak için com.aspose.psd.Region nesnesi. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Bu  com.aspose.psd.region  öğesinin tam bir derin kopyasını oluşturur.

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.graphicsPath  ile kesişmeyen iç kısmının yalnızca o bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Bu com.aspose.psd.region'den hariç tutmak için com.aspose.psd.GraphicsPath. |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.Rectangle  yapısının iç kısmının kesişmeyen yalnızca o bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Bu com.aspose.psd.region'den hariç tutmak için com.aspose.psd.Rectangle yapısı. |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Bu  com.aspose.psd.Region  öğesini, belirtilen  com.aspose.psd.RectangleF  yapısının iç kısmının kesişmeyen yalnızca o bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Bu com.aspose.psd.region'den hariç tutmak için com.aspose.psd.RectangleF yapısı. |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.region  ile kesişmeyen iç kısmının yalnızca o bölümünü içerecek şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Bu com.aspose.psd.region'den hariç tutmak için com.aspose.psd.Region. |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Bölge eylemlerini alır.

**Returns:**
com.aspose.internal.RegionAction[] - Bölge eylemleri.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.graphicsPath  ile kesişimi olacak şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Bu com.aspose.psd.region ile kesişmek için com.aspose.psd.GraphicsPath. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.Rectangle  yapısı ile kesişimi olacak şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Bu com.aspose.psd.region ile kesişmek için com.aspose.psd.Rectangle yapısı. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.RectangleF  yapısı ile kesişimi olacak şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Bu com.aspose.psd.region ile kesişmek için com.aspose.psd.RectangleF yapısı. |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Bu  com.aspose.psd.Region  nesnesini, belirtilen  com.aspose.psd.region  ile kesişimi olacak şekilde günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Bu  com.aspose.psd.Region  bu  com.aspose.psd.region  ile kesişecek. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Bu  com.aspose.psd.Region  nesnesinin, belirtilen çizim yüzeyinde boş bir iç kısmı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  çizim yüzeyini temsil eder. |

**Returns:**
boolean - bu  com.aspose.psd.Region  içi,  g  ile ilişkili dönüşüm uygulandığında boş ise true; aksi takdirde false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Belirtilen  com.aspose.psd.Region  nesnesinin, belirtilen çizim yüzeyinde bu  com.aspose.psd.Region  nesnesiyle aynı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Test edilecek  com.aspose.psd.Region . |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  çizim yüzeyini temsil eder. |

**Returns:**
boolean - dönüşüm  g  parametresiyle uygulandığında bölgenin içi bu bölgenin içiyle aynıysa True; aksi takdirde false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Bu  com.aspose.psd.Region  nesnesinin, belirtilen çizim yüzeyinde sonsuz bir iç kısmı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  çizim yüzeyini temsil eder. |

**Returns:**
boolean - bu  com.aspose.psd.Region  içi,  g  ile ilişkili dönüşüm uygulandığında sonsuz ise true; aksi takdirde false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Belirtilen  com.aspose.psd.Point  yapısının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Test edilecek  com.aspose.psd.Point  yapısı. |

**Returns:**
boolean -  point  bu  com.aspose.psd.Region  içinde bulunuyorsa true; aksi takdirde false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Belirtilen  com.aspose.psd.Point  yapısının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Test edilecek  com.aspose.psd.Point  yapısı. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean -  point  bu  com.aspose.psd.Region  içinde bulunuyorsa true; aksi takdirde false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Belirtilen  com.aspose.psd.PointF  yapısının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Test edilecek  com.aspose.psd.PointF  yapısı. |

**Returns:**
boolean -  point  bu  com.aspose.psd.Region  içinde bulunuyorsa true; aksi takdirde false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Belirtilen  com.aspose.psd.PointF  yapısının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Test edilecek  com.aspose.psd.PointF  yapısı. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean -  point  bu  com.aspose.psd.Region  içinde bulunuyorsa true; aksi takdirde false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Belirtilen  com.aspose.psd.Rectangle  yapısının herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Test edilecek  com.aspose.psd.Rectangle  yapısı. |

**Returns:**
boolean - bu metod,  rect  nin herhangi bir kısmı bu  com.aspose.psd.Region  içinde bulunduğunda true döner; aksi takdirde false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Belirtilen  com.aspose.psd.Rectangle  yapısının herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Test edilecek  com.aspose.psd.Rectangle  yapısı. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean -  rect  nin herhangi bir kısmı bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Belirtilen  com.aspose.psd.RectangleF  yapısının herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Test edilecek  com.aspose.psd.RectangleF  yapısı. |

**Returns:**
boolean -  rect  nin herhangi bir kısmı bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Belirtilen  com.aspose.psd.RectangleF  yapısının herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Test edilecek  com.aspose.psd.RectangleF  yapısı. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean -  rect  bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Belirtilen noktanın bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |

**Returns:**
boolean - belirtilen nokta bu  com.aspose.psd.Region  içinde bulunduğunda True; aksi takdirde false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek noktanın x koordinatı. |
| y | float | Test edilecek noktanın y koordinatı. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean - belirtilen nokta bu  com.aspose.psd.Region  içinde bulunduğunda True; aksi takdirde false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Belirtilen dikdörtgenin herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Test edilecek dikdörtgenin genişliği. |
| height | float | Test edilecek dikdörtgenin yüksekliği. |

**Returns:**
boolean - belirtilen dikdörtgenin herhangi bir kısmı bu  com.aspose.psd.Region  nesnesi içinde bulunduğunda true; aksi takdirde false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Belirtilen dikdörtgenin herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Test edilecek dikdörtgenin genişliği. |
| height | float | Test edilecek dikdörtgenin yüksekliği. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean - belirtilen dikdörtgenin herhangi bir kısmı bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Belirtilen noktanın, belirtilen  com.aspose.psd.Graphics  nesnesi kullanılarak çizildiğinde bu  com.aspose.psd.Region  nesnesi içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek noktanın x koordinatı. |
| y | int | Test edilecek noktanın y koordinatı. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean - belirtilen nokta bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Belirtilen dikdörtgenin herhangi bir kısmının bu  com.aspose.psd.region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Test edilecek dikdörtgenin genişliği. |
| height | int | Test edilecek dikdörtgenin yüksekliği. |

**Returns:**
boolean - belirtilen dikdörtgenin herhangi bir kısmı bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Belirtilen dikdörtgenin herhangi bir kısmının, belirtilen  com.aspose.psd.graphics  kullanılarak çizildiğinde bu  com.aspose.psd.Region  içinde bulunup bulunmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Test edilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Test edilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Test edilecek dikdörtgenin genişliği. |
| height | int | Test edilecek dikdörtgenin yüksekliği. |
| g | [Graphics](../../com.aspose.psd/graphics) | Bir  com.aspose.psd.Graphics  grafik bağlamını temsil eder. |

**Returns:**
boolean - belirtilen dikdörtgenin herhangi bir kısmı bu  com.aspose.psd.Region  içinde bulunduğunda true; aksi takdirde false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Bu  com.aspose.psd.Region  nesnesini boş bir iç kısım ile başlatır.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Bu  com.aspose.psd.Region  nesnesini sonsuz bir iç kısım ile başlatır.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Değişiklik olduğunda bölgeyi alır veya ayarlar.

Değer: Değişiklik anındaki bölge.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Bu com.aspose.psd.Region belirtilen com.aspose.psd.matrix ile dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Bu com.aspose.psd.region'ı dönüştürmek için kullanılan com.aspose.psd.Matrix. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Bu com.aspose.psd.Region koordinatlarını belirtilen miktar kadar kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | Bu com.aspose.psd.Region'ı yatay olarak kaydırma miktarı. |
| dy | float | Bu com.aspose.psd.Region'ı dikey olarak kaydırma miktarı. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Bu com.aspose.psd.Region koordinatlarını belirtilen miktar kadar kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | int | Bu com.aspose.psd.Region'ı yatay olarak kaydırma miktarı. |
| dy | int | Bu com.aspose.psd.Region'ı dikey olarak kaydırma miktarı. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.graphicsPath'in birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Bu com.aspose.psd.region ile birleştirilecek com.aspose.psd.GraphicsPath. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.Rectangle yapısının birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Bu com.aspose.psd.region ile birleştirilecek com.aspose.psd.Rectangle yapısı. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.RectangleF yapısının birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Bu com.aspose.psd.region ile birleştirilecek com.aspose.psd.RectangleF yapısı. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.region'in birleşimine günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Bu com.aspose.psd.region ile birleştirilecek com.aspose.psd.Region. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.graphicsPath'in kesişimini çıkartarak birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Bu com.aspose.psd.region ile XOR yapılacak com.aspose.psd.GraphicsPath. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.Rectangle yapısının kesişimini çıkartarak birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Bu com.aspose.psd.region ile XOR yapılacak com.aspose.psd.Rectangle yapısı. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.RectangleF yapısının kesişimini çıkartarak birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Bu com.aspose.psd.region ile XOR yapılacak com.aspose.psd.RectangleF yapısı. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Bu com.aspose.psd.Region'i kendisi ile belirtilen com.aspose.psd.region'in kesişimini çıkartarak birleşime günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Bu com.aspose.psd.region ile XOR yapılacak com.aspose.psd.Region. |

