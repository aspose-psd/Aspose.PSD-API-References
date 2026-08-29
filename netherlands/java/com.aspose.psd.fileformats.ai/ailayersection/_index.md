---
title: "AiLayerSection"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De Ai-formaatlagensectie"
type: docs
weight: 15
url: /nl/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

De Ai-formaatlagensectie
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Voegt de rasterafbeelding toe. |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Haalt op of stelt de blauwe kleurcomponent in. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Haalt op of stelt de index van de kleur in. |
| [getColorNumber()](#getColorNumber--) | Haalt op of stelt het kleurnummer in. |
| [getData()](#getData--) | Haalt de tekenreeksgegevens op. |
| [getDimValue()](#getDimValue--) | Haalt op of stelt de dim-waarde in als percentage. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getGreen()](#getGreen--) | Haalt op of stelt de groene kleurcomponent in. |
| [getName()](#getName--) | Haalt op of stelt de laagnaam in. |
| [getRasterImages()](#getRasterImages--) | Haalt de rasterafbeeldingen op. |
| [getRed()](#getRed--) | Haalt op of stelt de rode kleurcomponent in. |
| [getStream_internalized()](#getStream-internalized--) | Haalt de interne stream op. |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Haalt op of stelt een waarde in die aangeeft of deze instantie multilayer-maskers heeft. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Haalt op of stelt een waarde in die aangeeft of deze laag gedimd is. |
| [isLocked()](#isLocked--) | Haalt op of stelt een waarde in die aangeeft of deze laag vergrendeld is. |
| [isPreview()](#isPreview--) | Haalt op of stelt een waarde in die aangeeft of deze laag een preview is. |
| [isPrinted()](#isPrinted--) | Haalt op of stelt een waarde in die aangeeft of deze laag afgedrukt is. |
| [isShown()](#isShown--) | Haalt op of stelt een waarde in die aangeeft of deze laag weergegeven wordt. |
| [isTemplate()](#isTemplate--) | Haalt op of stelt een waarde in die aangeeft of deze laag een sjabloonlaag is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Haalt op of stelt de blauwe kleurcomponent in. |
| [setColorIndex(int value)](#setColorIndex-int-) | Haalt op of stelt de index van de kleur in. |
| [setColorNumber(int value)](#setColorNumber-int-) | Haalt op of stelt het kleurnummer in. |
| [setDimValue(int value)](#setDimValue-int-) | Haalt op of stelt de dim-waarde in als percentage. |
| [setGreen(int value)](#setGreen-int-) | Haalt op of stelt de groene kleurcomponent in. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze laag gedimd is. |
| [setLocked(boolean value)](#setLocked-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze laag vergrendeld is. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze instantie multilayer-maskers heeft. |
| [setName(String value)](#setName-java.lang.String-) | Haalt op of stelt de laagnaam in. |
| [setPreview(boolean value)](#setPreview-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze laag een preview is. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze laag afgedrukt is. |
| [setRed(int value)](#setRed-int-) | Haalt op of stelt de rode kleurcomponent in. |
| [setShown(boolean value)](#setShown-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze laag weergegeven wordt. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze laag een sjabloonlaag is. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Voegt de rasterafbeelding toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | De rasterafbeelding. |

### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |
| eigenschappen | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Haalt op of stelt de blauwe kleurcomponent in.

Waarde: De blauwe kleurcomponent.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Haalt op of stelt de index van de kleur in. Dit argument kan waarden tussen \\u20131 en 26 aannemen. Elk geheel getal vertegenwoordigt een kleur die aan de laag kan worden toegewezen voor gebruikersidentificatie.

Waarde: De index van de kleur.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Haalt op of stelt het kleurnummer in. -1 is de aangepaste kleurwaarde van de eigenschappen Rood, Groen, Blauw. Specificeert de kleuroptie van de laag\\u2019s.

Waarde: Het kleurnummer.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Haalt de tekenreeksgegevens op.

**Returns:**
java.lang.String - De tekenreeksgegevens van de sectie
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Haalt op of stelt de dimwaarde in als percentage. Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen in de laag tot het opgegeven percentage.

Waarde: De dimwaarde als percentage.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Haalt op of stelt de groene kleurcomponent in.

Waarde: De groene kleurcomponent.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Haalt op of stelt de laagnaam in. Specificeert de naam van het item zoals deze verschijnt in het Lagenpaneel.

Waarde: De laagnaam.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Haalt de rasterafbeeldingen op.

Waarde: De rasterafbeeldingen.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Haalt op of stelt de rode kleurcomponent in.

Waarde: De rode kleurcomponent.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Haalt de interne stream op.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Haalt op of stelt een waarde in die aangeeft of deze instantie multilayer-maskers heeft.

Waarde:  true  als deze instantie multilayer-maskers heeft; anders,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Haalt op of stelt een waarde in die aangeeft of deze laag gedimd is. Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen in de laag.

Waarde:  true  als deze laag gedimd is; anders,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Haalt op of stelt een waarde in die aangeeft of deze laag vergrendeld is. Voorkomt wijzigingen aan het item.

Waarde:  true  als deze laag vergrendeld is; anders,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Haalt op of stelt een waarde in die aangeeft of deze laag een voorbeeld is. Toont de in de laag aanwezige artwork in kleur in plaats van als contouren.

Waarde:  true  als deze laag een voorbeeld is; anders,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Haalt op of stelt een waarde in die aangeeft of deze laag afgedrukt wordt. Maakt de in de laag aanwezige artwork afdrukbaar als true.

Waarde:  true  als deze laag afgedrukt wordt; anders,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Haalt op of stelt een waarde in die aangeeft of deze laag wordt weergegeven. Toont alle in de laag aanwezige artwork op het tekenbord als true.

Waarde:  true  als deze laag wordt weergegeven; anders,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Haalt op of stelt een waarde in die aangeeft of deze laag een sjabloonlaag is.

Waarde:  true  als deze laag een sjabloon is; anders,  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Haalt op of stelt de blauwe kleurcomponent in.

Waarde: De blauwe kleurcomponent.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Haalt op of stelt de index van de kleur in. Dit argument kan waarden tussen \\u20131 en 26 aannemen. Elk geheel getal vertegenwoordigt een kleur die aan de laag kan worden toegewezen voor gebruikersidentificatie.

Waarde: De index van de kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Haalt op of stelt het kleurnummer in. -1 is de aangepaste kleurwaarde van de eigenschappen Rood, Groen, Blauw. Specificeert de kleuroptie van de laag\\u2019s.

Waarde: Het kleurnummer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Haalt op of stelt de dimwaarde in als percentage. Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen in de laag tot het opgegeven percentage.

Waarde: De dimwaarde als percentage.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Haalt op of stelt de groene kleurcomponent in.

Waarde: De groene kleurcomponent.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze laag gedimd is. Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen in de laag.

Waarde:  true  als deze laag gedimd is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze laag vergrendeld is. Voorkomt wijzigingen aan het item.

Waarde:  true  als deze laag vergrendeld is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze instantie multilayer-maskers heeft.

Waarde:  true  als deze instantie multilayer-maskers heeft; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt op of stelt de laagnaam in. Specificeert de naam van het item zoals deze verschijnt in het Lagenpaneel.

Waarde: De laagnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze laag een voorbeeld is. Toont de in de laag aanwezige artwork in kleur in plaats van als contouren.

Waarde:  true  als deze laag een voorbeeld is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze laag afgedrukt wordt. Maakt de in de laag aanwezige artwork afdrukbaar als true.

Waarde:  true  als deze laag afgedrukt wordt; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Haalt op of stelt de rode kleurcomponent in.

Waarde: De rode kleurcomponent.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze laag wordt weergegeven. Toont alle in de laag aanwezige artwork op het tekenbord als true.

Waarde:  true  als deze laag wordt weergegeven; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze laag een sjabloonlaag is.

Waarde:  true  als deze laag een sjabloon is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

