---
title: "LayerMaskDataFull"
second_title: "Java için Aspose.PSD API Referansı"
description: "LayerMaskDataFull sınıfını tanımlar; bu sınıf, katmanın hem katman hem de vektör maskeleri olduğu durumda PSD dosyası katmanındaki maske verileri hakkında bilgi içerir."
type: docs
weight: 22
url: /tr/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

LayerMaskDataFull sınıfını tanımlar; bu sınıf, katmanın hem katman hem de vektör maskeleri olduğu zaman PSD dosya katmanındaki maske verileri hakkında bilgi içerir. Aksi takdirde, bir [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) kullanılır. ImageData, raster maskesini ve rasterleştirilmiş vektör maskesini birleştirir. ImageData bayt uzunluğu, MaskRectangle.Width \* MaskRectangle.Height özelliklerine eşit olmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Yeni bir [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Katman maskesini klonlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengini alır veya ayarlar. |
| [getBottom()](#getBottom--) | Alt katman maskesinin konumunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Katman maskesi veri boyutunu alır. |
| [getDefaultColor()](#getDefaultColor--) | Varsayılan rengi alır veya ayarlar. |
| [getEnclosingBottom()](#getEnclosingBottom--) | PSD görüntü katmanındaki kapsayan alt raster maske konumunu alır veya ayarlar. |
| [getEnclosingLeft()](#getEnclosingLeft--) | PSD dosya katmanındaki kapsayan sol raster maske konumunu alır veya ayarlar. |
| [getEnclosingRight()](#getEnclosingRight--) | PSD dosya katmanındaki kapsayan sağ raster maske konumunu alır veya ayarlar. |
| [getEnclosingTop()](#getEnclosingTop--) | PSD görüntü katmanındaki raster maskenin kapsayan üst konumunu alır veya ayarlar. |
| [getFlags()](#getFlags--) | Katman maskesi bayraklarını alır veya ayarlar. |
| [getHeight_internalized()](#getHeight-internalized--) | Maskenin yüksekliğini alır. |
| [getImageData()](#getImageData--) | PSD dosyasındaki katman maskesi verilerini alır veya ayarlar (vektör maskesi varsa birleştirilmiş/son maske). |
| [getLeft()](#getLeft--) | Sol katman maskesi konumunu alır veya ayarlar. |
| [getMaskRectangle()](#getMaskRectangle--) | PSD dosyasındaki katman maskesinin mask  Rectangle  değerini alır veya ayarlar. |
| [getRealFlags()](#getRealFlags--) | Kullanıcı / raster maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. |
| [getRight()](#getRight--) | Sağ katman maskesi konumunu alır veya ayarlar. |
| [getTop()](#getTop--) | Üst katman maskesi konumunu alır veya ayarlar. |
| [getUserMaskData()](#getUserMaskData--) | PSD dosyasındaki bir katmanın kullanıcı (raster) maske verisini alır veya ayarlar. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | PSD görüntü katmanındaki kullanıcı maskesi (kapsayan) dikdörtgenini alır veya ayarlar. |
| [getWidth_internalized()](#getWidth-internalized--) | Maskenin genişliğini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Belirtilen  StreamContainer  içine [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) kaydeder. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Arka plan rengini alır veya ayarlar. |
| [setBottom(int value)](#setBottom-int-) | Alt katman maskesinin konumunu alır veya ayarlar. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Varsayılan rengi alır veya ayarlar. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | PSD görüntü katmanındaki kapsayan alt raster maske konumunu alır veya ayarlar. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | PSD dosya katmanındaki kapsayan sol raster maske konumunu alır veya ayarlar. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | PSD dosya katmanındaki kapsayan sağ raster maske konumunu alır veya ayarlar. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | PSD görüntü katmanındaki raster maskenin kapsayan üst konumunu alır veya ayarlar. |
| [setFlags(byte value)](#setFlags-byte-) | Katman maskesi bayraklarını alır veya ayarlar. |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD dosyasındaki katman maskesi verilerini alır veya ayarlar (vektör maskesi varsa birleştirilmiş/son maske). |
| [setLeft(int value)](#setLeft-int-) | Sol katman maskesi konumunu alır veya ayarlar. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD dosyasındaki katman maskesinin mask  Rectangle  değerini alır veya ayarlar. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Kullanıcı / raster maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. |
| [setRight(int value)](#setRight-int-) | Sağ katman maskesi konumunu alır veya ayarlar. |
| [setTop(int value)](#setTop-int-) | Üst katman maskesi konumunu alır veya ayarlar. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | PSD dosyasındaki bir katmanın kullanıcı (raster) maske verisini alır veya ayarlar. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | PSD görüntü katmanındaki kullanıcı maskesi (kapsayan) dikdörtgenini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Yeni bir [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) sınıfı örneği başlatır.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Arka plan rengini alır veya ayarlar.

Değer: Arka plan rengi.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


PSD görüntü katmanındaki kapsayan alt raster maske konumunu alır veya ayarlar.

Değer: Alt katman maskesi konumu.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


PSD dosya katmanındaki kapsayan sol raster maske konumunu alır veya ayarlar.

Değer: Sol katman maskesi konumu.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


PSD dosya katmanındaki kapsayan sağ raster maske konumunu alır veya ayarlar.

Değer: Sağ katman maskesi konumu.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


PSD görüntü katmanındaki raster maskenin kapsayan üst konumunu alır veya ayarlar.

Değer: Üst katman maskesi konumu.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Kullanıcı / raster maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. Vektör maskesi için Flags özelliği kullanılır.

Değer: Gerçek katman maskesi bayrakları.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


PSD dosyasındaki bir katmanın kullanıcı (raster) maske verisini alır veya ayarlar. (MaskData özelliğinde rasterleştirilmiş bir vektör maskesi vardır).

Değer: PSD görüntüsündeki katman görüntü verisi.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


PSD görüntü katmanındaki kullanıcı maskesi (kapsayan) dikdörtgenini alır veya ayarlar.

Değer: Kullanıcı maskesi Dikdörtgeni.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
public void save_internalized(StreamContainer streamContainer)
```


Belirtilen  StreamContainer  içine [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Verilerin kaydedileceği akış konteyneri. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Arka plan rengini alır veya ayarlar.

Değer: Arka plan rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


PSD görüntü katmanındaki kapsayan alt raster maske konumunu alır veya ayarlar.

Değer: Alt katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


PSD dosya katmanındaki kapsayan sol raster maske konumunu alır veya ayarlar.

Değer: Sol katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


PSD dosya katmanındaki kapsayan sağ raster maske konumunu alır veya ayarlar.

Değer: Sağ katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


PSD görüntü katmanındaki raster maskenin kapsayan üst konumunu alır veya ayarlar.

Değer: Üst katman maskesi konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Kullanıcı / raster maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. Vektör maskesi için Flags özelliği kullanılır.

Değer: Gerçek katman maskesi bayrakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


PSD dosyasındaki bir katmanın kullanıcı (raster) maske verisini alır veya ayarlar. (MaskData özelliğinde rasterleştirilmiş bir vektör maskesi vardır).

Değer: PSD görüntüsündeki katman görüntü verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


PSD görüntü katmanındaki kullanıcı maskesi (kapsayan) dikdörtgenini alır veya ayarlar.

Değer: Kullanıcı maskesi Dikdörtgeni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

