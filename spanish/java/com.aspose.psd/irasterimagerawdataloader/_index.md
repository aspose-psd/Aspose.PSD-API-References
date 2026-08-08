---
title: "IRasterImageRawDataLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El cargador de datos sin procesar de imagen raster."
type: docs
weight: 137
url: /es/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

El cargador de datos sin procesar de imagen raster.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Obtiene la configuración actual de datos brutos. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtiene un valor que indica si la carga de datos sin procesar es compatible. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Carga datos sin procesar. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración los datos se cargan sin conversión.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Obtiene un valor que indica si la carga de datos sin procesar es compatible.

**Returns:**
boolean -  true  si la carga de datos sin procesar es compatible; de lo contrario,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carga datos sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Los ajustes de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará una conversión de datos. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | El cargador de datos sin procesar. |

