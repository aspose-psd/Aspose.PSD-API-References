---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage‑konstruktor. Initierar en ny instans av PsdImage‑klassen från angiven sökväg från rasterbild, inte psd‑bild i sökvägen. Används för att initiera psd‑bild med standardparametrar  Färgläge  rgb 4 kanaler 8 bit per kanal Komprimering  Raw"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Initierar en ny instans av klassen [`PsdImage`](../) från angiven sökväg från rasterbild (inte psd‑bild i sökvägen). Används för att initiera psd‑bild med standardparametrar – Färgläge – rgb, 4 kanaler, 8 bit per kanal, Komprimering – Raw.

```csharp
public PsdImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Sökvägen för att läsa in pixel‑ och palettdata från och initiera med. |

### Se även

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initierar en ny instans av klassen [`PsdImage`](../) från angiven sökväg från rasterbild (inte psd‑bild i sökvägen) med konstruktörsparametrar.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Sökvägen för att läsa in pixel‑ och palettdata från och initiera med. |
| färgläge | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD‑bitdjupet per kanal. |
| kanaler | Int16 | Antalet PSD-kanaler. |
| psdVersion | Int32 | PSD-versionen. |
| komprimering | CompressionMethod | Komprimeringen att använda. |

### Se även

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initierar en ny instans av klassen [`PsdImage`](../) från angiven sökväg från rasterbild (inte psd‑bild i ström). Används för att initiera psd‑bild med standardparametrar – Färgläge – rgb, 4 kanaler, 8 bit per kanal, Komprimering – Raw.

```csharp
public PsdImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen för att läsa in pixel‑ och palettdata från och initiera med. |

### Se även

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initierar en ny instans av klassen [`PsdImage`](../) från angiven sökväg från rasterbild (inte psd‑bild i ström) med konstruktörsparametrar.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen för att läsa in pixel‑ och palettdata från och initiera med. |
| färgläge | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD‑bitdjupet per kanal. |
| kanaler | Int16 | Antalet PSD-kanaler. |
| psdVersion | Int32 | PSD-versionen. |
| komprimering | CompressionMethod | Komprimeringen att använda. |

### Se även

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initierar en ny instans av klassen [`PsdImage`](../) från befintlig rasterbild (inte psd‑bild) med RGB‑färgläge med 4 kanaler, 8 bit/kanal och ingen komprimering.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden för att läsa in pixel‑ och palettdata från och initiera med. |

### Se även

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initierar en ny instans av klassen [`PsdImage`](../) från befintlig rasterbild (inte psd‑bild) med konstruktörsparametrar.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden för att läsa in pixel‑ och palettdata från och initiera med. |
| färgläge | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD‑bitdjupet per kanal. |
| kanaler | Int16 | Antalet PSD-kanaler. |
| psdVersion | Int32 | PSD-versionen. |
| komprimering | CompressionMethod | Komprimeringen att använda. |

### Se även

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initierar en ny instans av klassen [`PsdImage`](../) med angiven bredd och höjd. Används för att initiera en tom psd‑bild.

```csharp
public PsdImage(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | Int32 | Bildbredden. |
| höjd | Int32 | Bildens höjd. |

### Se även

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initierar en ny instans av klassen [`PsdImage`](../) med angiven bredd, höjd, paletter, färgläge, kanalantal och kanalernas bitlängd samt angivna komprimeringslägesparametrar. Används för att initiera en tom psd‑bild.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | Int32 | Bildbredden. |
| höjd | Int32 | Bildens höjd. |
| colorPalette | IColorPalette | Färgpaletten. |
| färgläge | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD‑bitdjupet per kanal. |
| kanaler | Int16 | Antalet PSD-kanaler. |
| psdVersion | Int32 | PSD-versionen. |
| komprimering | CompressionMethod | Komprimeringen att använda. |

### Se även

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


