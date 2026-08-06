---
title: "ColorantCmyk"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente le colorant CMYK."
type: docs
weight: 13
url: /fr/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Représente le colorant CMYK.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Initialise une nouvelle instance de la classe  ColorantCmyk  . |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Initialise une nouvelle instance de la classe  ColorantCmyk  . |
## Champs

| Champ | Description |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Valeur maximale de couleur dans le colorant CMYK. |
| [ColorValueMin](#ColorValueMin) | Valeur minimale de couleur dans le colorant CMYK. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Ajoute la clé spécifiée. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Obtient ou définit la valeur du composant noir. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Obtient ou définit le type de la couleur. |
| [getCyan()](#getCyan--) | Obtient ou définit la valeur du composant cyan. |
| [getMagenta()](#getMagenta--) | Obtient ou définit la valeur du composant magenta. |
| [getMode()](#getMode--) | Obtient  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | Obtient l'URI de l'espace de noms par défaut. |
| [getPrefix()](#getPrefix--) | Obtient le préfixe. |
| [getSwatchName()](#getSwatchName--) | Obtient ou définit le nom de l'échantillon. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
| [getYellow()](#getYellow--) | Obtient ou définit la valeur du composant jaune. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Obtient ou définit la valeur du composant noir. |
| [setColorType(int value)](#setColorType-int-) | Obtient ou définit le type de la couleur. |
| [setCyan(float value)](#setCyan-float-) | Obtient ou définit la valeur du composant cyan. |
| [setMagenta(float value)](#setMagenta-float-) | Obtient ou définit la valeur du composant magenta. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Obtient ou définit le nom de l'échantillon. |
| [setYellow(float value)](#setYellow-float-) | Obtient ou définit la valeur du composant jaune. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Initialise une nouvelle instance de la classe  ColorantCmyk  .

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Initialise une nouvelle instance de la classe  ColorantCmyk  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| noir | float | La valeur du composant noir. |
| cyan | float | La valeur du composant couleur cyan. |
| magenta | float | La valeur du composant magenta. |
| jaune | float | La valeur du composant jaune. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Valeur maximale de couleur dans le colorant CMYK.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Valeur minimale de couleur dans le colorant CMYK.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Ajoute la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| valeur | java.lang.Object | La valeur à ajouter à. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Obtient ou définit la valeur du composant noir.

Valeur : la valeur du composant noir.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtient ou définit le type de la couleur.

Valeur : le type de la couleur.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Obtient ou définit la valeur du composant cyan.

Valeur : la valeur du composant cyan.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Obtient ou définit la valeur du composant magenta.

Valeur : la valeur du composant magenta.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Obtient  ColorMode .

Valeur : le mode couleur.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtient l'URI de l'espace de noms par défaut.

**Returns:**
java.lang.String - L'URI d'espace de noms par défaut.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtient le préfixe.

**Returns:**
java.lang.String - Le préfixe.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Obtient ou définit le nom de l'échantillon.

Valeur : le nom de l'échantillon.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Obtient ou définit la valeur du composant jaune.

Valeur : la valeur du composant jaune.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Obtient ou définit la valeur du composant noir.

Valeur : la valeur du composant noir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtient ou définit le type de la couleur.

Valeur : le type de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Obtient ou définit la valeur du composant cyan.

Valeur : la valeur du composant cyan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Obtient ou définit la valeur du composant magenta.

Valeur : la valeur du composant magenta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Obtient ou définit le nom de l'échantillon.

Valeur : le nom de l'échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Obtient ou définit la valeur du composant jaune.

Valeur : la valeur du composant jaune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

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

