---
title: "ImageAttributes"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir com.aspose.psd.ImageAttributes nesnesi, işleme sırasında bitmap ve metafile renklerinin nasıl manipüle edildiğine dair bilgileri içerir."
type: docs
weight: 55
url: /tr/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Bir  com.aspose.psd.ImageAttributes  nesnesi, bitmap ve metafile renklerinin oluşturma sırasında nasıl manipüle edildiği hakkında bilgi içerir. Bir  com.aspose.psd.ImageAttributes  nesnesi, renk ayarlama matrisleri, gri tonlama ayarlama matrisleri, gama düzeltme değerleri, renk haritası tabloları ve renk eşik değerleri dahil olmak üzere çeşitli renk ayarlama ayarlarını tutar. Oluşturma sırasında renkler düzeltilebilir, karartılabilir, aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için bir  com.aspose.psd.ImageAttributes  nesnesi başlatın ve bu  com.aspose.psd.ImageAttributes  nesnesinin yolunu (bir [Image](../../com.aspose.psd/image) yoluyla birlikte) drawImage metoduna geçirin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Yeni bir  com.aspose.psd.ImageAttributes  sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | GDI görüntü öznitelikleri. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Bu  com.aspose.psd.ImageAttributes  nesnesinin fırça renk yeniden eşleme tablosunu temizler. |
| [clearColorKey()](#clearColorKey--) | Varsayılan kategori için renk anahtarını (şeffaflık aralığı) temizler. |
| [clearColorKey(int type)](#clearColorKey-int-) | Belirtilen kategori için renk anahtarını (şeffaflık aralığı) temizler. |
| [clearColorMatrix()](#clearColorMatrix--) | Varsayılan kategori için renk ayarlama matrisini temizler. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Belirtilen kategori için renk ayarlama matrisini temizler. |
| [clearGamma()](#clearGamma--) | Varsayılan kategori için gama düzeltmeyi devre dışı bırakır. |
| [clearGamma(int type)](#clearGamma-int-) | Belirtilen kategori için gama düzeltmeyi devre dışı bırakır. |
| [clearNoOp()](#clearNoOp--) | Varsayılan kategori için NoOp ayarını temizler. |
| [clearNoOp(int type)](#clearNoOp-int-) | Belirtilen kategori için NoOp ayarını temizler. |
| [clearOutputChannel()](#clearOutputChannel--) | Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Belirtilen kategori için (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Varsayılan kategori için çıkış kanalı renk profili ayarını temizler. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Belirtilen kategori için çıkış kanalı renk profili ayarını temizler. |
| [clearRemapTable()](#clearRemapTable--) | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Belirtilen kategori için renk yeniden eşleme tablosunu temizler. |
| [clearThreshold()](#clearThreshold--) | Varsayılan kategori için eşik değerini temizler. |
| [clearThreshold(int type)](#clearThreshold-int-) | Belirtilen kategori için eşik değerini temizler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Varsayılan kategori için renk anahtarını ayarlar. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Belirtilen kategori için renk anahtarını (şeffaflık aralığı) ayarlar. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Varsayılan kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Varsayılan kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Belirtilen kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Belirtilen kategori için renk ayarlama matrisini ayarlar. |
| [setGamma(float gamma)](#setGamma-float-) | Varsayılan kategori için gama değerini ayarlar. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Belirtilen kategori için gama değerini ayarlar. |
| [setNoOp()](#setNoOp--) | Varsayılan kategori için renk ayarlamayı kapatır. |
| [setNoOp(int type)](#setNoOp-int-) | Belirtilen kategori için renk ayarlamayı kapatır. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Belirtilen kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Varsayılan kategori için çıkış kanalının renk profili dosyasını ayarlar. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Belirtilen kategori için çıkış kanalının renk profili dosyasını ayarlar. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Belirtilen kategori için renk yeniden eşleme tablosunu ayarlar. |
| [setThreshold(float threshold)](#setThreshold-float-) | Varsayılan kategori için eşik (şeffaflık aralığı) ayarlar. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Belirtilen kategori için eşik (şeffaflık aralığı) ayarlar. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Yeni bir  com.aspose.psd.ImageAttributes  sınıfı örneği başlatır.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


GDI görüntü öznitelikleri.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Bu  com.aspose.psd.ImageAttributes  nesnesinin fırça renk yeniden eşleme tablosunu temizler.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Varsayılan kategori için renk anahtarını (şeffaflık aralığı) temizler.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Belirtilen kategori için renk anahtarını (şeffaflık aralığı) temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk anahtarının temizlendiği kategoriyi belirtir. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Varsayılan kategori için renk ayarlama matrisini temizler.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Belirtilen kategori için renk ayarlama matrisini temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk ayarlama matrisinin temizlendiği kategoriyi belirtir. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Varsayılan kategori için gama düzeltmeyi devre dışı bırakır.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Belirtilen kategori için gama düzeltmeyi devre dışı bırakır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, gama düzeltmesinin devre dışı bırakıldığı kategoriyi belirtir. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Varsayılan kategori için NoOp ayarını temizler.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Belirtilen kategori için NoOp ayarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, NoOp ayarının temizlendiği kategoriyi belirtir. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Belirtilen kategori için (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, çıkış kanal ayarının temizlendiği kategoriyi belirtir. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Varsayılan kategori için çıkış kanalı renk profili ayarını temizler.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Belirtilen kategori için çıkış kanalı renk profili ayarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, çıkış kanal profili ayarının temizlendiği kategoriyi belirtir. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Varsayılan kategori için renk yeniden eşleme tablosunu temizler.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Belirtilen kategori için renk yeniden eşleme tablosunu temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, yeniden eşleme tablosunun temizlendiği kategoriyi belirtir. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Varsayılan kategori için eşik değerini temizler.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Belirtilen kategori için eşik değerini temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, eşik değerinin temizlendiği kategoriyi belirtir. |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap nesnelerinden oluşan bir dizi. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Varsayılan kategori için renk anahtarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Düşük renk anahtarı değeri. |
| colorHigh | [Color](../../com.aspose.psd/color) | Yüksek renk anahtarı değeri. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Belirtilen kategori için renk anahtarını (şeffaflık aralığı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Düşük renk anahtarı değeri. |
| colorHigh | [Color](../../com.aspose.psd/color) | Yüksek renk anahtarı değeri. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk anahtarının ayarlandığı kategoriyi belirtir. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Varsayılan kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Gri ölçek ayarlama matrisi. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Varsayılan kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Gri ölçek ayarlama matrisi. |
| bayraklar | int | Aspose.Imaging.ColorMatrixFlag öğesi, renk ayarlama ve gri ölçek ayarlama matrislerinden etkilenecek görüntü ve renk türünü belirtir. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Belirtilen kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Gri ölçek ayarlama matrisi. |
| mode | int | Aspose.Imaging.ColorMatrixFlag öğesi, renk ayarlama ve gri ölçek ayarlama matrislerinden etkilenecek görüntü ve renk türünü belirtir. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk ayarlama ve gri ölçek ayarlama matrislerinin ayarlandığı kategoriyi belirtir. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Varsayılan kategori için renk ayarlama matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Renk ayarlama matrisi. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Varsayılan kategori için renk ayarlama matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| bayraklar | int | Aspose.Imaging.ColorMatrixFlag öğesi, renk ayarlama matrisinden etkilenecek görüntü ve renk türünü belirtir. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Belirtilen kategori için renk ayarlama matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| mode | int | Aspose.Imaging.ColorMatrixFlag öğesi, renk ayarlama matrisinden etkilenecek görüntü ve renk türünü belirtir. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk ayarlama matrisinin ayarlandığı kategoriyi belirtir. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Varsayılan kategori için gama değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gama | float | Gama düzeltme değeri. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Belirtilen kategori için gama değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gama | float | Gama düzeltme değeri. |
| tür | int | Aspose.Imaging.ColorAdjustType sayımının bir öğesi, gama değerinin ayarlandığı kategoriyi belirtir. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Varsayılan kategori için renk ayarlamayı kapatır.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Belirtilen kategori için renk ayarlamayı kapatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk düzeltmesinin kapatıldığı kategoriyi belirtir. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayraklar | int | Aspose.Imaging.ColorChannelFlag öğesi, çıktı kanalını belirtir. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Belirtilen kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayraklar | int | Aspose.Imaging.ColorChannelFlag öğesi, çıktı kanalını belirtir. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, çıktı kanalının ayarlandığı kategoriyi belirtir. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Varsayılan kategori için çıkış kanalının renk profili dosyasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise bu parametre dosya adı olabilir. Aksi takdirde bu parametre tam nitelikli yol adı olmalıdır. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Belirtilen kategori için çıkış kanalının renk profili dosyasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise bu parametre dosya adı olabilir. Aksi takdirde bu parametre tam nitelikli yol adı olmalıdır. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, çıktı kanalının renk profili dosyasının ayarlandığı kategoriyi belirtir. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap türünde renk çiftlerinin bir dizisi. Her renk çifti mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Belirtilen kategori için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap türünde renk çiftlerinin bir dizisi. Her renk çifti mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk yeniden eşleme tablosunun ayarlandığı kategoriyi belirtir. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Varsayılan kategori için eşik (şeffaflık aralığı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Eşik değerini belirten gerçek sayı. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Belirtilen kategori için eşik (şeffaflık aralığı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | float | Maksimum veya minimum bir değere eşlenecek renkleri sıralamak için kesme noktası olarak kullanılan 0.0 ile 1.0 arasında bir eşik değeri. |
| tür | int | Aspose.Imaging.ColorAdjustType öğesi, renk eşiğinin ayarlandığı kategoriyi belirtir. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Dokunun, doldurduğu şekilden daha küçük olduğu durumlarda şekli doldurmak için döşenmesi sağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode öğesi, bir görüntünün tekrar eden kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Bir doku bir şekil boyunca ya da şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, doldurduğu şeklin boyutundan daha küçük olduğunda şekli doldurmak için şekil boyunca döşenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode öğesi, bir görüntünün tekrar eden kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |
| color | [Color](../../com.aspose.psd/color) | Render edilen bir görüntünün dışındaki piksellerin rengini belirten bir  com.aspose.psd.ImageAttributes  nesnesi. Bu renk, mod parametresi  WrapMode.Clamp  olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgeni görüntünün kendisinden daha büyük olduğunda görünür. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Bir doku bir şekil boyunca ya da şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, doldurduğu şeklin boyutundan daha küçük olduğunda şekli doldurmak için şekil boyunca döşenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode öğesi, bir görüntünün tekrar eden kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |
| color | [Color](../../com.aspose.psd/color) | Render edilen bir görüntünün dışındaki piksellerin rengini belirten bir renk nesnesi. Bu renk, mod parametresi  WrapMode.Clamp  olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgeni görüntünün kendisinden daha büyük olduğunda görünür. |
| sıkıştır | boolean | Bu parametrenin bir etkisi yoktur. False olarak ayarlayın. |

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

