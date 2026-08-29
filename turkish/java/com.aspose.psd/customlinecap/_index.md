---
title: "CustomLineCap"
second_title: "Java için Aspose.PSD API Referansı"
description: "Özel kullanıcı tanımlı bir çizgi ucunu kapsüller."
type: docs
weight: 34
url: /tr/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Özel kullanıcı tanımlı bir çizgi ucunu kapsüller.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Belirtilen ana hat ve dolgu ile CustomLineCap sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Belirtilen mevcut LineCap numaralandırmasından belirtilen ana hat ve dolgu ile CustomLineCap sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Belirtilen mevcut LineCap numaralandırmasından belirtilen ana hat, dolgu ve iç boşluk ile CustomLineCap sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Bu CustomLineCap'in temel alındığı LineCap numaralandırmasını alır. |
| [getBaseInset()](#getBaseInset--) | Kap ile çizgi arasındaki mesafeyi alır. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Özel kap için dolguyu tanımlayan nesneyi alır. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Bu özel kapa oluşan çizgileri başlatmak ve sonlandırmak için kullanılan kapları alır. |
| [getStrokeJoin()](#getStrokeJoin--) | Bu CustomLineCap nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirleyen LineJoin numaralandırmasını alır. |
| [getStrokePath()](#getStrokePath--) | Özel kap için ana hatı tanımlayan nesneyi alır. |
| [getWidthScale()](#getWidthScale--) | System.Drawing.Pen nesnesinin genişliğine göre bu CustomLineCap sınıf nesnesinin ölçekleneceği miktarı alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Bu CustomLineCap'in temel alındığı LineCap numaralandırmasını ayarlar. |
| [setBaseInset(float value)](#setBaseInset-float-) | Kap ile çizgi arasındaki mesafeyi ayarlar. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Özel kap için dolguyu tanımlayan nesneyi ayarlar. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Bu özel kapa oluşan çizgileri başlatmak ve sonlandırmak için kullanılan kapları ayarlar. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Bu CustomLineCap nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirleyen LineJoin numaralandırmasını ayarlar. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Özel kap için ana hatı tanımlayan nesneyi ayarlar. |
| [setWidthScale(float value)](#setWidthScale-float-) | System.Drawing.Pen nesnesinin genişliğine göre bu CustomLineCap sınıf nesnesinin ölçekleneceği miktarı ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Belirtilen ana hat ve dolgu ile CustomLineCap sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için dolguyu tanımlayan bir GraphicsPath nesnesi. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için ana hatı tanımlayan bir GraphicsPath nesnesi. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Belirtilen mevcut LineCap numaralandırmasından belirtilen ana hat ve dolgu ile CustomLineCap sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için dolguyu tanımlayan bir GraphicsPath nesnesi. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için ana hatı tanımlayan bir GraphicsPath nesnesi. |
| baseCap | int | Özel kapa oluşturulacak çizgi kapağı. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Belirtilen mevcut LineCap numaralandırmasından belirtilen ana hat, dolgu ve iç boşluk ile CustomLineCap sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için dolguyu tanımlayan bir GraphicsPath nesnesi. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için ana hatı tanımlayan bir GraphicsPath nesnesi. |
| baseCap | int | Özel kapa oluşturulacak çizgi kapağı. |
| baseInset | float | Kap ile çizgi arasındaki mesafe. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Bu CustomLineCap'in temel alındığı LineCap numaralandırmasını alır.

**Returns:**
int - Bu CustomLineCap'in temel alındığı LineCap numaralandırması.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Kap ile çizgi arasındaki mesafeyi alır.

**Returns:**
float - Kap başlangıcı ile satır sonu arasındaki mesafe.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Özel kap için dolguyu tanımlayan nesneyi alır.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Bu özel kapa oluşan çizgileri başlatmak ve sonlandırmak için kullanılan kapları alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startCap | int[] | Bu kap içinde bir satırın başlangıcında kullanılan  LineCap  enumarasyonu. |
| endCap | int[] | Bu kap içinde bir satırın sonunda kullanılan  LineCap  enumarasyonu. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Bu CustomLineCap nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirleyen LineJoin numaralandırmasını alır.

**Returns:**
int - Bu  CustomLineCap  nesnesinin satırları birleştirmek için kullandığı  LineJoin  enumarasyonu.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Özel kap için ana hatı tanımlayan nesneyi alır.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


System.Drawing.Pen nesnesinin genişliğine göre bu CustomLineCap sınıf nesnesinin ölçekleneceği miktarı alır.

**Returns:**
float - Kapın ölçeklendirileceği miktar.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Bu CustomLineCap'in temel alındığı LineCap numaralandırmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  CustomLineCap  nesnesinin dayandığı  LineCap  enumarasyonu. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Kap ile çizgi arasındaki mesafeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kap başlangıcı ile satır sonu arasındaki mesafe. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Özel kap için dolguyu tanımlayan nesneyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kap için doldurmayı tanımlayan nesne. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Bu özel kapa oluşan çizgileri başlatmak ve sonlandırmak için kullanılan kapları ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startCap | int | Bu kap içinde bir satırın başlangıcında kullanılan  LineCap  enumarasyonu. |
| endCap | int | Bu kap içinde bir satırın sonunda kullanılan  LineCap  enumarasyonu. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Bu CustomLineCap nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirleyen LineJoin numaralandırmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  CustomLineCap  nesnesinin satırları birleştirmek için kullandığı  LineJoin  enumarasyonu. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Özel kap için ana hatı tanımlayan nesneyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | Özel kapın ana hatlarını tanımlayan nesne. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


System.Drawing.Pen nesnesinin genişliğine göre bu CustomLineCap sınıf nesnesinin ölçekleneceği miktarı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Kapın ölçeklendirileceği miktar. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

