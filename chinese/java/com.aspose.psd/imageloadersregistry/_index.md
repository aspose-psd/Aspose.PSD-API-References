---
title: "ImageLoadersRegistry"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示图像加载器注册表。"
type: docs
weight: 59
url: /zh/java/com.aspose.psd/imageloadersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

表示图像加载器注册表。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageLoadersRegistry()](#ImageLoadersRegistry--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-) | 创建第一个适用于指定  stream  且可选的  loadOptions  的加载器。 |
| [createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-) | 获取第一个找到的支持的描述符，适用于指定的  stream  且可选的  loadOptions 。 |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | 获取按类型名称的第一个受支持的文件格式。 |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | 按类型名称获取第一个受支持的描述符。 |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | 获取已注册的描述符。 |
| [getRegisteredFormats()](#getRegisteredFormats--) | 获取已注册的图像加载格式。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.psd.IImageLoaderDescriptor-) | 注册指定的图像加载器描述符。 |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.psd.IImageLoaderDescriptor-) | 注册加载器。 |
| [toString()](#toString--) |  |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-) | 注销加载器。 |
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


创建第一个适用于指定  stream  且可选的  loadOptions  的加载器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

--------------------

第一个加载器实际上是最后注册的。 |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - The loader which supports the specified  stream  and  loadOptions  or null if no such loader is found.
### createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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


获取第一个找到的支持的描述符，适用于指定的  stream  且可选的  loadOptions 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 流。 |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

--------------------

第一个加载器描述符实际上将是最后注册的。 |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The loader descriptor which supports the specified  stream  and  loadOptions  or null if no such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


获取按类型名称的第一个受支持的文件格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | fileFormat | long | 受支持的描述符文件格式。 |

--------------------

第一个加载器描述符实际上将是最后注册的。 |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


按类型名称获取第一个受支持的描述符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | 描述符类型名称。 |

--------------------

第一个加载器描述符实际上将是最后注册的。 |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


获取已注册的描述符。

值：已注册的描述符。

**Returns:**
com.aspose.psd.IImageLoaderDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


获取已注册的图像加载格式。

值：已注册的图像加载格式。

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


注册指定的图像加载器描述符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | 图像加载器描述符。 |

### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


注册加载器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | 要注册的加载器描述符。 |

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


注销加载器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | 要注销的加载器描述符。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

