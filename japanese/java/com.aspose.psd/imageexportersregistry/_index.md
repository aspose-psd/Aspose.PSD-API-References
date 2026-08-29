---
title: "ImageExportersRegistry"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "画像エクスポーター レジストリを表します。"
type: docs
weight: 57
url: /ja/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

画像エクスポーター レジストリを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 指定された保存オプションと画像に適合する最初に見つかったエクスポーターを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 指定された保存オプションと画像に適合する最初に見つかったサポートされている記述子を取得します。 |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | 登録されたエクスポーター記述子を取得します。 |
| [getRegisteredFormats()](#getRegisteredFormats--) | 登録されたエクスポート形式を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | 指定された画像エクスポーター記述子を登録します。 |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | エクスポーターを登録します。 |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | エクスポーターの登録を解除します。 |
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


指定された保存オプションと画像に適合する最初に見つかったエクスポーターを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | エクスポートする画像です。 |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | エクスポートに使用する保存オプションです。 |

--------------------

最初のエクスポーターは実際には最後に登録されたものになります。 |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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


指定された保存オプションと画像に適合する最初に見つかったサポートされている記述子を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | エクスポートする画像です。 |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |

--------------------

最初のエクスポーター記述子は実際には最後に登録されたものになります。 |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


登録されたエクスポーター記述子を取得します。

値: 登録されたエクスポーター記述子です。

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


登録されたエクスポート形式を取得します。

値: 登録されたエクスポート形式です。

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


指定された画像エクスポーター記述子を登録します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | 画像エクスポーター記述子です。 |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


エクスポーターを登録します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | 登録するエクスポーター記述子。 |

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


エクスポーターの登録を解除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | 登録解除するエクスポーター記述子。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

