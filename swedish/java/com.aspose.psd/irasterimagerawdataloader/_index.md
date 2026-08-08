---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Rasterbildens rådatainläsare."
type: docs
weight: 137
url: /sv/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Rasterbildens rådatainläsare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Hämtar de aktuella rådatainställningarna. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Laddar rå data. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Hämtar ett värde som indikerar om inläsning av rådata stöds.

**Returns:**
boolean -  true  om inläsning av rådata stöds; annars,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laddar rå data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa rådata från. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Rådatainställningarna att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Rådatainläsaren. |

