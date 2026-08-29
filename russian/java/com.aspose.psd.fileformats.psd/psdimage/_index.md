---
title: "PsdImage"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет класс PsdImage, который предоставляет возможность загружать, редактировать и сохранять PSD‑файлы, а также обновлять свойства, добавлять водяные знаки, выполнять графические операции или конвертировать один формат файла в другой."
type: docs
weight: 14
url: /ru/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Определяет класс PsdImage, который предоставляет возможность загружать, редактировать, сохранять PSD‑файлы, а также обновлять свойства, добавлять водяные знаки, выполнять графические операции или конвертировать один формат файла в другой. Aspose.PSD поддерживает импорт в виде слоя и экспорт в следующие форматы: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, а также экспорт в Pdf с выделяемым текстом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути из растрового изображения (не PSD‑изображения в пути). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути из растрового изображения (не PSD‑изображения в пути) с параметрами конструктора. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути из растрового изображения (не PSD‑изображения в потоке). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути из растрового изображения (не PSD‑изображения в потоке) с параметрами конструктора. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из существующего растрового изображения (не PSD‑изображения) с режимом цвета RGB, 4 каналами, 8 бит/канал и без сжатия. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из существующего растрового изображения (не PSD‑изображения) с параметрами конструктора. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) с указанной шириной и высотой. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) с указанными шириной, высотой, палитрой, режимом цвета, количеством каналов и битовой глубиной каналов, а также с указанными параметрами режима сжатия. |
## Поля

| Поле | Описание |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Имя кодировки по умолчанию |
| [DefaultVersion](#DefaultVersion) | Версия PSD по умолчанию. |
| [OnCreate_internalized](#OnCreate-internalized) | Происходит, когда изображение загружено |
| [OnLoad_internalized](#OnLoad-internalized) | Происходит, когда изображение загружено методом createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Происходит, когда изображение загружено или сохранено |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Происходит, когда кредит был использован |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Объект, который можно использовать для синхронизации доступа к слоям. |
| [horizontalResolution](#horizontalResolution) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Добавляет слой корректировки черно‑белого. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Добавляет слой корректировки яркости/контрастности. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Добавляет слой корректировки микшера каналов с параметрами по умолчанию |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Добавляет слой корректировки цветового баланса. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Добавляет слой корректировки кривых. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Добавляет слой коррекции экспозиции. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Добавляет слой коррекции GradientMap. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Добавляет слой коррекции тона/насыщенности. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Добавляет слой инвертирования. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Добавляет слой. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Добавляет группу слоев. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Добавляет слой по индексу. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Добавляет слой коррекции уровней. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Добавляет слой фотофильтра. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Добавляет слой коррекции Posterize. |
| [addRegularLayer()](#addRegularLayer--) | Добавляет новый обычный слой. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Добавляет слой коррекции избирательного цвета. |
| [addShapeLayer()](#addShapeLayer--) | Добавить пустой слой Shape. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Добавляет новый слой Text. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Добавляет слой коррекции порога. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Добавляет слой коррекции яркости. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулировка яркости изображения. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Контрастирование изображения |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Гамма‑коррекция изображения. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция изображения. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Начинает процесс изменения размера. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли на основе интегрального изображения |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли на основе интегрального изображения |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Бинаризация изображения с предопределённым порогом. |
| [binarizeOtsu()](#binarizeOtsu--) | Бинаризация изображения с порогом Оцу. |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового DataStreamSupporter.DataStreamContainer не будет выполнена. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Определяет, может ли изображение быть загружено из указанного потока. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанных loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Определяет, может ли изображение быть загружено из указанного пути к файлу. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными save options. |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Преобразует формат этого изображения в указанный в параметрах. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Преобразует в aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Создаёт новое изображение, используя указанные create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Создаёт новое изображение из указанных изображений в качестве страниц. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Создаёт новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Обрезка изображения. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрезать изображение со смещениями. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Выполняет дизеринг текущего изображения. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Выполняет дизеринг текущего изображения. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Обрезка изображения. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Изменяет размер изображения. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Фильтрует указанный прямоугольник. |
| [flattenImage()](#flattenImage--) | Объединяет все слои. |
| [getActiveLayer()](#getActiveLayer--) | Получает или задаёт активный слой. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Получает 32-битный ARGB‑пиксель изображения. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Получает значение, указывающее, включена ли автоматическая настройка палитры. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает значение цвета фона. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Получает или задаёт цвет фона. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Получает количество бит на канал. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getBounds()](#getBounds--) | Получает границы изображения. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getChannelsCount()](#getChannelsCount--) | Получает количество каналов PSD. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Получает или задаёт профиль CMYK для CMYK PSD‑изображений. |
| [getColorMode()](#getColorMode--) | Получает или задаёт режим цвета. |
| [getCompression()](#getCompression--) | Получает метод сжатия. |
| [getContainer()](#getContainer--) | Получает контейнер  Image  . |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Получает текущие параметры изображения. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Получает поток данных объекта. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Получает глубоко настроенную палитру. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Получает массив пикселей по умолчанию 32-bit ARGB. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Получает массив необработанных данных по умолчанию. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Получает или задает шрифт замены по умолчанию. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Получает формат файла. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Получает формат файла. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Получает формат файла. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Получает прямоугольник, который охватывает текущее изображение. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Получает прямоугольник, который охватывает текущее изображение. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Получает палитру из специфических для формата мест. |
| [getGlobalAngle()](#getGlobalAngle--) | Получает или задает глобальный угол. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Получает информацию о глобальной маске слоя. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Получает или задает глобальные ресурсы слоя. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Получает или задает профиль цвета GRAY (монохромный) для градационных PSD‑изображений. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Получает или задает слои PSD. |
| [getImageOpacity()](#getImageOpacity--) | Получает непрозрачность этого изображения. |
| [getImageResources()](#getImageResources--) | Получает или задает ресурсы изображения PSD. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Получает внутренний трансформер данных. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Получает монитор прерываний. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Получает слой и маску. |
| [getLayers()](#getLayers--) | Получает или задает слои PSD. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Получает менеджер связанных слоев. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Получает или задает максимальное разрешённое выделение памяти для частичного сохранения вращения. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Получает менеджер памяти. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Получает дату и время последнего изменения ресурсного изображения. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Получает параметры, основанные на настройках оригинального файла. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Получает рисуемое изображение. |
| [getPalette()](#getPalette--) | Получает цветовую палитру. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Получает пиксель изображения. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Создает приватный кеш шрифтов. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает информацию обработчика события прогресса. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Получает информацию обработчика события прогресса. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Получает пропорциональную высоту. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Получает пропорциональную ширину. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Получает или задает заголовок PSD. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Получает или задает пользовательский конвертер цветов |
| [getRawDataFormat()](#getRawDataFormat--) | Получает формат необработанных данных. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Получает или задает индексированный конвертер цветов |
| [getRawLineSize()](#getRawLineSize--) | Получает размер необработанной строки в байтах. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Получает или задает профиль цвета RGB для CMYK PSD‑изображений. |
| [getRotateMode()](#getRotateMode--) | Получает или задает режим вращения. |
| [getSize()](#getSize--) | Получает размер изображения. |
| [getSkewAngle()](#getSkewAngle--) | Получает угол наклона. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Получает поставщик смарт‑объектов. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Получает путь к файлу исходного изображения, если он существует. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Получает корень синхронизации. |
| [getTimeline()](#getTimeline--) | Получает Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет изображения. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Получает обновлённые ресурсы с совершенно новым блоком ресурсов. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Получает значение, указывающее, использует ли объект стратегию оптимизации памяти |
| [getUseRawData()](#getUseRawData--) | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда загрузка необработанных данных доступна. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Получает используемую палитру. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Получает лицензию предприятия. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [getVerticalResolution()](#getVerticalResolution--) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getXmpData()](#getXmpData--) | Получает или задает метаданные XMP. |
| [grayscale()](#grayscale--) | Преобразование изображения в его градацию серого |
| [hasAlpha()](#hasAlpha--) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого RasterImage. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Получает значение, указывающее, имеет ли изображение цвет фона. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Получает или задает значение, указывающее, изменилось ли это изображение после загрузки. |
| [hasTransparencyData()](#hasTransparencyData--) | Получает или задает значение, указывающее, содержит ли первый альфа‑канал данные прозрачности для объединённого результата при указании данных слоёв. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Получает или задает максимальное значение прогресса |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Указывает прогресс. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Вставляет слой после указанного слоя со всеми подготовительными действиями. |
| [isCached()](#isCached--) | Получает значение, указывающее, кэшируются ли данные изображения в данный момент. |
| [isFlatten()](#isFlatten--) | Получает значение, указывающее, является ли PSD‑изображение сплющенным. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [isUsePalette()](#isUsePalette--) | Получает значение, указывающее, используется ли палитра изображения. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загружает новое изображение из указанного потока. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Загружает новое изображение из указанного потока. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [load(String filePath)](#load-java.lang.String-) | Загружает новое изображение из указанного файла. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного файла. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Загружает 32-битные пиксели ARGB. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Загружает 64-битные пиксели ARGB. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Загружает пиксели в формате CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Загружает пиксели в формате CMYK. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Частично загружает 32-битные пиксели ARGB пакетами. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Частично загружает пиксели пакетами. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Загружает пиксели. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Загружает необработанные данные изображения, используя механизм частичной обработки. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Загружает необработанные данные. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Загружает новое изображение из указанного потока. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Объединяет слои. |
| [normalizeAngle()](#normalizeAngle--) | Нормализует угол. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Нормализует угол. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Вызывается, когда контейнер этого [Image](../../com.aspose.psd/image) был установлен. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Удаляет глобальный ресурс текстового движка — метод используется для некоторых PSD‑файлов с текстовыми слоями, которые после обработки нельзя открыть в Adobe Photoshop (в основном из‑за отсутствующих шрифтов, связанных с текстовыми слоями). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Заменяет один цвет другим с допустимой разницей и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Заменяет один цвет другим с допустимой разницей и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Заменяет все непрозрачные цвета новым цветом и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Заменяет все непрозрачные цвета новым цветом и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Изменяет высоту пропорционально. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Изменяет высоту пропорционально. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Изменяет высоту пропорционально. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Изменяет ширину пропорционально. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Изменяет ширину пропорционально. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Изменяет ширину пропорционально. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Изменяет размер слоя с указанным обратным масштабом. |
| [rotate(float angle)](#rotate-float-) | Вращает изображение вокруг центра. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Вращает изображение вокруг центра. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Сохраняет данные изображения в базовый поток. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет данные объекта в указанный поток. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Сохраняет данные объекта в указанный поток. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Сохраняет данные объекта в указанное файловое расположение в указанном файловом формате согласно параметрам сохранения. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет данные объекта в указанное файловое расположение. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Сохраняет данные объекта в указанное файловое расположение. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Сохраняет данные объекта в указанное файловое расположение в указанном файловом формате согласно параметрам сохранения. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Сохраняет данные объекта в указанное файловое расположение в указанном файловом формате согласно параметрам сохранения. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Сохраняет 32-битные пиксели ARGB. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Сохраняет пиксели. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Сохраняет пиксели. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Сохраняет пиксели. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Сохраняет необработанные данные. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Сохраняет данные изображения в указанный поток, используя заданные параметры сохранения и границы. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Получает или задаёт активный слой. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Устанавливает значение, указывающее, следует ли автоматически корректировать палитру. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Получает или задает значение цвета фона. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Получает или задаёт цвет фона. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Получает или задаёт профиль CMYK для CMYK PSD‑изображений. |
| [setColorMode(short value)](#setColorMode-short-) | Получает или задаёт режим цвета. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Устанавливает контейнер Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Устанавливает загрузчик данных напрямую. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Устанавливает поток данных объекта. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Устанавливает палитру в места, специфичные для формата. |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | Глобальный угол. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Получает или задает глобальные ресурсы слоя. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Профиль цвета GRAY (монохромный) для градационных PSD‑изображений. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Устанавливает значение, указывающее, следует ли [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Получает или задает значение, указывающее, изменилось ли это изображение после загрузки. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Получает или задает ресурсы изображения PSD. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Устанавливает внутренний трансформатор данных. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Устанавливает монитор прерываний. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Получает или задает слои PSD. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Получает или задает максимальное разрешённое выделение памяти для частичного сохранения вращения. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Устанавливает менеджер памяти. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Устанавливает цветовую палитру. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Устанавливает палитру изображения. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Устанавливает пиксель изображения для указанной позиции. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Получает или задает пользовательский конвертер цветов |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Получает или задает индексированный конвертер цветов |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Устанавливает разрешение для этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Получает или задает профиль цвета RGB для CMYK PSD‑изображений. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Получает или задает режим вращения. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Получает или задает значение, указывающее, содержит ли первый альфа‑канал данные прозрачности для объединённого результата при указании данных слоёв. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Получает прозрачный цвет изображения. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда загрузка необработанных данных доступна. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Устанавливает лицензию предприятия. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Получает или задает метаданные XMP. |
| [toBitmap()](#toBitmap--) | Преобразует растровое изображение в bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Создаёт новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути к растровому изображению (не PSD‑файлу в пути). Используется для инициализации PSD‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь для загрузки пиксельных и палитровых данных и их инициализации. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути из растрового изображения (не PSD‑изображения в пути) с параметрами конструктора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь для загрузки пиксельных и палитровых данных и их инициализации. |
| colorMode | short | Цветовой режим. |
| channelBitDepth | short | Глубина цвета PSD на канал. |
| channels | short | Количество каналов PSD. |
| psdVersion | int | Версия PSD. |
| compression | short | Сжатие, которое будет использоваться. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Создаёт новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути к растровому изображению (не PSD‑файлу в потоке). Используется для инициализации PSD‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки пиксельных и палитровых данных и их инициализации. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из указанного пути из растрового изображения (не PSD‑изображения в потоке) с параметрами конструктора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки пиксельных и палитровых данных и их инициализации. |
| colorMode | short | Цветовой режим. |
| channelBitDepth | short | Глубина цвета PSD на канал. |
| channels | short | Количество каналов PSD. |
| psdVersion | int | Версия PSD. |
| compression | short | Сжатие, которое будет использоваться. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из существующего растрового изображения (не PSD‑изображения) с режимом цвета RGB, 4 каналами, 8 бит/канал и без сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Изображение для загрузки пиксельных и палитровых данных и их инициализации. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Инициализирует новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) из существующего растрового изображения (не PSD‑изображения) с параметрами конструктора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Изображение для загрузки пиксельных и палитровых данных и их инициализации. |
| colorMode | short | Цветовой режим. |
| channelBitDepth | short | Глубина цвета PSD на канал. |
| channels | short | Количество каналов PSD. |
| psdVersion | int | Версия PSD. |
| compression | short | Сжатие, которое будет использоваться. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Создаёт новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) с указанной шириной и высотой. Используется для инициализации пустого PSD‑изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Ширина изображения. |
| высота | int | Высота изображения. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Создаёт новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) с указанными шириной, высотой, paletter, режимом цвета, количеством каналов и разрядностью каналов, а также параметрами режима сжатия. Используется для инициализации пустого PSD‑изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Ширина изображения. |
| высота | int | Высота изображения. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |
| colorMode | short | Цветовой режим. |
| channelBitDepth | short | Глубина цвета PSD на канал. |
| channels | short | Количество каналов PSD. |
| psdVersion | int | Версия PSD. |
| compression | short | Сжатие, которое будет использоваться. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Имя кодировки по умолчанию

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


Версия PSD по умолчанию.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Происходит, когда изображение загружено

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Происходит, когда изображение загружено методом createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Происходит, когда изображение загружено или сохранено

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Происходит, когда кредит был использован

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Объект, который можно использовать для синхронизации доступа к слоям.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Добавляет слой корректировки черно‑белого.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Добавляет слой корректировки яркости/контрастности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Яркость. |
| contrast | int | Контраст. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Добавляет слой корректировки микшера каналов с параметрами по умолчанию

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Добавляет слой корректировки цветового баланса.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Добавляет слой корректировки кривых.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exposure | float |  |
| смещение | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Добавляет слой коррекции экспозиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exposure | float | Экспозиция. |
| смещение | float | Смещение. |
| gammaCorrection | float | Гамма‑коррекция. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Добавляет слой коррекции GradientMap.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Добавляет слой коррекции тона/насыщенности.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Добавляет слой инвертирования.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Добавляет слой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Добавляет группу слоев.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| groupName | java.lang.String | Имя группы. |
| индекс | int | Индекс слоя, после которого нужно вставить. |
| startBehaviour | boolean | если установить значение  true  [start behaviour] тогда группа будет в открытом состоянии при запуске, иначе в свернутом состоянии. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Добавляет слой по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой. |
| индекс | int | Индекс. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Добавляет слой коррекции уровней.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Добавляет слой фотофильтра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Цвет. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Добавляет слой коррекции Posterize.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Добавляет новый обычный слой.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Добавляет слой коррекции избирательного цвета.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Добавьте пустой слой Shape. Без путей. Их следует добавить в слой shape перед сохранением.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Добавляет новый слой Text.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Текст слоя. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник слоя. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Добавляет слой коррекции порога.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Добавляет слой коррекции яркости.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Регулировка яркости изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Контрастирование изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Гамма‑коррекция изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gamma | float | Коэффициент гаммы для красного, зелёного и синего каналов |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Гамма‑коррекция изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Начинает процесс изменения размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина изображения. |
| newHeight | int | Новая высота изображения. |

**Returns:**
com.aspose.internal.IResizeController - контроллер изменения размера.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли на основе интегрального изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли на основе интегрального изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |
| windowSize | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Бинаризация изображения с предопределённым порогом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Бинаризация изображения с порогом Оцу.

### cacheData() {#cacheData--}
```
public void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных из базового DataStreamSupporter.DataStreamContainer не будет выполнена.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Определяет, может ли изображение быть загружено из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружать. |

**Returns:**
boolean -  true  если изображение может быть загружено из указанного потока; иначе,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанных loadOptions.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружать. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
boolean -  true  если изображение может быть загружено из указанного потока; иначе,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Определяет, может ли изображение быть загружено из указанного пути к файлу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |

**Returns:**
boolean -  true  если изображение может быть загружено из указанного файла; иначе,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных open options.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
boolean -  true  если изображение может быть загружено из указанного файла; иначе,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными save options.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения для использования. |

**Returns:**
boolean -  true  если изображение может быть сохранено в указанный формат файла, представленный переданными параметрами сохранения; иначе,  false .
### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Преобразует формат этого изображения в указанный в параметрах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Новые параметры. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Преобразует в aps.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры. |
| mode | int | Режим. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник обрезки. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - страница APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Создаёт новое изображение, используя указанные create options.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры изображения. |
| ширина | int | Ширина. |
| высота | int | Высота. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Создаёт новое изображение, используя указанные изображения в качестве страниц

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Изображения. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Создаёт новое изображение из указанных изображений в качестве страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Изображения. |
| disposeImages | boolean | если установлено в  true  [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Создаёт новый экземпляр класса [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | Заголовок PSD. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Данные цвета. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Ресурсы изображения. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Информация о слое и маске. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Данные изображения. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |
| version | int | Версия PSD. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |
| noLayerLoad | boolean | Не загружать слой |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| ширина | int |  |
| высота | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезка изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Обрезать изображение со смещениями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Смещение влево. |
| rightShift | int | Сдвиг вправо. |
| topShift | int | Сдвиг вверх. |
| bottomShift | int | Сдвиг вниз. |

### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Выполняет дизеринг текущего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Выполняет дизеринг текущего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Пользовательская палитра для дизеринга. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Обрезка изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Настройки изменения размера. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Фильтрует указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Параметры. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Объединяет все слои.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Получает или задаёт активный слой.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Получает 32-битный ARGB‑пиксель изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Позиция пикселя по оси x. |
| y | int | Позиция пикселя по оси y. |

**Returns:**
int - 32-битный ARGB пиксель для указанного положения.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Получает значение, указывающее, включена ли автоматическая настройка палитры.

**Returns:**
boolean -  true  если включена автоматическая корректировка палитры; иначе,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает или задает значение цвета фона.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Получает или задает цвет фона. Он виден под прозрачными объектами.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Получает количество бит на канал.

Значение: Биты на канал.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

Значение: количество бит на пиксель изображения.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает границы изображения.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int - подсказка размера буфера, определяющая максимальный допустимый размер для всех внутренних буферов.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Получает количество каналов PSD.

Значение: Количество каналов PSD.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


Получает или задает CMYK профиль цвета для CMYK PSD изображений. Должен использоваться вместе с RgbColorProfile для корректного преобразования цветов.

Значение: CMYK цветовой профиль.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Получает или задаёт режим цвета.

Значение: Режим цвета.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Получает метод сжатия.

Значение: Сжатие.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Получает контейнер  Image  .

Значение: Контейнер Image.

Если это свойство не равно null, это указывает, что изображение находится внутри другого изображения.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Получает текущие параметры изображения.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Получает поток данных объекта.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Получает глубоко настроенную палитру.

**Returns:**
boolean - Глубокая настройка палитры.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Получает массив пикселей по умолчанию 32-bit ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, для которого получаются пиксели. |

**Returns:**
int[] - Массив пикселей по умолчанию.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Получает параметры по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| аргументы | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, для которого получаются пиксели. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, для которого получаются пиксели. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Частичный загрузчик необработанных данных. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Настройки необработанных данных. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Получает массив необработанных данных по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, для которого получаются необработанные данные. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Настройки необработанных данных. |

**Returns:**
byte[] - Массив необработанных данных по умолчанию.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Получает или задает шрифт замены по умолчанию. Если шрифт замены установлен, он будет использоваться для рендеринга. Нам нужен этот метод для внутренней поддержки

**Returns:**
java.lang.String - Имя шрифта замены
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получает значение формата файла

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Получает формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Поток. |

--------------------

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли быть загружен поток. |

**Returns:**
long - Определённый формат файла.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Получает формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток. |

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли быть загружен поток. |

**Returns:**
long - Определённый формат файла.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Получает формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу. |

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли быть загружен файл. |

**Returns:**
long - Определённый формат файла.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Получает прямоугольник, который охватывает текущее изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, для которого нужно получить подходящий прямоугольник. |
| ширина | int | Ширина объекта. |
| высота | int | Высота объекта. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Получает прямоугольник, который охватывает текущее изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, для которого нужно получить подходящий прямоугольник. |
| пиксели | int[] | 32-битные ARGB пиксели. |
| ширина | int | Ширина объекта. |
| высота | int | Высота объекта. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Получает палитру из специфических для формата мест.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Получает или задает глобальный угол.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Получает информацию о глобальной маске слоя.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Получает или задает глобальные ресурсы слоя.

Значение: глобальные ресурсы слоёв.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Получает или задает профиль цвета GRAY (монохромный) для градационных PSD‑изображений.

Значение: GRAY (монохромный) цветовой профиль.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

Значение: Высота изображения.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Получает или задает слои PSD.

Значение: слои PSD.

--------------------

Обратите внимание, что если слоёв нет, другая связанная информация в разделе информации о слоях и масках не будет сохранена (маски слоёв, ресурсы и т.д.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Получает непрозрачность этого изображения.

**Returns:**
float - Значение непрозрачности от 0.0 (полностью прозрачный) до 1.0 (полностью непрозрачный).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Получает или задает ресурсы изображения PSD.

Значение: ресурсы изображения PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Получает внутренний трансформер данных.

Значение: Внутренний трансформер данных.

**Returns:**
com.aspose.internal.IInnerDataTransformer - внутренний трансформер данных.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Получает монитор прерываний.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Получает слой и маску.

Значение: слой и маска.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Получает или задает слои PSD.

Значение: слои PSD.

--------------------

Обратите внимание, что если слоёв нет, другая связанная информация в разделе информации о слоях и масках не будет сохранена (маски слоёв, ресурсы и т.д.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Получает менеджер связанных слоев.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Получает или задает максимальное разрешённое выделение памяти для частичного сохранения вращения.

**Returns:**
int - Максимальное допустимое выделение памяти для частичного сохранения вращения.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Получает менеджер памяти.

Значение: Менеджер памяти.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr — менеджер памяти.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Получает дату и время последнего изменения ресурсного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| useDefault | boolean | если установлено в  true  использует информацию из FileInfo как значение по умолчанию. |

**Returns:**
java.util.Date — Дата и время последнего изменения ресурсного изображения.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений. Например, если мы загрузим чёрно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его, используя метод  DataStreamSupporter.Save(string) , будет получено PNG‑изображение с 8‑битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их в метод  Image.Save(string, ImageOptionsBase)  в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Получает рисуемое изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Получает пиксель изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Позиция пикселя по оси x. |
| y | int | Позиция пикселя по оси y. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены.

**Returns:**
boolean -  true  если компоненты изображения должны быть предварительно умножены; иначе,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Создает приватный кеш шрифтов.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache — Частный кэш шрифтов.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Получает информацию обработчика события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Получает информацию обработчика события прогресса.

Значение: Информация обработчика события прогресса.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Получает пропорциональную высоту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Ширина. |
| высота | int | Высота. |
| newWidth | int | Новая ширина. |

**Returns:**
int - Пропорциональная высота.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Получает пропорциональную ширину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Ширина. |
| высота | int | Высота. |
| newHeight | int | Новая высота. |

**Returns:**
int - Пропорциональная ширина.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Получает или задает заголовок PSD.

Значение: заголовок PSD.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Получает или задает пользовательский конвертер цветов

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Получает формат необработанных данных.

Значение: формат необработанных данных.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без конвертации.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы

**Returns:**
int - Запасной индекс, используемый, когда индекс палитры выходит за пределы.
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Получает или задает индексированный конвертер цветов

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Получает размер необработанной строки в байтах.

**Returns:**
int - Размер необработанной строки в байтах.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Получает или задает RGB цветовой профиль для изображений CMYK PSD. Должен использоваться вместе с CmykColorProfile для корректного преобразования цветов.

Значение: RGB цветовой профиль.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Получает или задает режим вращения.

**Returns:**
int - Режим вращения.
### getSize() {#getSize--}
```
public Size getSize()
```


Получает размер изображения.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Получает угол наклона. Этот метод применим к отсканированным текстовым документам, чтобы определить угол наклона при сканировании.

**Returns:**
float - Угол наклона в градусах.
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Получает поставщик смарт‑объектов.

Значение: поставщик смарт‑объектов.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Получает путь к файлу исходного изображения, если он существует. Возвращает пустую строку, если не удаётся найти исходный путь.

**Returns:**
java.lang.String - Путь к файлу исходного изображения.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Получает корень синхронизации.

Значение: Корень синхронизации.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Получает Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Получает прозрачный цвет изображения.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Получает или задает значение, указывающее, следует ли обновлять метаданные XMP.

**Returns:**
boolean -  true  если обновлять метаданные XMP; иначе,  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Получает обновлённые ресурсы с совершенно новым блоком ресурсов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Ресурсы. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | Ресурс для добавления к существующим ресурсам. |
| removeDuplicates | boolean | если установлено в  true  удаляет ресурсы с одинаковыми идентификаторами. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Возвращает массив с обновлёнными блоками ресурсов.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Получает значение, указывающее, использует ли объект стратегию оптимизации памяти

Значение:  true  если объект использует стратегию оптимизации памяти; иначе,  false .

**Returns:**
boolean - значение, указывающее, использует ли объект стратегию оптимизации памяти
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда загрузка необработанных данных доступна.

**Returns:**
boolean -  true  если использовать загрузку необработанных данных, когда она доступна; иначе,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Получает используемую палитру.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Получает лицензию предприятия.

**Returns:**
java.lang.Object - Лицензия предприятия в виде объекта.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает или задает версию.

Значение: Версия.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

Значение: Ширина изображения.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает или задает метаданные XMP.

Значение: XMP метаданные.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразование изображения в его градацию серого

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого RasterImage.

Значение:  true  если у этого экземпляра есть альфа-канал; иначе,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Получает значение, указывающее, имеет ли изображение цвет фона.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Получает или задает значение, указывающее, изменилось ли это изображение после загрузки.

Значение:  true  если у этого экземпляра изменено изображение; иначе  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Получает или задает значение, указывающее, содержит ли первый альфа‑канал данные прозрачности для объединённого результата при указании данных слоёв.

Значение:  true  если первый альфа‑канал содержит данные прозрачности для объединённого результата при указании данных слоёв; иначе  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Получает значение, указывающее, имеет ли изображение прозрачный цвет.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Получает или задает максимальное значение прогресса

Значение: Максимальное значение прогресса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Указывает прогресс.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Вставляет слой после указанного слоя со всеми подготовительными действиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой для вставки. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Получает значение, указывающее, кэшируются ли данные изображения в данный момент.

**Returns:**
boolean -  true  если данные изображения кэшированы; иначе,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Получает значение, указывающее, является ли PSD‑изображение сплющенным.

Значение:  true  если этот экземпляр уплощён; иначе  false .

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Получает значение, указывающее, доступна ли загрузка необработанных данных.

**Returns:**
boolean -  true  если загрузка необработанных данных доступна; иначе,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Получает значение, указывающее, используется ли палитра изображения.

Значение:  true  если палитра используется в изображении; иначе,  false .

**Returns:**
boolean - значение, указывающее, используется ли палитра изображения.
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл, из которого загружается изображение. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл, из которого загружается изображение. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Загружает новое изображение из указанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, из которого загружается изображение. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Загружает новое изображение из указанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, из которого загружается изображение. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Загружает 32-битные пиксели ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
int[] — массив загруженных 32‑битных ARGB пикселей.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Загружает 64-битные пиксели ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
long[] — массив загруженных 64‑битных ARGB пикселей.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Загружает пиксели в формате CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
int[] — массив загруженных CMYK пикселей, представленных как 32‑битные целочисленные значения.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Загружает пиксели в формате CMYK. Этот метод устарел. Пожалуйста, используйте более эффективный метод loadCmyk32Pixels(Rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
com.aspose.psd.CmykColor[] — массив загруженных CMYK пикселей.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Частично загружает 32-битные пиксели ARGB пакетами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Желаемый прямоугольник. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Загрузчик 32‑битных ARGB пикселей. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Частично загружает пиксели пакетами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Желаемый прямоугольник. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Загрузчик пикселей. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Загружает пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются пиксели. |

**Returns:**
com.aspose.psd.Color[] — массив загруженных пикселей.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Загружает необработанные данные изображения, используя механизм частичной обработки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Желаемая прямоугольная область изображения, из которой загружаются данные. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Настройки необработанных данных. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Загружает необработанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы целевого изображения. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, если данные не в указанном формате, будет выполнено их преобразование. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, из которого загружается изображение. |
| startPosition | long | Начальная позиция, из которой загружается изображение. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, из которого загружается изображение. |
| startPosition | long | Начальная позиция, из которой загружается изображение. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Объединяет слои.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The bottom layer. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Верхний слой. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Нормализует угол. Этот метод применяется к отсканированным текстовым документам, чтобы избавиться от наклона сканирования. Этот метод использует [.getSkewAngle](../../null/\#getSkewAngle) и [.rotate(float)](../../null/\#rotate-float-) методы.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Нормализует угол. Этот метод применяется к отсканированным текстовым документам, чтобы избавиться от наклона сканирования. Этот метод использует [.getSkewAngle](../../null/\#getSkewAngle) и [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) методы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeProportionally | boolean | если установить в true размер вашего изображения будет изменён в соответствии с проекциями вращённого прямоугольника (угловые точки), в противном случае размеры останутся неизменными, а только внутреннее содержимое изображения будет вращаться. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Цвет фона. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Вызывается, когда контейнер этого [Image](../../com.aspose.psd/image) был установлен.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Индекс строки сканирования, начиная с нуля. |

**Returns:**
int[] — массив 32‑битных значений цвета ARGB строки сканирования.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Индекс строки сканирования, начиная с нуля. |

**Returns:**
com.aspose.psd.Color[] — массив значений цвета пикселей строки сканирования.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Удаляет глобальный ресурс текстового движка — метод используется для некоторых PSD‑файлов с текстовыми слоями, которые не могут быть открыты в Adobe Photoshop после обработки (в основном из‑за отсутствующих шрифтов в текстовых слоях). После использования этой опции пользователю необходимо выполнить следующее в открытом в Photoshop файле: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые окончательные изменения макета.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Заменяет один цвет другим с допустимой разницей и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Старый цвет, который будет заменён. |
| oldColorDiff | byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| newColor | [Color](../../com.aspose.psd/color) | Новый цвет, которым заменяется старый цвет. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Заменяет один цвет другим с допустимой разницей и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColorArgb | int | Значение ARGB старого цвета, которое будет заменено. |
| oldColorDiff | byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| newColorArgb | int | Значение ARGB нового цвета, которым заменяется старый цвет. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Новый цвет, которым заменяются непрозрачные цвета. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorArgb | int | Значение ARGB нового цвета, которым заменяются непрозрачные цвета. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Изменяет размер изображения. По умолчанию используется ResizeType.LeftTopToLeftTop.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Настройки изменения размера. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Изменяет высоту пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Изменяет высоту пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Изменяет высоту пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип изменения размера. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Изменяет размер слоя с указанным обратным масштабом. (новая ширина = старая ширина / масштаб; новая высота = старая высота / масштаб)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | double | Масштаб X. |
| scaleY | double | Масштаб Y. |
| resizeType | int | Тип изменения размера. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Вращает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Вращает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | если установить в true размер вашего изображения будет изменён в соответствии с проекциями вращённого прямоугольника (угловые точки), в противном случае размеры останутся неизменными, а только внутреннее содержимое изображения будет вращаться. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Цвет фона. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Сохраняет данные изображения в базовый поток.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет данные объекта в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения данных объекта. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения данных изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения данных изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Сохраняет данные объекта в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Поток для сохранения данных объекта. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Сохраняет данные объекта в указанное файловое расположение в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл для сохранения данных изображения. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл для сохранения данных изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет данные объекта в указанное файловое расположение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для сохранения данных объекта. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Сохраняет данные объекта в указанное файловое расположение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для сохранения данных объекта. |
| overWrite | boolean | если установлено в true, перезаписывает содержимое файла, иначе будет выполнено добавление. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Сохраняет данные объекта в указанное файловое расположение в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Сохраняет данные объекта в указанное файловое расположение в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Сохраняет 32-битные пиксели ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, в который сохраняются пиксели. |
| пиксели | int[] | Массив 32‑битных ARGB‑пикселей. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Сохраняет пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, в который сохраняются пиксели. |
| пиксели | int[] | Пиксели CMYK, представленные как 32‑битные целочисленные значения. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Сохраняет пиксели. Этот метод устарел. Пожалуйста, используйте более эффективный метод saveCmyk32Pixels(Rectangle, int[]).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, в который сохраняются пиксели. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Массив пикселей CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Сохраняет пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, в который сохраняются пиксели. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Массив пикселей. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Сохраняет необработанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Сырые данные. |
| dataOffset | int | Начальное смещение необработанных данных. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник необработанных данных. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Настройки необработанных данных, в которых находятся данные. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Сохраняет данные изображения в указанный поток, используя заданные параметры сохранения и границы. При необходимости экспортирует только указанные слои для предварительного просмотра рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, в который будут сохранены данные изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения для использования. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите значение Rectangle.Empty, чтобы использовать исходные границы. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Конкретные слои для экспорта. Значение null указывает на поведение по умолчанию — все слои. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток для сохранения данных изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Получает или задаёт активный слой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Позиция пикселя по оси x. |
| y | int | Позиция пикселя по оси y. |
| argb32Color | int | 32-битный пиксель ARGB для указанной позиции. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Устанавливает значение, указывающее, следует ли автоматически корректировать палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если включено автоматическое регулирование палитры; иначе false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Получает или задает значение, указывающее, имеет ли изображение фоновый цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Получает или задает значение цвета фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Получает или задает цвет фона. Он виден под прозрачными объектами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | подсказка размера буфера, определяющая максимальный разрешённый размер для всех внутренних буферов. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Получает или задает CMYK профиль цвета для CMYK PSD изображений. Должен использоваться вместе с RgbColorProfile для корректного преобразования цветов.

Значение: CMYK цветовой профиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Получает или задаёт режим цвета.

Значение: Режим цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Устанавливает контейнер Image.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Контейнер Image. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Устанавливает загрузчик данных напрямую.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Загрузчик данных. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Устанавливает поток данных объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Поток данных объекта. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Устанавливает палитру в места, специфичные для формата.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Новая 32-битная палитра ARGB. |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


Глобальный угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Получает или задает глобальные ресурсы слоя.

Значение: глобальные ресурсы слоёв.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Профиль цвета GRAY (монохромный) для градационных PSD‑изображений.

Значение: GRAY (монохромный) цветовой профиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Получает или задает горизонтальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Устанавливает значение, указывающее, следует ли [ignore after save].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если [ignore after save]; иначе false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Получает или задает значение, указывающее, изменилось ли это изображение после загрузки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если у этого экземпляра изменено изображение; иначе false. |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Получает или задает ресурсы изображения PSD.

Значение: ресурсы изображения PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Устанавливает внутренний трансформатор данных.

Значение: Внутренний трансформер данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.IInnerDataTransformer | внутренний трансформатор данных. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Устанавливает монитор прерываний.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | монитор прерываний. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Получает или задает слои PSD.

Значение: слои PSD.

--------------------

Обратите внимание, что если слоёв нет, другая связанная информация в разделе информации о слоях и масках не будет сохранена (маски слоёв, ресурсы и т.д.).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Получает или задает максимальное разрешённое выделение памяти для частичного сохранения вращения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальное разрешённое выделение памяти для частичного сохранения с поворотом. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Устанавливает менеджер памяти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Менеджер памяти. |
| needDispose | boolean | если установлено в  true  [нужна очистка]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Устанавливает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Устанавливает палитру изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Палитра для установки. |
| updateColors | boolean | если установлено в  true  цвета будут обновлены в соответствии с новой палитрой; иначе индексы цветов останутся без изменений. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Устанавливает пиксель изображения для указанной позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Позиция пикселя по оси x. |
| y | int | Позиция пикселя по оси y. |
| color | [Color](../../com.aspose.psd/color) | Цвет пикселя для указанной позиции. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true  если компоненты изображения должны быть предварительно умножены; иначе,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Получает или задает пользовательский конвертер цветов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Пользовательский конвертер цветов |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Запасной индекс, используемый, когда индекс палитры выходит за пределы |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Получает или задает индексированный конвертер цветов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Конвертер индексированных цветов |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Устанавливает разрешение для этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение, в точках на дюйм,  RasterImage . |
| dpiY | double | Вертикальное разрешение, в точках на дюйм,  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Получает или задает RGB цветовой профиль для изображений CMYK PSD. Должен использоваться вместе с CmykColorProfile для корректного преобразования цветов.

Значение: RGB цветовой профиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Получает или задает режим вращения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Режим вращения. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Получает или задает значение, указывающее, содержит ли первый альфа‑канал данные прозрачности для объединённого результата при указании данных слоёв.

Значение:  true  если первый альфа‑канал содержит данные прозрачности для объединённого результата при указании данных слоёв; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Получает значение, указывающее, имеет ли изображение прозрачный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Получает прозрачный цвет изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Получает или задает значение, указывающее, следует ли обновлять метаданные XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true  если обновлять метаданные XMP; иначе,  false . |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда загрузка необработанных данных доступна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true  если использовать загрузку необработанных данных, когда она доступна.; иначе,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Устанавливает лицензию предприятия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Лицензия предприятия. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Получает или задает версию.

Значение: Версия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Получает или задает метаданные XMP.

Значение: XMP метаданные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Преобразует растровое изображение в bitmap.

**Returns:**
java.awt.image.BufferedImage - Битмап
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Индекс строки сканирования, начиная с нуля. |
| argb32Pixels | int[] | Массив 32‑битных цветов ARGB для записи. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scanLineIndex | int | Индекс строки сканирования, начиная с нуля. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Массив цветов пикселей для записи. |

