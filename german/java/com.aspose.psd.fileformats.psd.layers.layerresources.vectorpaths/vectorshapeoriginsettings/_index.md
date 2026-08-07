---
title: "VectorShapeOriginSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Einstellungen für den Ursprung von Vektorformen."
type: docs
weight: 24
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

Einstellungen für den Ursprung von Vektorformen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | Initialisiert eine neue Instanz der Klasse [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | Der Deskriptorschlüssel zum Speichern des Formursprungsindex. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | Der Deskriptorschlüssel für die Ursprungsrechteck-Radien |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | Der Deskriptorschlüssel für die Ursprungsauflösung |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | Der Deskriptorschlüssel für den Ursprungs-Formbegrenzungsrahmen |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | Der Schlüssel des Ursprungstyp-Deskriptors |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | Der Deskriptorschlüssel zum Speichern des ungültig gemachten Formwerts. |
| [KnownKeys_internalized](#KnownKeys-internalized) | Die bekannten Eigenschaftsschlüssel |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | Liefert die eindeutige Kennung. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | Liefert oder setzt die Eckpunkte des Ursprungskastens. |
| [getOriginIndex()](#getOriginIndex--) | Liefert oder setzt den Index der Ursprungsgestalt. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | Liefert oder setzt das Rechteck der Ursprungsradianten. |
| [getOriginResolution()](#getOriginResolution--) | Liefert oder setzt die Auflösung des Ursprungs. |
| [getOriginShapeBox()](#getOriginShapeBox--) | Liefert oder setzt die Begrenzungsbox der Ursprungsgestalt. |
| [getOriginType()](#getOriginType--) | Liefert oder setzt den Typ des Ursprungs. |
| [getTransform()](#getTransform--) | Liefert oder setzt die Transformationsmatrix. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | Liefert oder setzt einen Wert, der angibt, ob diese Instanz unbekannte Eigenschaften hat. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Liefert oder setzt einen Wert, der angibt, ob diese Instanz geändert wurde. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprungskasten-Eckpunkte hat. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprung-Index hat. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | Liefert einen Wert, der angibt, ob das Rechteck der Ursprungsradianten vorhanden ist. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprung-Auflösung hat. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Rechteck-Eigenschaft hat. |
| [isOriginTypePresent()](#isOriginTypePresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprungstyp hat. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | Bestimmt, ob die Eigenschaft mit dem angegebenen Schlüssel vorhanden ist. |
| [isShapeInvalidated()](#isShapeInvalidated--) | Liefert oder setzt einen Wert, der angibt, ob die Form ungültig gemacht wurde. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für ungültig gemachte Form gesetzt hat. |
| [isTransformPresent()](#isTransformPresent--) | Liefert einen Wert, der angibt, ob diese Instanz die Transformations-Eigenschaft hat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | Liefert oder setzt einen Wert, der angibt, ob diese Instanz geändert wurde. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | Liefert oder setzt die Eckpunkte des Ursprungskastens. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | Liefert oder setzt den Index der Ursprungsgestalt. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | Liefert oder setzt das Rechteck der Ursprungsradianten. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | Liefert oder setzt die Auflösung des Ursprungs. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | Liefert oder setzt die Begrenzungsbox der Ursprungsgestalt. |
| [setOriginType(int value)](#setOriginType-int-) | Liefert oder setzt den Typ des Ursprungs. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | Liefert oder setzt einen Wert, der angibt, ob die Form ungültig gemacht wurde. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | Liefert oder setzt die Transformationsmatrix. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | Liefert oder setzt einen Wert, der angibt, ob diese Instanz unbekannte Eigenschaften hat. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


Initialisiert eine neue Instanz der Klasse [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isShapeInvalidated | boolean | Der Wert, der angibt, ob die Form ungültig ist. |
| originIndex | int | Der Ursprung-Index der Form. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


Der Deskriptorschlüssel zum Speichern des Formursprungsindex.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


Der Deskriptorschlüssel für die Ursprungsrechteck-Radien

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


Der Deskriptorschlüssel für die Ursprungsauflösung

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


Der Deskriptorschlüssel für den Ursprungs-Formbegrenzungsrahmen

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


Der Schlüssel des Ursprungstyp-Deskriptors

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


Der Deskriptorschlüssel zum Speichern des ungültig gemachten Formwerts.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


Die bekannten Eigenschaftsschlüssel

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liefert die eindeutige Kennung.

Wert: Der eindeutige Bezeichner.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


Liefert oder setzt die Eckpunkte des Ursprungskastens.

Wert: Die Ecken des Ursprungskastens.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


Liefert oder setzt den Index der Ursprungsgestalt.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


Liefert oder setzt das Rechteck der Ursprungsradianten.

Wert: Das Rechteck der Ursprungsradianten.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


Liefert oder setzt die Auflösung des Ursprungs.

Wert: Die Auflösung des Ursprungs.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


Liefert oder setzt die Begrenzungsbox der Ursprungsgestalt.

Wert: Die Ursprung-Form-Box.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


Liefert oder setzt den Typ des Ursprungs.

Wert: Der Typ des Ursprungs.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


Liefert oder setzt die Transformationsmatrix.

Wert: Die Transformationsmatrix.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


Liefert oder setzt einen Wert, der angibt, ob diese Instanz unbekannte Eigenschaften hat.

Wert:  true  wenn diese Instanz unbekannte Eigenschaften hat; andernfalls  false .

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


Liefert oder setzt einen Wert, der angibt, ob diese Instanz geändert wurde.

Wert:  true  wenn diese Instanz geändert wurde; andernfalls  false .

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprungskasten-Eckpunkte hat.

Wert:  true  wenn diese Instanz die Eigenschaft Ursprungskasten-Ecken hat; andernfalls  false .

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprung-Index hat.

Wert:  true  wenn diese Instanz die Eigenschaft Ursprung-Index hat; andernfalls  false .

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


Liefert einen Wert, der angibt, ob das Rechteck der Ursprungsradianten vorhanden ist.

Wert:  true  wenn diese Instanz die Eigenschaft Ursprung-Radianten-Rechteck hat; andernfalls  false .

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprung-Auflösung hat.

Wert:  true  wenn diese Instanz die Eigenschaft Ursprung-Auflösung hat; andernfalls  false .

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Rechteck-Eigenschaft hat.

Wert:  true  wenn diese Instanz die Eigenschaft Ursprung-Form-Rechteck hat; andernfalls  false .

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für Ursprungstyp hat.

Wert:  true  wenn diese Instanz die Eigenschaft Ursprungstyp hat; andernfalls  false .

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


Bestimmt, ob die Eigenschaft mit dem angegebenen Schlüssel vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Der Eigenschaftsschlüssel. |

**Returns:**
bool -  true  wenn die Eigenschaft mit dem angegebenen Schlüssel vorhanden ist; andernfalls  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


Liefert oder setzt einen Wert, der angibt, ob die Form ungültig gemacht wurde.

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Eigenschaft für ungültig gemachte Form gesetzt hat.

Wert:  true  wenn diese Instanz ein ungültiges Form-Eigenschafts-Set hat; andernfalls  false .

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


Liefert einen Wert, der angibt, ob diese Instanz die Transformations-Eigenschaft hat.

Wert:  true  wenn diese Instanz die Transformations-Eigenschaft hat; andernfalls  false .

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


Liefert oder setzt einen Wert, der angibt, ob diese Instanz geändert wurde.

Wert:  true  wenn diese Instanz geändert wurde; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


Liefert oder setzt die Eckpunkte des Ursprungskastens.

Wert: Die Ecken des Ursprungskastens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


Liefert oder setzt den Index der Ursprungsgestalt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


Liefert oder setzt das Rechteck der Ursprungsradianten.

Wert: Das Rechteck der Ursprungsradianten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


Liefert oder setzt die Auflösung des Ursprungs.

Wert: Die Auflösung des Ursprungs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


Liefert oder setzt die Begrenzungsbox der Ursprungsgestalt.

Wert: Die Ursprung-Form-Box.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


Liefert oder setzt den Typ des Ursprungs.

Wert: Der Typ des Ursprungs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob die Form ungültig gemacht wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


Liefert oder setzt die Transformationsmatrix.

Wert: Die Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob diese Instanz unbekannte Eigenschaften hat.

Wert:  true  wenn diese Instanz unbekannte Eigenschaften hat; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

