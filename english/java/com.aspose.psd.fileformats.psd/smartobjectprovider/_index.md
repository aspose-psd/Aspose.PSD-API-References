---
title: SmartObjectProvider
second_title: Aspose.PSD for Java API Reference
description: Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.
type: docs
weight: 17
url: /java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.
## Methods

| Method | Description |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Converts layers to an embedded smart object. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Converts layers to an embedded smart object. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Initializes a new instance of the [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) class. |
| [embedAllLinked()](#embedAllLinked--) | Embeds all linked smart objects in the image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Gets the type of the smart object layer content. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Gets the embedded or linked file contents. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Gets the link data source by unique id. |
| [getLayersForUpdateContents_internalized()](#getLayersForUpdateContents-internalized--) | It gets or sets layer when contents must be changed |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Loads the contents. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Creates a new smart object layer by coping the source one. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [replaceContents_internalized(System.Guid uniqueId, byte[] contents)](#replaceContents-internalized-com.aspose.ms.System.Guid-byte---) | Replaces the contents with the provided contents to embed. |
| [replaceContents_internalized(PlacedResource placedResource, String linkedPath, System.Guid oldGuid)](#replaceContents-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-com.aspose.ms.System.Guid-) |  |
| [replaceContents_internalized(PlacedResource placedResource, String linkedPath, System.Guid oldGuid, boolean isReplaceOnlyThis)](#replaceContents-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-com.aspose.ms.System.Guid-boolean-) | Replaces the contents with the provided external file. |
| [setContents_internalized(System.Guid uniqueId, byte[] data)](#setContents-internalized-com.aspose.ms.System.Guid-byte---) | Sets the embedded or external file contents. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Sets (replaces or adds) the link data source in the global link resource. |
| [setLayersForUpdateContents_internalized(System.Collections.Generic.List<SmartObjectLayer> value)](#setLayersForUpdateContents-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer--) | It gets or sets layer when contents must be changed |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Updates the content of all modified smart objects in the image. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Converts layers to an embedded smart object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | The layers. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Converts layers to an embedded smart object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerNumbers | int[] | The layer numbers. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Initializes a new instance of the [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | The container. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Embeds all linked smart objects in the image.

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


Gets the type of the smart object layer content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier. |

**Returns:**
int - The type of the smart object layer content.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Gets the embedded or linked file contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier of the link data source. |

**Returns:**
byte[] - The  byte[]  contents.
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Gets the link data source by unique id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### getLayersForUpdateContents_internalized() {#getLayersForUpdateContents-internalized--}
```
public final System.Collections.Generic.List<SmartObjectLayer> getLayersForUpdateContents_internalized()
```


It gets or sets layer when contents must be changed

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


Loads the contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | The load options. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Creates a new smart object layer by coping the source one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | The source layer. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### replaceContents_internalized(System.Guid uniqueId, byte[] contents) {#replaceContents-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceContents_internalized(System.Guid uniqueId, byte[] contents)
```


Replaces the contents with the provided contents to embed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier of the existing data source. |
| contents | byte[] | The contents. |

**Returns:**
com.aspose.ms.System.Guid - The unique identifier of the created embedded data source.  LiFdDataSource .
### replaceContents_internalized(PlacedResource placedResource, String linkedPath, System.Guid oldGuid) {#replaceContents-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-com.aspose.ms.System.Guid-}
```
public final System.Guid replaceContents_internalized(PlacedResource placedResource, String linkedPath, System.Guid oldGuid)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |
| oldGuid | com.aspose.ms.System.Guid |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceContents_internalized(PlacedResource placedResource, String linkedPath, System.Guid oldGuid, boolean isReplaceOnlyThis) {#replaceContents-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-com.aspose.ms.System.Guid-boolean-}
```
public final System.Guid replaceContents_internalized(PlacedResource placedResource, String linkedPath, System.Guid oldGuid, boolean isReplaceOnlyThis)
```


Replaces the contents with the provided external file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | The placed resource. |
| linkedPath | java.lang.String | The absolute path to the linked file. |
| oldGuid | com.aspose.ms.System.Guid | Guid of old resource |
| isReplaceOnlyThis | boolean |  |

**Returns:**
com.aspose.ms.System.Guid - The unique identifier Guid of the created linked data source. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data) {#setContents-internalized-com.aspose.ms.System.Guid-byte---}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data)
```


Sets the embedded or external file contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier of the link data source. |
| data | byte[] | The data. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Sets (replaces or adds) the link data source in the global link resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | The link data source. |

### setLayersForUpdateContents_internalized(System.Collections.Generic.List<SmartObjectLayer> value) {#setLayersForUpdateContents-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer--}
```
public final void setLayersForUpdateContents_internalized(System.Collections.Generic.List<SmartObjectLayer> value)
```


It gets or sets layer when contents must be changed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer> |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


Updates the content of all modified smart objects in the image.

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

