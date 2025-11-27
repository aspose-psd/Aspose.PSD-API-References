---
title: IImageExporterDescriptor
second_title: Aspose.PSD for Java API Reference
description: Represents the image exporter descriptor.
type: docs
weight: 122
url: /java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance in memory and multithreading issues.
## Methods

| Method | Description |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Determines whether image exporter can export the specified image to the specified image format specified by save options. |
| [createInstance()](#createInstance--) | Creates a new exporter instance. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Determines whether image exporter can export the specified image to the specified image format specified by save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | The image to export. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options base. |

**Returns:**
boolean -  true  if exporter created by this descriptor can export the specified image to the specified file format; otherwise,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Creates a new exporter instance.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
