---
title: "MaskingOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente les options communes de masquage d'image."
type: docs
weight: 16
url: /fr/java/com.aspose.psd.masking.options/maskingoptions/
---

**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Représente les options communes de masquage d'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Le numéro de l'objet d'arrière-plan |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Obtient les arguments pour l'algorithme de segmentation. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Obtient la couleur de remplacement d'arrière-plan. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Obtient une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |
| [getExportOptions()](#getExportOptions--) | Obtient les options d'exportation d'image. |
| [getMaskingArea()](#getMaskingArea--) | Obtient la zone de masquage. |
| [getMethod()](#getMethod--) | Obtient la méthode de segmentation. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Définit les arguments pour l'algorithme de segmentation. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Définit la couleur de remplacement d'arrière-plan. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Définit une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Définit les options d'exportation d'image. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Définit la zone de masquage. |
| [setMethod(int value)](#setMethod-int-) | Définit la méthode de segmentation. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Le numéro de l'objet d'arrière-plan

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Obtient les arguments pour l'algorithme de segmentation.

Valeur : les arguments pour l'algorithme de segmentation.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Obtient la couleur de remplacement d'arrière-plan.

Valeur : la couleur de remplacement d'arrière-plan. Cette couleur sera utilisée comme couleur d'arrière-plan dans les images résultantes.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Obtient une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan.

Valeur :  true  si décomposer ; sinon,  false .

**Returns:**
booléen - une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Obtient les options d'exportation d'image.

Valeur : les options d'exportation d'image qui seront utilisées pour créer les images résultantes.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Obtient la zone de masquage.

Valeur : la zone de masquage qui est une zone partielle de l'image source. La valeur Rectangle.Empty signifie la zone complète de l'image source.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Obtient la méthode de segmentation.

Valeur : la méthode de segmentation.

**Returns:**
int - la méthode de segmentation.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Définit les arguments pour l'algorithme de segmentation.

Valeur : les arguments pour l'algorithme de segmentation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | les arguments pour l'algorithme de segmentation. |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Définit la couleur de remplacement d'arrière-plan.

Valeur : la couleur de remplacement d'arrière-plan. Cette couleur sera utilisée comme couleur d'arrière-plan dans les images résultantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | la couleur de remplacement d'arrière-plan. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Définit une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan.

Valeur :  true  si décomposer ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | une valeur indiquant s'il est inutile de séparer chaque Shape du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Définit les options d'exportation d'image.

Valeur : les options d'exportation d'image qui seront utilisées pour créer les images résultantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | les options d'exportation d'image. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Définit la zone de masquage.

Valeur : la zone de masquage qui est une zone partielle de l'image source. La valeur Rectangle.Empty signifie la zone complète de l'image source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | la zone de masquage. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Définit la méthode de segmentation.

Valeur : la méthode de segmentation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la méthode de segmentation. |

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

