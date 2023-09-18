---
title: ISmartObjectLayerResource
second_title: Aspose.PSD for Java API Reference
description: Defines the ISmartObjectLayerResource interface that contains information about a smart object layer resource in the PSD file.
type: docs
weight: 18
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/ismartobjectlayerresource/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public interface ISmartObjectLayerResource extends IPlacedLayerResource
```

Defines the ISmartObjectLayerResource interface that contains information about a smart object layer resource in the PSD file. Is is also a markup interface used to designate both Sold and Sole resources in the Adobe\\ufffd Photoshop\\ufffd images.
## Methods

| Method | Description |
| --- | --- |
| [getPlacedId()](#getPlacedId--) | Gets or sets the unique identifier of this smart object layer data in the PSD image. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | Gets or sets the unique identifier of this smart object layer data in the PSD image. |
### getPlacedId() {#getPlacedId--}
```
public abstract UUID getPlacedId()
```


Gets or sets the unique identifier of this smart object layer data in the PSD image.

Value: The unique identifier of this smart object layer resource.

**Returns:**
java.util.UUID
### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public abstract void setPlacedId(UUID value)
```


Gets or sets the unique identifier of this smart object layer data in the PSD image.

Value: The unique identifier of this smart object layer resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

