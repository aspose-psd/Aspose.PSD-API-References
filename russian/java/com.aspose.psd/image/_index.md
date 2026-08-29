---
title: "Image"
second_title: "Aspose.PSD for Java API Справочник"
description: "Image является базовым классом для всех типов изображений."
type: docs
weight: 54
url: /ru/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

Image является базовым классом для всех типов изображений.
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
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового DataStreamSupporter.DataStreamContainer не будет выполнена. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Определяет, может ли изображение быть загружено из указанного потока. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанных loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Определяет, может ли изображение быть загружено из указанного пути к файлу. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными save options. |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Преобразует в aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Создаёт новое изображение, используя указанные create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Создаёт новое изображение из указанных изображений в качестве страниц. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Получает значение, указывающее, включена ли автоматическая настройка палитры. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает значение цвета фона. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getBounds()](#getBounds--) | Получает границы изображения. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Получает контейнер  Image  . |
| [getDataStreamContainer()](#getDataStreamContainer--) | Получает поток данных объекта. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Получает глубоко настроенную палитру. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Получает формат файла. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Получает формат файла. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Получает формат файла. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Получает прямоугольник, который охватывает текущее изображение. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Получает прямоугольник, который охватывает текущее изображение. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Получает монитор прерываний. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Получает менеджер памяти. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает параметры, основанные на настройках оригинального файла. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Получает рисуемое изображение. |
| [getPalette()](#getPalette--) | Получает цветовую палитру. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Создает приватный кеш шрифтов. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает информацию обработчика события прогресса. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Получает информацию обработчика события прогресса. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Получает пропорциональную высоту. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Получает пропорциональную ширину. |
| [getSize()](#getSize--) | Получает размер изображения. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Получает путь к файлу исходного изображения, если он существует. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Получает значение, указывающее, использует ли объект стратегию оптимизации памяти |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Получает лицензию предприятия. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Получает значение, указывающее, имеет ли изображение цвет фона. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Получает или задает значение, указывающее, изменилось ли это изображение после загрузки. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Получает или задает максимальное значение прогресса |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Указывает прогресс. |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных. |
| [isUsePalette()](#isUsePalette--) | Получает значение, указывающее, используется ли палитра изображения. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загружает новое изображение из указанного потока. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Загружает новое изображение из указанного потока. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [load(String filePath)](#load-java.lang.String-) | Загружает новое изображение из указанного файла. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного файла. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Загружает новое изображение из указанного потока. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Вызывается, когда контейнер этого [Image](../../com.aspose.psd/image) был установлен. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Изменяет высоту пропорционально. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Изменяет высоту пропорционально. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Изменяет высоту пропорционально. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Изменяет ширину пропорционально. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Изменяет ширину пропорционально. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Изменяет ширину пропорционально. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Устанавливает значение, указывающее, следует ли автоматически корректировать палитру. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Получает или задает значение цвета фона. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Устанавливает контейнер Image. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Устанавливает поток данных объекта. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Устанавливает значение, указывающее, следует ли [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Получает или задает значение, указывающее, изменилось ли это изображение после загрузки. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Устанавливает монитор прерываний. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Устанавливает менеджер памяти. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Устанавливает цветовую палитру. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Устанавливает палитру изображения. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Все продукты Aspose должны реализовывать этот метод. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Преобразует в aps.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры изображения. |
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
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Получает высоту изображения.

**Returns:**
int - Высота изображения.
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
### getSize() {#getSize--}
```
public Size getSize()
```


Получает размер изображения.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Получает путь к файлу исходного изображения, если он существует. Возвращает пустую строку, если не удаётся найти исходный путь.

**Returns:**
java.lang.String - Путь к файлу исходного изображения.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Получает значение, указывающее, использует ли объект стратегию оптимизации памяти

Значение:  true  если объект использует стратегию оптимизации памяти; иначе,  false .

**Returns:**
boolean - значение, указывающее, использует ли объект стратегию оптимизации памяти
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Получает лицензию предприятия.

**Returns:**
java.lang.Object - Лицензия предприятия в виде объекта.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Получает ширину изображения.

**Returns:**
int - Ширина изображения.
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Устанавливает поток данных объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Поток данных объекта. |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Устанавливает палитру изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Палитра для установки. |
| updateColors | boolean | если установлено в  true  цвета будут обновлены в соответствии с новой палитрой; иначе индексы цветов останутся без изменений. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Все продукты Aspose должны реализовать этот метод. Он вызывается продуктом GroupDocs, чтобы указать, лицензирован ли сам GroupDocs, и задать пользовательский водяной знак. Когда GroupDocs лицензирован, этот экземпляр документа также должен вести себя как лицензированный, даже если продукт Aspose не лицензирован.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

