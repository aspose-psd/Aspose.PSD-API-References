---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示图像导出器描述符。"
type: docs
weight: 122
url: /zh/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

表示图像导出器描述符。导出器描述符用于克服在内存中保存每个导出器实例以及多线程问题的必要性。
## Methods

| Method | 描述 |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 确定图像导出器是否可以将指定的图像导出为保存选项指定的图像格式。 |
| [createInstance()](#createInstance--) | 创建一个新的导出器实例。 |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


确定图像导出器是否可以将指定的图像导出为保存选项指定的图像格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要导出的图像。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项基类。 |

**Returns:**
boolean - true，如果此描述符创建的导出器可以将指定的图像导出为指定的文件格式；否则， false。
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


创建一个新的导出器实例。

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
