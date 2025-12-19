---
title: LiFdDataSource
second_title: Aspose.PSD for Java API Reference
description: Defines the liFD data source class in PSD File that contains information about an embedded file.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFdDataSource extends LinkDataSource
```

Defines the liFD data source class in PSD File that contains information about an embedded file. This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files
## Constructors

| Constructor | Description |
| --- | --- |
| [LiFdDataSource()](#LiFdDataSource--) | Initializes a new instance of the [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) class. |
| [LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) class. |
## Fields

| Field | Description |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | The descriptor version. |
| [LatestVersion_internalized](#LatestVersion-internalized) | The latest available version of the link data source |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | The unexpected link data source type value |
| [ZeroChar_internalized](#ZeroChar-internalized) | The zero character |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Gets or sets a value indicating whether the PSD asset is locked. |
| [getAssetModTime()](#getAssetModTime--) | Gets or sets the asset modified time, for Adobe® Photoshop® \\u0421\\u0421 Libraries assets. |
| [getChildDocId()](#getChildDocId--) | Gets or sets the child document identifier in the liFE or liFD data source of the Lnk2 / LnkE Adobe® Photoshop® resource. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Gets or sets the resource class id. |
| [getClassName_internalized()](#getClassName-internalized--) | Gets or sets the resource class name. |
| [getCompId()](#getCompId--) | Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Gets or sets ContentID property. |
| [getData()](#getData--) | Gets or sets the embedded smart object data in PSD file. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Gets the length of the embedded data. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Gets the length of the link source data. |
| [getFileCreator()](#getFileCreator--) | Gets or sets the file creator in the PSD format LnkE / Lnk2 resource. |
| [getFileType()](#getFileType--) | Gets or sets the type of the embedded or external file which Adobe® Photoshop® Lnk2 / LnkE resource contains or links. |
| [getItems_internalized()](#getItems-internalized--) | Gets or sets OSTypeStructure array that define resource properties. |
| [getLength()](#getLength--) | Gets the link data source length in bytes. |
| [getOriginalCompId()](#getOriginalCompId--) | Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected. |
| [getOriginalFileName()](#getOriginalFileName--) | Gets the original file name of the data source in the Adobe® Photoshop® global link resource. |
| [getType()](#getType--) | Gets the Adobe® Photoshop® global link data source type that can be one of the following or none: The embedded linked file liFD that corresponds to the PSD Lnk2Resource The external linked file liFE that corresponds to the PSD LnkeResource The linked file alias liFA |
| [getUniqueId()](#getUniqueId--) | Gets the global unique identifier of the data source in the PSD link resource. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Gets or sets the unknown data that goes before Items OSTypeStructures properties. |
| [getVersion()](#getVersion--) | Gets the version of the data source in the PSD LnkE / Lnk2 resource. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Gets or sets a value indicating whether this link data source has the file open descriptor: CompId and OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Gets a value indicating whether this PSD link data source links to the Adobe® Photoshop® \\u0421\\u0421 Library item. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Saves the link data source block data. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Gets or sets a value indicating whether the PSD asset is locked. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Gets or sets the asset modified time, for Adobe® Photoshop® \\u0421\\u0421 Libraries assets. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Gets or sets the child document identifier in the liFE or liFD data source of the Lnk2 / LnkE Adobe® Photoshop® resource. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Gets or sets the resource class id. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Gets or sets the resource class name. |
| [setCompId(int value)](#setCompId-int-) | Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Gets or sets ContentID property. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets the embedded smart object data in PSD file. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Gets or sets the file creator in the PSD format LnkE / Lnk2 resource. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Gets or sets a value indicating whether this link data source has the file open descriptor: CompId and OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Gets or sets the type of the embedded or external file which Adobe® Photoshop® Lnk2 / LnkE resource contains or links. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Gets or sets OSTypeStructure array that define resource properties. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Gets a value indicating whether this PSD link data source links to the Adobe® Photoshop® \\u0421\\u0421 Library item. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Gets the original file name of the data source in the Adobe® Photoshop® global link resource. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Sets the property value by type structure. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Gets the global unique identifier of the data source in the PSD link resource. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Gets or sets the unknown data that goes before Items OSTypeStructures properties. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFdDataSource() {#LiFdDataSource--}
```
public LiFdDataSource()
```


Initializes a new instance of the [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) class.

### LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Initializes a new instance of the [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| version | int | The version. |
| uniqueId | java.util.UUID | The unique identifier. |
| originalFileName | java.lang.String | Name of the original file. |
| fileType | java.lang.String | Type of the file. |
| fileCreator | java.lang.String | The file creator. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


The descriptor version.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


The latest available version of the link data source

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


The unexpected link data source type value

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


The zero character

### create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFdDataSource create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| version | int |  |
| guid | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource)
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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Gets or sets a value indicating whether the PSD asset is locked. The asset locked state, for Adobe® Photoshop® \\u0421\\u0421 Libraries assets.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Gets or sets the asset modified time, for Adobe® Photoshop® \\u0421\\u0421 Libraries assets.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Gets or sets the child document identifier in the liFE or liFD data source of the Lnk2 / LnkE Adobe® Photoshop® resource.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Gets or sets the resource class id.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Gets or sets the resource class name.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected. Comps are compositions of a page layout which designers can create. Using layer comps, you can create, manage, and view multiple versions of a layout in a single Adobe® Photoshop® file. A layer comp is a snapshot of a state of the Layers panel. Layer comps save three types of layer options but this property gets the Layer Comp selection identifier for Smart Objects.  Layer comps in Smart Objects 

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Gets or sets ContentID property. The value of this property is read and saved only when Version is >= 8.

**Returns:**
java.lang.String
### getData() {#getData--}
```
public final byte[] getData()
```


Gets or sets the embedded smart object data in PSD file.

Value: The the embedded smart object data.

**Returns:**
byte[]
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Gets the length of the embedded data.

Value: The length of the embedded data.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Gets the length of the link source data.

**Returns:**
long - The source data length.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Gets or sets the file creator in the PSD format LnkE / Lnk2 resource.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Gets or sets the type of the embedded or external file which Adobe® Photoshop® Lnk2 / LnkE resource contains or links.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Gets or sets OSTypeStructure array that define resource properties.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Gets the link data source length in bytes.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected. This property gets the original layer Comp selection identifier for Smart Objects.  Layer comps in Smart Objects 

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Gets the original file name of the data source in the Adobe® Photoshop® global link resource.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Gets the Adobe® Photoshop® global link data source type that can be one of the following or none: The embedded linked file liFD that corresponds to the PSD Lnk2Resource The external linked file liFE that corresponds to the PSD LnkeResource The linked file alias liFA

Value: The PSD link data source type.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Gets the global unique identifier of the data source in the PSD link resource.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Gets or sets the unknown data that goes before Items OSTypeStructures properties.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets the version of the data source in the PSD LnkE / Lnk2 resource.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Gets or sets a value indicating whether this link data source has the file open descriptor: CompId and OriginalCompId.

Value:  true  if this instance has file open descriptor; otherwise,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Gets a value indicating whether this PSD link data source links to the Adobe® Photoshop® \\u0421\\u0421 Library item.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Saves the link data source block data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Gets or sets a value indicating whether the PSD asset is locked. The asset locked state, for Adobe® Photoshop® \\u0421\\u0421 Libraries assets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Gets or sets the asset modified time, for Adobe® Photoshop® \\u0421\\u0421 Libraries assets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Gets or sets the child document identifier in the liFE or liFD data source of the Lnk2 / LnkE Adobe® Photoshop® resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Gets or sets the resource class id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Gets or sets the resource class name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected. Comps are compositions of a page layout which designers can create. Using layer comps, you can create, manage, and view multiple versions of a layout in a single Adobe® Photoshop® file. A layer comp is a snapshot of a state of the Layers panel. Layer comps save three types of layer options but this property gets the Layer Comp selection identifier for Smart Objects.  Layer comps in Smart Objects 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Gets or sets ContentID property. The value of this property is read and saved only when Version is >= 8.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Gets or sets the embedded smart object data in PSD file.

Value: The the embedded smart object data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Gets or sets the file creator in the PSD format LnkE / Lnk2 resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Gets or sets a value indicating whether this link data source has the file open descriptor: CompId and OriginalCompId.

Value:  true  if this instance has file open descriptor; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Gets or sets the type of the embedded or external file which Adobe® Photoshop® Lnk2 / LnkE resource contains or links.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Gets or sets OSTypeStructure array that define resource properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Gets a value indicating whether this PSD link data source links to the Adobe® Photoshop® \\u0421\\u0421 Library item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected. This property gets the original layer Comp selection identifier for Smart Objects.  Layer comps in Smart Objects 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Gets the original file name of the data source in the Adobe® Photoshop® global link resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Sets the property value by type structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structure. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Gets the global unique identifier of the data source in the PSD link resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Gets or sets the unknown data that goes before Items OSTypeStructures properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

