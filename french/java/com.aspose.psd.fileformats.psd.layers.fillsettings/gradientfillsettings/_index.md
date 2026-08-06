---
title: "GradientFillSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres de l'effet de remplissage du gradient."
type: docs
weight: 14
url: /fr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Paramètres de l'effet de remplissage du gradient.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Initialise une nouvelle instance de la classe [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
## Champs

| Champ | Description |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [getAngle()](#getAngle--) | Obtient ou définit l’angle. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Obtient ou définit les limites du conteneur de calque afin de calculer correctement la position du dégradé. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Calcule et renvoie l'échelle de dégradé **denormalized** (Échelle UI) correspondant à la valeur actuelle de Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est en tramage. |
| [getFillType()](#getFillType--) | Le type de remplissage. |
| [getGradient()](#getGradient--) | Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Obtient ou définit le type du dégradé. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtient ou définit le décalage horizontal en pourcentage. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Obtient ou définit la méthode d'interpolation du dégradé. |
| [getReverse()](#getReverse--) | Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est inversé. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle de dégradé **normalized** (en pourcentage) |
| [getVerticalOffset()](#getVerticalOffset--) | Obtient ou définit le décalage vertical en pourcentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Déclenche la modification de la valeur. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtient ou définit l’angle. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Obtient ou définit les limites du conteneur de calque afin de calculer correctement la position du dégradé. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Convertit la valeur d'échelle (UI) dénormalisée spécifiée en son équivalent **normalized** et l'affecte à Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est en tramage. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Obtient ou définit le type du dégradé. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtient ou définit le décalage horizontal en pourcentage. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Obtient ou définit la méthode d'interpolation du dégradé. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est inversé. |
| [setScale(int value)](#setScale-int-) | Obtient ou définit l'échelle de dégradé **normalized** (en pourcentage) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtient ou définit le décalage vertical en pourcentage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Initialise une nouvelle instance de la classe [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Obtient ou définit une valeur indiquant si [align with layer].

Valeur :  true  si [align with layer] ; sinon,  false .

**Returns:**
booléen
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtient ou définit l’angle.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Obtient ou définit les limites du conteneur de calque afin de calculer correctement la position du dégradé.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Calcule et renvoie l'échelle de dégradé **denormalized** (Échelle UI) correspondant à la valeur actuelle de Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Les limites du dégradé. |

**Returns:**
int - L'échelle dénormalisée (UI) en pourcentage telle qu'affichée dans Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est en tramage.

Valeur :  true  si tramage ; sinon,  false .

**Returns:**
booléen
### getFillType() {#getFillType--}
```
public int getFillType()
```


Le type de remplissage.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Obtient ou définit le type du dégradé.

Valeur : Le type du dégradé.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Obtient ou définit le décalage horizontal en pourcentage.

Valeur: Le décalage horizontal.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Obtient ou définit la méthode d'interpolation du dégradé.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Returns:**
booléen
### getScale() {#getScale--}
```
public final int getScale()
```


Obtient ou définit l'échelle de dégradé **normalized** (en pourcentage)

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Obtient ou définit le décalage vertical en pourcentage.

Valeur: Le décalage vertical.

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


Déclenche la modification de la valeur.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Obtient ou définit une valeur indiquant si [align with layer].

Valeur :  true  si [align with layer] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtient ou définit l’angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Obtient ou définit les limites du conteneur de calque afin de calculer correctement la position du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Convertit la valeur d'échelle dénormalisée (UI) spécifiée en son équivalent **normalisé** et l'affecte à Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). La conversion applique l'Angle actuel du gradient ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) et la zone de remplissage fournie pour calculer le facteur de normalisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'échelle dénormalisée, échelle UI en pourcentage telle qu'affichée par Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | Les limites du dégradé. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est en tramage.

Valeur :  true  si tramage ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Obtient ou définit le type du dégradé.

Valeur : Le type du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Obtient ou définit le décalage horizontal en pourcentage.

Valeur: Le décalage horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Obtient ou définit la méthode d'interpolation du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Obtient ou définit une valeur indiquant si ce [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Obtient ou définit l'échelle de dégradé **normalized** (en pourcentage)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Obtient ou définit le décalage vertical en pourcentage.

Valeur: Le décalage vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

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

