---
title: "TiffStreamReader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लीटल एंडियन TIFF फ़ाइल स्वरूप को संभालने के लिए TIFF स्ट्रीम।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

लीटल एंडियन TIFF फ़ाइल स्वरूप को संभालने के लिए TIFF स्ट्रीम।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | रीडर की लंबाई प्राप्त करता है। |
| [getThrowExceptions()](#getThrowExceptions--) | एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि क्या गलत डेटा प्रोसेसिंग (स्ट्रीम को पढ़ते या लिखते समय) पर अपवाद फेंके जाते हैं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | स्ट्रीम से बाइट मानों की एक एरे पढ़ता है। |
| [readBytes(long position, long count)](#readBytes-long-long-) | स्ट्रीम से अनसाइन्ड बाइट मानों की एक एरे पढ़ता है। |
| [readDouble(long position)](#readDouble-long-) | स्ट्रीम से एक एकल डबल मान पढ़ता है। |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | स्ट्रीम से डबल मानों की एक एरे पढ़ता है। |
| [readFloat(long position)](#readFloat-long-) | स्ट्रीम से एक एकल फ़्लोट मान पढ़ता है। |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | स्ट्रीम से फ़्लोट मानों की एक एरे पढ़ता है। |
| [readRational(long position)](#readRational-long-) | स्ट्रीम से एक एकल रैशनल नंबर मान पढ़ता है। |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | स्ट्रीम से रैशनल मानों की एक एरे पढ़ता है। |
| [readSByte(long position)](#readSByte-long-) | स्ट्रीम से साइन्ड बाइट डेटा पढ़ता है। |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | स्ट्रीम से साइन्ड बाइट मानों की एक एरे पढ़ता है। |
| [readSLong(long position)](#readSLong-long-) | स्ट्रीम से साइन्ड इंटेजर मान पढ़ता है। |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | स्ट्रीम से साइन्ड इंटेजर मानों की एक एरे पढ़ता है। |
| [readSRational(long position)](#readSRational-long-) | स्ट्रीम से एक एकल साइन्ड रैशनल नंबर मान पढ़ता है। |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | स्ट्रीम से साइन्ड रैशनल मानों की एक एरे पढ़ता है। |
| [readSShort(long position)](#readSShort-long-) | स्ट्रीम से साइन्ड शॉर्ट मान पढ़ता है। |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | स्ट्रीम से साइन किए गए शॉर्ट मानों की एक एरे पढ़ता है। |
| [readString_internalized(long position)](#readString-internalized-long-) | स्ट्रीम से स्ट्रिंग पढ़ता है। |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | स्ट्रीम से स्ट्रिंग पढ़ता है। |
| [readULong(long position)](#readULong-long-) | स्ट्रीम से अनसाइन्ड इंटीजर मान पढ़ें। |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक एरे पढ़ता है। |
| [readUShort(long position)](#readUShort-long-) | स्ट्रीम से अनसाइन्ड शॉर्ट मान पढ़ें। |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक एरे पढ़ता है। |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि क्या गलत डेटा प्रोसेसिंग (स्ट्रीम को पढ़ते या लिखते समय) पर अपवाद फेंके जाते हैं। |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | अधोस्त डेटा को स्ट्रीम कंटेनर में परिवर्तित करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा | byte[] | बाइट एरे डेटा। |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा | byte[] | बाइट एरे डेटा। |
| startIndex | int | डेटा में प्रारंभिक सूचकांक। |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा | byte[] | बाइट एरे डेटा। |
| startIndex | int | डेटा में प्रारंभिक सूचकांक। |
| dataLength | int | डेटा की लंबाई। |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


TiffStreamReader वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

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
### getLength() {#getLength--}
```
public long getLength()
```


रीडर की लंबाई प्राप्त करता है।

मान: रीडर की लंबाई।

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि क्या गलत डेटा प्रोसेसिंग (स्ट्रीम को पढ़ते या लिखते समय) पर अपवाद फेंके जाते हैं।

मान:  true  यदि गलत डेटा प्रोसेसिंग पर अपवाद फेंके जाते हैं; अन्यथा, त्रुटि स्थितियों को चुपचाप अनदेखा किया जाता है।

**Returns:**
boolean
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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


स्ट्रीम से बाइट मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | byte[] | भरने के लिए एरे। |
| arrayIndex | int | मान डालना शुरू करने के लिए एरे सूचकांक। |
| position | long | पढ़ने के लिए स्ट्रीम स्थिति। |
| count | long | पढ़ने के लिए तत्वों की संख्या। |

**Returns:**
long - बाइट मानों की एरे।
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


स्ट्रीम से अनसाइन्ड बाइट मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
byte[] - अनसाइन्ड बाइट मानों की एरे।
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


स्ट्रीम से एक एकल डबल मान पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
double - एकल डबल मान।
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


स्ट्रीम से डबल मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
double[] - डबल मानों की सरणी।
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


स्ट्रीम से एक एकल फ़्लोट मान पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
float - एकल फ़्लोट मान।
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


स्ट्रीम से फ़्लोट मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
float[] - फ़्लोट मानों की सरणी।
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


स्ट्रीम से एक एकल रैशनल नंबर मान पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


स्ट्रीम से रैशनल मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - रैशनल मानों की सरणी।
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


स्ट्रीम से साइन्ड बाइट डेटा पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
byte - साइन किया गया बाइट मान।
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


स्ट्रीम से साइन्ड बाइट मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
byte[] - साइन किए गए बाइट मानों की सरणी।
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


स्ट्रीम से साइन्ड इंटेजर मान पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
int - एक साइन किया गया पूर्णांक मान।
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


स्ट्रीम से साइन्ड इंटेजर मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
int[] - साइन किए गए पूर्णांक मानों की सरणी।
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


स्ट्रीम से एक एकल साइन्ड रैशनल नंबर मान पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


स्ट्रीम से साइन्ड रैशनल मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - साइन किए गए रैशनल मानों की सरणी।
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


स्ट्रीम से साइन्ड शॉर्ट मान पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
short - एक साइन किया गया शॉर्ट मान।
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


स्ट्रीम से साइन किए गए शॉर्ट मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
short[] - साइन किए गए शॉर्ट मानों की सरणी।
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


स्ट्रीम से स्ट्रिंग पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | स्थिति। |

**Returns:**
java.lang.String - स्ट्रिंग।
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


स्ट्रीम से स्ट्रिंग पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | स्थिति। |
| लंबाई | long | लंबाई। |

**Returns:**
java.lang.String - स्ट्रिंग।
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


स्ट्रीम से अनसाइन्ड इंटीजर मान पढ़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
long - एक अनसाइन्ड पूर्णांक मान।
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
long[] - अनसाइन्ड पूर्णांक मानों की सरणी।
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


स्ट्रीम से अनसाइन्ड शॉर्ट मान पढ़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |

**Returns:**
int - एक अनसाइन्ड शॉर्ट मान।
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


स्ट्रीम से अनसाइन्ड इंटीजर मानों की एक एरे पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | long | पढ़ने के लिए स्थिति। |
| count | long | तत्वों की संख्या। |

**Returns:**
int[] - अनसाइन्ड पूर्णांक मानों की सरणी।
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि क्या गलत डेटा प्रोसेसिंग (स्ट्रीम को पढ़ते या लिखते समय) पर अपवाद फेंके जाते हैं।

मान:  true  यदि गलत डेटा प्रोसेसिंग पर अपवाद फेंके जाते हैं; अन्यथा, त्रुटि स्थितियों को चुपचाप अनदेखा किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


अधोस्त डेटा को स्ट्रीम कंटेनर में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startPosition | long | रूपांतरण शुरू करने के लिए प्रारंभिक स्थिति। |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

