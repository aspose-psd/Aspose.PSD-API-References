---
title: "IRasterImageRawDataLoader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le chargeur de données brutes d'image raster."
type: docs
weight: 137
url: /fr/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Le chargeur de données brutes d'image raster.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Obtient les paramètres actuels des données brutes. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtient une valeur indiquant si le chargement de données brutes est pris en charge. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Charge des données brutes. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Obtient les paramètres de données brutes actuels. Notez que lors de l'utilisation de ces paramètres, les données sont chargées sans conversion.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Obtient une valeur indiquant si le chargement de données brutes est pris en charge.

**Returns:**
booléen -  vrai  si le chargement de données brutes est pris en charge ; sinon,  faux .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Charge des données brutes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Les paramètres de données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas au format spécifié, une conversion des données sera effectuée. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Le chargeur de données brutes. |

