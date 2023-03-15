---
title: PsdImage.PsdImage
second_title: Aspose.PSD för .NET API-referens
description: PsdImage byggare. Initierar en ny instans avPsdImage klass från angiven sökväg från rasterbild inte psdbild i sökväg. Används för att initiera psdbild med standardparametrar  Färgläge  rgb 4 kanaler 8 bitar per kanal Kompression  Raw.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Initierar en ny instans av[`PsdImage`](../) klass från angiven sökväg från rasterbild (inte psd-bild i sökväg). Används för att initiera psd-bild med standardparametrar - Färgläge - rgb, 4 kanaler, 8 bitar per kanal, Kompression - Raw.

```csharp
public PsdImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda pixel- och palettdata från och initiera med. |

### Se även

* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initierar en ny instans av[`PsdImage`](../) klass från angiven sökväg från rasterbild (inte psd-bild i sökväg) med konstruktorparametrar.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda pixel- och palettdata från och initiera med. |
| colorMode | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD-bitdjupet per kanal. |
| channels | Int16 | PSD-kanalerna räknas. |
| psdVersion | Int32 | PSD-versionen. |
| compression | CompressionMethod | Kompressionen att använda. |

### Se även

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initierar en ny instans av[`PsdImage`](../) klass från angiven sökväg från rasterbild (inte psd-bild i ström). Används för att initiera psd-bild med standardparametrar - Färgläge - rgb, 4 kanaler, 8 bitar per kanal, Kompression - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att ladda pixel- och palettdata från och initiera med. |

### Se även

* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initierar en ny instans av[`PsdImage`](../) klass från angiven sökväg från rasterbild (inte psd-bild i ström) med konstruktorparametrar.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att ladda pixel- och palettdata från och initiera med. |
| colorMode | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD-bitdjupet per kanal. |
| channels | Int16 | PSD-kanalerna räknas. |
| psdVersion | Int32 | PSD-versionen. |
| compression | CompressionMethod | Kompressionen att använda. |

### Se även

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initierar en ny instans av[`PsdImage`](../)klass från befintlig rasterbild (ej psd-bild) med RGB-färgläge med 4 kanaler 8 bitar/kanal och ingen komprimering.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden att ladda pixel- och palettdata från och initiera med. |

### Se även

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initierar en ny instans av[`PsdImage`](../) klass från befintlig rasterbild (inte psd-bild) med konstruktorparametrar.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden att ladda pixel- och palettdata från och initiera med. |
| colorMode | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD-bitdjupet per kanal. |
| channels | Int16 | PSD-kanalerna räknas. |
| psdVersion | Int32 | PSD-versionen. |
| compression | CompressionMethod | Kompressionen att använda. |

### Se även

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initierar en ny instans av[`PsdImage`](../) klass med angiven bredd och höjd. Används för att initiera tom psd-bild.

```csharp
public PsdImage(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd. |
| height | Int32 | Bildhöjden. |

### Se även

* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initierar en ny instans av[`PsdImage`](../) klass med specificerad bredd, höjd, paletter, färgläge, kanalantal och kanalers bitlängd och specificerade komprimeringslägesparametrar. Används för att initiera tom psd-bild.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd. |
| height | Int32 | Bildhöjden. |
| colorPalette | IColorPalette | Färgpaletten. |
| colorMode | ColorModes | Färgläget. |
| channelBitDepth | Int16 | PSD-bitdjupet per kanal. |
| channels | Int16 | PSD-kanalerna räknas. |
| psdVersion | Int32 | PSD-versionen. |
| compression | CompressionMethod | Kompressionen att använda. |

### Se även

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)


