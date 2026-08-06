---
title: "IGradientFillSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Interface de base pour les paramètres de remplissage de dégradé."
type: docs
weight: 23
url: /fr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Interface de base pour les paramètres de remplissage de dégradé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [getAngle()](#getAngle--) | Obtient ou définit l’angle. |
| [getDither()](#getDither--) | Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est dithérisé. |
| [getGradient()](#getGradient--) | Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Obtient ou définit le type du dégradé. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtient ou définit le décalage horizontal. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Obtient ou définit la méthode d'interpolation du dégradé. |
| [getReverse()](#getReverse--) | Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est inversé. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle du gradient **normalisée** (en pourcentage). |
| [getVerticalOffset()](#getVerticalOffset--) | Obtient ou définit le décalage vertical. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtient ou définit l’angle. |
| [setDither(boolean value)](#setDither-boolean-) | Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est dithérisé. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Obtient ou définit le type du dégradé. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtient ou définit le décalage horizontal. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Obtient ou définit la méthode d'interpolation du dégradé. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est inversé. |
| [setScale(int value)](#setScale-int-) | Obtient ou définit l'échelle du gradient **normalisée** (en pourcentage). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtient ou définit le décalage vertical. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Obtient ou définit une valeur indiquant si [align with layer].

Valeur :  true  si [align with layer] ; sinon,  false .

**Returns:**
booléen
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Obtient ou définit l’angle.

Valeur : l'angle.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est dithérisé.

Valeur :  true  si tramage ; sinon,  false .

**Returns:**
booléen
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Obtient ou définit le type du dégradé.

Valeur : Le type du dégradé.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Obtient ou définit le décalage horizontal.

Valeur: Le décalage horizontal.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Obtient ou définit la méthode d'interpolation du dégradé.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Returns:**
booléen
### getScale() {#getScale--}
```
public abstract int getScale()
```


Obtient ou définit l'échelle du gradient **normalisée** (en pourcentage).

Valeur : l'échelle.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Obtient ou définit le décalage vertical.

Valeur: Le décalage vertical.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Obtient ou définit une valeur indiquant si [align with layer].

Valeur :  true  si [align with layer] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Obtient ou définit l’angle.

Valeur : l'angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est dithérisé.

Valeur :  true  si tramage ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Obtient ou définit le type du dégradé.

Valeur : Le type du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Obtient ou définit le décalage horizontal.

Valeur: Le décalage horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Obtient ou définit la méthode d'interpolation du dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Obtient ou définit une valeur indiquant si cet [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Obtient ou définit l'échelle du gradient **normalisée** (en pourcentage).

Valeur : l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Obtient ou définit le décalage vertical.

Valeur: Le décalage vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

