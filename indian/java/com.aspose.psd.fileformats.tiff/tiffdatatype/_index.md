---
title: "TiffDataType"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "टिफ डेटा टाइप।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

टिफ डेटा टाइप।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | वर्तमान इंस्टेंस की तुलना उसी प्रकार के दूसरे ऑब्जेक्ट से करता है और एक पूर्णांक लौटाता है जो दर्शाता है कि वर्तमान इंस्टेंस क्रम में दूसरे ऑब्जेक्ट से पहले, बाद में, या उसी स्थिति में है। |
| [deepClone()](#deepClone--) | इस इंस्टेंस की डीप क्लोन करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | टैग डेटा को फिट करने के लिए 12 बाइट्स पर्याप्त न होने की स्थिति में अतिरिक्त डेटा आकार बाइट्स में प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | तत्वों की गिनती प्राप्त करता है। |
| [getDataSize()](#getDataSize--) | टैग डेटा को फिट करने के लिए 12 बाइट्स पर्याप्त न होने की स्थिति में अतिरिक्त डेटा आकार बाइट्स में प्राप्त करता है। |
| [getId()](#getId--) | टैग आईडी का पूर्णांक प्रतिनिधित्व प्राप्त करता है। |
| [getTagId()](#getTagId--) | टैग आईडी प्राप्त करता है। |
| [getTagType()](#getTagType--) | टैग प्रकार प्राप्त करता है। |
| [getValue()](#getValue--) | इस डेटा प्रकार में मौजूद मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | टैग निजी है या नहीं यह दर्शाने वाला मान प्राप्त करता है। |
| [isValid()](#isValid--) | टैग डेटा वैध है या नहीं यह दर्शाने वाला मान प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | टैग डेटा पढ़ता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | इस डेटा प्रकार में मौजूद मान सेट करता है। |
| [toString()](#toString--) | एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | अतिरिक्त टैग डेटा लिखता है। |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | टैग डेटा लिखता है। |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


वर्तमान इंस्टेंस की तुलना उसी प्रकार के दूसरे ऑब्जेक्ट से करता है और एक पूर्णांक लौटाता है जो दर्शाता है कि वर्तमान इंस्टेंस क्रम में दूसरे ऑब्जेक्ट से पहले, बाद में, या उसी स्थिति में है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | इस इंस्टेंस की तुलना करने के लिए एक ऑब्जेक्ट। |

**Returns:**
int - एक 32-बिट साइन किया गया पूर्णांक जो तुलना किए जा रहे ऑब्जेक्ट्स के सापेक्ष क्रम को दर्शाता है। रिटर्न वैल्यू के अर्थ इस प्रकार हैं: मान अर्थ शून्य से कम इस इंस्टेंस का क्रम obj से कम है। शून्य इस इंस्टेंस का क्रम obj के बराबर है। शून्य से अधिक इस इंस्टेंस का क्रम obj से अधिक है।
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


इस इंस्टेंस की डीप क्लोन करता है।

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


टैग डेटा को फिट करने के लिए 12 बाइट्स पर्याप्त न होने की स्थिति में अतिरिक्त डेटा आकार बाइट्स में प्राप्त करता है।

**Returns:**
long - बाइट्स में अतिरिक्त डेटा आकार।

यह डेटा बाइट्स की गिनती है जो शब्द सीमा (word boundary) के अनुसार संरेखित है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


तत्वों की गिनती प्राप्त करता है।

**Returns:**
long - तत्वों की गिनती।
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


टैग डेटा को फिट करने के लिए 12 बाइट्स पर्याप्त न होने की स्थिति में अतिरिक्त डेटा आकार बाइट्स में प्राप्त करता है।

**Returns:**
long - बाइट्स में अतिरिक्त डेटा आकार।

यह सटीक बाइट्स की गिनती है।
### getId() {#getId--}
```
public int getId()
```


टैग आईडी का पूर्णांक प्रतिनिधित्व प्राप्त करता है।

**Returns:**
int - टैग आईडी का पूर्णांक प्रतिनिधित्व
### getTagId() {#getTagId--}
```
public int getTagId()
```


टैग आईडी प्राप्त करता है।

**Returns:**
int - टैग आईडी।
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


टैग प्रकार प्राप्त करता है।

**Returns:**
int - टैग प्रकार।
### getValue() {#getValue--}
```
public abstract Object getValue()
```


इस डेटा प्रकार में मौजूद मान प्राप्त करता है।

**Returns:**
java.lang.Object - मान।
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


टैग निजी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। निजी TIFF टैग वे टैग होते हैं जिनका टैग आईडी 32768 से अधिक होता है।

**Returns:**
boolean -  true  यदि टैग डेटा वैध है; अन्यथा,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


टैग डेटा वैध है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। वैध टैग में ऐसा डेटा होता है जिसे संरक्षित किया जा सकता है। अमान्य टैग को संग्रहीत नहीं किया जा सकता।

**Returns:**
boolean -  true  यदि टैग डेटा वैध है; अन्यथा,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


टैग डेटा पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | डेटा स्ट्रीम। |
| position | long | टैग स्थिति। |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


इस डेटा प्रकार में मौजूद मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | मान। |

### toString() {#toString--}
```
public String toString()
```


एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है।

**Returns:**
java.lang.String - एक  System.String  जो इस उदाहरण का प्रतिनिधित्व करता है।
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


अतिरिक्त टैग डेटा लिखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | डेटा स्ट्रीम। |

**Returns:**
long - वास्तविक लिखे गए बाइट्स।
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


टैग डेटा लिखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | डेटा स्ट्रीम। |
| additionalDataOffset | long | अतिरिक्त डेटा लिखने के लिए ऑफसेट। |

