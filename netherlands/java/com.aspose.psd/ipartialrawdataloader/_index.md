---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De gedeeltelijke gegevenslader."
type: docs
weight: 133
url: /nl/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

De gedeeltelijke gegevenslader.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Verwerkt de geladen gegevens. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Verwerkt de geladen gegevens. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Verwerkt de geladen gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De gegevensrechthoek. |
| gegevens | byte[] | De ruwe gegevens. |
| start | [Point](../../com.aspose.psd/point) | Het startpunt van de gegevens. Als dit niet gelijk is aan (left,top) betekent dit dat we geen volledige rechthoek hebben. |
| end | [Point](../../com.aspose.psd/point) | Het eindpunt van de gegevens. Als dit niet gelijk is aan (right,bottom) betekent dit dat we geen volledige rechthoek hebben. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Verwerkt de geladen gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De gegevensrechthoek. |
| gegevens | byte[] | De ruwe gegevens. |
| start | [Point](../../com.aspose.psd/point) | Het startpunt van de gegevens. Als dit niet gelijk is aan (left,top) betekent dit dat we geen volledige rechthoek hebben. |
| end | [Point](../../com.aspose.psd/point) | Het eindpunt van de gegevens. Als dit niet gelijk is aan (right,bottom) betekent dit dat we geen volledige rechthoek hebben. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

