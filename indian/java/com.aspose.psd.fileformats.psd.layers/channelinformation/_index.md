---
title: "ChannelInformation"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "चैनल जानकारी।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

चैनल जानकारी।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | उपयोगकर्ता (रास्टर) मास्क चैनल आईडी। |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | छोटा (रास्टर या वेक्टर) मास्क चैनल आईडी। |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | अल्फा चैनल आईडी। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | यह चैनल डेटा को संपीड़ित करता है। |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | निर्दिष्ट चैनल जानकारी को क्लोन करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | चैनल बिट गहराई प्राप्त करता है। |
| [getChannelID()](#getChannelID--) | चैनल आईडी को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | संपीड़न विधि को प्राप्त करता है या सेट करता है। |
| [getData_internalized()](#getData-internalized--) | चैनल डेटा को प्राप्त करता है या सेट करता है। |
| [getLength()](#getLength--) | चैनल की लंबाई बाइट्स में प्राप्त करता है। |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | PSD का संस्करण प्राप्त करता है। |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | असंपीड़ित डेटा प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | जाँचता है कि चैनल ShortMask है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | चैनल डेटा सहेजता है। |
| [setChannelID(short value)](#setChannelID-short-) | चैनल आईडी को प्राप्त करता है या सेट करता है। |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | संपीड़ित डेटा सेट करता है। |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | संपीड़न विधि को प्राप्त करता है या सेट करता है। |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | संपीड़ित डेटा सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


उपयोगकर्ता (रास्टर) मास्क चैनल आईडी। (यदि लेयर में दोनों वेक्टर और रास्टर मास्क हैं)।

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


छोटा (रास्टर या वेक्टर) मास्क चैनल आईडी। (यदि लेयर में केवल एक वेक्टर या रास्टर मास्क है लेकिन दोनों नहीं)।

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


अल्फा चैनल आईडी।

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


यह चैनल डेटा को संपीड़ित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawData | byte[] | संपीड़न के लिए कच्चा डेटा |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | लेयर की सीमाएँ |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | लेयर मास्क की सीमाएँ |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| width | int |  |
| height | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


निर्दिष्ट चैनल जानकारी को क्लोन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | सूचना। |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - क्लोन किया गया लेयर मास्क।
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


चैनल बिट गहराई प्राप्त करता है।

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


चैनल आईडी को प्राप्त करता है या सेट करता है।

मान: चैनल आईडी।

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


संपीड़न विधि को प्राप्त करता है या सेट करता है।

मान: संपीड़न विधि।

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


चैनल डेटा को प्राप्त करता है या सेट करता है।

मान: चैनल डेटा।

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


चैनल की लंबाई बाइट्स में प्राप्त करता है।

मान: लंबाई।

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


PSD का संस्करण प्राप्त करता है।

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


असंपीड़ित डेटा प्राप्त करता है।

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


जाँचता है कि चैनल ShortMask है या नहीं।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


चैनल डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| is32BitColor | boolean | सही यदि रंग 32-बिट मोड में है |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


चैनल आईडी को प्राप्त करता है या सेट करता है।

मान: चैनल आईडी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


संपीड़ित डेटा सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| compressedData | byte[] | संपीड़ित डेटा। |
| channelWidth | int | चैनल की चौड़ाई। |
| channelHeight | int | चैनल की ऊँचाई। |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


संपीड़न विधि को प्राप्त करता है या सेट करता है।

मान: संपीड़न विधि।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


संपीड़ित डेटा सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawData | byte[] | कच्चा डेटा। |
| imageSize | [Size](../../com.aspose.psd/size) | छवि का आकार |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | वर्तमान channelData की सीमाएँ। यदि छवि बड़ी है तो प्रक्रिया के दौरान इसे विभाजित किया जाएगा और currentBounds != imageBounds |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

