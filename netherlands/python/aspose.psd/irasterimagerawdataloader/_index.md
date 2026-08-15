---
title: "IRasterImageRawDataLoader Klasse"
type: docs
weight: 2020
url: /nl/python-net/aspose.psd/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | Haalt een waarde op die aangeeft of het laden van ruwe gegevens wordt ondersteund. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Haalt de huidige ruwe‑gegevensinstellingen op. Let op: bij het gebruik van deze instellingen worden de gegevens geladen zonder conversie. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | Laadt ruwe gegevens. |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Laadt ruwe gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om ruwe gegevens van te laden. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens die gebruikt moeten worden voor geladen gegevens. Opmerking: als de gegevens niet in het opgegeven formaat zijn, wordt er een gegevensconversie uitgevoerd. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | De ruwe gegevenslader. |

