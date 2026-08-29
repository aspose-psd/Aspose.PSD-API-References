---
title: "معلومات القناة"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "معلومات القناة."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

معلومات القناة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | معرف قناة قناع المستخدم (الراستر). |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | معرف قناة القناع القصير (الراستر أو المتجه). |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | معرف قناة ألفا |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | يقوم بضغط بيانات القناة |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | ينسخ معلومات القناة المحددة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | يحصل على عمق بت القناة. |
| [getChannelID()](#getChannelID--) | يحصل أو يضبط معرف القناة. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | يحصل أو يضبط طريقة الضغط. |
| [getData_internalized()](#getData-internalized--) | يحصل أو يضبط بيانات القناة. |
| [getLength()](#getLength--) | يحصل على طول القناة بالبايت. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | يحصل على نسخة PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | يحصل على البيانات غير المضغوطة. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | يتحقق ما إذا كانت القناة قناع قصير أم لا |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | يحفظ بيانات القناة. |
| [setChannelID(short value)](#setChannelID-short-) | يحصل أو يضبط معرف القناة. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | يضبط البيانات المضغوطة. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | يحصل أو يضبط طريقة الضغط. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | يضبط البيانات المضغوطة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| طريقة الضغط | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


معرف قناة قناع المستخدم (الراستر). (إذا كان الطبقة تحتوي على كل من القناع المتجه والراستر).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


معرف قناة القناع القصير (الراستر أو المتجه). (إذا كان الطبقة تحتوي على قناع متجه أو راستر واحد فقط وليس كليهما).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


معرف قناة ألفا

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


يقوم بضغط بيانات القناة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات الخام | byte[] | البيانات الخام للضغط |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود الطبقة |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود قناع الطبقة |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات المضغوطة | byte[] |  |
| طريقة الضغط | short |  |
| العرض | int |  |
| الارتفاع | int |  |
| الرأس | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| طريقة الضغط | short |  |
| الرأس | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


ينسخ معلومات القناة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | المعلومات. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - القناع المستنسخ للطبقة.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


يحصل على عمق بت القناة.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


يحصل أو يضبط معرف القناة.

القيمة: معرف القناة.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


يحصل أو يضبط طريقة الضغط.

القيمة: طريقة الضغط.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


يحصل أو يضبط بيانات القناة.

القيمة: بيانات القناة.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


يحصل على طول القناة بالبايت.

القيمة: الطول.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


يحصل على نسخة PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


يحصل على البيانات غير المضغوطة.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


يتحقق ما إذا كانت القناة قناع قصير أم لا

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




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


يحفظ بيانات القناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ إليها. |
| is32BitColor | boolean | صحيح إذا كان اللون في وضع 32-بت |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


يحصل أو يضبط معرف القناة.

القيمة: معرف القناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


يضبط البيانات المضغوطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات المضغوطة | byte[] | البيانات المضغوطة. |
| channelWidth | int | عرض القناة. |
| channelHeight | int | ارتفاع القناة. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


يحصل أو يضبط طريقة الضغط.

القيمة: طريقة الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


يضبط البيانات المضغوطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات الخام | byte[] | البيانات الخام. |
| imageSize | [Size](../../com.aspose.psd/size) | حجم الصورة |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود بيانات القناة الحالية. إذا كانت الصورة كبيرة سيتم تقسيمها أثناء المعالجة و currentBounds != imageBounds |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

