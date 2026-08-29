---
title: "NoiseGradientFillSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe de définition du dégradé de bruit."
type: docs
weight: 18
url: /fr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Classe de définition du dégradé de bruit.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Initialise une nouvelle instance de la classe [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings). |
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
| [getColorModel()](#getColorModel--) | Obtient ou définit le modèle de couleur - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither. |
| [getExpansionCount()](#getExpansionCount--) | Obtient ou définit le nombre d'expansion ( = 2 pour Photoshop 6.0). |
| [getFillType()](#getFillType--) | Le type de remplissage. |
| [getGradientMode()](#getGradientMode--) | Obtient le mode de ce dégradé. |
| [getGradientName()](#getGradientName--) | Obtient ou définit le nom du dégradé. |
| [getGradientType()](#getGradientType--) | Obtient ou définit le type du dégradé. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtient ou définit le décalage horizontal en pourcentage. |
| [getMaximumColor()](#getMaximumColor--) | Obtient ou définit la couleur maximale de PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Obtient ou définit la couleur minimale de PixelDataFormat. |
| [getReverse()](#getReverse--) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Obtient ou définit la graine aléatoire utilisée pour générer les couleurs du dégradé de bruit. |
| [getRoughness()](#getRoughness--) | Obtient ou définit le facteur de rugosité. |
| [getScale()](#getScale--) | Obtient ou définit l'échelle. |
| [getShowTransparency()](#getShowTransparency--) | Obtient ou définit le drapeau d'affichage de la transparence. |
| [getUseVectorColor()](#getUseVectorColor--) | Obtient ou définit le drapeau d'utilisation de la couleur vectorielle. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtient ou définit le décalage vertical en pourcentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Déclenche la modification de la valeur. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtient ou définit une valeur indiquant si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtient ou définit l’angle. |
| [setColorModel(short value)](#setColorModel-short-) | Obtient ou définit le modèle de couleur - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Obtient ou définit le nombre d'expansion ( = 2 pour Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Obtient le mode de ce dégradé. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Obtient ou définit le nom du dégradé. |
| [setGradientType(int value)](#setGradientType-int-) | Obtient ou définit le type du dégradé. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtient ou définit le décalage horizontal en pourcentage. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtient ou définit la couleur maximale de PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtient ou définit la couleur minimale de PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Obtient ou définit la graine aléatoire utilisée pour générer les couleurs du dégradé de bruit. |
| [setRoughness(int value)](#setRoughness-int-) | Obtient ou définit le facteur de rugosité. |
| [setScale(int value)](#setScale-int-) | Obtient ou définit l'échelle. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Obtient ou définit le drapeau d'affichage de la transparence. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Obtient ou définit le drapeau d'utilisation de la couleur vectorielle. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtient ou définit le décalage vertical en pourcentage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Initialise une nouvelle instance de la classe [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings).

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Obtient ou définit le modèle de couleur - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est dither.

Valeur :  true  si tramage ; sinon,  false .

**Returns:**
booléen
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Obtient ou définit le nombre d'expansion ( = 2 pour Photoshop 6.0).

**Returns:**
short
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Obtient ou définit la couleur maximale de PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Obtient ou définit la couleur minimale de PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) est inversé.

Valeur :  true  si inversé ; sinon,  false .

**Returns:**
booléen
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Obtient ou définit la graine aléatoire utilisée pour générer les couleurs du dégradé de bruit.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Obtient ou définit le facteur de rugosité.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Obtient ou définit l'échelle.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Obtient ou définit le drapeau d'affichage de la transparence.

**Returns:**
booléen
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Obtient ou définit le drapeau d'utilisation de la couleur vectorielle.

**Returns:**
booléen
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Obtient ou définit le modèle de couleur - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Obtient ou définit le nombre d'expansion ( = 2 pour Photoshop 6.0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Obtient ou définit la couleur maximale de PixelDataFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Obtient ou définit la couleur minimale de PixelDataFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Obtient ou définit la graine aléatoire utilisée pour générer les couleurs du dégradé de bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Obtient ou définit le facteur de rugosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Obtient ou définit l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Obtient ou définit le drapeau d'affichage de la transparence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Obtient ou définit le drapeau d'utilisation de la couleur vectorielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

