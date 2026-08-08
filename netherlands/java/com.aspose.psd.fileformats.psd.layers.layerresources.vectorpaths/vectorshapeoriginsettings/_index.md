---
title: "VectorShapeOriginSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Instellingen voor oorsprong van vectorvorm."
type: docs
weight: 24
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

Instellingen voor oorsprong van vectorvorm.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | Initialiseert een nieuw exemplaar van de klasse [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | De descriptor‑sleutel om de vorm‑origin‑index op te slaan. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | De descriptor‑sleutel voor de straal van de oorsprong‑rechthoek. |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | De descriptor‑sleutel voor de resolutie van de oorsprong. |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | De descriptor‑sleutel voor de begrenzende box van de oorsprongsvorm. |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | De descriptor‑sleutel voor het type van de oorsprong. |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | De descriptor‑sleutel om de ongeldig gemaakte waarde van de vorm op te slaan. |
| [KnownKeys_internalized](#KnownKeys-internalized) | De bekende eigenschapssleutels. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | Haalt de unieke identifier op. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | Haalt de hoeken van de oorsprong‑box op of stelt deze in. |
| [getOriginIndex()](#getOriginIndex--) | Haalt de index van de oorsprongsvorm op of stelt deze in. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | Haalt de straal‑rechthoek van de oorsprong op of stelt deze in. |
| [getOriginResolution()](#getOriginResolution--) | Haalt de resolutie van de oorsprong op of stelt deze in. |
| [getOriginShapeBox()](#getOriginShapeBox--) | Haalt de begrenzende box van de oorsprongsvorm op of stelt deze in. |
| [getOriginType()](#getOriginType--) | Haalt het type van de oorsprong op of stelt dit in. |
| [getTransform()](#getTransform--) | Haalt op of stelt de transformatie-matrix in. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | Haalt op of stelt een waarde in die aangeeft of deze instantie onbekende eigenschappen heeft. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Haalt op of stelt een waarde in die aangeeft of deze instantie gewijzigd is. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | Haalt een waarde op die aangeeft of deze instantie de eigenschap origin box corners heeft. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | Haalt een waarde op die aangeeft of deze instantie de eigenschap origin index heeft. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | Haalt een waarde op die aangeeft of deze instantie een origin radii rectangle bevat. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | Haalt een waarde op die aangeeft of deze instantie de eigenschap origin resolution heeft. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | Haalt een waarde op die aangeeft of deze instantie de eigenschap rectangle heeft. |
| [isOriginTypePresent()](#isOriginTypePresent--) | Haalt een waarde op die aangeeft of deze instantie de eigenschap origin type heeft. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | Bepaalt of de eigenschap met de opgegeven sleutel aanwezig is. |
| [isShapeInvalidated()](#isShapeInvalidated--) | Haalt op of stelt een waarde in die aangeeft of de vorm ongeldig is. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | Haalt een waarde op die aangeeft of deze instantie een shape invalidated-eigenschap heeft. |
| [isTransformPresent()](#isTransformPresent--) | Haalt een waarde op die aangeeft of deze instantie de eigenschap transform heeft. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze instantie gewijzigd is. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | Haalt de hoeken van de oorsprong‑box op of stelt deze in. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | Haalt de index van de oorsprongsvorm op of stelt deze in. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | Haalt de straal‑rechthoek van de oorsprong op of stelt deze in. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | Haalt de resolutie van de oorsprong op of stelt deze in. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | Haalt de begrenzende box van de oorsprongsvorm op of stelt deze in. |
| [setOriginType(int value)](#setOriginType-int-) | Haalt het type van de oorsprong op of stelt dit in. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | Haalt op of stelt een waarde in die aangeeft of de vorm ongeldig is. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | Haalt op of stelt de transformatie-matrix in. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze instantie onbekende eigenschappen heeft. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


Initialiseert een nieuw exemplaar van de klasse [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isShapeInvalidated | boolean | De waarde van shape is invalidated. |
| originIndex | int | De shape origin index. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


De descriptor‑sleutel om de vorm‑origin‑index op te slaan.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


De descriptor‑sleutel voor de straal van de oorsprong‑rechthoek.

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


De descriptor‑sleutel voor de resolutie van de oorsprong.

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


De descriptor‑sleutel voor de begrenzende box van de oorsprongsvorm.

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


De descriptor‑sleutel voor het type van de oorsprong.

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


De descriptor‑sleutel om de ongeldig gemaakte waarde van de vorm op te slaan.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


De bekende eigenschapssleutels.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getId_internalized() {#getId-internalized--}
```
public final System.Guid getId_internalized()
```


Haalt de unieke identifier op.

Waarde: De unieke identifier.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


Haalt de hoeken van de oorsprong‑box op of stelt deze in.

Waarde: De origin box corners.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


Haalt de index van de oorsprongsvorm op of stelt deze in.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


Haalt de straal‑rechthoek van de oorsprong op of stelt deze in.

Waarde: De origin radii rectangle.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


Haalt de resolutie van de oorsprong op of stelt deze in.

Waarde: De origin resolution.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


Haalt de begrenzende box van de oorsprongsvorm op of stelt deze in.

Waarde: De origin shape box.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


Haalt het type van de oorsprong op of stelt dit in.

Waarde: Het type van de origin.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


Haalt op of stelt de transformatie-matrix in.

Waarde: De transformatie-matrix.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


Haalt op of stelt een waarde in die aangeeft of deze instantie onbekende eigenschappen heeft.

Waarde:  true  als dit exemplaar onbekende eigenschappen heeft; anders,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


Haalt op of stelt een waarde in die aangeeft of deze instantie gewijzigd is.

Waarde:  true  als dit exemplaar is gewijzigd; anders,  false .

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


Haalt een waarde op die aangeeft of deze instantie de eigenschap origin box corners heeft.

Waarde:  true  als dit exemplaar de eigenschap origin box corners heeft; anders,  false .

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


Haalt een waarde op die aangeeft of deze instantie de eigenschap origin index heeft.

Waarde:  true  als dit exemplaar de eigenschap origin index heeft; anders,  false .

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


Haalt een waarde op die aangeeft of deze instantie een origin radii rectangle bevat.

Waarde:  true  als dit exemplaar de eigenschap origin radii rectangle heeft; anders,  false .

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


Haalt een waarde op die aangeeft of deze instantie de eigenschap origin resolution heeft.

Waarde:  true  als dit exemplaar de eigenschap origin resolution heeft; anders,  false .

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


Haalt een waarde op die aangeeft of deze instantie de eigenschap rectangle heeft.

Waarde:  true  als dit exemplaar de eigenschap origin shape rectangle heeft; anders,  false .

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


Haalt een waarde op die aangeeft of deze instantie de eigenschap origin type heeft.

Waarde:  true  als dit exemplaar de eigenschap origin type heeft; anders,  false .

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


Bepaalt of de eigenschap met de opgegeven sleutel aanwezig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De eigenschapssleutel. |

**Returns:**
boolean -  true  als de eigenschap met de opgegeven sleutel aanwezig is; anders,  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


Haalt op of stelt een waarde in die aangeeft of de vorm ongeldig is.

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


Haalt een waarde op die aangeeft of deze instantie een shape invalidated-eigenschap heeft.

Waarde:  true  als dit exemplaar een eigenschap set shape invalidated heeft; anders,  false .

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


Haalt een waarde op die aangeeft of deze instantie de eigenschap transform heeft.

Waarde:  true  als dit exemplaar de eigenschap transform heeft; anders,  false .

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




### setChanged_internalized(boolean value) {#setChanged-internalized-boolean-}
```
public final void setChanged_internalized(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze instantie gewijzigd is.

Waarde:  true  als dit exemplaar is gewijzigd; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


Haalt de hoeken van de oorsprong‑box op of stelt deze in.

Waarde: De origin box corners.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


Haalt de index van de oorsprongsvorm op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


Haalt de straal‑rechthoek van de oorsprong op of stelt deze in.

Waarde: De origin radii rectangle.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


Haalt de resolutie van de oorsprong op of stelt deze in.

Waarde: De origin resolution.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


Haalt de begrenzende box van de oorsprongsvorm op of stelt deze in.

Waarde: De origin shape box.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


Haalt het type van de oorsprong op of stelt dit in.

Waarde: Het type van de origin.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de vorm ongeldig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


Haalt op of stelt de transformatie-matrix in.

Waarde: De transformatie-matrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze instantie onbekende eigenschappen heeft.

Waarde:  true  als dit exemplaar onbekende eigenschappen heeft; anders,  false .

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

