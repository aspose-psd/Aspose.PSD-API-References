---
title: "LayerResourcesRegistry"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет реестр ресурсов слоя."
type: docs
weight: 26
url: /ru/java/com.aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Inheritance:**
java.lang.Object
```
public final class LayerResourcesRegistry
```

Представляет реестр ресурсов слоя.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LayerResourcesRegistry()](#LayerResourcesRegistry--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, int psdVersion)](#getFirstSupportedDescriptor-java.io.InputStream-int-) | Получает первый поддерживаемый дескриптор открывателя. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Получает зарегистрированные дескрипторы. |
| [hashCode()](#hashCode--) |  |
| [loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-) | Загружает [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), используя первый найденный открыватель, подходящий для указанного  потока . |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerDefaultPsdOptions_internalized()](#registerDefaultPsdOptions-internalized--) | Регистрирует параметры PSD по умолчанию. |
| [registerOpener(ILayerResourceLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Регистрирует открыватель. |
| [registerPsdLoadOptions_internalized(PsdLoadOptions load)](#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-) | Регистрирует параметры загрузки PSD. |
| [toString()](#toString--) |  |
| [unregisterOpener(ILayerResourceLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Удаляет регистрацию открывателя. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerResourcesRegistry() {#LayerResourcesRegistry--}
```
public LayerResourcesRegistry()
```


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
### getFirstSupportedDescriptor(InputStream stream, int psdVersion) {#getFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Получает первый поддерживаемый дескриптор открывателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
|  | psdVersion | int | Версия PSD. |

--------------------

Первый загрузчик на самом деле будет последним зарегистрированным. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static ILayerResourceLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Получает первый поддерживаемый дескриптор по его имени типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Имя типа дескриптора. |

--------------------

Первый дескриптор открывателя на самом деле будет последним зарегистрированным. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static ILayerResourceLoader[] getRegisteredDescriptors()
```


Получает зарегистрированные дескрипторы.

Значение: Зарегистрированные дескрипторы.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Загружает [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), используя первый найденный открыватель, подходящий для указанного  потока .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
|  | psdVersion | int | Версия PSD. |

--------------------

Первый открыватель на самом деле будет последним зарегистрированным. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerDefaultPsdOptions_internalized() {#registerDefaultPsdOptions-internalized--}
```
public static void registerDefaultPsdOptions_internalized()
```


Регистрирует параметры PSD по умолчанию.

### registerOpener(ILayerResourceLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void registerOpener(ILayerResourceLoader openerDescriptor)
```


Регистрирует открыватель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Дескриптор открывателя для регистрации. |

### registerPsdLoadOptions_internalized(PsdLoadOptions load) {#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-}
```
public static void registerPsdLoadOptions_internalized(PsdLoadOptions load)
```


Регистрирует параметры загрузки PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| load | [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) | Загрузка. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(ILayerResourceLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void unregisterOpener(ILayerResourceLoader openerDescriptor)
```


Удаляет регистрацию открывателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Дескриптор открывателя для отмены регистрации. |

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

