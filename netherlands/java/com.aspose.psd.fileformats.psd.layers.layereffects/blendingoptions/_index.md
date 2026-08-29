---
title: "BlendingOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "BlendingOptions."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---

**Inheritance:**
java.lang.Object
```
public class BlendingOptions
```

BlendingOptions. Het is een wrapper voor BaseFxResource die een API biedt voor laageffecten.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ResourceChanged_internalized](#ResourceChanged-internalized) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | Voegt de kleuroverlay toe. |
| [addDropShadow()](#addDropShadow--) | Voegt het slagschaduw‑effect toe. |
| [addGradientOverlay()](#addGradientOverlay--) | Voegt de Gradient overlay toe. |
| [addInnerShadow()](#addInnerShadow--) | Voegt het binnenste schaduw‑effect toe. |
| [addOuterGlow()](#addOuterGlow--) | Voegt het buitenste gloed‑effect toe. |
| [addPatternOverlay()](#addPatternOverlay--) | Voegt de patroonoverlay toe. |
| [addStroke(int fillType)](#addStroke-int-) | Voegt het lijn‑effect toe. |
| [calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)](#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-) | Berekent de grenzen van de laag inclusief visuele effecten. |
| [create_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAreEffectsEnabled()](#getAreEffectsEnabled--) | Haalt op of stelt de zichtbaarheid van alle laageffecten in. |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | Haalt de effecten op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAreEffectsEnabled(boolean value)](#setAreEffectsEnabled-boolean-) | Haalt op of stelt de zichtbaarheid van alle laageffecten in. |
| [setEffects(ILayerEffect[] value)](#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---) | Haalt de effecten op. |
| [setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)](#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Maakt de nieuwe patroongegevens aan en zet deze in een [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instantie. |
| [toString()](#toString--) |  |
| [updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Werkt de effecten bij als deze nieuwer is. |
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


Voegt de kleuroverlay toe.

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - Created [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) object
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


Voegt het slagschaduw‑effect toe.

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - Created [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) object
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


Voegt de Gradient overlay toe.

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - Created [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) object
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


Voegt het binnenste schaduw‑effect toe.

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - Created [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) object
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


Voegt het buitenste gloed‑effect toe.

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - Created [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) object
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


Voegt de patroonoverlay toe.

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - Created [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) object
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


Voegt het lijn‑effect toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillType | int | Het type vulling om de stroke te vullen. |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - Created [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) object.
### calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle) {#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-}
```
public final Rectangle calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)
```


Berekent de grenzen van de laag inclusief visuele effecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | De oorspronkelijke grenzen van de laag. |
| globalAngle | int | De globale lichthoek die wordt gebruikt voor bepaalde effecten. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The calculated bounds including the visual effects.
### create_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static BlendingOptions create_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAreEffectsEnabled() {#getAreEffectsEnabled--}
```
public final boolean getAreEffectsEnabled()
```


Haalt op of stelt de zichtbaarheid van alle laageffecten in.

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


Haalt de effecten op.

Waarde: De effecten.

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


Haalt op of stelt de zichtbaarheid van alle laageffecten in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setEffects(ILayerEffect[] value) {#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---}
```
public void setEffects(ILayerEffect[] value)
```


Haalt de effecten op.

Waarde: De effecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayerEffect\[\]](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect) |  |

### setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings) {#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)
```


Maakt de nieuwe patroongegevens aan en zet deze in een [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| patternSettings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | De patroonvullingsinstellingen. |

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


Werkt de effecten bij als deze nieuwer is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | De laagstijl met effecten. |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | De patt resource. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

