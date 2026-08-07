---
title: "BlendingOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "BlendingOptions."
type: docs
weight: 10
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---

**Inheritance:**
java.lang.Object
```
public class BlendingOptions
```

BlendingOptions. यह BaseFxResource के लिए एक रैपर है जो लेयर इफ़ेक्ट्स के लिए API प्रदान करता है
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ResourceChanged_internalized](#ResourceChanged-internalized) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | रंग ओवरले जोड़ता है। |
| [addDropShadow()](#addDropShadow--) | ड्रॉप शैडो प्रभाव जोड़ता है। |
| [addGradientOverlay()](#addGradientOverlay--) | ग्रेडिएंट ओवरले जोड़ता है। |
| [addInnerShadow()](#addInnerShadow--) | इनर शैडो प्रभाव जोड़ता है। |
| [addOuterGlow()](#addOuterGlow--) | आउटर ग्लो प्रभाव जोड़ता है। |
| [addPatternOverlay()](#addPatternOverlay--) | पैटर्न ओवरले जोड़ता है। |
| [addStroke(int fillType)](#addStroke-int-) | स्ट्रोक प्रभाव जोड़ता है। |
| [calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)](#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-) | लेयर की सीमाओं की गणना करता है जिसमें दृश्य इफ़ेक्ट्स शामिल हैं। |
| [create_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAreEffectsEnabled()](#getAreEffectsEnabled--) | सभी लेयर इफ़ेक्ट्स की दृश्यता प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | इफ़ेक्ट्स प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAreEffectsEnabled(boolean value)](#setAreEffectsEnabled-boolean-) | सभी लेयर इफ़ेक्ट्स की दृश्यता प्राप्त करता है या सेट करता है। |
| [setEffects(ILayerEffect[] value)](#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---) | इफ़ेक्ट्स प्राप्त करता है। |
| [setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)](#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | नया पैटर्न डेटा बनाता है और इसे [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) इंस्टेंस में सेट करता है। |
| [toString()](#toString--) |  |
| [updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | यदि यह नया है तो इफ़ेक्ट्स को अपडेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceChanged_internalized {#ResourceChanged-internalized}
```
public final Event<System.EventHandler<ResourceChangedEventArgs>> ResourceChanged_internalized
```


### addColorOverlay() {#addColorOverlay--}
```
public final ColorOverlayEffect addColorOverlay()
```


रंग ओवरले जोड़ता है।

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - Created [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) object
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


ड्रॉप शैडो प्रभाव जोड़ता है।

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - Created [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) object
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


ग्रेडिएंट ओवरले जोड़ता है।

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - Created [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) object
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


इनर शैडो प्रभाव जोड़ता है।

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - Created [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) object
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


आउटर ग्लो प्रभाव जोड़ता है।

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - Created [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) object
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


पैटर्न ओवरले जोड़ता है।

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - Created [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) object
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


स्ट्रोक प्रभाव जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillType | int | स्ट्रोक को भरने के लिए भराव का प्रकार। |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - Created [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) object.
### calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle) {#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-}
```
public final Rectangle calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)
```


लेयर की सीमाओं की गणना करता है जिसमें दृश्य इफ़ेक्ट्स शामिल हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | लेयर की मूल सीमाएँ। |
| globalAngle | int | कुछ इफ़ेक्ट्स के लिए उपयोग किया गया वैश्विक प्रकाश कोण। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The calculated bounds including the visual effects.
### create_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static BlendingOptions create_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
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
### getAreEffectsEnabled() {#getAreEffectsEnabled--}
```
public final boolean getAreEffectsEnabled()
```


सभी लेयर इफ़ेक्ट्स की दृश्यता प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffects() {#getEffects--}
```
public final ILayerEffect[] getEffects()
```


इफ़ेक्ट्स प्राप्त करता है।

मान: इफ़ेक्ट्स।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect[]
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




### setAreEffectsEnabled(boolean value) {#setAreEffectsEnabled-boolean-}
```
public final void setAreEffectsEnabled(boolean value)
```


सभी लेयर इफ़ेक्ट्स की दृश्यता प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setEffects(ILayerEffect[] value) {#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---}
```
public void setEffects(ILayerEffect[] value)
```


इफ़ेक्ट्स प्राप्त करता है।

मान: इफ़ेक्ट्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILayerEffect\[\]](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect) |  |

### setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings) {#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)
```


नया पैटर्न डेटा बनाता है और इसे [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) इंस्टेंस में सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| patternSettings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | पैटर्न भराव सेटिंग्स। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```


यदि यह नया है तो इफ़ेक्ट्स को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | इफ़ेक्ट्स के साथ लेयर शैली। |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | यह patt संसाधन। |

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

