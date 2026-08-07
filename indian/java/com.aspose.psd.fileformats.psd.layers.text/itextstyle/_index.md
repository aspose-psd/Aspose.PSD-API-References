---
title: "ITextStyle"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "टेक्स्ट स्टाइल के साथ काम करने के लिए इंटरफ़ेस"
type: docs
weight: 14
url: /hi/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

टेक्स्ट स्टाइल के साथ काम करने के लिए इंटरफ़ेस
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | निर्दिष्ट शैली लागू करता है। |
| [getAutoKerning()](#getAutoKerning--) | ऑटो कर्निंग प्राप्त करता है या सेट करता है। |
| [getAutoLeading()](#getAutoLeading--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [automatic leading] है या नहीं। |
| [getBaselineShift()](#getBaselineShift--) | बेसलाइन शिफ्ट। |
| [getContextualAlternates()](#getContextualAlternates--) | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले संदर्भात्मक विकल्प। |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले वैकल्पिक लिगेचर, विशेष रूप से स्क्रिप्ट फ़ॉन्ट्स में। |
| [getFauxBold()](#getFauxBold--) | फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है। |
| [getFauxItalic()](#getFauxItalic--) | फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है। |
| [getFillColor()](#getFillColor--) | भरण का रंग प्राप्त करता है या सेट करता है। |
| [getFontBaseline()](#getFontBaseline--) | फ़ॉन्ट बेसलाइन। |
| [getFontCaps()](#getFontCaps--) | फ़ॉन्ट कैप्स। |
| [getFontIndex()](#getFontIndex--) | फ़ॉन्ट इंडेक्स प्राप्त करता है। |
| [getFontName()](#getFontName--) | फ़ॉन्ट नाम प्राप्त करता है या सेट करता है। |
| [getFontSize()](#getFontSize--) | फ़ॉन्ट का आकार प्राप्त करता है या सेट करता है। |
| [getFractions()](#getFractions--) | भिन्न प्रतीकों को विशेष ग्लिफ़ से बदला जा सकता है। |
| [getHindiNumbers()](#getHindiNumbers--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [hindi numbers]। |
| [getHorizontalScale()](#getHorizontalScale--) | क्षैतिज स्केल। |
| [getKerning()](#getKerning--) | कर्निंग प्राप्त करता है या सेट करता है। |
| [getLanguageIndex()](#getLanguageIndex--) | भाषा इंडेक्स प्राप्त करता है। |
| [getLeading()](#getLeading--) | लीडिंग प्राप्त करता है या सेट करता है। |
| [getStandardLigatures()](#getStandardLigatures--) | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले मानक संदर्भात्मक लिगेचर। |
| [getStrikethrough()](#getStrikethrough--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [strikethrough]। |
| [getStrokeColor()](#getStrokeColor--) | स्ट्रोक का रंग प्राप्त करता है या सेट करता है। |
| [getTracking()](#getTracking--) | ट्रैकिंग प्राप्त करता है या सेट करता है। |
| [getUnderline()](#getUnderline--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [underline]। |
| [getVerticalScale()](#getVerticalScale--) | ऊर्ध्वाधर स्केल। |
| [get_noBreak()](#get-noBreak--) | नो ब्रेक मान प्राप्त करता है ot सेट करता है। |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | निर्धारित करता है कि निर्दिष्ट शैली समान है या नहीं। |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | मानक ऊर्ध्वाधर रोमन संरेखण प्राप्त करता है या सेट करता है। |
| [setAutoKerning(int value)](#setAutoKerning-int-) | ऑटो कर्निंग प्राप्त करता है या सेट करता है। |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [automatic leading] है या नहीं। |
| [setBaselineShift(double value)](#setBaselineShift-double-) | बेसलाइन शिफ्ट। |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले संदर्भात्मक विकल्प। |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले वैकल्पिक लिगेचर, विशेष रूप से स्क्रिप्ट फ़ॉन्ट्स में। |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है। |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है। |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | भरण का रंग प्राप्त करता है या सेट करता है। |
| [setFontBaseline(int value)](#setFontBaseline-int-) | फ़ॉन्ट बेसलाइन। |
| [setFontCaps(int value)](#setFontCaps-int-) | फ़ॉन्ट कैप्स। |
| [setFontName(String value)](#setFontName-java.lang.String-) | फ़ॉन्ट नाम प्राप्त करता है या सेट करता है। |
| [setFontSize(double value)](#setFontSize-double-) | फ़ॉन्ट का आकार प्राप्त करता है या सेट करता है। |
| [setFractions(boolean value)](#setFractions-boolean-) | भिन्न प्रतीकों को विशेष ग्लिफ़ से बदला जा सकता है। |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [hindi numbers]। |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | क्षैतिज स्केल। |
| [setKerning(int value)](#setKerning-int-) | कर्निंग प्राप्त करता है या सेट करता है। |
| [setLeading(double value)](#setLeading-double-) | लीडिंग प्राप्त करता है या सेट करता है। |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले मानक संदर्भात्मक लिगेचर। |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [strikethrough]। |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | स्ट्रोक का रंग प्राप्त करता है या सेट करता है। |
| [setTracking(int value)](#setTracking-int-) | ट्रैकिंग प्राप्त करता है या सेट करता है। |
| [setUnderline(boolean value)](#setUnderline-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [underline]। |
| [setVerticalScale(double value)](#setVerticalScale-double-) | ऊर्ध्वाधर स्केल। |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | मानक ऊर्ध्वाधर रोमन संरेखण प्राप्त करता है या सेट करता है। |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | नो ब्रेक मान प्राप्त करता है ot सेट करता है। |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


निर्दिष्ट शैली लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | शैली। |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


ऑटो कर्निंग प्राप्त करता है या सेट करता है।

मान: दो अक्षरों के बीच का ऑटो कर्निंग।

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [automatic leading] है या नहीं।

मान: true यदि [automatic leading]; अन्यथा, false।

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


बेसलाइन शिफ्ट।

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले संदर्भात्मक विकल्प।

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले वैकल्पिक लिगेचर, विशेष रूप से स्क्रिप्ट फ़ॉन्ट्स में।

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


भरण का रंग प्राप्त करता है या सेट करता है।

मान: भराव का रंग।

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


फ़ॉन्ट बेसलाइन।

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


फ़ॉन्ट कैप्स।

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


फ़ॉन्ट इंडेक्स प्राप्त करता है।

मान: फ़ॉन्ट।

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


फ़ॉन्ट नाम प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


फ़ॉन्ट का आकार प्राप्त करता है या सेट करता है।

मान: फ़ॉन्ट का आकार।

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


भिन्न प्रतीकों को विशेष ग्लिफ़ से बदला जा सकता है।

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [hindi numbers]।

मान: true यदि [hindi numbers]; अन्यथा, false।

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


क्षैतिज स्केल।

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


कर्निंग प्राप्त करता है या सेट करता है।

मान: दो अक्षरों के बीच का कर्निंग।

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


भाषा इंडेक्स प्राप्त करता है।

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


लीडिंग प्राप्त करता है या सेट करता है।

मान: लीडिंग।

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले मानक संदर्भात्मक लिगेचर।

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [strikethrough]।

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


स्ट्रोक का रंग प्राप्त करता है या सेट करता है।

मान: स्ट्रोक का रंग।

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


ट्रैकिंग प्राप्त करता है या सेट करता है।

मान: ट्रैकिंग।

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [underline]।

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


ऊर्ध्वाधर स्केल।

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


नो ब्रेक मान प्राप्त करता है ot सेट करता है।

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


निर्धारित करता है कि निर्दिष्ट शैली समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | शैली। |

**Returns:**
बूलियन - यदि निर्दिष्ट शैली समान है तो true; अन्यथा, false।
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


मानक वर्टिकल रोमन संरेखण प्राप्त करता है या सेट करता है। यह BaselineDirection संसाधन मान पर आधारित है और केवल तब लागू होता है जब टेक्स्ट अभिविन्यास [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) हो।

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


ऑटो कर्निंग प्राप्त करता है या सेट करता है।

मान: दो अक्षरों के बीच का ऑटो कर्निंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [automatic leading] है या नहीं।

मान: true यदि [automatic leading]; अन्यथा, false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


बेसलाइन शिफ्ट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले संदर्भात्मक विकल्प।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले वैकल्पिक लिगेचर, विशेष रूप से स्क्रिप्ट फ़ॉन्ट्स में।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


फ़ॉक्स बोल्ड सक्षम है या नहीं, प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


भरण का रंग प्राप्त करता है या सेट करता है।

मान: भराव का रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


फ़ॉन्ट बेसलाइन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


फ़ॉन्ट कैप्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


फ़ॉन्ट नाम प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


फ़ॉन्ट का आकार प्राप्त करता है या सेट करता है।

मान: फ़ॉन्ट का आकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


भिन्न प्रतीकों को विशेष ग्लिफ़ से बदला जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [hindi numbers]।

मान: true यदि [hindi numbers]; अन्यथा, false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


क्षैतिज स्केल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


कर्निंग प्राप्त करता है या सेट करता है।

मान: दो अक्षरों के बीच का कर्निंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


लीडिंग प्राप्त करता है या सेट करता है।

मान: लीडिंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले मानक संदर्भात्मक लिगेचर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [strikethrough]।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


स्ट्रोक का रंग प्राप्त करता है या सेट करता है।

मान: स्ट्रोक का रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


ट्रैकिंग प्राप्त करता है या सेट करता है।

मान: ट्रैकिंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [underline]।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


ऊर्ध्वाधर स्केल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


मानक वर्टिकल रोमन संरेखण प्राप्त करता है या सेट करता है। यह BaselineDirection संसाधन मान पर आधारित है और केवल तब लागू होता है जब टेक्स्ट अभिविन्यास [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


नो ब्रेक मान प्राप्त करता है ot सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

