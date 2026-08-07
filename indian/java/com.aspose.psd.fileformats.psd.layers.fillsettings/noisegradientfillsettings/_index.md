---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "नॉइज़ ग्रेडिएंट डिफिनिशन क्लास।"
type: docs
weight: 18
url: /hi/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

नॉइज़ ग्रेडिएंट डिफिनिशन क्लास।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | नया उदाहरण प्रारंभ करता है [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getAngle()](#getAngle--) | कोण प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | प्राप्त करता है या सेट करता है Color Model - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getExpansionCount()](#getExpansionCount--) | प्राप्त करता है या सेट करता है Expansion count ( = 2 for Photoshop 6.0). |
| [getFillType()](#getFillType--) | फ़िल प्रकार। |
| [getGradientMode()](#getGradientMode--) | इस ग्रेडिएंट के लिए मोड प्राप्त करता है। |
| [getGradientName()](#getGradientName--) | ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है। |
| [getGradientType()](#getGradientType--) | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| [getHorizontalOffset()](#getHorizontalOffset--) | प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [getMaximumColor()](#getMaximumColor--) | प्राप्त करता है या सेट करता है Maximum color of PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | प्राप्त करता है या सेट करता है Minimum color of PixelDataFormat. |
| [getReverse()](#getReverse--) | इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getRndNumberSeed()](#getRndNumberSeed--) | प्राप्त करता है या सेट करता है random number seed used to generate colors for Noise gradient |
| [getRoughness()](#getRoughness--) | प्राप्त करता है या सेट करता है Roughness factor. |
| [getScale()](#getScale--) | स्केल को प्राप्त करता है या सेट करता है। |
| [getShowTransparency()](#getShowTransparency--) | प्राप्त करता है या सेट करता है flag for showing transparency. |
| [getUseVectorColor()](#getUseVectorColor--) | प्राप्त करता है या सेट करता है flag for using vector color. |
| [getVerticalOffset()](#getVerticalOffset--) | प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | मान परिवर्तन को ट्रिगर करता है। |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setAngle(double value)](#setAngle-double-) | कोण प्राप्त करता है या सेट करता है। |
| [setColorModel(short value)](#setColorModel-short-) | प्राप्त करता है या सेट करता है Color Model - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setExpansionCount(short value)](#setExpansionCount-short-) | प्राप्त करता है या सेट करता है Expansion count ( = 2 for Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | इस ग्रेडिएंट के लिए मोड प्राप्त करता है। |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है। |
| [setGradientType(int value)](#setGradientType-int-) | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | प्राप्त करता है या सेट करता है Maximum color of PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | प्राप्त करता है या सेट करता है Minimum color of PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | प्राप्त करता है या सेट करता है random number seed used to generate colors for Noise gradient |
| [setRoughness(int value)](#setRoughness-int-) | प्राप्त करता है या सेट करता है Roughness factor. |
| [setScale(int value)](#setScale-int-) | स्केल को प्राप्त करता है या सेट करता है। |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | प्राप्त करता है या सेट करता है flag for showing transparency. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | प्राप्त करता है या सेट करता है flag for using vector color. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


नया उदाहरण प्रारंभ करता है [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) क्लास का।

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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि [align with layer]; अन्यथा,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


कोण प्राप्त करता है या सेट करता है।

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


प्राप्त करता है या सेट करता है Color Model - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि डिथर है तो true; अन्यथा false।

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


प्राप्त करता है या सेट करता है Expansion count ( = 2 for Photoshop 6.0).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


फ़िल प्रकार।

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


इस ग्रेडिएंट के लिए मोड प्राप्त करता है। निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)।

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है।

Value: ग्रेडिएंट का नाम।

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

मान: ग्रेडिएंट का प्रकार।

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Returns:**
double
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


प्राप्त करता है या सेट करता है Maximum color of PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


प्राप्त करता है या सेट करता है Minimum color of PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि रिवर्स है तो true; अन्यथा false।

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


प्राप्त करता है या सेट करता है random number seed used to generate colors for Noise gradient

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


प्राप्त करता है या सेट करता है Roughness factor.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


स्केल को प्राप्त करता है या सेट करता है।

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


प्राप्त करता है या सेट करता है flag for showing transparency.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


प्राप्त करता है या सेट करता है flag for using vector color.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Returns:**
double
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


लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि [align with layer]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


कोण प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


प्राप्त करता है या सेट करता है Color Model - RGB/HSB/LAB (3/4/6).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि डिथर है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


प्राप्त करता है या सेट करता है Expansion count ( = 2 for Photoshop 6.0).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


इस ग्रेडिएंट के लिए मोड प्राप्त करता है। निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है।

Value: ग्रेडिएंट का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

मान: ग्रेडिएंट का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


प्राप्त करता है या सेट करता है Maximum color of PixelDataFormat.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


प्राप्त करता है या सेट करता है Minimum color of PixelDataFormat.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


इस [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि रिवर्स है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


प्राप्त करता है या सेट करता है random number seed used to generate colors for Noise gradient

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


प्राप्त करता है या सेट करता है Roughness factor.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


स्केल को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


प्राप्त करता है या सेट करता है flag for showing transparency.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


प्राप्त करता है या सेट करता है flag for using vector color.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

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

