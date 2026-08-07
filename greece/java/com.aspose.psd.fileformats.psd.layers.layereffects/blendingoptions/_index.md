---
title: "BlendingOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "BlendingOptions."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---

**Inheritance:**
java.lang.Object
```
public class BlendingOptions
```

BlendingOptions. Αυτή είναι μια περιτύλιξη για το BaseFxResource που παρέχει API για εφέ στρώσης
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ResourceChanged_internalized](#ResourceChanged-internalized) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addColorOverlay()](#addColorOverlay--) | Προσθέτει την επικάλυψη χρώματος. |
| [addDropShadow()](#addDropShadow--) | Προσθέτει το εφέ σκιάς πτώσης. |
| [addGradientOverlay()](#addGradientOverlay--) | Προσθέτει την επικάλυψη Gradient. |
| [addInnerShadow()](#addInnerShadow--) | Προσθέτει το εφέ εσωτερικής σκιάς. |
| [addOuterGlow()](#addOuterGlow--) | Προσθέτει το εφέ εξωτερικής λάμψης. |
| [addPatternOverlay()](#addPatternOverlay--) | Προσθέτει την επικάλυψη Pattern. |
| [addStroke(int fillType)](#addStroke-int-) | Προσθέτει το εφέ γραμμής. |
| [calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)](#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-) | Υπολογίζει τα όρια της στρώσης συμπεριλαμβανομένων των οπτικών εφέ. |
| [create_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAreEffectsEnabled()](#getAreEffectsEnabled--) | Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσης. |
| [getClass()](#getClass--) |  |
| [getEffects()](#getEffects--) | Λαμβάνει τα εφέ. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAreEffectsEnabled(boolean value)](#setAreEffectsEnabled-boolean-) | Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσης. |
| [setEffects(ILayerEffect[] value)](#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---) | Λαμβάνει τα εφέ. |
| [setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)](#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Δημιουργεί τα νέα δεδομένα μοτίβου και τα ορίζει στο αντικείμενο [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updateEffectsSources_internalized(LayerStyleFX layerStyle, PattResource pattResource)](#updateEffectsSources-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Ενημερώνει τα εφέ εάν είναι πιο πρόσφατα. |
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


Προσθέτει την επικάλυψη χρώματος.

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) - Created [ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect) object
### addDropShadow() {#addDropShadow--}
```
public final DropShadowEffect addDropShadow()
```


Προσθέτει το εφέ σκιάς πτώσης.

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) - Created [DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect) object
### addGradientOverlay() {#addGradientOverlay--}
```
public final GradientOverlayEffect addGradientOverlay()
```


Προσθέτει την επικάλυψη Gradient.

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) - Created [GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect) object
### addInnerShadow() {#addInnerShadow--}
```
public final InnerShadowEffect addInnerShadow()
```


Προσθέτει το εφέ εσωτερικής σκιάς.

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) - Created [InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect) object
### addOuterGlow() {#addOuterGlow--}
```
public final OuterGlowEffect addOuterGlow()
```


Προσθέτει το εφέ εξωτερικής λάμψης.

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) - Created [OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect) object
### addPatternOverlay() {#addPatternOverlay--}
```
public final PatternOverlayEffect addPatternOverlay()
```


Προσθέτει την επικάλυψη Pattern.

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) - Created [PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect) object
### addStroke(int fillType) {#addStroke-int-}
```
public final StrokeEffect addStroke(int fillType)
```


Προσθέτει το εφέ γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillType | int | Ο τύπος γεμίσματος για τη γραμμή. |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) - Created [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) object.
### calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle) {#calculateBoundsWithEffects-internalized-com.aspose.psd.Rectangle-int-}
```
public final Rectangle calculateBoundsWithEffects_internalized(Rectangle layerBounds, int globalAngle)
```


Υπολογίζει τα όρια της στρώσης συμπεριλαμβανομένων των οπτικών εφέ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα αρχικά όρια της στρώσης. |
| globalAngle | int | Η παγκόσμια γωνία φωτός που χρησιμοποιείται για ορισμένα εφέ. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The calculated bounds including the visual effects.
### create_internalized(LayerStyleFX layerStyle, PattResource pattResource) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static BlendingOptions create_internalized(LayerStyleFX layerStyle, PattResource pattResource)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAreEffectsEnabled() {#getAreEffectsEnabled--}
```
public final boolean getAreEffectsEnabled()
```


Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσης.

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


Λαμβάνει τα εφέ.

Τιμή: Τα εφέ.

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


Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setEffects(ILayerEffect[] value) {#setEffects-com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect---}
```
public void setEffects(ILayerEffect[] value)
```


Λαμβάνει τα εφέ.

Τιμή: Τα εφέ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILayerEffect\[\]](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect) |  |

### setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings) {#setNewPatternToFillSettings-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setNewPatternToFillSettings_internalized(PatternFillSettings patternSettings)
```


Δημιουργεί τα νέα δεδομένα μοτίβου και τα ορίζει στο αντικείμενο [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| patternSettings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Οι ρυθμίσεις γεμίσματος μοτίβου. |

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


Ενημερώνει τα εφέ εάν είναι πιο πρόσφατα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layerStyle | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX | Το στυλ στρώσης με εφέ. |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | Ο πόρος patt. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

