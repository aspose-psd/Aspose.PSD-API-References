---
title: "IPlacedLayerResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD dosyasındaki yerleştirilmiş bir katman hakkında bilgi içeren IPlacedLayerResource arayüzünü tanımlar."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

IPlacedLayerResource arayüzünü tanımlar; bu arayüz PSD dosyasındaki yerleştirilmiş bir katman hakkında bilgi içerir. Adobe\ufffd Photoshop\ufffd görüntülerinde PlLd, Sold ve Sole kaynaklarını işaretlemek için kullanılan bir işaretleme arayüzüdür. Adobe\ufffd Photoshop\ufffd görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır. |
| [getBottom()](#getBottom--) | PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır. |
| [getBounds()](#getBounds--) | PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [getItems()](#getItems--) | Warp öğeleri alınır veya ayarlanır. |
| [getLeft()](#getLeft--) | PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır. |
| [getPageNumber()](#getPageNumber--) | PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır. |
| [getPerspective()](#getPerspective--) | PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır. |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır. |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır. |
| [getRight()](#getRight--) | PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır. |
| [getTop()](#getTop--) | PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır. |
| [getTotalPages()](#getTotalPages--) | PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır. |
| [getTransformMatrix()](#getTransformMatrix--) | PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır. |
| [getUOrder()](#getUOrder--) | PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır. |
| [getUniqueId()](#getUniqueId--) | PSD görüntüsündeki yerleştirilmiş akıllı nesne katmanının küresel benzersiz tanımlayıcısını alır veya ayarlar. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar. |
| [getValue()](#getValue--) | PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar. |
| [getVersion()](#getVersion--) | PSD dosyasındaki yerleştirilmiş katmanın sürümünü alır, genellikle 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [isCustom()](#isCustom--) | Bu örneğin bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır. |
| [setBottom(double value)](#setBottom-double-) | PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır. |
| [setCustom(boolean value)](#setCustom-boolean-) | Bu örneğin bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Warp öğeleri alınır veya ayarlanır. |
| [setLeft(double value)](#setLeft-double-) | PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır. |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır. |
| [setPerspective(double value)](#setPerspective-double-) | PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır. |
| [setRight(double value)](#setRight-double-) | PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır. |
| [setTop(double value)](#setTop-double-) | PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır. |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır. |
| [setUOrder(int value)](#setUOrder-int-) | PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD görüntüsündeki yerleştirilmiş akıllı nesne katmanının küresel benzersiz tanımlayıcısını alır veya ayarlar. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar. |
| [setValue(double value)](#setValue-double-) | PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın anti-alias politikası.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın alt konumu.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sınırları.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır.

Değer: Yatay ağ noktalarının ölçü birimi.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Warp öğeleri alınır veya ayarlanır.

Değer: Bükülme öğeleri.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sol konumu.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sayfa numarası.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın perspektif değeri.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın diğer perspektif değeri.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır.

Değer: Yerleştirilen katmanın türü.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sağ konumu.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın üst konumu.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın toplam sayfa sayısı.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır.

Değer: Yerleştirilen katmanın dönüşüm matrisi.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın U sırası değeri.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


PSD görüntüsündeki yerleştirilmiş akıllı nesne katmanının küresel benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Yerleştirilen katmanın benzersiz tanımlayıcısı.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın V sırası değeri.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın bükülme değeri.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


PSD dosyasındaki yerleştirilmiş katmanın sürümünü alır, genellikle 3-5.

Değer: Yerleştirilmiş veya akıllı nesne katmanının sürümü.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Dikey ağ noktalarının ölçü birimini alır veya ayarlar.

Değer: Dikey ağ noktalarının ölçü birimi.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Bu örnek bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. true ise ağ noktalarını içerir. false olarak ayarlanırsa ağ noktalarını siler.

Değer:  true  eğer yerleştirilmiş veya akıllı nesne katman kaynağı özel stile sahipse; aksi takdirde  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın anti-alias politikası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın alt konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sınırları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Bu örnek bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. true ise ağ noktalarını içerir. false olarak ayarlanırsa ağ noktalarını siler.

Değer:  true  eğer yerleştirilmiş veya akıllı nesne katman kaynağı özel stile sahipse; aksi takdirde  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır.

Değer: Yatay ağ noktalarının ölçü birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Warp öğeleri alınır veya ayarlanır.

Değer: Bükülme öğeleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sol konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sayfa numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın perspektif değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın diğer perspektif değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır.

Değer: Yerleştirilen katmanın türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sağ konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın üst konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın toplam sayfa sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır.

Değer: Yerleştirilen katmanın dönüşüm matrisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın U sırası değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


PSD görüntüsündeki yerleştirilmiş akıllı nesne katmanının küresel benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Yerleştirilen katmanın benzersiz tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın V sırası değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın bükülme değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Dikey ağ noktalarının ölçü birimini alır veya ayarlar.

Değer: Dikey ağ noktalarının ölçü birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

