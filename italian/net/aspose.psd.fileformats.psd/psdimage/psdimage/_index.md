---
title: PsdImage
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Inizializza una nuova istanza diPsdImageaspose.psd.fileformats.psd/psdimage classe dal percorso specificato dallimmagine raster non immagine psd nel percorso. Utilizzato per inizializzare limmagine psd con parametri predefiniti  Modalità colore  RGB 4 canali 8 bit per canale Compressione  Raw.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel percorso). Utilizzato per inizializzare l'immagine psd con parametri predefiniti - Modalità colore - RGB, 4 canali, 8 bit per canale, Compressione - Raw.

```csharp
public PsdImage(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare e inizializzare i dati di pixel e tavolozza. |

### Guarda anche

* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel percorso) con parametri del costruttore.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso da cui caricare e inizializzare i dati di pixel e tavolozza. |
| colorMode | ColorModes | La modalità colore. |
| channelBitDepth | Int16 | La profondità di bit PSD per canale. |
| channels | Int16 | I canali PSD contano. |
| psdVersion | Int32 | La versione PSD. |
| compression | CompressionMethod | La compressione da usare. |

### Guarda anche

* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel flusso). Utilizzato per inizializzare l'immagine psd con parametri predefiniti - Modalità colore - RGB, 4 canali, 8 bit per canale, Compressione - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare i dati di pixel e tavolozza e con cui inizializzare. |

### Guarda anche

* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel flusso) con parametri del costruttore.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da cui caricare i dati di pixel e tavolozza e con cui inizializzare. |
| colorMode | ColorModes | La modalità colore. |
| channelBitDepth | Int16 | La profondità di bit PSD per canale. |
| channels | Int16 | I canali PSD contano. |
| psdVersion | Int32 | La versione PSD. |
| compression | CompressionMethod | La compressione da usare. |

### Guarda anche

* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage)classe da immagine raster esistente (non immagine psd) con modalità colore RGB con 4 canali 8 bit/canale e nessuna compressione.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine da cui caricare i dati di pixel e tavolozza e con cui inizializzare. |

### Guarda anche

* class [RasterImage](../../../aspose.psd/rasterimage)
* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe dall'immagine raster esistente (non immagine psd) con parametri del costruttore.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | RasterImage | L'immagine da cui caricare i dati di pixel e tavolozza e con cui inizializzare. |
| colorMode | ColorModes | La modalità colore. |
| channelBitDepth | Int16 | La profondità di bit PSD per canale. |
| channels | Int16 | I canali PSD contano. |
| psdVersion | Int32 | La versione PSD. |
| compression | CompressionMethod | La compressione da usare. |

### Guarda anche

* class [RasterImage](../../../aspose.psd/rasterimage)
* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe con larghezza e altezza specificate. Utilizzato per inizializzare l'immagine psd vuota.

```csharp
public PsdImage(int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine. |
| height | Int32 | L'altezza dell'immagine. |

### Guarda anche

* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Inizializza una nuova istanza di[`PsdImage`](../../psdimage) classe con larghezza, altezza, tavolozza, modalità colore, conteggio canali e lunghezza in bit dei canali specificati e parametri della modalità di compressione specificati. Utilizzato per inizializzare l'immagine psd vuota.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Int32 | La larghezza dell'immagine. |
| height | Int32 | L'altezza dell'immagine. |
| colorPalette | IColorPalette | La tavolozza dei colori. |
| colorMode | ColorModes | La modalità colore. |
| channelBitDepth | Int16 | La profondità di bit PSD per canale. |
| channels | Int16 | I canali PSD contano. |
| psdVersion | Int32 | La versione PSD. |
| compression | CompressionMethod | La compressione da usare. |

### Guarda anche

* interface [IColorPalette](../../../aspose.psd/icolorpalette)
* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
