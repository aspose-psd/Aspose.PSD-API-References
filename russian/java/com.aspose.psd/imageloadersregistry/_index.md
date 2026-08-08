---
title: "ImageLoadersRegistry"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет реестр загрузчиков изображений."
type: docs
weight: 59
url: /ru/java/com.aspose.psd/imageloadersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Представляет реестр загрузчиков изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageLoadersRegistry()](#ImageLoadersRegistry--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-) | Создает первый найденный загрузчик, подходящий для указанного  stream  и, при необходимости,  loadOptions . |
| [createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного  stream  и, при необходимости,  loadOptions . |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Получает первый поддерживаемый формат файла по его имени типа. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Получает зарегистрированные дескрипторы. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Получает зарегистрированные форматы загрузки изображений. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.psd.IImageLoaderDescriptor-) | Регистрирует указанный дескриптор загрузчика изображений. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.psd.IImageLoaderDescriptor-) | Регистрирует загрузчик. |
| [toString()](#toString--) |  |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-) | Отменяет регистрацию загрузчика. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageLoadersRegistry() {#ImageLoadersRegistry--}
```
public ImageLoadersRegistry()
```


### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Создает первый найденный загрузчик, подходящий для указанного  stream  и, при необходимости,  loadOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

--------------------

Первый загрузчик на самом деле будет последним зарегистрированным. |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - The loader which supports the specified  stream  and  loadOptions  or null if no such loader is found.
### createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader)
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
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Получает первый найденный поддерживаемый дескриптор, подходящий для указанного  stream  и, при необходимости,  loadOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

--------------------

Первый дескриптор загрузчика фактически будет последним зарегистрированным. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The loader descriptor which supports the specified  stream  and  loadOptions  or null if no such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Получает первый поддерживаемый формат файла по его имени типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | long | Поддерживаемый формат файла дескриптора. |

--------------------

Первый дескриптор загрузчика фактически будет последним зарегистрированным. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Получает первый поддерживаемый дескриптор по его имени типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Имя типа дескриптора. |

--------------------

Первый дескриптор загрузчика фактически будет последним зарегистрированным. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Получает зарегистрированные дескрипторы.

Значение: Зарегистрированные дескрипторы.

**Returns:**
com.aspose.psd.IImageLoaderDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Получает зарегистрированные форматы загрузки изображений.

Значение: Зарегистрированные форматы загрузки изображений.

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




### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Регистрирует указанный дескриптор загрузчика изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика изображений. |

### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Регистрирует загрузчик.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика для регистрации. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Отменяет регистрацию загрузчика.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика для отмены регистрации. |

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

