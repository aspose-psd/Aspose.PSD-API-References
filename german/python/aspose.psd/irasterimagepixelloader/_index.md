---
title: "IRasterImagePixelLoader Klasse"
type: docs
weight: 2010
url: /de/python-net/aspose.psd/irasterimagepixelloader/
---

**Summary:** The raster image pixel loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImagePixelLoader

**Inheritance:** IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Liest die aktuellen Rohdaten‑Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [load_partial_pixels(rectangle, partial_pixel_loader)](#load_partial_pixels_rectangle_partial_pixel_loader_1) | Lädt Pixel teilweise (nach Blöcken). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Lädt Rohdaten. |


### Method: load_partial_pixels(rectangle, partial_pixel_loader) {#load_partial_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_pixels(rectangle, partial_pixel_loader) 
```

Lädt Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Der partielle Pixel-Lader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Lädt Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Rohdaten geladen werden. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Der Rohdaten-Lader. |

