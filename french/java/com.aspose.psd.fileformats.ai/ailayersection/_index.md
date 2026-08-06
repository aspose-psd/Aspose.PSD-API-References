---
title: "AiLayerSection"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La section de calque du format Ai"
type: docs
weight: 15
url: /fr/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

La section de calque du format Ai
## Méthodes

| Méthode | Description |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Ajoute l'image raster. |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Obtient ou définit le composant de couleur bleu. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Obtient ou définit l'index de la couleur. |
| [getColorNumber()](#getColorNumber--) | Obtient ou définit le numéro de couleur. |
| [getData()](#getData--) | Obtient les données de chaîne. |
| [getDimValue()](#getDimValue--) | Obtient ou définit la valeur d'assombrissement en pourcentage. |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getGreen()](#getGreen--) | Obtient ou définit le composant de couleur vert. |
| [getName()](#getName--) | Obtient ou définit le nom du calque. |
| [getRasterImages()](#getRasterImages--) | Obtient les images raster. |
| [getRed()](#getRed--) | Obtient ou définit le composant de couleur rouge. |
| [getStream_internalized()](#getStream-internalized--) | Obtient le flux interne |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Obtient ou définit une valeur indiquant si cette couche est atténuée. |
| [isLocked()](#isLocked--) | Obtient ou définit une valeur indiquant si cette couche est verrouillée. |
| [isPreview()](#isPreview--) | Obtient ou définit une valeur indiquant si cette couche est en aperçu. |
| [isPrinted()](#isPrinted--) | Obtient ou définit une valeur indiquant si cette couche est imprimée. |
| [isShown()](#isShown--) | Obtient ou définit une valeur indiquant si cette couche est affichée. |
| [isTemplate()](#isTemplate--) | Obtient ou définit une valeur indiquant si cette couche est une couche modèle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Obtient ou définit le composant de couleur bleu. |
| [setColorIndex(int value)](#setColorIndex-int-) | Obtient ou définit l'index de la couleur. |
| [setColorNumber(int value)](#setColorNumber-int-) | Obtient ou définit le numéro de couleur. |
| [setDimValue(int value)](#setDimValue-int-) | Obtient ou définit la valeur d'assombrissement en pourcentage. |
| [setGreen(int value)](#setGreen-int-) | Obtient ou définit le composant de couleur vert. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Obtient ou définit une valeur indiquant si cette couche est atténuée. |
| [setLocked(boolean value)](#setLocked-boolean-) | Obtient ou définit une valeur indiquant si cette couche est verrouillée. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom du calque. |
| [setPreview(boolean value)](#setPreview-boolean-) | Obtient ou définit une valeur indiquant si cette couche est en aperçu. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Obtient ou définit une valeur indiquant si cette couche est imprimée. |
| [setRed(int value)](#setRed-int-) | Obtient ou définit le composant de couleur rouge. |
| [setShown(boolean value)](#setShown-boolean-) | Obtient ou définit une valeur indiquant si cette couche est affichée. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Obtient ou définit une valeur indiquant si cette couche est une couche modèle. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Ajoute l'image raster.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | L'image raster. |

### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |
| propriétés | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Obtient ou définit le composant de couleur bleu.

Valeur : le composant bleu.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Obtient ou définit l'index de la couleur. Cet argument peut prendre des valeurs entre \\u20131 et 26. Chaque entier représente une couleur qui peut être attribuée à la couche à des fins d'identification par l'utilisateur.

Valeur : l'index de la couleur.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Obtient ou définit le numéro de couleur. -1 correspond à la valeur de couleur personnalisée provenant des propriétés Rouge, Vert, Bleu. Spécifie le paramètre de couleur de la couche\\u2019s.

Valeur : le numéro de couleur.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Obtient les données de chaîne.

**Returns:**
java.lang.String - Les données de chaîne de la section
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Obtient ou définit la valeur d'atténuation en pourcentage. Réduit l'intensité des images liées et des images bitmap contenues dans la couche au pourcentage spécifié.

Valeur : la valeur d'atténuation en pourcentage.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Obtient ou définit le composant de couleur vert.

Valeur : le composant vert.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom de la couche. Spécifie le nom de l'élément tel qu'il apparaît dans le panneau Couches.

Valeur : le nom du calque.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Obtient les images raster.

Valeur : les images raster.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Obtient ou définit le composant de couleur rouge.

Valeur : le composant rouge.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Obtient le flux interne

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches.

Valeur :  true  si cette instance possède des masques multicouches ; sinon,  false .

**Returns:**
booléen
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Obtient ou définit une valeur indiquant si cette couche est atténuée. Réduit l'intensité des images liées et des images bitmap contenues dans la couche.

Valeur :  true  si cette couche est atténuée ; sinon,  false .

**Returns:**
booléen
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtient ou définit une valeur indiquant si cette couche est verrouillée. Empêche les modifications de l'élément.

Valeur :  true  si cette couche est verrouillée ; sinon,  false .

**Returns:**
booléen
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Obtient ou définit une valeur indiquant si cette couche est en aperçu. Affiche le travail artistique contenu dans la couche en couleur plutôt qu'en contours.

Valeur :  true  si cette couche est en aperçu ; sinon,  false .

**Returns:**
booléen
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Obtient ou définit une valeur indiquant si ce calque est imprimé. Rend le dessin contenu dans le calque imprimable si vrai.

Valeur :  true  si ce calque est imprimé ; sinon,  false .

**Returns:**
booléen
### isShown() {#isShown--}
```
public final boolean isShown()
```


Obtient ou définit une valeur indiquant si ce calque est affiché. Affiche tout le dessin contenu dans le calque sur le plan de travail si vrai.

Valeur :  true  si ce calque est affiché ; sinon,  false .

**Returns:**
booléen
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Obtient ou définit une valeur indiquant si cette couche est une couche modèle.

Valeur :  true  si ce calque est un modèle ; sinon,  false .

**Returns:**
booléen
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Obtient ou définit le composant de couleur bleu.

Valeur : le composant bleu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Obtient ou définit l'index de la couleur. Cet argument peut prendre des valeurs entre \\u20131 et 26. Chaque entier représente une couleur qui peut être attribuée à la couche à des fins d'identification par l'utilisateur.

Valeur : l'index de la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Obtient ou définit le numéro de couleur. -1 correspond à la valeur de couleur personnalisée provenant des propriétés Rouge, Vert, Bleu. Spécifie le paramètre de couleur de la couche\\u2019s.

Valeur : le numéro de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Obtient ou définit la valeur d'atténuation en pourcentage. Réduit l'intensité des images liées et des images bitmap contenues dans la couche au pourcentage spécifié.

Valeur : la valeur d'atténuation en pourcentage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Obtient ou définit le composant de couleur vert.

Valeur : le composant vert.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Obtient ou définit une valeur indiquant si cette couche est atténuée. Réduit l'intensité des images liées et des images bitmap contenues dans la couche.

Valeur :  true  si cette couche est atténuée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Obtient ou définit une valeur indiquant si cette couche est verrouillée. Empêche les modifications de l'élément.

Valeur :  true  si cette couche est verrouillée ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches.

Valeur :  true  si cette instance possède des masques multicouches ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtient ou définit le nom de la couche. Spécifie le nom de l'élément tel qu'il apparaît dans le panneau Couches.

Valeur : le nom du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Obtient ou définit une valeur indiquant si cette couche est en aperçu. Affiche le travail artistique contenu dans la couche en couleur plutôt qu'en contours.

Valeur :  true  si cette couche est en aperçu ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Obtient ou définit une valeur indiquant si ce calque est imprimé. Rend le dessin contenu dans le calque imprimable si vrai.

Valeur :  true  si ce calque est imprimé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Obtient ou définit le composant de couleur rouge.

Valeur : le composant rouge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Obtient ou définit une valeur indiquant si ce calque est affiché. Affiche tout le dessin contenu dans le calque sur le plan de travail si vrai.

Valeur :  true  si ce calque est affiché ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Obtient ou définit une valeur indiquant si cette couche est une couche modèle.

Valeur :  true  si ce calque est un modèle ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

