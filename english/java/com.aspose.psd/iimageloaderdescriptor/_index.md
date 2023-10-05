---
title: IImageLoaderDescriptor
second_title: Aspose.PSD for Java API Reference
description: The image loader descriptor specifying the loader properties.
type: docs
weight: 125
url: /java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome the necessity to contain each image loader instance in memory and multithreading issues.
## Methods

| Method | Description |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Determines whether image loader can read a new image from the specified stream and optionally using the  loadOptions . |
| [createInstance()](#createInstance--) | Creates a new loader instance. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Determines whether image loader can read a new image from the specified stream and optionally using the  loadOptions .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | The file format details specified by  loadOptions . The  loadOptions  may be null. |

**Returns:**
boolean -  true  if image loader created by this descriptor can read image from stream; otherwise,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Creates a new loader instance.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
