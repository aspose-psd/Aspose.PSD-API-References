---
title: "ImageCreatorsRegistry"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет реестр создателей изображений."
type: docs
weight: 56
url: /ru/java/com.aspose.psd/imagecreatorsregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Представляет реестр создателей изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageCreatorsRegistry()](#ImageCreatorsRegistry--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-) | Создает первый найденный создатель, подходящий для указанного. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Получает зарегистрированные дескрипторы. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Получает зарегистрированные форматы создания изображений. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageCreatorDescriptor imageCreatorDescriptor)](#register-com.aspose.psd.IImageCreatorDescriptor-) | Регистрирует указанный дескриптор создателя изображений. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.psd.IImageCreatorDescriptor-) | Регистрирует создателя. |
| [toString()](#toString--) |  |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-) | Отменяет регистрацию создателя. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageCreatorsRegistry() {#ImageCreatorsRegistry--}
```
public ImageCreatorsRegistry()
```


### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Создает первый найденный создатель, подходящий для указанного.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры изображения. |

--------------------

Первый создатель фактически будет последним зарегистрированным. |

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - The creator which supports the specified or null if no such creator is found.
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
### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Получает первый найденный поддерживаемый дескриптор, подходящий для указанного.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры изображения. |

--------------------

Первый дескриптор создателя фактически будет последним зарегистрированным. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Получает зарегистрированные дескрипторы.

Значение: Зарегистрированные дескрипторы.

**Returns:**
com.aspose.psd.IImageCreatorDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Получает зарегистрированные форматы создания изображений.

Значение: Зарегистрированные форматы создания изображений.

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




### register(IImageCreatorDescriptor imageCreatorDescriptor) {#register-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor imageCreatorDescriptor)
```


Регистрирует указанный дескриптор создателя изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageCreatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Дескриптор создателя изображений. |

### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Регистрирует создателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Дескриптор создателя для регистрации. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Отменяет регистрацию создателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Дескриптор создателя. |

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

