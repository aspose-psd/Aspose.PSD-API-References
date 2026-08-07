---
title: "DataStreamSupporter"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "डेटा स्ट्रीम कंटेनर।"
type: docs
weight: 38
url: /hi/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

डेटा स्ट्रीम कंटेनर।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | जब छवि लोड या सहेजी गई तब होता है |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | जब क्रेडिट उपयोग किया गया तब होता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [cacheData()](#cacheData--) | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित DataStreamSupporter.DataStreamContainer से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | यदि स्रोत छवि मौजूद है तो उसका फ़ाइल पाथ प्राप्त करता है। |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | एक मान प्राप्त करता है जो यह दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति का उपयोग करता है या नहीं |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | ऑब्जेक्ट का डेटा वर्तमान DataStreamSupporter में सहेजता है। |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [save(String filePath)](#save-java.lang.String-) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | ऑब्जेक्ट की डेटा स्ट्रीम सेट करता है। |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | सेव के बाद [ignore after save] को दर्शाने वाला मान सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


जब छवि लोड या सहेजी गई तब होता है

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


जब क्रेडिट उपयोग किया गया तब होता है

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित DataStreamSupporter.DataStreamContainer से कोई अतिरिक्त डेटा लोडिंग नहीं होगी।

### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है।

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


यदि स्रोत छवि मौजूद है तो उसका फ़ाइल पथ प्राप्त करता है। यदि स्रोत पथ नहीं मिल रहा है तो खाली स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - स्रोत छवि का फ़ाइल पथ।
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति का उपयोग करता है या नहीं

मान:  true  यदि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति उपयोग करता है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति उपयोग करता है या नहीं
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है।

**Returns:**
boolean - एक मान जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


ऑब्जेक्ट का डेटा वर्तमान DataStreamSupporter में सहेजता है।

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल | java.io.RandomAccessFile | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |
| overWrite | boolean | यदि true पर सेट किया गया है तो फ़ाइल की सामग्री को ओवरराइट करें, अन्यथा जोड़ दिया जाएगा। |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


ऑब्जेक्ट की डेटा स्ट्रीम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | ऑब्जेक्ट का डेटा स्ट्रीम। |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


सेव के बाद [ignore after save] को दर्शाने वाला मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि [ignore after save]; अन्यथा, false। |

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

