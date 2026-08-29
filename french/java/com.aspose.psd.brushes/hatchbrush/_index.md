---
title: "HatchBrush"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit une brosse rectangulaire avec un style de hachure, une couleur de premier plan et une couleur d'arrière-plan."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.brushes/hatchbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class HatchBrush extends Brush
```

Définit une brosse rectangulaire avec un style de hachure, une couleur de premier plan et une couleur d'arrière-plan. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Crée un nouveau clone profond du Brush actuel. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur des espaces entre les lignes de hachure. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getForegroundColor()](#getForegroundColor--) | Obtient la couleur des lignes de hachure. |
| [getHatchStyle()](#getHatchStyle--) | Obtient le style de hachure de cette brosse. |
| [getOpacity()](#getOpacity--) | Obtient l'opacité du pinceau. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Définit la couleur des espaces entre les lignes de hachure. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.psd.Color-) | Définit la couleur des lignes de hachure. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Définit le style de hachure de cette brosse. |
| [setOpacity(float value)](#setOpacity-float-) | Définit l'opacité du pinceau. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crée un nouveau clone profond du Brush actuel.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur des espaces entre les lignes de hachure.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of spaces between the hatch lines.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtient la couleur des lignes de hachure.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of hatch lines.
### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtient le style de hachure de cette brosse.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtient l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Returns:**
float - La valeur d'opacité du pinceau.
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Définit la couleur des espaces entre les lignes de hachure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | La couleur des espaces entre les lignes de hachure. |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.psd.Color-}
```
public void setForegroundColor(Color value)
```


Définit la couleur des lignes de hachure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | La couleur des lignes de hachure. |

### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Définit le style de hachure de cette brosse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur d'opacité du pinceau. |

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

