---
title: "IRasterImageRawDataLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Raster görüntü ham veri yükleyicisi."
type: docs
weight: 137
url: /tr/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Raster görüntü ham veri yükleyicisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Mevcut ham veri ayarlarını alır. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ham veri yüklemenin desteklenip desteklenmediğini gösteren bir değeri alır. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Ham veriyi yükler. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğine dikkat edin.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Ham veri yüklemenin desteklenip desteklenmediğini gösteren bir değeri alır.

**Returns:**
boolean -  raw data loading destekleniyorsa true; aksi takdirde  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Ham veriyi yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Ham verinin yükleneceği dikdörtgen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Yüklenen veri için kullanılacak ham veri ayarları. Belirtilen formatta değilse veri dönüşümü gerçekleştirileceğini unutmayın. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ham veri yükleyicisi. |

