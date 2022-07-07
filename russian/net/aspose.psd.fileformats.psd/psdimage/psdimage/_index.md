---
title: PsdImage
second_title: Справочник по Aspose.PSD для .NET API
description: Инициализирует новый экземпляр классаPsdImageaspose.psd.fileformats.psd/psdimageпо указанному пути из растрового изображения не psd изображение в пути. Используется для инициализации psd изображения с параметрами по умолчанию - Цветовой режим - rgb 4 канала 8 бит на канал Сжатие - Raw.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)по указанному пути из растрового изображения (не psd изображение в пути). Используется для инициализации psd изображения с параметрами по умолчанию - Цветовой режим - rgb, 4 канала, 8 бит на канал, Сжатие - Raw.

```csharp
public PsdImage(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки данных пикселей и палитры и инициализации. |

### Смотрите также

* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)по указанному пути из растрового изображения (не psd изображение в пути) с параметрами конструктора.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки данных пикселей и палитры и инициализации. |
| colorMode | ColorModes | Цветовой режим. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Используемое сжатие. |

### Смотрите также

* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)по указанному пути из растрового изображения (не psd изображение в потоке). Используется для инициализации psd изображения с параметрами по умолчанию - Цветовой режим - rgb, 4 канала, 8 бит на канал, Сжатие - Raw.

```csharp
public PsdImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого загружаются данные о пикселях и палитре и выполняется инициализация. |

### Смотрите также

* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)по указанному пути из растрового изображения (не psd изображение в потоке) с параметрами конструктора.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого загружаются данные о пикселях и палитре и выполняется инициализация. |
| colorMode | ColorModes | Цветовой режим. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Используемое сжатие. |

### Смотрите также

* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)из существующего растрового изображения (не psd изображения) с цветовым режимом RGB с 4 каналами 8 бит/канал и без сжатия.

```csharp
public PsdImage(RasterImage rasterImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение для загрузки данных о пикселях и палитре и инициализации. |

### Смотрите также

* class [RasterImage](../../../aspose.psd/rasterimage)
* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)из существующего растрового изображения (не psd изображения) с параметрами конструктора.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение для загрузки данных о пикселях и палитре и инициализации. |
| colorMode | ColorModes | Цветовой режим. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Используемое сжатие. |

### Смотрите также

* class [RasterImage](../../../aspose.psd/rasterimage)
* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)с указанными шириной и высотой. Используется для инициализации пустого изображения psd.

```csharp
public PsdImage(int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |

### Смотрите также

* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

Инициализирует новый экземпляр класса[`PsdImage`](../../psdimage)с указанными шириной, высотой, палитрой, цветом режим, количество каналов и разрядность каналов, а также заданные параметры режима сжатия. Используется для инициализации пустого изображения psd.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |
| colorPalette | IColorPalette | Цветовая палитра. |
| colorMode | ColorModes | Цветовой режим. |
| channelBitDepth | Int16 | Битовая глубина PSD на канал. |
| channels | Int16 | Количество каналов PSD. |
| psdVersion | Int32 | Версия PSD. |
| compression | CompressionMethod | Используемое сжатие. |

### Смотрите также

* interface [IColorPalette](../../../aspose.psd/icolorpalette)
* enum [ColorModes](../../colormodes)
* enum [CompressionMethod](../../compressionmethod)
* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
