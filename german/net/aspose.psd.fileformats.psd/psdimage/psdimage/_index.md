---
title: PsdImage.PsdImage
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdImage constructeur. Initialisiert eine neue Instanz vonPsdImage Klasse aus dem angegebenen Pfad aus dem Rasterbild nicht das PSDBild im Pfad. Wird verwendet um ein PSDBild mit Standardparametern zu initialisieren  Farbmodus  RGB 4 Kanäle 8 Bit pro Kanal Komprimierung  Raw.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse aus dem angegebenen Pfad aus dem Rasterbild (nicht das PSD-Bild im Pfad). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – RGB, 4 Kanäle, 8 Bit pro Kanal, Komprimierung – Raw.

```csharp
public PsdImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Pixel- und Palettendaten und zum Initialisieren. |

### Siehe auch

* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse aus dem angegebenen Pfad aus dem Rasterbild (kein PSD-Bild im Pfad) mit Konstruktorparametern.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Pixel- und Palettendaten und zum Initialisieren. |
| colorMode | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bittiefe pro Kanal. |
| channels | Int16 | Die PSD-Kanäle zählen. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Komprimierung. |

### Siehe auch

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse aus dem angegebenen Pfad vom Rasterbild (kein PSD-Bild im Stream). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – RGB, 4 Kanäle, 8 Bit pro Kanal, Komprimierung – Raw.

```csharp
public PsdImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem Pixel- und Palettendaten geladen und mit dem initialisiert werden soll. |

### Siehe auch

* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse aus dem angegebenen Pfad vom Rasterbild (kein PSD-Bild im Stream) mit Konstruktorparametern.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem Pixel- und Palettendaten geladen und mit dem initialisiert werden soll. |
| colorMode | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bittiefe pro Kanal. |
| channels | Int16 | Die PSD-Kanäle zählen. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Komprimierung. |

### Siehe auch

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initialisiert eine neue Instanz von[`PsdImage`](../)Klasse aus vorhandenem Rasterbild (kein PSD-Bild) mit RGB-Farbmodus mit 4 Kanälen 8 Bit/Kanal und ohne Komprimierung.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, aus dem Pixel- und Palettendaten geladen und mit dem es initialisiert werden soll. |

### Siehe auch

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse aus vorhandenem Rasterbild (nicht PSD-Bild) mit Konstruktorparametern.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, aus dem Pixel- und Palettendaten geladen und mit dem es initialisiert werden soll. |
| colorMode | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bittiefe pro Kanal. |
| channels | Int16 | Die PSD-Kanäle zählen. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Komprimierung. |

### Siehe auch

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD-Bild zu initialisieren.

```csharp
public PsdImage(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |

### Siehe auch

* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initialisiert eine neue Instanz von[`PsdImage`](../) Klasse mit angegebener Breite, Höhe, Paletter, Farbmodus, Kanalanzahl und Kanalbitlänge und angegebenen Komprimierungsmodusparametern. Wird verwendet, um ein leeres PSD-Bild zu initialisieren.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |
| colorPalette | IColorPalette | Die Farbpalette. |
| colorMode | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bittiefe pro Kanal. |
| channels | Int16 | Die PSD-Kanäle zählen. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Komprimierung. |

### Siehe auch

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)


