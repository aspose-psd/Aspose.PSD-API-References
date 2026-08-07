---
title: "PatternFillSettings"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "पैटर्न फ़िल इफ़ेक्ट सेटिंग्स"
type: docs
weight: 20
url: /hi/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

पैटर्न फ़िल इफ़ेक्ट सेटिंग्स
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | एक नया उदाहरण प्रारंभ करता है [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | LFX2 संसाधन नोड्स उत्पन्न करता है। |
| [getAlignWithLayer()](#getAlignWithLayer--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [link with layer] है या नहीं। |
| [getAngle()](#getAngle--) | कोण प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | रंग प्राप्त करता है या सेट करता है। |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | फ़िल प्रकार |
| [getHorizontalOffset()](#getHorizontalOffset--) | क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है। |
| [getLinked()](#getLinked--) | इस [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) का लिंक्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getPatternData()](#getPatternData--) | पैटर्न डेटा प्राप्त करता है या सेट करता है। |
| [getPatternHeight()](#getPatternHeight--) | पैटर्न की ऊँचाई प्राप्त करता है या सेट करता है। |
| [getPatternId()](#getPatternId--) | पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है। |
| [getPatternName()](#getPatternName--) | पैटर्न का नाम प्राप्त करता है या सेट करता है। |
| [getPatternWidth()](#getPatternWidth--) | पैटर्न की चौड़ाई प्राप्त करता है या सेट करता है। |
| [getPhase_internalized()](#getPhase-internalized--) | फेज़ प्राप्त करता है या सेट करता है। |
| [getPointType()](#getPointType--) | बिंदु का प्रकार प्राप्त करता है या सेट करता है। |
| [getScale()](#getScale--) | स्केल को प्राप्त करता है या सेट करता है। |
| [getVerticalOffset()](#getVerticalOffset--) | ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | मान परिवर्तन को ट्रिगर करता है। |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [link with layer] है या नहीं। |
| [setAngle(double value)](#setAngle-double-) | कोण प्राप्त करता है या सेट करता है। |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | रंग प्राप्त करता है या सेट करता है। |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है। |
| [setLinked(boolean value)](#setLinked-boolean-) | इस [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) का लिंक्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setPatternData(int[] value)](#setPatternData-int---) | पैटर्न डेटा प्राप्त करता है या सेट करता है। |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | पैटर्न के पिक्सेल बफ़र और सहेजते समय उपयोग करने के लिए संपीड़न मोड सेट करता है। |
| [setPatternHeight(int value)](#setPatternHeight-int-) | पैटर्न की ऊँचाई प्राप्त करता है या सेट करता है। |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है। |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | पैटर्न का नाम प्राप्त करता है या सेट करता है। |
| [setPatternWidth(int value)](#setPatternWidth-int-) | पैटर्न की चौड़ाई प्राप्त करता है या सेट करता है। |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | फेज़ प्राप्त करता है या सेट करता है। |
| [setPointType(String value)](#setPointType-java.lang.String-) | बिंदु का प्रकार प्राप्त करता है या सेट करता है। |
| [setScale(double value)](#setScale-double-) | स्केल को प्राप्त करता है या सेट करता है। |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है। |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | पैटर्न के डिफ़ॉल्ट डेटा को [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) उदाहरण में सेट करता है। |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | पैटर्न गुणों को [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) उदाहरण से अपडेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


एक नया उदाहरण प्रारंभ करता है [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) क्लास का।

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


LFX2 संसाधन नोड्स उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pointType | java.lang.String | बिंदु का प्रकार। |
| color | [Color](../../com.aspose.psd/color) | रंग। |
| patternName | java.lang.String | पैटर्न का नाम। |
| identifier | java.lang.String | पहचानकर्ता। |
| स्केल | double | स्केल। |
| जुड़ा हुआ | boolean | यदि सेट किया गया है  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | ऑफ़सेट। |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) की सूची
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [link with layer] है या नहीं।

मान:  true  यदि [link with layer]; अन्यथा,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


कोण प्राप्त करता है या सेट करता है।

मान: कोण।

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


रंग प्राप्त करता है या सेट करता है।

मान: रंग।

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


फ़िल प्रकार

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


इस [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) का लिंक्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि जुड़ा हुआ; अन्यथा,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


पैटर्न डेटा प्राप्त करता है या सेट करता है।

मान: पैटर्न डेटा।

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


पैटर्न की ऊँचाई प्राप्त करता है या सेट करता है।

मान: पैटर्न की ऊँचाई।

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है।

मान: पैटर्न पहचानकर्ता।

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


पैटर्न का नाम प्राप्त करता है या सेट करता है।

मान: पैटर्न का नाम।

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


पैटर्न की चौड़ाई प्राप्त करता है या सेट करता है।

मान: पैटर्न की चौड़ाई।

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


फेज़ प्राप्त करता है या सेट करता है।

मान: चरण।

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


बिंदु का प्रकार प्राप्त करता है या सेट करता है।

मान: बिंदु का प्रकार।

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


स्केल को प्राप्त करता है या सेट करता है।

मान: स्केल।

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


मान परिवर्तन को ट्रिगर करता है।

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [link with layer] है या नहीं।

मान:  true  यदि [link with layer]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


कोण प्राप्त करता है या सेट करता है।

मान: कोण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


रंग प्राप्त करता है या सेट करता है।

मान: रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


इस [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) का लिंक्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि जुड़ा हुआ; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


पैटर्न डेटा प्राप्त करता है या सेट करता है।

मान: पैटर्न डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


पैटर्न के पिक्सेल बफ़र और सहेजते समय उपयोग करने के लिए संपीड़न मोड सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| patternData | int[] | 32-बिट पिक्सेल में  0xAARRGGBB . |
| compressionModeOnSave | byte | संपीड़न मोड जिसका उपयोग PSD फ़ाइल सहेजते समय पैटर्न डेटा के संपीड़न को परिभाषित करने के लिए किया जाता है। |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


पैटर्न की ऊँचाई प्राप्त करता है या सेट करता है।

मान: पैटर्न की ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है।

मान: पैटर्न पहचानकर्ता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


पैटर्न का नाम प्राप्त करता है या सेट करता है।

मान: पैटर्न का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


पैटर्न की चौड़ाई प्राप्त करता है या सेट करता है।

मान: पैटर्न की चौड़ाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


फेज़ प्राप्त करता है या सेट करता है।

मान: चरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


बिंदु का प्रकार प्राप्त करता है या सेट करता है।

मान: बिंदु का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


स्केल को प्राप्त करता है या सेट करता है।

मान: स्केल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


पैटर्न के डिफ़ॉल्ट डेटा को [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) उदाहरण में सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | पैटर्न भराव सेटिंग्स। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


पैटर्न गुणों को [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) उदाहरण से अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | यह [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) पैटर्न डेटा के साथ उदाहरण। |

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

