---
title: "SolidGradient"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres de l'effet de remplissage du gradient."
type: docs
weight: 13
url: /fr/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Paramètres de l'effet de remplissage du gradient.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Initialise une nouvelle instance de la classe [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Ajoute le point de couleur. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Ajoute le point de couleur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Génère les nœuds de ressources LFX2. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Obtient ou définit les points de couleur. |
| [getGradientMode()](#getGradientMode--) | Obtient le mode de ce dégradé. |
| [getGradientName()](#getGradientName--) | Obtient ou définit le nom du dégradé. |
| [getInterpolation()](#getInterpolation--) | Obtient ou définit l'interpolation. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Obtient ou définit les points de transparence. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Supprime le point de couleur. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Supprime le point de transparence. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Obtient ou définit les points de couleur. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Obtient ou définit le nom du dégradé. |
| [setInterpolation(short value)](#setInterpolation-short-) | Obtient ou définit l'interpolation. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Obtient ou définit les points de transparence. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Initialise une nouvelle instance de la classe [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient).

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Ajoute le point de couleur.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Ajoute le point de couleur.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Génère les nœuds de ressources LFX2.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Liste générée de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Obtient ou définit les points de couleur.

Valeur : les points de couleur.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
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
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Obtient ou définit l'interpolation. Détermine la douceur, lorsque le 'Gradient Type' = 'Solid'. Plage de valeurs : 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Obtient ou définit les points de transparence.

Valeur : les points de transparence.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


Supprime le point de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Le point. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Supprime le point de transparence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Le point. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Obtient ou définit les points de couleur.

Valeur : les points de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Obtient ou définit l'interpolation. Détermine la douceur, lorsque le 'Gradient Type' = 'Solid'. Plage de valeurs : 0-4096.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Obtient ou définit les points de transparence.

Valeur : les points de transparence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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

