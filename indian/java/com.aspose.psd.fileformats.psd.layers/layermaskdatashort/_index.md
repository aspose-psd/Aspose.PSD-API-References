---
title: "LayerMaskDataShort"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "LayerMaskDataShort क्लास को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखती है जब लेयर में केवल रास्टर या वेक्टर मास्क होते हैं लेकिन दोनों नहीं।"
type: docs
weight: 23
url: /hi/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

LayerMaskDataShort क्लास को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखता है जब लेयर में केवल रास्टर या वेक्टर मास्क हो लेकिन दोनों नहीं। अन्यथा, एक [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) का उपयोग किया जाता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData में रास्टर मास्क डेटा बाइट्स होते हैं। यदि लेयर में केवल वेक्टर मास्क है तो ImageData में वेक्टर मास्क रास्टराइज़्ड (कैश्ड) डेटा बाइट्स होते हैं। LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) बाइट्स की लंबाई LayerMaskData.MaskRectangle ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) प्रॉपर्टीज़ की Width * Height के बराबर होनी चाहिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | एक नया उदाहरण प्रारंभ करता है [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | लेयर मास्क को क्लोन करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | निचले लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | लेयर मास्क डेटा का आकार प्राप्त करता है। |
| [getDefaultColor()](#getDefaultColor--) | डिफ़ॉल्ट रंग प्राप्त करता है या सेट करता है। |
| [getFlags()](#getFlags--) | लेयर मास्क फ़्लैग्स प्राप्त करता है या सेट करता है। |
| [getHeight_internalized()](#getHeight-internalized--) | मास्क की ऊँचाई प्राप्त करता है। |
| [getImageData()](#getImageData--) | PSD फ़ाइल में लेयर मास्क डेटा (या यदि वेक्टर मास्क है तो संयुक्त/अंतिम मास्क) प्राप्त करता है या सेट करता है। |
| [getLeft()](#getLeft--) | बाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getMaskRectangle()](#getMaskRectangle--) | PSD फ़ाइल में लेयर मास्क के मास्क आयत प्राप्त करता है या सेट करता है। |
| [getPadding()](#getPadding--) | लेयर मास्क पैडिंग को प्राप्त करता है या सेट करता है। |
| [getRight()](#getRight--) | दाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getTop()](#getTop--) | ऊपर के लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getWidth_internalized()](#getWidth-internalized--) | मास्क की चौड़ाई प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | निर्दिष्ट StreamContainer में [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) को सहेजता है। |
| [setBottom(int value)](#setBottom-int-) | निचले लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | डिफ़ॉल्ट रंग प्राप्त करता है या सेट करता है। |
| [setFlags(byte value)](#setFlags-byte-) | लेयर मास्क फ़्लैग्स प्राप्त करता है या सेट करता है। |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD फ़ाइल में लेयर मास्क डेटा (या यदि वेक्टर मास्क है तो संयुक्त/अंतिम मास्क) प्राप्त करता है या सेट करता है। |
| [setLeft(int value)](#setLeft-int-) | बाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD फ़ाइल में लेयर मास्क के मास्क आयत प्राप्त करता है या सेट करता है। |
| [setPadding(short value)](#setPadding-short-) | लेयर मास्क पैडिंग को प्राप्त करता है या सेट करता है। |
| [setRight(int value)](#setRight-int-) | दाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setTop(int value)](#setTop-int-) | ऊपर के लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


एक नया उदाहरण प्रारंभ करता है [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) क्लास का।

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


इस उदाहरण को क्लोन करता है।

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


लेयर मास्क को क्लोन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | मास्क। |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


निचले लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

मान: निचले लेयर मास्क की स्थिति।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


लेयर मास्क डेटा का आकार प्राप्त करता है।

Value: लेयर मास्क डेटा का आकार।

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


डिफ़ॉल्ट रंग प्राप्त करता है या सेट करता है।

Value: डिफ़ॉल्ट रंग।

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


लेयर मास्क फ़्लैग्स प्राप्त करता है या सेट करता है।

Value: लेयर मास्क फ़्लैग्स।

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


मास्क की ऊँचाई प्राप्त करता है।

Value: ऊँचाई।

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


PSD फ़ाइल में लेयर मास्क डेटा (या यदि वेक्टर मास्क है तो संयुक्त/अंतिम मास्क) प्राप्त करता है या सेट करता है।

Value: इमेज डेटा।

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


बाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: बायाँ लेयर मास्क स्थिति।

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


लेयर मास्क के मास्क  Rectangle  को प्राप्त करता है या सेट करता है PSD फ़ाइल में। यह बाएँ, दाएँ, ऊपर और नीचे गुण लेता है और  Rectangle  बनाता है।

Value: मास्क आयत।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


लेयर मास्क पैडिंग को प्राप्त करता है या सेट करता है।

मान: लेयर मास्क पैडिंग।

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


दाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: दायाँ लेयर मास्क स्थिति।

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


ऊपर के लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: ऊपर लेयर मास्क स्थिति।

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


मास्क की चौड़ाई प्राप्त करता है।

Value: चौड़ाई।

**Returns:**
int
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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public void save_internalized(StreamContainer streamContainer)
```


निर्दिष्ट StreamContainer में [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | डेटा सहेजने के लिए स्ट्रीम कंटेनर। |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


निचले लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

मान: निचले लेयर मास्क की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


डिफ़ॉल्ट रंग प्राप्त करता है या सेट करता है।

Value: डिफ़ॉल्ट रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


लेयर मास्क फ़्लैग्स प्राप्त करता है या सेट करता है।

Value: लेयर मास्क फ़्लैग्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


PSD फ़ाइल में लेयर मास्क डेटा (या यदि वेक्टर मास्क है तो संयुक्त/अंतिम मास्क) प्राप्त करता है या सेट करता है।

Value: इमेज डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


बाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: बायाँ लेयर मास्क स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


लेयर मास्क के मास्क  Rectangle  को प्राप्त करता है या सेट करता है PSD फ़ाइल में। यह बाएँ, दाएँ, ऊपर और नीचे गुण लेता है और  Rectangle  बनाता है।

Value: मास्क आयत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


लेयर मास्क पैडिंग को प्राप्त करता है या सेट करता है।

मान: लेयर मास्क पैडिंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


दाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: दायाँ लेयर मास्क स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


ऊपर के लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: ऊपर लेयर मास्क स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

