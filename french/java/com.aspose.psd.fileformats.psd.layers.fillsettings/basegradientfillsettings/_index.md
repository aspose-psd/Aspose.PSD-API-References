---
title: "BaseGradientFillSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe de définition de gradient de base."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Classe de définition de dégradé de base. Elle contient des propriétés communes aux deux types de dégradé (Solid et Noise).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Initialise une nouvelle instance de la classe [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings). |
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
| [getDither()](#getDither--) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither. |
| [getFillType()](#getFillType--) | Le type de remplissage. |
| [getGradientMode()](#getGradientMode--) | Obtient le mode de ce dégradé. |
| [getGradientName()](#getGradientName--) | Obtient ou définit le nom du dégradé. |
| [getGradientType()](#getGradientType--) | Obtient ou définit le type du dégradé. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtient ou définit le décalage horizontal en pourcentage. |
| [getReverse()](#getReverse--) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtient ou définit le décalage vertical en pourcentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Déclenche la modification de la valeur. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtient ou définit l’angle. |
| [setDither(boolean value)](#setDither-boolean-) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Obtient le mode de ce dégradé. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Obtient ou définit le nom du dégradé. |
| [setGradientType(int value)](#setGradientType-int-) | Obtient ou définit le type du dégradé. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtient ou définit le décalage horizontal en pourcentage. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé. |
| [setScale(int value)](#setScale-int-) | Obtient ou définit l'échelle. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtient ou définit le décalage vertical en pourcentage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Initialise une nouvelle instance de la classe [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings).

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
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither.

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
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Obtient le mode de ce dégradé. Détermine le 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Obtient ou définit le nom du dégradé.

Valeur: le nom du dégradé.

**Returns:**
java.lang.String
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Returns:**
booléen
### getScale() {#getScale--}
```
public final int getScale()
```


Obtient ou définit l'échelle.

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

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither.

Valeur :  true  si tramage ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Obtient le mode de ce dégradé. Détermine le 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Obtient ou définit le nom du dégradé.

Valeur: le nom du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Obtient ou définit l'échelle.

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

