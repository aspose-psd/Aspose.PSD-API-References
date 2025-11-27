---
title: IPartialRawDataLoader
second_title: Aspose.PSD for Java API Reference
description: The partial data loader.
type: docs
weight: 133
url: /java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

The partial data loader.
## Methods

| Method | Description |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Processes the loaded data. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Processes the loaded data. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Processes the loaded data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The data rectangle. |
| data | byte[] | The raw data. |
| start | [Point](../../com.aspose.psd/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.psd/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Processes the loaded data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The data rectangle. |
| data | byte[] | The raw data. |
| start | [Point](../../com.aspose.psd/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.psd/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

