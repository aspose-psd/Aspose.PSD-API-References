---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Teil-Daten‑Lader."
type: docs
weight: 133
url: /de/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Der Teil-Daten‑Lader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Verarbeitet die geladenen Daten. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Verarbeitet die geladenen Daten. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Verarbeitet die geladenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Datenrechteck. |
| Daten | byte[] | Die Rohdaten. |
| start | [Point](../../com.aspose.psd/point) | Der Startdatenpunkt. Wenn er nicht gleich (left,top) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.psd/point) | Der Enddatenpunkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Verarbeitet die geladenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Datenrechteck. |
| Daten | byte[] | Die Rohdaten. |
| start | [Point](../../com.aspose.psd/point) | Der Startdatenpunkt. Wenn er nicht gleich (left,top) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.psd/point) | Der Enddatenpunkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

