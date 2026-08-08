---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De rasterafbeelding ruwe gegevensloader."
type: docs
weight: 137
url: /nl/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

De rasterafbeelding ruwe gegevensloader.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Haalt de huidige ruwe gegevensinstellingen op. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Haalt een waarde op die aangeeft of het laden van ruwe gegevens wordt ondersteund. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Laadt ruwe gegevens. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Haalt de huidige ruwe gegevensinstellingen op. Let op: bij gebruik van deze instellingen worden de gegevens geladen zonder conversie.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Haalt een waarde op die aangeeft of het laden van ruwe gegevens wordt ondersteund.

**Returns:**
boolean -  true  als het laden van ruwe gegevens wordt ondersteund; anders,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laadt ruwe gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om ruwe gegevens van te laden. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | De ruwe-gegevensinstellingen die gebruikt moeten worden voor geladen gegevens. Opmerking: als gegevens niet in het opgegeven formaat zijn, wordt gegevensconversie uitgevoerd. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | De ruwe-gegevensloader. |

