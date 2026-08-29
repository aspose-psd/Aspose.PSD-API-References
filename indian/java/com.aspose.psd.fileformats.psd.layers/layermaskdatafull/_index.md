---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "LayerMaskDataFull क्लास को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखती है जब लेयर में दोनों लेयर और वेक्टर मास्क होते हैं।"
type: docs
weight: 22
url: /hi/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

LayerMaskDataFull क्लास को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखती है जब लेयर में दोनों लेयर और वेक्टर मास्क होते हैं। अन्यथा, एक [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) उपयोग किया जाता है। ImageData में रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क का संयुक्त रूप शामिल है। ImageData बाइट्स की लंबाई MaskRectangle.Width \* MaskRectangle.Height गुणों के बराबर होनी चाहिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | एक नया उदाहरण प्रारंभ करता है [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | लेयर मास्क को क्लोन करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | बैकग्राउंड रंग को प्राप्त करता है या सेट करता है। |
| [getBottom()](#getBottom--) | निचले लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | लेयर मास्क डेटा का आकार प्राप्त करता है। |
| [getDefaultColor()](#getDefaultColor--) | डिफ़ॉल्ट रंग प्राप्त करता है या सेट करता है। |
| [getEnclosingBottom()](#getEnclosingBottom--) | PSD इमेज लेयर में संलग्न नीचे वाले रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getEnclosingLeft()](#getEnclosingLeft--) | PSD फ़ाइल लेयर में संलग्न बाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getEnclosingRight()](#getEnclosingRight--) | PSD फ़ाइल लेयर में संलग्न दाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getEnclosingTop()](#getEnclosingTop--) | PSD इमेज लेयर में रास्टर मास्क की संलग्न शीर्ष स्थिति प्राप्त करता है या सेट करता है। |
| [getFlags()](#getFlags--) | लेयर मास्क फ़्लैग्स प्राप्त करता है या सेट करता है। |
| [getHeight_internalized()](#getHeight-internalized--) | मास्क की ऊँचाई प्राप्त करता है। |
| [getImageData()](#getImageData--) | PSD फ़ाइल में लेयर मास्क डेटा (या यदि वेक्टर मास्क है तो संयुक्त/अंतिम मास्क) प्राप्त करता है या सेट करता है। |
| [getLeft()](#getLeft--) | बाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getMaskRectangle()](#getMaskRectangle--) | PSD फ़ाइल में लेयर मास्क के मास्क आयत प्राप्त करता है या सेट करता है। |
| [getRealFlags()](#getRealFlags--) | लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है जो उपयोगकर्ता / रास्टर मास्क के लिए उपयोग होते हैं। |
| [getRight()](#getRight--) | दाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getTop()](#getTop--) | ऊपर के लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [getUserMaskData()](#getUserMaskData--) | PSD फ़ाइल में लेयर के उपयोगकर्ता (रास्टर) मास्क डेटा को प्राप्त करता है या सेट करता है। |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | PSD इमेज लेयर में उपयोगकर्ता मास्क (परिधि) आयत को प्राप्त करता है या सेट करता है। |
| [getWidth_internalized()](#getWidth-internalized--) | मास्क की चौड़ाई प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | निर्दिष्ट StreamContainer में [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) को सहेजता है। |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | बैकग्राउंड रंग को प्राप्त करता है या सेट करता है। |
| [setBottom(int value)](#setBottom-int-) | निचले लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | डिफ़ॉल्ट रंग प्राप्त करता है या सेट करता है। |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | PSD इमेज लेयर में संलग्न नीचे वाले रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | PSD फ़ाइल लेयर में संलग्न बाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | PSD फ़ाइल लेयर में संलग्न दाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | PSD इमेज लेयर में रास्टर मास्क की संलग्न शीर्ष स्थिति प्राप्त करता है या सेट करता है। |
| [setFlags(byte value)](#setFlags-byte-) | लेयर मास्क फ़्लैग्स प्राप्त करता है या सेट करता है। |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD फ़ाइल में लेयर मास्क डेटा (या यदि वेक्टर मास्क है तो संयुक्त/अंतिम मास्क) प्राप्त करता है या सेट करता है। |
| [setLeft(int value)](#setLeft-int-) | बाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD फ़ाइल में लेयर मास्क के मास्क आयत प्राप्त करता है या सेट करता है। |
| [setRealFlags(byte value)](#setRealFlags-byte-) | लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है जो उपयोगकर्ता / रास्टर मास्क के लिए उपयोग होते हैं। |
| [setRight(int value)](#setRight-int-) | दाएँ लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setTop(int value)](#setTop-int-) | ऊपर के लेयर मास्क की स्थिति प्राप्त करता है या सेट करता है। |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | PSD फ़ाइल में लेयर के उपयोगकर्ता (रास्टर) मास्क डेटा को प्राप्त करता है या सेट करता है। |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | PSD इमेज लेयर में उपयोगकर्ता मास्क (परिधि) आयत को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


एक नया उदाहरण प्रारंभ करता है [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) क्लास का।

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


बैकग्राउंड रंग को प्राप्त करता है या सेट करता है।

मान: पृष्ठभूमि रंग।

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


PSD इमेज लेयर में संलग्न नीचे वाले रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है।

मान: निचले लेयर मास्क की स्थिति।

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


PSD फ़ाइल लेयर में संलग्न बाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: बायाँ लेयर मास्क स्थिति।

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


PSD फ़ाइल लेयर में संलग्न दाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: दायाँ लेयर मास्क स्थिति।

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


PSD इमेज लेयर में रास्टर मास्क की संलग्न शीर्ष स्थिति प्राप्त करता है या सेट करता है।

Value: ऊपर लेयर मास्क स्थिति।

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है जो उपयोगकर्ता / रास्टर मास्क के लिए उपयोग होते हैं। वेक्टर मास्क के लिए Flags प्रॉपर्टी का उपयोग किया जाता है।

मान: वास्तविक लेयर मास्क फ़्लैग्स।

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


PSD फ़ाइल में लेयर के उपयोगकर्ता (रास्टर) मास्क डेटा को प्राप्त करता है या सेट करता है। (MaskData प्रॉपर्टी में एक रास्टराइज़्ड वेक्टर मास्क है)।

मान: PSD इमेज में लेयर इमेज डेटा।

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


PSD इमेज लेयर में उपयोगकर्ता मास्क (परिधि) आयत को प्राप्त करता है या सेट करता है।

मान: उपयोगकर्ता मास्क आयत।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


बैकग्राउंड रंग को प्राप्त करता है या सेट करता है।

मान: पृष्ठभूमि रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


PSD इमेज लेयर में संलग्न नीचे वाले रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है।

मान: निचले लेयर मास्क की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


PSD फ़ाइल लेयर में संलग्न बाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: बायाँ लेयर मास्क स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


PSD फ़ाइल लेयर में संलग्न दाएँ रास्टर मास्क की स्थिति प्राप्त करता है या सेट करता है।

Value: दायाँ लेयर मास्क स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


PSD इमेज लेयर में रास्टर मास्क की संलग्न शीर्ष स्थिति प्राप्त करता है या सेट करता है।

Value: ऊपर लेयर मास्क स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है जो उपयोगकर्ता / रास्टर मास्क के लिए उपयोग होते हैं। वेक्टर मास्क के लिए Flags प्रॉपर्टी का उपयोग किया जाता है।

मान: वास्तविक लेयर मास्क फ़्लैग्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


PSD फ़ाइल में लेयर के उपयोगकर्ता (रास्टर) मास्क डेटा को प्राप्त करता है या सेट करता है। (MaskData प्रॉपर्टी में एक रास्टराइज़्ड वेक्टर मास्क है)।

मान: PSD इमेज में लेयर इमेज डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


PSD इमेज लेयर में उपयोगकर्ता मास्क (परिधि) आयत को प्राप्त करता है या सेट करता है।

मान: उपयोगकर्ता मास्क आयत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

