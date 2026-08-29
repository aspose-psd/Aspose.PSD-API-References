---
title: "AutoMaskingGraphCutOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les options de masquage automatique GraphCut."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Les options de masquage automatique GraphCut.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Initialise une nouvelle instance de la classe [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Champs

| Champ | Description |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Le numéro de l'objet d'arrière-plan |
## Méthodes

| Méthode | Description |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Ajouter les arguments du masquage automatique. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Remplir les traits par défaut. |
| [getArgs()](#getArgs--) | Obtient les arguments pour l'algorithme de segmentation. |
| [getAssumedObjects()](#getAssumedObjects--) | Obtient les objets supposés. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Obtient la couleur de remplacement d'arrière-plan. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Obtient une valeur indiquant si les traits par défaut doivent être calculés. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Obtient le rectangle des objets combinés. |
| [getDecompose()](#getDecompose--) | Obtient une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Obtient les traits d'arrière-plan par défaut. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Obtient les traits de premier plan par défaut pré-calculés. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Obtient les rectangles des objets par défaut. |
| [getExportOptions()](#getExportOptions--) | Obtient les options d'exportation d'image. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Obtient le rayon de flou. |
| [getMaskingArea()](#getMaskingArea--) | Obtient la zone de masquage. |
| [getMethod()](#getMethod--) | Obtient la méthode de segmentation. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Obtient le gestionnaire d'événement de progression du processus de pré-calcul des points par défaut. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Obtient une valeur indiquant si la collection d'objets supposés contient des objets humains. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Définit les arguments pour l'algorithme de segmentation. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Définit les objets supposés. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Définit la couleur de remplacement d'arrière-plan. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Définit une valeur indiquant si les traits par défaut doivent être calculés. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Le rectangle des objets combinés. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Définit une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Les traits d'arrière-plan par défaut. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Les traits de premier plan par défaut pré-calculés. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Les rectangles des objets par défaut. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Définit les options d'exportation d'image. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Définit le rayon de flou. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Une valeur indiquant si la collection d'objets supposés contient des objets humains. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Définit la zone de masquage. |
| [setMethod(int value)](#setMethod-int-) | Définit la méthode de segmentation. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression du processus de pré-calcul des points par défaut. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Initialise une nouvelle instance de la classe [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Le numéro de l'objet d'arrière-plan

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Ajouter les arguments du masquage automatique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Remplir les traits par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Obtient les arguments pour l'algorithme de segmentation.

Valeur : les arguments pour l'algorithme de segmentation.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Obtient les objets supposés.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - les objets supposés.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Obtient la couleur de remplacement d'arrière-plan.

Valeur : la couleur de remplacement d'arrière-plan. Cette couleur sera utilisée comme couleur d'arrière-plan dans les images résultantes.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Obtient une valeur indiquant si les traits par défaut doivent être calculés.

**Returns:**
boolean - une valeur indiquant si les traits par défaut doivent être calculés.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Obtient le rectangle des objets combinés.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Obtient une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan.

Valeur :  true  si décomposer ; sinon,  false .

**Returns:**
booléen - une valeur indiquant s'il est inutile de séparer chaque forme du masque en tant qu'objet individuel ou en tant qu'objet uni du masque séparé de l'arrière-plan.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Obtient les traits d'arrière-plan par défaut.

**Returns:**
com.aspose.psd.Point[] - les traits d'arrière-plan par défaut.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Obtient les traits de premier plan par défaut pré-calculés.

**Returns:**
com.aspose.psd.Point[] - les traits de premier plan par défaut pré-calculés.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Obtient les rectangles des objets par défaut.

**Returns:**
com.aspose.psd.Rectangle[] - les rectangles des objets par défaut.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Obtient les options d'exportation d'image.

Valeur : les options d'exportation d'image qui seront utilisées pour créer les images résultantes.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Obtient le rayon de flou.

**Returns:**
int - le rayon de flou.
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression du processus de pré-calcul des points par défaut.

Valeur : Le gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Obtient une valeur indiquant si la collection d'objets supposés contient des objets humains.

**Returns:**
boolean - une valeur indiquant si la collection d'objets supposés contient des objets humains.
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Définit les objets supposés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | les objets supposés. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Définit une valeur indiquant si les traits par défaut doivent être calculés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | une valeur indiquant si les traits par défaut doivent être calculés. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Le rectangle des objets combinés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | le rectangle combiné des objets. |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Les traits d'arrière-plan par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | les traits d'arrière-plan par défaut. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Les traits de premier plan par défaut pré-calculés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | les traits de premier plan par défaut pré-calculés. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Les rectangles des objets par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | les rectangles des objets par défaut. |

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

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Définit le rayon de flou.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le rayon de flou. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Une valeur indiquant si la collection d'objets supposés contient des objets humains.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | une valeur indiquant si la collection d'objets supposés contient des objets humains. |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Définit le gestionnaire d'événement de progression du processus de pré-calcul des points par défaut.

Valeur : Le gestionnaire d'événement de progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | le gestionnaire d'événement de progression du processus de pré-calcul des points par défaut. |

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

