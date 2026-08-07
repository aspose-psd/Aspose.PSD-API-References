---
title: "StreamContainer"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "स्ट्रीम कंटेनर को दर्शाता है जो स्ट्रीम को रखता है और स्ट्रीम प्रोसेसिंग रूटीन प्रदान करता है।"
type: docs
weight: 103
url: /hi/java/com.aspose.psd/streamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

स्ट्रीम कंटेनर को दर्शाता है जो स्ट्रीम को रखता है और स्ट्रीम प्रोसेसिंग रूटीन प्रदान करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | StreamContainer वर्ग का एक नया उदाहरण प्रारंभ करता है। |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) |  |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | StreamContainer वर्ग का एक नया उदाहरण प्रारंभ करता है। |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | क्रमिक रूप से पढ़ते समय पढ़ने और लिखने के बाइट्स की गिनती निर्दिष्ट करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [canRead()](#canRead--) | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम पढ़ने का समर्थन करता है या नहीं। |
| [canSeek()](#canSeek--) | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं। |
| [canWrite()](#canWrite--) | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम लिखने का समर्थन करता है या नहीं। |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | इस स्ट्रीम के सभी बफ़र साफ़ करता है और किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखवाता है। |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getLength()](#getLength--) | स्ट्रीम की लंबाई बाइट्स में प्राप्त या सेट करता है। |
| [getPosition()](#getPosition--) | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। |
| [getStream()](#getStream--) | डेटा स्ट्रीम प्राप्त करता है। |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | सिंक्रनाइज़्ड संसाधन तक पहुँच को सिंक्रनाइज़ करने के लिए उपयोग किया जा सकने वाला ऑब्जेक्ट प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | एक मान प्राप्त करता है जो दर्शाता है कि यह स्ट्रीम बंद करने पर नष्ट किया जाता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | निर्दिष्ट बाइट्स बफ़र को भरने के लिए बाइट्स पढ़ता है। |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है। |
| [readByte()](#readByte--) | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है। |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | स्ट्रीम के सभी डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [save(String filePath)](#save-java.lang.String-) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| [seek(long offset, int origin)](#seek-long-int-) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है। |
| [seekBegin()](#seekBegin--) | स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। |
| [setLength(long value)](#setLength-long-) | स्ट्रीम की लंबाई बाइट्स में प्राप्त या सेट करता है। |
| [setPosition(long value)](#setPosition-long-) | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | स्ट्रीम डेटा को  byte  array में परिवर्तित करता है। |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | स्ट्रीम डेटा को  byte  array में परिवर्तित करता है। |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) |   com.aspose.imaging.StreamContainer  से  System.IO.Stream  में स्पष्ट रूपांतरण करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | निर्दिष्ट सभी बाइट्स को स्ट्रीम में लिखता है। |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | बाइट्स की एक श्रृंखला को वर्तमान स्ट्रीम में लिखता है और लिखे गए बाइट्स की संख्या से इस स्ट्रीम के भीतर वर्तमान स्थिति को आगे बढ़ाता है। |
| [writeByte(byte value)](#writeByte-byte-) | स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है। |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | समाहित डेटा को दूसरे  StreamContainer  में कॉपी करता है। |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | समाहित डेटा को दूसरे  StreamContainer  में कॉपी करता है। |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


StreamContainer वर्ग का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | स्ट्रीम। |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


StreamContainer वर्ग का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | डेटा स्ट्रीम। |
| disposeStream | boolean | यदि  true  पर सेट किया गया है तो कंटेनर नष्ट होने पर स्ट्रीम भी नष्ट कर दी जाएगी। |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


क्रमिक रूप से पढ़ते समय पढ़ने और लिखने के बाइट्स की गिनती निर्दिष्ट करता है।

### canRead() {#canRead--}
```
public boolean canRead()
```


एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम पढ़ने का समर्थन करता है या नहीं।

मान: यदि स्ट्रीम पढ़ने का समर्थन करता है तो true; अन्यथा false।

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं।

मान: यदि स्ट्रीम सीकिंग का समर्थन करता है तो true; अन्यथा false।

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम लिखने का समर्थन करता है या नहीं।

मान: यदि स्ट्रीम लिखने का समर्थन करता है तो true; अन्यथा false।

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

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
### flush() {#flush--}
```
public void flush()
```


इस स्ट्रीम के सभी बफ़र साफ़ करता है और किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखवाता है।

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getLength() {#getLength--}
```
public long getLength()
```


स्ट्रीम की लंबाई बाइट्स में प्राप्त या सेट करता है। यह मान StreamContainer कन्स्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति द्वारा System.IO.Stream.Length से कम होता है।

मान: स्ट्रीम की लंबाई।

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। यह मान StreamContainer कन्स्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है।

मान: वर्तमान स्ट्रीम स्थिति।

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


डेटा स्ट्रीम प्राप्त करता है।

मान: डेटा स्ट्रीम।

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


सिंक्रनाइज़्ड संसाधन तक पहुँच को सिंक्रनाइज़ करने के लिए उपयोग किया जा सकने वाला ऑब्जेक्ट प्राप्त करता है।

मान: वह ऑब्जेक्ट जो सिंक्रनाइज़्ड संसाधन तक पहुँच को समन्वयित करने के लिए उपयोग किया जा सकता है।

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह स्ट्रीम बंद करने पर नष्ट किया जाता है या नहीं।

मान: यदि स्ट्रीम को बंद करने पर डिस्पोज़ किया जाता है तो true; अन्यथा false।

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




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


निर्दिष्ट बाइट्स बफ़र को भरने के लिए बाइट्स पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाइट्स | byte[] | भरने के लिए बाइट्स। |

**Returns:**
int - पढ़े गए बाइट्स की संख्या। यदि स्ट्रीम में पर्याप्त बाइट्स नहीं हैं तो यह मान बफ़र में बाइट्स की संख्या से कम हो सकता है।
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बफ़र | byte[] | बाइट्स की एक एरे। जब यह मेथड रिटर्न करता है, बफ़र में निर्दिष्ट बाइट एरे होता है जिसमें ऑफ़सेट और (ऑफ़सेट + काउंट - 1) के बीच के मान वर्तमान स्रोत से पढ़े गए बाइट्स द्वारा प्रतिस्थापित होते हैं। |
| ऑफ़सेट | int | बफ़र में शून्य-आधारित बाइट ऑफ़सेट जहाँ से वर्तमान स्ट्रीम से पढ़ा गया डेटा संग्रहीत करना शुरू किया जाता है। |
| count | int | वर्तमान स्ट्रीम से पढ़े जाने वाले अधिकतम बाइट्स की संख्या। |

**Returns:**
int - बफ़र में पढ़े गए कुल बाइट्स की संख्या। यदि अनुरोधित बाइट्स उपलब्ध नहीं हैं तो यह अनुरोधित संख्या से कम हो सकता है, या यदि स्ट्रीम का अंत पहुँच गया हो तो शून्य (0) हो सकता है।
### readByte() {#readByte--}
```
public int readByte()
```


स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है।

**Returns:**
int - अनसाइन्ड बाइट को Int32 में कास्ट किया गया मान, या यदि स्ट्रीम के अंत पर हो तो -1।
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार ReadWriteBytesCount और स्ट्रीम Length मान का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | डेटा को सहेजने के लिए स्ट्रीम। |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


स्ट्रीम के सभी डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम Length मान का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | डेटा को सहेजने के लिए स्ट्रीम। |
| bufferSize | int | बफ़र। |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | डेटा को सहेजने के लिए स्ट्रीम। |
| bufferSize | int | बफ़र आकार। डिफ़ॉल्ट रूप से ReadWriteBytesCount मान उपयोग किया जाता है। |
| लंबाई | long | कॉपी करने के लिए स्ट्रीम डेटा की लंबाई। डिफ़ॉल्ट रूप से लंबाई को Length मान पर सेट किया जाता है। |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार ReadWriteBytesCount और स्ट्रीम Length मान का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | स्ट्रीम डेटा को सहेजने के लिए फ़ाइल पथ। |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम Length मान का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | स्ट्रीम डेटा को सहेजने के लिए फ़ाइल पथ। |
| bufferSize | int | बफ़र आकार। डिफ़ॉल्ट रूप से ReadWriteBytesCount मान उपयोग किया जाता है। |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | स्ट्रीम डेटा को सहेजने के लिए फ़ाइल पथ। |
| bufferSize | int | बफ़र आकार। डिफ़ॉल्ट रूप से ReadWriteBytesCount मान उपयोग किया जाता है। |
| लंबाई | long | कॉपी करने के लिए स्ट्रीम डेटा की लंबाई। डिफ़ॉल्ट रूप से लंबाई को Length मान पर सेट किया जाता है। |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ऑफ़सेट | long | origin पैरामीटर के सापेक्ष एक बाइट ऑफ़सेट। यह मान StreamContainer कंस्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है। |
| origin | int | एक मान जिसका प्रकार  System.IO.SeekOrigin  है, जो नई स्थिति प्राप्त करने के लिए उपयोग किए जाने वाले संदर्भ बिंदु को दर्शाता है। |

**Returns:**
long - वर्तमान स्ट्रीम के भीतर नई स्थिति।
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है।

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


स्ट्रीम की लंबाई बाइट्स में प्राप्त या सेट करता है। यह मान StreamContainer कन्स्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति द्वारा System.IO.Stream.Length से कम होता है।

मान: स्ट्रीम की लंबाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। यह मान StreamContainer कन्स्ट्रक्टर में पास किए गए प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है।

मान: वर्तमान स्ट्रीम स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


स्ट्रीम डेटा को  byte  array में परिवर्तित करता है।

**Returns:**
byte[] - स्ट्रीम डेटा को byte एरे में परिवर्तित किया गया।
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


स्ट्रीम डेटा को  byte  array में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | बाइट्स पढ़ना शुरू करने की स्थिति। |
| bytesCount | long | पढ़ने के लिए बाइट्स की संख्या। |

**Returns:**
byte[] - स्ट्रीम डेटा को byte एरे में परिवर्तित किया गया।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


  com.aspose.imaging.StreamContainer  से  System.IO.Stream  में स्पष्ट रूपांतरण करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

**Returns:**
com.aspose.ms.System.IO.Stream - रूपांतरण का परिणाम।
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


निर्दिष्ट सभी बाइट्स को स्ट्रीम में लिखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाइट्स | byte[] | लिखने के लिए बाइट्स। |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


बाइट्स की एक श्रृंखला को वर्तमान स्ट्रीम में लिखता है और लिखे गए बाइट्स की संख्या से इस स्ट्रीम के भीतर वर्तमान स्थिति को आगे बढ़ाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बफ़र | byte[] | बाइट्स की एक एरे। यह मेथड buffer से count बाइट्स को वर्तमान स्ट्रीम में कॉपी करता है। |
| ऑफ़सेट | int | buffer में शून्य-आधारित बाइट ऑफ़सेट जहाँ से बाइट्स को वर्तमान स्ट्रीम में कॉपी करना शुरू किया जाता है। |
| count | int | वर्तमान स्ट्रीम में लिखे जाने वाले बाइट्स की संख्या। |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte | स्ट्रीम में लिखने के लिए बाइट। |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


समाहित डेटा को दूसरे  StreamContainer  में कॉपी करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | कॉपी करने के लिए स्ट्रीम कंटेनर। |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


समाहित डेटा को दूसरे  StreamContainer  में कॉपी करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | कॉपी करने के लिए स्ट्रीम कंटेनर। |
| लंबाई | long | लिखने के लिए बाइट्स की संख्या। |

