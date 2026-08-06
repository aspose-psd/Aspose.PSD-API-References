---
title: "ILayerEffect"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Interface pour les effets de calque"
type: docs
weight: 20
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Interface pour les effets de calque
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Obtient ou définit le mode de fusion. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcule et obtient les limites des pixels d'effet en fonction des limites des pixels du calque d'entrée. |
| [getEffectType()](#getEffectType--) | Obtient un type d'effet |
| [getOpacity()](#getOpacity--) | Obtient ou définit l'opacité où 255 = 100 % |
| [isVisible()](#isVisible--) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtient ou définit le mode de fusion. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtient ou définit l'opacité où 255 = 100 % |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit une valeur indiquant si cette instance est visible. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Obtient ou définit le mode de fusion.

Valeur : le mode de fusion.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Calcule et obtient les limites des pixels d'effet en fonction des limites des pixels du calque d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites des pixels du calque. |
| globalAngle | int | L'angle global pour calculer l'angle de lumière global. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Obtient un type d'effet

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Obtient ou définit l'opacité où 255 = 100 %

Valeur : l'opacité.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Obtient ou définit une valeur indiquant si cette instance est visible.

Valeur:  true  si cette instance est visible ; sinon,  false .

**Returns:**
booléen
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Obtient ou définit le mode de fusion.

Valeur : le mode de fusion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Obtient ou définit l'opacité où 255 = 100 %

Valeur : l'opacité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est visible.

Valeur:  true  si cette instance est visible ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

