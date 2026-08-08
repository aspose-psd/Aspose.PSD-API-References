---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Den partiella dataläsaren."
type: docs
weight: 133
url: /sv/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Den partiella dataläsaren.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Bearbetar den laddade datan. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Bearbetar den laddade datan. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Bearbetar den laddade datan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Daterektangeln. |
| data | byte[] | Rådata. |
| start | [Point](../../com.aspose.psd/point) | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.psd/point) | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Bearbetar den laddade datan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Daterektangeln. |
| data | byte[] | Rådata. |
| start | [Point](../../com.aspose.psd/point) | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.psd/point) | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

