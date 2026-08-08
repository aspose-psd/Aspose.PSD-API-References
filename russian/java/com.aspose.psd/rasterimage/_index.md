---
title: "RasterImage"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет растровое изображение, поддерживающее операции растровой графики."
type: docs
weight: 86
url: /ru/java/com.aspose.psd/rasterimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver
```

Представляет растровое изображение, поддерживающее операции растровой графики.
## Поля

| Поле | Описание |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Происходит, когда изображение загружено |
| [OnLoad_internalized](#OnLoad-internalized) | Происходит, когда изображение загружено методом createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Происходит, когда изображение загружено или сохранено |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Происходит, когда кредит был использован |
## Методы

| Метод | Описание |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулировка яркости изображения. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Контрастирование изображения |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Гамма‑коррекция изображения. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Гамма‑коррекция изображения. |
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
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Преобразует в aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Создаёт новое изображение, используя указанные create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Создаёт новое изображение из указанных изображений в качестве страниц. |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Обрезает указанный прямоугольник. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрезать изображение со смещениями. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Выполняет дизеринг текущего изображения. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Выполняет дизеринг текущего изображения. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Фильтрует указанный прямоугольник. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Получает 32-битный ARGB‑пиксель изображения. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Получает значение, указывающее, включена ли автоматическая настройка палитры. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает значение цвета фона. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getBounds()](#getBounds--) | Получает границы изображения. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Получает контейнер  Image  . |
| [getDataStreamContainer()](#getDataStreamContainer--) | Получает поток данных объекта. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Получает глубоко настроенную палитру. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Получает массив пикселей по умолчанию 32-bit ARGB. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Получает массив необработанных данных по умолчанию. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Получает формат файла. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Получает формат файла. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Получает формат файла. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Получает прямоугольник, который охватывает текущее изображение. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Получает прямоугольник, который охватывает текущее изображение. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Получает палитру из специфических для формата мест. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Получает непрозрачность этого изображения. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Получает монитор прерываний. |
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
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Получает или задает пользовательский конвертер цветов |
| [getRawDataFormat()](#getRawDataFormat--) | Получает формат необработанных данных. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Получает или задает индексированный конвертер цветов |
| [getRawLineSize()](#getRawLineSize--) | Получает размер необработанной строки в байтах. |
| [getSize()](#getSize--) | Получает размер изображения. |
| [getSkewAngle()](#getSkewAngle--) | Получает угол наклона. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Получает путь к файлу исходного изображения, если он существует. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет изображения. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Получает значение, указывающее, использует ли объект стратегию оптимизации памяти |
| [getUseRawData()](#getUseRawData--) | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда загрузка необработанных данных доступна. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Получает используемую палитру. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Получает лицензию предприятия. |
| [getVerticalResolution()](#getVerticalResolution--) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого RasterImage. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getXmpData()](#getXmpData--) | Получает или задает метаданные XMP. |
| [grayscale()](#grayscale--) | Преобразование изображения в его градацию серого |
| [hasAlpha()](#hasAlpha--) | Получает значение, указывающее, имеет ли этот экземпляр альфа-канал. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Получает значение, указывающее, имеет ли изображение цвет фона. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Получает или задает значение, указывающее, изменилось ли это изображение после загрузки. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Получает или задает максимальное значение прогресса |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Указывает прогресс. |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [isUsePalette()](#isUsePalette--) | Получает значение, указывающее, используется ли палитра изображения. |
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
| [normalizeAngle()](#normalizeAngle--) | Нормализует угол. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Нормализует угол. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Вызывается, когда контейнер этого [Image](../../com.aspose.psd/image) был установлен. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Заменяет один цвет другим с допустимой разницей и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Заменяет один цвет другим с допустимой разницей и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Заменяет все непрозрачные цвета новым цветом и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Заменяет все непрозрачные цвета новым цветом и сохраняет оригинальное альфа-значение, чтобы сохранить плавные края. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Изменяет размер изображения с расширенными параметрами. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Изменяет высоту пропорционально. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Изменяет высоту пропорционально. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Изменяет высоту пропорционально. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Изменяет ширину пропорционально. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Изменяет ширину пропорционально. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Изменяет ширину пропорционально. |
| [rotate(float angle)](#rotate-float-) | Вращает изображение вокруг центра. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Вращает изображение вокруг центра. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Сохраняет данные изображения в указанный поток в указанном файловом формате согласно параметрам сохранения. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Устанавливает значение, указывающее, следует ли автоматически корректировать палитру. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Получает или задает значение цвета фона. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Устанавливает контейнер Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Устанавливает загрузчик данных напрямую. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Устанавливает поток данных объекта. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Устанавливает палитру в места, специфичные для формата. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Устанавливает значение, указывающее, следует ли [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Получает или задает значение, указывающее, изменилось ли это изображение после загрузки. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Устанавливает монитор прерываний. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Устанавливает менеджер памяти. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Устанавливает цветовую палитру. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Устанавливает палитру изображения. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Устанавливает пиксель изображения для указанной позиции. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Получает или задает пользовательский конвертер цветов |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Получает или задает индексированный конвертер цветов |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Устанавливает разрешение для этого RasterImage. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Получает прозрачный цвет изображения. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда загрузка необработанных данных доступна. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Все продукты Aspose должны реализовывать этот метод. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Получает или задает вертикальное разрешение, в пикселях на дюйм, этого RasterImage. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Получает или задает метаданные XMP. |
| [toBitmap()](#toBitmap--) | Преобразует растровое изображение в bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
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
public abstract void cacheData()
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
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезает указанный прямоугольник.

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
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int - Количество бит на пиксель изображения.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Получает контейнер  Image  .

Значение: Контейнер Image.

Если это свойство не равно null, это указывает, что изображение находится внутри другого изображения.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Получает высоту изображения.

**Returns:**
int - Высота изображения.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получает или задает горизонтальное разрешение в пикселях на дюйм для этого RasterImage.

**Returns:**
double - Горизонтальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Получает непрозрачность этого изображения.

**Returns:**
float - Значение непрозрачности от 0.0 (полностью прозрачный) до 1.0 (полностью непрозрачный).
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Получает монитор прерываний.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Получает путь к файлу исходного изображения, если он существует. Возвращает пустую строку, если не удаётся найти исходный путь.

**Returns:**
java.lang.String - Путь к файлу исходного изображения.
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого RasterImage.

**Returns:**
double - Вертикальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Получает ширину изображения.

**Returns:**
int - Ширина изображения.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает или задает метаданные XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразование изображения в его градацию серого

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получает значение, указывающее, имеет ли этот экземпляр альфа-канал.

**Returns:**
boolean -  true  если у этого экземпляра есть альфа‑канал; иначе,  false .
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

**Returns:**
boolean -  true  если у этого экземпляра изменено изображение; иначе,  false .
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных.

**Returns:**
boolean — значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных.
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


Изменяет размер изображения с расширенными параметрами.

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
public abstract void rotateFlip(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип поворота и отражения. |

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
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Получает или задает горизонтальное разрешение в пикселях на дюйм для этого RasterImage.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | Горизонтальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Устанавливает монитор прерываний.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | монитор прерываний. |

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


Устанавливает разрешение для этого RasterImage.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение, в точках на дюйм,  RasterImage . |
| dpiY | double | Вертикальное разрешение, в точках на дюйм,  RasterImage . |

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


Все продукты Aspose должны реализовать этот метод. Он вызывается продуктом GroupDocs, чтобы указать, лицензирован ли сам GroupDocs, и задать пользовательский водяной знак. Когда GroupDocs лицензирован, этот экземпляр документа также должен вести себя как лицензированный, даже если продукт Aspose не лицензирован.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Получает или задает вертикальное разрешение, в пикселях на дюйм, этого RasterImage.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | Вертикальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Получает или задает метаданные XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Метаданные XMP. |

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

