---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Rasterbild‑Rohdaten‑Lader."
type: docs
weight: 137
url: /de/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Der Rasterbild‑Rohdaten‑Lader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Liest die aktuellen Rohdaten-Einstellungen. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Lädt Rohdaten. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Ruft die aktuellen Rohdaten-Einstellungen ab. Hinweis: Bei Verwendung dieser Einstellungen werden die Daten ohne Konvertierung geladen.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird.

**Returns:**
boolesch -  true  wenn das Laden von Rohdaten unterstützt wird; andernfalls  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Lädt Rohdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem Rohdaten geladen werden. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Die Rohdaten‑Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn die Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Der Rohdaten‑Lader. |

