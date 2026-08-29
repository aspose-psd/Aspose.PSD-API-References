---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Konstruktor. Erstellt eine neue Instanz der PsdImage-Klasse aus dem angegebenen Pfad eines Rasterbildes, das kein PSD-Bild im Pfad ist. Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren: Farbmodus rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression Raw."
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Pfad). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw.

```csharp
public PsdImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Der Pfad, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |

### Siehe auch

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Pfad) mit Konstruktorparametern.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Der Pfad, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |
| Farbmodus | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bit-Tiefe pro Kanal. |
| channels | Int16 | Die Anzahl der PSD-Kanäle. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Kompression. |

### Siehe auch

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Stream). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw.

```csharp
public PsdImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |

### Siehe auch

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Stream) mit Konstruktorparametern.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |
| Farbmodus | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bit-Tiefe pro Kanal. |
| channels | Int16 | Die Anzahl der PSD-Kanäle. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Kompression. |

### Siehe auch

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse aus einem vorhandenen Rasterbild (kein PSD-Bild) mit RGB-Farbmodus, 4 Kanälen, 8 Bit/Kanal und ohne Kompression.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |

### Siehe auch

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse aus einem vorhandenen Rasterbild (kein PSD-Bild) mit Konstruktorparametern.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |
| Farbmodus | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bit-Tiefe pro Kanal. |
| channels | Int16 | Die Anzahl der PSD-Kanäle. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Kompression. |

### Siehe auch

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD-Bild zu initialisieren.

```csharp
public PsdImage(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | Int32 | Die Bildbreite. |
| Höhe | Int32 | Die Bildhöhe. |

### Siehe auch

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initialisiert eine neue Instanz der [`PsdImage`](../)-Klasse mit angegebenen Breite, Höhe, Palette, Farbmodus, Kanalanzahl und Kanal-Bit-Länge sowie angegebenen Kompressionsmodus-Parametern. Wird verwendet, um ein leeres PSD-Bild zu initialisieren.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | Int32 | Die Bildbreite. |
| Höhe | Int32 | Die Bildhöhe. |
| colorPalette | IColorPalette | Die Farbpalette. |
| Farbmodus | ColorModes | Der Farbmodus. |
| channelBitDepth | Int16 | Die PSD-Bit-Tiefe pro Kanal. |
| channels | Int16 | Die Anzahl der PSD-Kanäle. |
| psdVersion | Int32 | Die PSD-Version. |
| compression | CompressionMethod | Die zu verwendende Kompression. |

### Siehe auch

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


