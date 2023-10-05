---
title: ImageExportersRegistry
second_title: Aspose.PSD for Java API Reference
description: Represents the image exporters registry.
type: docs
weight: 57
url: /java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Represents the image exporters registry.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Creates the first found exporter suitable for the specified save options and image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Gets the fist found supported descriptor suitable for the specified save options and image. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Gets the registered exporter descriptors. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Gets the registered export formats. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Registers the specified image exporter descriptor. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Registers the exporter. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Unregisters the exporter. |
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


Creates the first found exporter suitable for the specified save options and image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to export. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The save options to use for export.

--------------------

The first exporter will be actually the last registered. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the fist found supported descriptor suitable for the specified save options and image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to export. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options.

--------------------

The first exporter descriptor will be actually the last registered. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Gets the registered exporter descriptors.

Value: The registered exporter descriptors.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Gets the registered export formats.

Value: The registered export formats.

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


Registers the specified image exporter descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | The image exporter descriptor. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registers the exporter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | The exporter descriptor to register. |

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


Unregisters the exporter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | The exporter descriptor to unregister. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

