---
title: Lnk3Resource
second_title: Aspose.PSD for Java API Reference
description: Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image.
type: docs
weight: 16
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk3resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkresource), [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource)
```
public class Lnk3Resource extends Lnk2Resource
```

Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image. The link resource may contain several [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) instances which can be accessed by indexer.
## Constructors

| Constructor | Description |
| --- | --- |
| [Lnk3Resource()](#Lnk3Resource--) | Initializes a new instance of the [Lnk3Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk3resource) class. |
## Fields

| Field | Description |
| --- | --- |
| [CannotAddTheDataSourceMessage_internalized](#CannotAddTheDataSourceMessage-internalized) | The 'cannot add the data source' message |
| [DataSourceTypeIsWrongMessage_internalized](#DataSourceTypeIsWrongMessage-internalized) | 'The data source type is wrong' message |
| [LengthOSourceLengthField](#LengthOSourceLengthField) | The length of data source length field. |
| [LengthOfResourceLengthField](#LengthOfResourceLengthField) | The length of total resource length field. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
## Methods

| Method | Description |
| --- | --- |
| [addDataSource_internalized(LinkDataSource dataSource)](#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Adds the data source. |
| [addOrReplaceDataSource_internalized(LinkDataSource dataSource)](#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Adds the or replace data source. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [create_internalized(LinkDataSource[] dataSources)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSourceCount()](#getDataSourceCount--) | Gets the count of link data sources which can be accessed by the indexer. |
| [getDataSources_internalized()](#getDataSources-internalized--) | Gets the data sources LinkDataSource[] array. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the PSD global link resource length in bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the PSD format version. |
| [getSignature()](#getSignature--) | Gets the PSD global link resource signature. |
| [getType_internalized()](#getType-internalized--) | Gets or sets the PSD global link resource type that can be one of the following or none: The embedded linked file liFD that corresponds to the Lnk2Resource and Lnk3Resource The external linked file liFE that corresponds to the LnkeResource The linked file alias liFA |
| [get_Item(int index)](#get-Item-int-) | Gets the  LiFdDataSource  at the specified index. |
| [get_Item(UUID index)](#get-Item-java.util.UUID-) | Gets the [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) at the specified index which is the link data source unique identifier.. |
| [get_Item_internalized(System.Guid index)](#get-Item-internalized-com.aspose.ms.System.Guid-) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this link resource instance is empty. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDataSource_internalized(System.Guid uniqueId)](#removeDataSource-internalized-com.aspose.ms.System.Guid-) | Removes the link data source. |
| [replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Replaces the data source. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource block data. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Lnk3Resource() {#Lnk3Resource--}
```
public Lnk3Resource()
```


Initializes a new instance of the [Lnk3Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk3resource) class.

### CannotAddTheDataSourceMessage_internalized {#CannotAddTheDataSourceMessage-internalized}
```
public static final String CannotAddTheDataSourceMessage_internalized
```


The 'cannot add the data source' message

### DataSourceTypeIsWrongMessage_internalized {#DataSourceTypeIsWrongMessage-internalized}
```
public static final String DataSourceTypeIsWrongMessage_internalized
```


'The data source type is wrong' message

### LengthOSourceLengthField {#LengthOSourceLengthField}
```
public static final int LengthOSourceLengthField
```


The length of data source length field.

### LengthOfResourceLengthField {#LengthOfResourceLengthField}
```
public static final int LengthOfResourceLengthField
```


The length of total resource length field.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


The PSB header version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


The PSB-specific resource signature.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


The PSD header version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


The common resource signature.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


The type tool info key.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


The type tool info key.

### addDataSource_internalized(LinkDataSource dataSource) {#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addDataSource_internalized(LinkDataSource dataSource)
```


Adds the data source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | The link data source. |

### addOrReplaceDataSource_internalized(LinkDataSource dataSource) {#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addOrReplaceDataSource_internalized(LinkDataSource dataSource)
```


Adds the or replace data source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | The data source. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Checks the and set if resource is PSB specific. Some resources are not recognized for now, but we have full list of PSB specific resources which changes their behaviour on save. So we need to check this in UnknownResource at least

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The key. |

### create_internalized(LinkDataSource[] dataSources) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource---}
```
public static Lnk3Resource create_internalized(LinkDataSource[] dataSources)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSources | [LinkDataSource\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) |  |

**Returns:**
[Lnk3Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk3resource)
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
### getDataSourceCount() {#getDataSourceCount--}
```
public final int getDataSourceCount()
```


Gets the count of link data sources which can be accessed by the indexer.

Value: The data source count.

**Returns:**
int
### getDataSources_internalized() {#getDataSources-internalized--}
```
public final LinkDataSource[] getDataSources_internalized()
```


Gets the data sources LinkDataSource[] array.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Gets or sets the header.

Value: The header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public int getKey()
```


Gets the layer resource key.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Gets the PSD global link resource length in bytes.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Gets the prefix length. Default value is 12 for 8BIM resources. and 16 for 8B64

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| psdVersion | int | The PSD version. |

**Returns:**
int - The Prefix Length.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Gets the PSD format version.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the PSD global link resource signature.

**Returns:**
int
### getType_internalized() {#getType-internalized--}
```
public final int getType_internalized()
```


Gets or sets the PSD global link resource type that can be one of the following or none: The embedded linked file liFD that corresponds to the Lnk2Resource and Lnk3Resource The external linked file liFE that corresponds to the LnkeResource The linked file alias liFA

Value: The PSD link resource type.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final LiFdDataSource get_Item(int index)
```


Gets the  LiFdDataSource  at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. Value: The  LiFdDataSource . |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) - The  LiFdDataSource  instance.
### get_Item(UUID index) {#get-Item-java.util.UUID-}
```
public final LinkDataSource get_Item(UUID index)
```


Gets the [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) at the specified index which is the link data source unique identifier..

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | java.util.UUID | The index as link data source unique identifier. Value: The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource). |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item_internalized(System.Guid index) {#get-Item-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource get_Item_internalized(System.Guid index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | com.aspose.ms.System.Guid |  |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Gets a value indicating whether this link resource instance is empty.

Value:  true  if this link resource is empty; otherwise,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determines whether the resource is PSB specific.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The resource key. |

**Returns:**
boolean -  true  if the resource is PSB specific; otherwise,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Gets a value indicating whether this instance is resource PSB specific.

Value:  true  if this instance is resource PSB specific; otherwise,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeDataSource_internalized(System.Guid uniqueId) {#removeDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final void removeDataSource_internalized(System.Guid uniqueId)
```


Removes the link data source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier. |

### replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)
```


Replaces the data source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | The unique identifier. |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | The link data source. |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Saves the resource block data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |
| psdVersion | int | The PSD version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Saves the custom resource header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Saves the header signature, identifier and length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |
| isLengthLong | boolean | if set to  true  length is long. |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Gets or sets the header.

Value: The header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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

