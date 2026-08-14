---
title: "IRasterImageArgb32PixelLoader Klasse"
type: docs
weight: 2000
url: /de/python-net/aspose.psd/irasterimageargb32pixelloader/
---

**Summary:** The raster image 32-bit ARGB pixel loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImageArgb32PixelLoader

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
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_1) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Lädt Rohdaten. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

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

