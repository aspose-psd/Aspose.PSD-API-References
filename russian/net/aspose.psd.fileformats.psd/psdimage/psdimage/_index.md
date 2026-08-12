---
title: "PsdImage.PsdImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор PsdImage. Инициализирует новый экземпляр класса PsdImage из указанного пути к растровому изображению, а не к PSD‑файлу в пути. Используется для инициализации PSD‑изображения с параметрами по умолчанию  режим цвета  rgb 4 канала 8 бит на канал Сжатие  Raw"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

Инициализирует новый экземпляр класса [`PsdImage`](../) из указанного пути к растровому изображению (не к PSD‑файлу в пути). Используется для инициализации PSD‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, Сжатие — Raw.

```csharp
public PsdImage(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки пиксельных и палитровых данных и инициализации. |

### См. также

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Инициализирует новый экземпляр класса [`PsdImage`](../) из указанного пути к растровому изображению (не к PSD‑файлу в пути) с параметрами конструктора.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки пиксельных и палитровых данных и инициализации. |
| colorMode | ColorModes | Режим цвета. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Сжатие, которое следует использовать. |

### См. также

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Создаёт новый экземпляр класса [`PsdImage`](../) из указанного пути растрового изображения (не psd image в потоке). Используется для инициализации psd image с параметрами по умолчанию - режим цвета - rgb, 4 channels, 8 bit per channel, Compression - Raw.

```csharp
public PsdImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого загружаются данные пикселей и палитры, и с которым производится инициализация. |

### См. также

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Создаёт новый экземпляр класса [`PsdImage`](../) из указанного пути растрового изображения (не psd image в потоке) с параметрами конструктора.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого загружаются данные пикселей и палитры, и с которым производится инициализация. |
| colorMode | ColorModes | Режим цвета. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Сжатие, которое следует использовать. |

### См. также

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Создаёт новый экземпляр класса [`PsdImage`](../) из существующего растрового изображения (не psd image) с режимом цвета RGB, 4 каналами, 8 бит/канал и без сжатия.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение, из которого загружаются данные пикселей и палитры, и с которым производится инициализация. |

### См. также

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Создаёт новый экземпляр класса [`PsdImage`](../) из существующего растрового изображения (не psd image) с параметрами конструктора.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение, из которого загружаются данные пикселей и палитры, и с которым производится инициализация. |
| colorMode | ColorModes | Режим цвета. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Сжатие, которое следует использовать. |

### См. также

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Создаёт новый экземпляр класса [`PsdImage`](../) с указанной шириной и высотой. Используется для инициализации пустого psd image.

```csharp
public PsdImage(int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |

### См. также

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Создаёт новый экземпляр класса [`PsdImage`](../) с указанными шириной, высотой, paletter, режимом цвета, количеством каналов и битовой глубиной каналов, а также параметрами режима сжатия. Используется для инициализации пустого psd image.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |
| colorPalette | IColorPalette | Цветовая палитра. |
| colorMode | ColorModes | Режим цвета. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Сжатие, которое следует использовать. |

### См. также

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


