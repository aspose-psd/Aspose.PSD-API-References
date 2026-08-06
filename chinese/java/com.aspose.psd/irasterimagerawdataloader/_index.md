---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "光栅图像原始数据加载器。"
type: docs
weight: 137
url: /zh/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

光栅图像原始数据加载器。
## Methods

| Method | 描述 |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | 获取当前的原始数据设置。 |
| [isRawDataAvailable()](#isRawDataAvailable--) | 获取指示是否支持原始数据加载的值。 |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 加载原始数据。 |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


获取指示是否支持原始数据加载的值。

**Returns:**
boolean - 如果支持原始数据加载则为 true；否则为 false。
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


加载原始数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 用于加载原始数据的矩形。 |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 原始数据加载器。 |

