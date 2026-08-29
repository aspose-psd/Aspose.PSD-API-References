---
title: "IPartialRawDataLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kısmi veri yükleyicisi."
type: docs
weight: 133
url: /tr/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Kısmi veri yükleyicisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Yüklenen verileri işler. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Yüklenen verileri işler. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Yüklenen verileri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Veri dikdörtgeni. |
| veri | byte[] | Ham veri. |
| start | [Point](../../com.aspose.psd/point) | Başlangıç veri noktası. (sol,üst) eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| end | [Point](../../com.aspose.psd/point) | Bitiş veri noktası. (sağ,alt) eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Yüklenen verileri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Veri dikdörtgeni. |
| veri | byte[] | Ham veri. |
| start | [Point](../../com.aspose.psd/point) | Başlangıç veri noktası. (sol,üst) eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| end | [Point](../../com.aspose.psd/point) | Bitiş veri noktası. (sağ,alt) eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

