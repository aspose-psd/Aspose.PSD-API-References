---
title: PsdImage.PsdImage
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage constructeur. Initialise une nouvelle instance duPsdImage classe à partir du chemin spécifié à partir de limage raster et non de limage psd dans le chemin. Utilisé pour initialiser limage psd avec les paramètres par défaut  Mode couleur  rvb 4 canaux 8 bits par canal Compression  Raw.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Initialise une nouvelle instance du[`PsdImage`](../) classe à partir du chemin spécifié à partir de l'image raster (et non de l'image psd dans le chemin). Utilisé pour initialiser l'image psd avec les paramètres par défaut - Mode couleur - rvb, 4 canaux, 8 bits par canal, Compression - Raw.

```csharp
public PsdImage(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger les données de pixel et de palette et initialiser avec. |

### Voir également

* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Initialise une nouvelle instance du[`PsdImage`](../) classe à partir du chemin spécifié à partir de l'image raster (et non de l'image psd dans le chemin) avec les paramètres du constructeur.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger les données de pixel et de palette et initialiser avec. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bit PSD par canal. |
| channels | Int16 | Les canaux PSD comptent. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir également

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Initialise une nouvelle instance du[`PsdImage`](../) classe à partir du chemin spécifié à partir de l'image raster (et non de l'image psd dans le flux). Utilisé pour initialiser l'image psd avec les paramètres par défaut - Mode couleur - rvb, 4 canaux, 8 bits par canal, Compression - Raw.

```csharp
public PsdImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger les données de pixel et de palette et avec lequel initialiser. |

### Voir également

* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Initialise une nouvelle instance du[`PsdImage`](../) classe à partir du chemin spécifié à partir de l'image raster (pas de l'image psd dans le flux) avec les paramètres du constructeur.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger les données de pixel et de palette et avec lequel initialiser. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bit PSD par canal. |
| channels | Int16 | Les canaux PSD comptent. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir également

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Initialise une nouvelle instance du[`PsdImage`](../)classe à partir d'une image raster existante (pas d'image psd) avec mode couleur RVB avec 4 canaux 8 bits/canal et sans compression.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image à partir de laquelle charger les données de pixel et de palette et avec laquelle initialiser. |

### Voir également

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Initialise une nouvelle instance du[`PsdImage`](../) classe à partir d'une image raster existante (pas d'image psd) avec les paramètres du constructeur.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image à partir de laquelle charger les données de pixel et de palette et avec laquelle initialiser. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bit PSD par canal. |
| channels | Int16 | Les canaux PSD comptent. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir également

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Initialise une nouvelle instance du[`PsdImage`](../) classe avec une largeur et une hauteur spécifiées. Utilisé pour initialiser une image psd vide.

```csharp
public PsdImage(int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image. |
| height | Int32 | La hauteur de l'image. |

### Voir également

* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Initialise une nouvelle instance du[`PsdImage`](../) classe avec la largeur, la hauteur, le paletter, le mode de couleur, le nombre de canaux et la longueur en bits spécifiés et les paramètres de mode de compression spécifiés. Utilisé pour initialiser une image psd vide.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image. |
| height | Int32 | La hauteur de l'image. |
| colorPalette | IColorPalette | La palette de couleurs. |
| colorMode | ColorModes | Le mode couleur. |
| channelBitDepth | Int16 | La profondeur de bit PSD par canal. |
| channels | Int16 | Les canaux PSD comptent. |
| psdVersion | Int32 | La version PSD. |
| compression | CompressionMethod | La compression à utiliser. |

### Voir également

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)


