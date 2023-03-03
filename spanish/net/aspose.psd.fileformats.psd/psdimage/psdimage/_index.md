---
title: PsdImage.PsdImage
second_title: Referencia de API de Aspose.PSD para .NET
description: PsdImage constructor. Inicializa una nueva instancia delPsdImage clase de la ruta especificada de la imagen ráster no la imagen psd en la ruta. Se utiliza para inicializar la imagen psd con los parámetros predeterminados  Modo de color  rgb 4 canales 8 bits por canal Compresión  Raw.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Inicializa una nueva instancia del[`PsdImage`](../) clase de la ruta especificada de la imagen ráster (no la imagen psd en la ruta). Se utiliza para inicializar la imagen psd con los parámetros predeterminados - Modo de color - rgb, 4 canales, 8 bits por canal, Compresión - Raw.

```csharp
public PsdImage(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta desde la que se cargan los datos de píxeles y paletas y se inicializa. |

### Ver también

* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Inicializa una nueva instancia del[`PsdImage`](../) clase de la ruta especificada de la imagen ráster (no la imagen psd en la ruta) con parámetros de constructor.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | La ruta desde la que se cargan los datos de píxeles y paletas y se inicializa. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits PSD por canal. |
| channels | Int16 | Los canales PSD cuentan. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a utilizar. |

### Ver también

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Inicializa una nueva instancia del[`PsdImage`](../) clase de la ruta especificada de la imagen ráster (no la imagen psd en la transmisión). Se utiliza para inicializar la imagen psd con los parámetros predeterminados - Modo de color - rgb, 4 canales, 8 bits por canal, Compresión - Raw.

```csharp
public PsdImage(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia desde la que se cargan los datos de píxeles y paletas y con la que se inicializa. |

### Ver también

* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Inicializa una nueva instancia del[`PsdImage`](../) clase de la ruta especificada de la imagen ráster (no la imagen psd en la transmisión) con parámetros de constructor.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia desde la que se cargan los datos de píxeles y paletas y con la que se inicializa. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits PSD por canal. |
| channels | Int16 | Los canales PSD cuentan. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a utilizar. |

### Ver también

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Inicializa una nueva instancia del[`PsdImage`](../)clase de imagen ráster existente (no imagen psd) con modo de color RGB con 4 canales de 8 bits/canal y sin compresión.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen desde la que se cargarán los datos de píxeles y la paleta y se inicializará. |

### Ver también

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Inicializa una nueva instancia del[`PsdImage`](../) clase de imagen ráster existente (no imagen psd) con parámetros de constructor.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rasterImage | RasterImage | La imagen desde la que se cargarán los datos de píxeles y la paleta y se inicializará. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits PSD por canal. |
| channels | Int16 | Los canales PSD cuentan. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a utilizar. |

### Ver también

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Inicializa una nueva instancia del[`PsdImage`](../) clase con ancho y alto especificados. Se utiliza para inicializar la imagen psd vacía.

```csharp
public PsdImage(int width, int height)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |

### Ver también

* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Inicializa una nueva instancia del[`PsdImage`](../) clase con ancho, alto, paleta, modo de color, número de canales y longitud de bits de canales especificados y parámetros de modo de compresión especificados. Se utiliza para inicializar la imagen psd vacía.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| width | Int32 | El ancho de la imagen. |
| height | Int32 | La altura de la imagen. |
| colorPalette | IColorPalette | La paleta de colores. |
| colorMode | ColorModes | El modo de color. |
| channelBitDepth | Int16 | La profundidad de bits PSD por canal. |
| channels | Int16 | Los canales PSD cuentan. |
| psdVersion | Int32 | La versión PSD. |
| compression | CompressionMethod | La compresión a utilizar. |

### Ver también

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)


