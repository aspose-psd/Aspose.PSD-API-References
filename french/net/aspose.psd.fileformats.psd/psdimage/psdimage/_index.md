---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur PsdImage. Initialise une nouvelle instance de la classe PsdImage à partir du chemin spécifié d'une image raster, pas d'une image PSD dans le chemin. Utilisé pour initialiser l'image PSD avec les paramètres par défaut  Mode couleur  rgb 4 canaux 8 bits par canal Compression  Raw"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Initialise une nouvelle instance de la classe [`PsdImage`](../) à partir du chemin spécifié d'une image raster (pas d'image PSD dans le chemin). Utilisé pour initialiser l'image PSD avec les paramètres par défaut - Mode couleur - rgb, 4 canaux, 8 bits par canal, Compression - Raw.

```csharp
public PsdImage(string path)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Le chemin depuis lequel charger les données de pixels et de palette et avec lequel initialiser. |

### Voir aussi

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initialise une nouvelle instance de la classe [`PsdImage`](../) à partir du chemin spécifié d'une image raster (pas d'image PSD dans le chemin) avec les paramètres du constructeur.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Le chemin depuis lequel charger les données de pixels et de palette et avec lequel initialiser. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bits PSD par canal. |
| channels | Int16 | Le nombre de canaux PSD. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir aussi

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initialise une nouvelle instance de la classe [`PsdImage`](../) à partir du chemin spécifié d'une image raster (pas d'image psd dans le flux). Utilisée pour initialiser une image psd avec les paramètres par défaut - Mode couleur - rgb, 4 canaux, 8 bits par canal, Compression - Raw.

```csharp
public PsdImage(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger les données de pixels et de palette et avec lequel initialiser. |

### Voir aussi

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initialise une nouvelle instance de la classe [`PsdImage`](../) à partir du chemin spécifié d'une image raster (pas d'image psd dans le flux) avec les paramètres du constructeur.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger les données de pixels et de palette et avec lequel initialiser. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bits PSD par canal. |
| channels | Int16 | Le nombre de canaux PSD. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir aussi

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initialise une nouvelle instance de la classe [`PsdImage`](../) à partir d'une image raster existante (pas d'image psd) avec le mode couleur RGB, 4 canaux, 8 bits par canal et aucune compression.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image à partir de laquelle charger les données de pixels et de palette et avec laquelle initialiser. |

### Voir aussi

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initialise une nouvelle instance de la classe [`PsdImage`](../) à partir d'une image raster existante (pas d'image psd) avec les paramètres du constructeur.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image à partir de laquelle charger les données de pixels et de palette et avec laquelle initialiser. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bits PSD par canal. |
| channels | Int16 | Le nombre de canaux PSD. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir aussi

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initialise une nouvelle instance de la classe [`PsdImage`](../) avec la largeur et la hauteur spécifiées. Utilisée pour initialiser une image psd vide.

```csharp
public PsdImage(int width, int height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | Int32 | La largeur de l'image. |
| hauteur | Int32 | La hauteur de l'image. |

### Voir aussi

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initialise une nouvelle instance de la classe [`PsdImage`](../) avec les paramètres de largeur, hauteur, palette, mode couleur, nombre de canaux et longueur de bits des canaux, ainsi que le mode de compression spécifié. Utilisée pour initialiser une image psd vide.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | Int32 | La largeur de l'image. |
| hauteur | Int32 | La hauteur de l'image. |
| colorPalette | IColorPalette | La palette de couleurs. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bits PSD par canal. |
| channels | Int16 | Le nombre de canaux PSD. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir aussi

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


