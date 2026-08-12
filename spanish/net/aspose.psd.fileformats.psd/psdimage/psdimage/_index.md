---
title: "PsdImage.PsdImage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor PsdImage. Inicializa una nueva instancia de la clase PsdImage a partir de la ruta especificada de una imagen raster, no de una imagen psd en la ruta. Se utiliza para inicializar una imagen psd con parámetros predeterminados  Modo de color  rgb 4 canales 8 bits por canal Compresión  Raw"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Inicializa una nueva instancia de la clase [`PsdImage`](../) a partir de la ruta especificada de una imagen raster (no una imagen psd en la ruta). Se utiliza para inicializar una imagen psd con parámetros predeterminados - Modo de color - rgb, 4 canales, 8 bits por canal, Compresión - Raw.

```csharp
public PsdImage(string path)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | String | La ruta desde la cual cargar los datos de píxeles y paleta y con la que inicializar. |

### Ver también

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Inicializa una nueva instancia de la clase [`PsdImage`](../) a partir de la ruta especificada de una imagen raster (no una imagen psd en la ruta) con parámetros del constructor.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | String | La ruta desde la cual cargar los datos de píxeles y paleta y con la que inicializar. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits del PSD por canal. |
| channels | Int16 | El recuento de canales PSD. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a usar. |

### Ver también

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Inicializa una nueva instancia de la clase [`PsdImage`](../) a partir de la ruta especificada de una imagen raster (no una imagen psd en el flujo). Se usa para inicializar una imagen psd con parámetros predeterminados: modo de color - rgb, 4 canales, 8 bits por canal, compresión - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del cual cargar los datos de píxeles y paleta y con el que inicializar. |

### Ver también

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Inicializa una nueva instancia de la clase [`PsdImage`](../) a partir de la ruta especificada de una imagen raster (no una imagen psd en el flujo) con parámetros del constructor.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del cual cargar los datos de píxeles y paleta y con el que inicializar. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits del PSD por canal. |
| channels | Int16 | El recuento de canales PSD. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a usar. |

### Ver también

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Inicializa una nueva instancia de la clase [`PsdImage`](../) a partir de una imagen raster existente (no una imagen psd) con modo de color RGB, 4 canales, 8 bits por canal y sin compresión.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen de la cual cargar los datos de píxeles y paleta y con la que inicializar. |

### Ver también

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Inicializa una nueva instancia de la clase [`PsdImage`](../) a partir de una imagen raster existente (no una imagen psd) con parámetros del constructor.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen de la cual cargar los datos de píxeles y paleta y con la que inicializar. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits del PSD por canal. |
| channels | Int16 | El recuento de canales PSD. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a usar. |

### Ver también

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Inicializa una nueva instancia de la clase [`PsdImage`](../) con ancho y alto especificados. Se usa para inicializar una imagen psd vacía.

```csharp
public PsdImage(int width, int height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |

### Ver también

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Inicializa una nueva instancia de la clase [`PsdImage`](../) con ancho, alto, paleta, modo de color, recuento de canales y longitud de bits de los canales, y con los parámetros de modo de compresión especificados. Se usa para inicializar una imagen psd vacía.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |
| colorPalette | IColorPalette | La paleta de colores. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits del PSD por canal. |
| channels | Int16 | El recuento de canales PSD. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a usar. |

### Ver también

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


