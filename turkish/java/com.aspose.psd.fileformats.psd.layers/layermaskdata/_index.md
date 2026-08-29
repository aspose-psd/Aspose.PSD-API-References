---
title: "LayerMaskData"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar."
type: docs
weight: 21
url: /tr/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

PSD dosyasındaki katman maskesi verileri hakkında bilgi içeren temel LayerMaskData sınıfını tanımlar. Adobe\\ufffd Photoshop\\ufffd dosyalarını programlı olarak değiştirmeye ve PSD formatı düzenlemesini otomatikleştirmeye yardımcı olabilir. Katmanda yalnızca raster maskesi varsa ImageData raster maske veri baytlarını içerir. Katmanda yalnızca vektör maskesi varsa ImageData vektör maskesinin rasterleştirilmiş (önbelleğe alınmış) veri baytlarını içerir. Katmanda hem raster hem vektör maskeleri varsa ImageData raster maskeyi ve rasterleştirilmiş vektör maskesini birleştirir. ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#setImageData-byte---)) bayt uzunluğu, MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\\#setMaskRectangle-Rectangle-)) özelliklerinin Genişlik \\* Yükseklik değerine eşit olmalıdır. Dikkat, sadece LayerMaskData'yi kaldırmak/eklemek/güncellemek doğru kaydetme için yeterli değildir çünkü kanallar güncellenmez; yine de doğru render sağlayabilir. Bunun için [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\\#addLayerMask-LayerMaskData-) yöntemi kullanılmalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Katman maskesini klonlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Alt katman maskesinin konumunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Katman maskesi veri boyutunu alır. |
| [getDefaultColor()](#getDefaultColor--) | Varsayılan rengi alır veya ayarlar. |
| [getFlags()](#getFlags--) | Katman maskesi bayraklarını alır veya ayarlar. |
| [getHeight_internalized()](#getHeight-internalized--) | Maskenin yüksekliğini alır. |
| [getImageData()](#getImageData--) | PSD dosyasındaki katman maskesi verilerini alır veya ayarlar (vektör maskesi varsa birleştirilmiş/son maske). |
| [getLeft()](#getLeft--) | Sol katman maskesi konumunu alır veya ayarlar. |
| [getMaskRectangle()](#getMaskRectangle--) | PSD dosyasındaki katman maskesinin mask  Rectangle  değerini alır veya ayarlar. |
| [getRight()](#getRight--) | Sağ katman maskesi konumunu alır veya ayarlar. |
| [getTop()](#getTop--) | Üst katman maskesi konumunu alır veya ayarlar. |
| [getWidth_internalized()](#getWidth-internalized--) | Maskenin genişliğini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Belirtilen  StreamContainer  içine [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) kaydeder. |
| [setBottom(int value)](#setBottom-int-) | Alt katman maskesinin konumunu alır veya ayarlar. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Varsayılan rengi alır veya ayarlar. |
| [setFlags(byte value)](#setFlags-byte-) | Katman maskesi bayraklarını alır veya ayarlar. |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD dosyasındaki katman maskesi verilerini alır veya ayarlar (vektör maskesi varsa birleştirilmiş/son maske). |
| [setLeft(int value)](#setLeft-int-) | Sol katman maskesi konumunu alır veya ayarlar. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD dosyasındaki katman maskesinin mask  Rectangle  değerini alır veya ayarlar. |
| [setRight(int value)](#setRight-int-) | Sağ katman maskesi konumunu alır veya ayarlar. |
| [setTop(int value)](#setTop-int-) | Üst katman maskesi konumunu alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Bu örneği klonlar.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Katman maskesini klonlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Maske. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Alt katman maskesinin konumunu alır veya ayarlar.

Değer: Alt katman maskesi konumu.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Katman maskesi veri boyutunu alır.

Değer: Katman maskesi veri boyutu.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Varsayılan rengi alır veya ayarlar.

Değer: Varsayılan renk.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Katman maskesi bayraklarını alır veya ayarlar.

Değer: Katman maskesi bayrakları.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Maskenin yüksekliğini alır.

Değer: Yükseklik.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


PSD dosyasındaki katman maskesi verilerini alır veya ayarlar (vektör maskesi varsa birleştirilmiş/son maske).

Değer: Görüntü verisi.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Sol katman maskesi konumunu alır veya ayarlar.

Değer: Sol katman maskesi konumu.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


PSD dosyasındaki katman maskesinin mask  Rectangle  değerini alır veya ayarlar. Sol, sağ, üst ve alt özelliklerini alır ve  Rectangle  oluşturur.

Değer: Maske dikdörtgeni.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRight() {#getRight--}
```
public final int getRight()
```


Sağ katman maskesi konumunu alır veya ayarlar.

Değer: Sağ katman maskesi konumu.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Üst katman maskesi konumunu alır veya ayarlar.

Değer: Üst katman maskesi konumu.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Maskenin genişliğini alır.

Değer: Genişlik.

**Returns:**
int
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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public abstract void save_internalized(StreamContainer streamContainer)
```


Belirtilen  StreamContainer  içine [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Verilerin kaydedileceği akış konteyneri. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Alt katman maskesinin konumunu alır veya ayarlar.

Değer: Alt katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Varsayılan rengi alır veya ayarlar.

Değer: Varsayılan renk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Katman maskesi bayraklarını alır veya ayarlar.

Değer: Katman maskesi bayrakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


PSD dosyasındaki katman maskesi verilerini alır veya ayarlar (vektör maskesi varsa birleştirilmiş/son maske).

Değer: Görüntü verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Sol katman maskesi konumunu alır veya ayarlar.

Değer: Sol katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


PSD dosyasındaki katman maskesinin mask  Rectangle  değerini alır veya ayarlar. Sol, sağ, üst ve alt özelliklerini alır ve  Rectangle  oluşturur.

Değer: Maske dikdörtgeni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Sağ katman maskesi konumunu alır veya ayarlar.

Değer: Sağ katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Üst katman maskesi konumunu alır veya ayarlar.

Değer: Üst katman maskesi konumu.

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

