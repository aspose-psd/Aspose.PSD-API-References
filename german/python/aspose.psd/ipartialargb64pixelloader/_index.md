---
title: "IPartialArgb64PixelLoader-Klasse"
type: docs
weight: 1920
url: /de/python-net/aspose.psd/ipartialargb64pixelloader/
---

**Summary:** The 64-bit ARGB pixels loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialArgb64PixelLoader

**Inheritance:** IPartialArgb32PixelLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Verarbeitet die geladenen Pixel. |
| [process64(pixels_rectangle, pixels, start, end)](#process64_pixels_rectangle_pixels_start_end_2) | Verarbeitet die geladenen Pixel. |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Verarbeitet die geladenen Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Pixelrechteck. |
| pixels | int | Die 64‑Bit‑ARGB‑Pixel. |
| start | [Point](/psd/python-net/aspose.psd/point) | Der Startpixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](/psd/python-net/aspose.psd/point) | Der Endpixel-Punkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass es kein vollständiges Rechteck ist. |

### Method: process64(pixels_rectangle, pixels, start, end) {#process64_pixels_rectangle_pixels_start_end_2}


```
 process64(pixels_rectangle, pixels, start, end) 
```

Verarbeitet die geladenen Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Pixelrechteck. |
| pixels | long | Die 64‑Bit‑ARGB‑Pixel. |
| start | [Point](/psd/python-net/aspose.psd/point) | Der Startpixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](/psd/python-net/aspose.psd/point) | Der Endpixel-Punkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass es kein vollständiges Rechteck ist. |

