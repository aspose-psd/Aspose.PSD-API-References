---
title: "VectorShapeOriginSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres d'origine de forme vectorielle."
type: docs
weight: 24
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

Paramètres d'origine de forme vectorielle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | Initialise une nouvelle instance de la classe [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | La clé de descripteur pour enregistrer l'index d'origine de la forme. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | La clé du descripteur des rayons du rectangle d'origine |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | La clé du descripteur de résolution d'origine |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | La clé du descripteur de la boîte englobante d'origine de la forme |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | La clé du descripteur de type d'origine |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | La clé du descripteur pour enregistrer la valeur d'invalidation de la forme. |
| [KnownKeys_internalized](#KnownKeys-internalized) | Les clés de propriétés connues |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | Obtient l'identifiant unique. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | Obtient ou définit les coins de la boîte d'origine. |
| [getOriginIndex()](#getOriginIndex--) | Obtient ou définit l'index de forme d'origine. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | Obtient ou définit le rectangle des rayons d'origine. |
| [getOriginResolution()](#getOriginResolution--) | Obtient ou définit la résolution d'origine. |
| [getOriginShapeBox()](#getOriginShapeBox--) | Obtient ou définit la boîte englobante de la forme d'origine. |
| [getOriginType()](#getOriginType--) | Obtient ou définit le type de l'origine. |
| [getTransform()](#getTransform--) | Obtient ou définit la matrice de transformation. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | Obtient ou définit une valeur indiquant si cette instance possède des propriétés inconnues. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Obtient ou définit une valeur indiquant si cette instance a été modifiée. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | Obtient une valeur indiquant si cette instance possède la propriété des coins de la boîte d'origine. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | Obtient une valeur indiquant si cette instance possède la propriété d'index d'origine. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | Obtient une valeur indiquant si le rectangle des rayons d'origine est présent dans cette instance. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | Obtient une valeur indiquant si cette instance possède la propriété de résolution d'origine. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | Obtient une valeur indiquant si cette instance possède la propriété du rectangle. |
| [isOriginTypePresent()](#isOriginTypePresent--) | Obtient une valeur indiquant si cette instance possède la propriété de type d'origine. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | Détermine si la propriété avec la clé spécifiée est présente. |
| [isShapeInvalidated()](#isShapeInvalidated--) | Obtient ou définit une valeur indiquant si la forme est invalidée. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | Obtient une valeur indiquant si cette instance possède une propriété de forme invalidée définie. |
| [isTransformPresent()](#isTransformPresent--) | Obtient une valeur indiquant si cette instance possède la propriété de transformation. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | Obtient ou définit une valeur indiquant si cette instance a été modifiée. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | Obtient ou définit les coins de la boîte d'origine. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | Obtient ou définit l'index de forme d'origine. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | Obtient ou définit le rectangle des rayons d'origine. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | Obtient ou définit la résolution d'origine. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | Obtient ou définit la boîte englobante de la forme d'origine. |
| [setOriginType(int value)](#setOriginType-int-) | Obtient ou définit le type de l'origine. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | Obtient ou définit une valeur indiquant si la forme est invalidée. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | Obtient ou définit la matrice de transformation. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | Obtient ou définit une valeur indiquant si cette instance possède des propriétés inconnues. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


Initialise une nouvelle instance de la classe [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isShapeInvalidated | booléen | La valeur de la forme invalidée. |
| originIndex | int | L'index d'origine de la forme. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


La clé de descripteur pour enregistrer l'index d'origine de la forme.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


La clé du descripteur des rayons du rectangle d'origine

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


La clé du descripteur de résolution d'origine

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


La clé du descripteur de la boîte englobante d'origine de la forme

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


La clé du descripteur de type d'origine

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


La clé du descripteur pour enregistrer la valeur d'invalidation de la forme.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


Les clés de propriétés connues

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient l'identifiant unique.

Valeur : l'identifiant unique.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


Obtient ou définit les coins de la boîte d'origine.

Valeur : les coins de la boîte d'origine.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


Obtient ou définit l'index de forme d'origine.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


Obtient ou définit le rectangle des rayons d'origine.

Valeur : le rectangle des rayons d'origine.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


Obtient ou définit la résolution d'origine.

Valeur : la résolution d'origine.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


Obtient ou définit la boîte englobante de la forme d'origine.

Valeur : la boîte de forme d'origine.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


Obtient ou définit le type de l'origine.

Valeur : le type de l'origine.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


Obtient ou définit la matrice de transformation.

Valeur : la matrice de transformation.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


Obtient ou définit une valeur indiquant si cette instance possède des propriétés inconnues.

Valeur :  true  si cette instance possède des propriétés inconnues ; sinon,  false .

**Returns:**
booléen
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


Obtient ou définit une valeur indiquant si cette instance a été modifiée.

Valeur :  true  si cette instance a été modifiée ; sinon,  false .

**Returns:**
booléen
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


Obtient une valeur indiquant si cette instance possède la propriété des coins de la boîte d'origine.

Valeur :  true  si cette instance possède la propriété des coins de la boîte d'origine ; sinon,  false .

**Returns:**
booléen
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


Obtient une valeur indiquant si cette instance possède la propriété d'index d'origine.

Valeur :  true  si cette instance possède la propriété d'index d'origine ; sinon,  false .

**Returns:**
booléen
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


Obtient une valeur indiquant si le rectangle des rayons d'origine est présent dans cette instance.

Valeur :  true  si cette instance possède la propriété du rectangle des rayons d'origine ; sinon,  false .

**Returns:**
booléen
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


Obtient une valeur indiquant si cette instance possède la propriété de résolution d'origine.

Valeur :  true  si cette instance possède la propriété de résolution d'origine ; sinon,  false .

**Returns:**
booléen
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


Obtient une valeur indiquant si cette instance possède la propriété du rectangle.

Valeur :  true  si cette instance possède la propriété du rectangle de forme d'origine ; sinon,  false .

**Returns:**
booléen
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


Obtient une valeur indiquant si cette instance possède la propriété de type d'origine.

Valeur :  true  si cette instance possède la propriété du type d'origine ; sinon,  false .

**Returns:**
booléen
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


Détermine si la propriété avec la clé spécifiée est présente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé de la propriété. |

**Returns:**
booléen -  true  si la propriété avec la clé spécifiée est présente ; sinon,  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


Obtient ou définit une valeur indiquant si la forme est invalidée.

**Returns:**
booléen
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


Obtient une valeur indiquant si cette instance possède une propriété de forme invalidée définie.

Valeur :  true  si cette instance possède un ensemble de propriétés de forme invalidée ; sinon,  false .

**Returns:**
booléen
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


Obtient une valeur indiquant si cette instance possède la propriété de transformation.

Valeur :  true  si cette instance possède la propriété de transformation ; sinon,  false .

**Returns:**
booléen
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


Obtient ou définit une valeur indiquant si cette instance a été modifiée.

Valeur :  true  si cette instance a été modifiée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


Obtient ou définit les coins de la boîte d'origine.

Valeur : les coins de la boîte d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


Obtient ou définit l'index de forme d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


Obtient ou définit le rectangle des rayons d'origine.

Valeur : le rectangle des rayons d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


Obtient ou définit la résolution d'origine.

Valeur : la résolution d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


Obtient ou définit la boîte englobante de la forme d'origine.

Valeur : la boîte de forme d'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


Obtient ou définit le type de l'origine.

Valeur : le type de l'origine.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


Obtient ou définit une valeur indiquant si la forme est invalidée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


Obtient ou définit la matrice de transformation.

Valeur : la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance possède des propriétés inconnues.

Valeur :  true  si cette instance possède des propriétés inconnues ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

