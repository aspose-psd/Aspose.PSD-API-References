---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "IPlacedLayerResource इंटरफ़ेस को परिभाषित करता है जो PSD फ़ाइल में रखी गई लेयर के बारे में जानकारी रखता है।"
type: docs
weight: 17
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

IPlacedLayerResource इंटरफ़ेस को परिभाषित करता है जो PSD फ़ाइल में प्लेस्ड लेयर की जानकारी रखता है। यह एक मार्कअप इंटरफ़ेस है जिसका उपयोग Adobe\ufffd Photoshop\ufffd इमेजेज़ में PlLd, Sold और Sole रिसोर्सेज़ को निर्दिष्ट करने के लिए किया जाता है। यह Adobe\ufffd Photoshop\ufffd इमेजेज़ में स्मार्ट ऑब्जेक्ट लेयर्स को सपोर्ट करने के लिए उपयोग किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD छवि में रखी गई लेयर की एंटी एलियास नीति को प्राप्त करता है या सेट करता है। |
| [getBottom()](#getBottom--) | PSD छवि में रखी गई लेयर के नीचे स्थान को प्राप्त करता है या सेट करता है। |
| [getBounds()](#getBounds--) | PSD फ़ाइल में रखी गई लेयर की सीमाओं को प्राप्त करता है या सेट करता है। |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| [getItems()](#getItems--) | warp आइटम्स को प्राप्त करता है या सेट करता है। |
| [getLeft()](#getLeft--) | PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है। |
| [getPageNumber()](#getPageNumber--) | PSD फ़ाइल में रखी गई लेयर के पृष्ठ संख्या को प्राप्त करता है या सेट करता है। |
| [getPerspective()](#getPerspective--) | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य अन्य मान को प्राप्त करता है या सेट करता है। |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD फ़ाइल में रखी गई लेयर के प्रकार को प्राप्त करता है या सेट करता है। |
| [getRight()](#getRight--) | PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है। |
| [getTop()](#getTop--) | PSD छवि में रखी गई लेयर के शीर्ष स्थान को प्राप्त करता है या सेट करता है। |
| [getTotalPages()](#getTotalPages--) | PSD फ़ाइल में रखी गई लेयर के कुल पृष्ठों को प्राप्त करता है या सेट करता है। |
| [getTransformMatrix()](#getTransformMatrix--) | PSD फ़ाइल में रखी गई लेयर के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| [getUOrder()](#getUOrder--) | PSD फ़ाइल में रखी गई लेयर के U क्रम मान को प्राप्त करता है या सेट करता है। |
| [getUniqueId()](#getUniqueId--) | PSD इमेज में स्मार्ट ऑब्जेक्ट प्लेस्ड लेयर का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त या सेट करता है। |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | PSD फ़ाइल में रखी गई लेयर के V क्रम मान को प्राप्त करता है या सेट करता है। |
| [getValue()](#getValue--) | PSD इमेज में रखी गई लेयर के वार्प मान को प्राप्त करता है या सेट करता है। |
| [getVersion()](#getVersion--) | PSD फ़ाइल में रखी गई लेयर का संस्करण प्राप्त करता है, आमतौर पर 3-5। |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| [isCustom()](#isCustom--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि इस इंस्टेंस का वार्प स्टाइल कस्टम है या नहीं। |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD छवि में रखी गई लेयर की एंटी एलियास नीति को प्राप्त करता है या सेट करता है। |
| [setBottom(double value)](#setBottom-double-) | PSD छवि में रखी गई लेयर के नीचे स्थान को प्राप्त करता है या सेट करता है। |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD फ़ाइल में रखी गई लेयर की सीमाओं को प्राप्त करता है या सेट करता है। |
| [setCustom(boolean value)](#setCustom-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि इस इंस्टेंस का वार्प स्टाइल कस्टम है या नहीं। |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | warp आइटम्स को प्राप्त करता है या सेट करता है। |
| [setLeft(double value)](#setLeft-double-) | PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है। |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD फ़ाइल में रखी गई लेयर के पृष्ठ संख्या को प्राप्त करता है या सेट करता है। |
| [setPerspective(double value)](#setPerspective-double-) | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य अन्य मान को प्राप्त करता है या सेट करता है। |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD फ़ाइल में रखी गई लेयर के प्रकार को प्राप्त करता है या सेट करता है। |
| [setRight(double value)](#setRight-double-) | PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है। |
| [setTop(double value)](#setTop-double-) | PSD छवि में रखी गई लेयर के शीर्ष स्थान को प्राप्त करता है या सेट करता है। |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD फ़ाइल में रखी गई लेयर के कुल पृष्ठों को प्राप्त करता है या सेट करता है। |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD फ़ाइल में रखी गई लेयर के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| [setUOrder(int value)](#setUOrder-int-) | PSD फ़ाइल में रखी गई लेयर के U क्रम मान को प्राप्त करता है या सेट करता है। |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD इमेज में स्मार्ट ऑब्जेक्ट प्लेस्ड लेयर का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त या सेट करता है। |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | PSD फ़ाइल में रखी गई लेयर के V क्रम मान को प्राप्त करता है या सेट करता है। |
| [setValue(double value)](#setValue-double-) | PSD इमेज में रखी गई लेयर के वार्प मान को प्राप्त करता है या सेट करता है। |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


PSD छवि में रखी गई लेयर की एंटी एलियास नीति को प्राप्त करता है या सेट करता है।

मान: रखी गई लेयर की एंटी-अलियास नीति।

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


PSD छवि में रखी गई लेयर के नीचे स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई लेयर का निचला स्थान।

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


PSD फ़ाइल में रखी गई लेयर की सीमाओं को प्राप्त करता है या सेट करता है।

मान: रखी गई लेयर की सीमाएँ।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है।

मान: क्षैतिज मेष बिंदुओं की माप इकाई।

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रखी गई परत के क्षैतिज मेष बिंदु।

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


warp आइटम्स को प्राप्त करता है या सेट करता है।

मान: वॉर्प वस्तुएँ।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का बायाँ स्थान।

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


PSD फ़ाइल में रखी गई लेयर के पृष्ठ संख्या को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का पृष्ठ संख्या।

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का परिप्रेक्ष्य मान।

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य अन्य मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का परिप्रेक्ष्य अन्य मान।

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


PSD फ़ाइल में रखी गई लेयर के प्रकार को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का प्रकार।

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का दायाँ स्थान।

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


PSD छवि में रखी गई लेयर के शीर्ष स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का शीर्ष स्थान।

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


PSD फ़ाइल में रखी गई लेयर के कुल पृष्ठों को प्राप्त करता है या सेट करता है।

मान: रखी गई परत के कुल पृष्ठ।

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


PSD फ़ाइल में रखी गई लेयर के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का ट्रांसफ़ॉर्म मैट्रिक्स।

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


PSD फ़ाइल में रखी गई लेयर के U क्रम मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का U क्रम मान।

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


PSD इमेज में स्मार्ट ऑब्जेक्ट प्लेस्ड लेयर का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त या सेट करता है।

मान: रखी गई परत की अनूठी पहचानकर्ता।

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


PSD फ़ाइल में रखी गई लेयर के V क्रम मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का V क्रम मान।

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


PSD इमेज में रखी गई लेयर के वार्प मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का वॉर्प मान।

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


PSD फ़ाइल में रखी गई लेयर का संस्करण प्राप्त करता है, आमतौर पर 3-5।

मान: रखी गई या स्मार्ट ऑब्जेक्ट लेयर का संस्करण।

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है।

मान: लंबवत मेष बिंदुओं की माप इकाई।

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रखी गई परत के क्षैतिज मेष बिंदु।

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


इस उदाहरण के warp style को कस्टम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true है तो इसमें mesh points होते हैं। यदि false सेट किया जाता है तो यह mesh points को मिटा देता है।

मान:  true  यदि रखी गई या स्मार्ट ऑब्जेक्ट लेयर रिसोर्स में कस्टम स्टाइल है; अन्यथा,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


PSD छवि में रखी गई लेयर की एंटी एलियास नीति को प्राप्त करता है या सेट करता है।

मान: रखी गई लेयर की एंटी-अलियास नीति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


PSD छवि में रखी गई लेयर के नीचे स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई लेयर का निचला स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


PSD फ़ाइल में रखी गई लेयर की सीमाओं को प्राप्त करता है या सेट करता है।

मान: रखी गई लेयर की सीमाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


इस उदाहरण के warp style को कस्टम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true है तो इसमें mesh points होते हैं। यदि false सेट किया जाता है तो यह mesh points को मिटा देता है।

मान:  true  यदि रखी गई या स्मार्ट ऑब्जेक्ट लेयर रिसोर्स में कस्टम स्टाइल है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है।

मान: क्षैतिज मेष बिंदुओं की माप इकाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रखी गई परत के क्षैतिज मेष बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


warp आइटम्स को प्राप्त करता है या सेट करता है।

मान: वॉर्प वस्तुएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का बायाँ स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


PSD फ़ाइल में रखी गई लेयर के पृष्ठ संख्या को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का पृष्ठ संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का परिप्रेक्ष्य मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य अन्य मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का परिप्रेक्ष्य अन्य मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


PSD फ़ाइल में रखी गई लेयर के प्रकार को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का दायाँ स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


PSD छवि में रखी गई लेयर के शीर्ष स्थान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का शीर्ष स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


PSD फ़ाइल में रखी गई लेयर के कुल पृष्ठों को प्राप्त करता है या सेट करता है।

मान: रखी गई परत के कुल पृष्ठ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


PSD फ़ाइल में रखी गई लेयर के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का ट्रांसफ़ॉर्म मैट्रिक्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


PSD फ़ाइल में रखी गई लेयर के U क्रम मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का U क्रम मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


PSD इमेज में स्मार्ट ऑब्जेक्ट प्लेस्ड लेयर का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त या सेट करता है।

मान: रखी गई परत की अनूठी पहचानकर्ता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


PSD फ़ाइल में रखी गई लेयर के V क्रम मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का V क्रम मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


PSD इमेज में रखी गई लेयर के वार्प मान को प्राप्त करता है या सेट करता है।

मान: रखी गई परत का वॉर्प मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है।

मान: लंबवत मेष बिंदुओं की माप इकाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रखी गई परत के क्षैतिज मेष बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double[] |  |

