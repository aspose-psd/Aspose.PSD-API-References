---
title: IRasterImageRawDataLoader
second_title: Aspose.PSD for Java API Reference
description: The raster image raw data loader.
type: docs
weight: 138
url: /java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

The raster image raw data loader.
## Methods

| Method | Description |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Gets the current raw data settings. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Gets a value indicating whether raw data loading is supported. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Loads raw data. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Gets the current raw data settings. Note when using these settings the data loads without conversion.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Gets a value indicating whether raw data loading is supported.

**Returns:**
boolean -  true  if raw data loading is supported; otherwise,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Loads raw data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load raw data from. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | The raw data loader. |

