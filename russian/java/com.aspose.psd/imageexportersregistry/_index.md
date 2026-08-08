---
title: "ImageExportersRegistry"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет реестр экспортеров изображений"
type: docs
weight: 57
url: /ru/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Представляет реестр экспортеров изображений
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Получает зарегистрированные дескрипторы экспортеров. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Получает зарегистрированные форматы экспорта. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Регистрирует указанный дескриптор экспортера изображений. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Регистрирует экспортер. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Снимает регистрацию экспортеру. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageExportersRegistry() {#ImageExportersRegistry--}
```
public ImageExportersRegistry()
```


### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для экспорта. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры сохранения, используемые для экспорта. |

--------------------

Первый экспортер фактически будет последним зарегистрированным. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для экспорта. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры. |

--------------------

Первый дескриптор экспортера фактически будет последним зарегистрированным. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Получает зарегистрированные дескрипторы экспортеров.

Значение: Зарегистрированные дескрипторы экспортеров.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Получает зарегистрированные форматы экспорта.

Значение: Зарегистрированные форматы экспорта.

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### register(IImageExporterDescriptor imageExporterDescriptor) {#register-com.aspose.psd.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor imageExporterDescriptor)
```


Регистрирует указанный дескриптор экспортера изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Дескриптор экспортера изображений. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Регистрирует экспортер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Дескриптор экспортера для регистрации. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Снимает регистрацию экспортеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Дескриптор экспортера для снятия регистрации. |

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

