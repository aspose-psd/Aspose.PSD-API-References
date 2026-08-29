---
title: "ImageAttributes"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Un objet com.aspose.psd.ImageAttributes contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées lors du rendu."
type: docs
weight: 55
url: /fr/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Un objet com.aspose.psd.ImageAttributes contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées lors du rendu. Un objet com.aspose.psd.ImageAttributes maintient plusieurs paramètres d'ajustement des couleurs, y compris les matrices d'ajustement des couleurs, les matrices d'ajustement en niveaux de gris, les valeurs de correction gamma, les tables de correspondance des couleurs et les valeurs de seuil de couleur. Lors du rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un objet com.aspose.psd.ImageAttributes et transmettez le chemin de cet objet com.aspose.psd.ImageAttributes (ainsi que le chemin d'une [Image](../../com.aspose.psd/image)) à la méthode drawImage.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialise une nouvelle instance de la classe com.aspose.psd.ImageAttributes. |
## Champs

| Champ | Description |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | Les attributs d'image GDI. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Efface la table de remappage des couleurs du pinceau de cet objet com.aspose.psd.ImageAttributes. |
| [clearColorKey()](#clearColorKey--) | Efface la clé de couleur (plage de transparence) pour la catégorie par défaut. |
| [clearColorKey(int type)](#clearColorKey-int-) | Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [clearColorMatrix()](#clearColorMatrix--) | Efface la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Efface la matrice d'ajustement des couleurs pour une catégorie spécifiée. |
| [clearGamma()](#clearGamma--) | Désactive la correction gamma pour la catégorie par défaut. |
| [clearGamma(int type)](#clearGamma-int-) | Désactive la correction gamma pour une catégorie spécifiée. |
| [clearNoOp()](#clearNoOp--) | Efface le paramètre NoOp pour la catégorie par défaut. |
| [clearNoOp(int type)](#clearNoOp-int-) | Efface le paramètre NoOp pour une catégorie spécifiée. |
| [clearOutputChannel()](#clearOutputChannel--) | Efface le paramètre du canal de sortie CMYK (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Efface le paramètre du canal de sortie (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Efface le paramètre du profil de couleur du canal de sortie pour la catégorie par défaut. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Efface le paramètre du profil de couleur du canal de sortie pour une catégorie spécifiée. |
| [clearRemapTable()](#clearRemapTable--) | Efface la table de remappage des couleurs pour la catégorie par défaut. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Efface la table de remappage des couleurs pour une catégorie spécifiée. |
| [clearThreshold()](#clearThreshold--) | Efface la valeur de seuil pour la catégorie par défaut. |
| [clearThreshold(int type)](#clearThreshold-int-) | Efface la valeur de seuil pour une catégorie spécifiée. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Définit la table de remappage des couleurs pour la catégorie de pinceau. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Définit la clé de couleur pour la catégorie par défaut. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement en niveaux de gris pour la catégorie par défaut. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement en niveaux de gris pour la catégorie par défaut. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement en niveaux de gris pour une catégorie spécifiée. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Définit la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Définit la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Définit la matrice d'ajustement des couleurs pour une catégorie spécifiée. |
| [setGamma(float gamma)](#setGamma-float-) | Définit la valeur gamma pour la catégorie par défaut. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Définit la valeur gamma pour une catégorie spécifiée. |
| [setNoOp()](#setNoOp--) | Désactive l'ajustement des couleurs pour la catégorie par défaut. |
| [setNoOp(int type)](#setNoOp-int-) | Désactive l'ajustement des couleurs pour une catégorie spécifiée. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Définit le canal de sortie CMYK (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Définit le canal de sortie CMYK (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Définit le fichier de profil couleur du canal de sortie pour la catégorie par défaut. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Définit le fichier de profil couleur du canal de sortie pour une catégorie spécifiée. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Définit la table de remappage des couleurs pour la catégorie par défaut. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Définit la table de remappage des couleurs pour une catégorie spécifiée. |
| [setThreshold(float threshold)](#setThreshold-float-) | Définit le seuil (plage de transparence) pour la catégorie par défaut. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Définit le seuil (plage de transparence) pour une catégorie spécifiée. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Définit le mode d'enroulement utilisé pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialise une nouvelle instance de la classe com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


Les attributs d'image GDI.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Efface la table de remappage des couleurs du pinceau de cet objet com.aspose.psd.ImageAttributes.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Efface la clé de couleur (plage de transparence) pour la catégorie par défaut.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle la clé de couleur est effacée. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Efface la matrice d'ajustement des couleurs pour la catégorie par défaut.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Efface la matrice d'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle la matrice d'ajustement des couleurs est effacée. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Désactive la correction gamma pour la catégorie par défaut.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Désactive la correction gamma pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle la correction gamma est désactivée. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Efface le paramètre NoOp pour la catégorie par défaut.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Efface le paramètre NoOp pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle le paramètre NoOp est effacé. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Efface le paramètre du canal de sortie CMYK (cyan-magenta-jaune-noir) pour la catégorie par défaut.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Efface le paramètre du canal de sortie (cyan-magenta-jaune-noir) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle le paramètre du canal de sortie est effacé. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Efface le paramètre du profil de couleur du canal de sortie pour la catégorie par défaut.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Efface le paramètre du profil de couleur du canal de sortie pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle le paramètre de profil du canal de sortie est effacé. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Efface la table de remappage des couleurs pour la catégorie par défaut.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Efface la table de remappage des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle la table de remappage est effacée. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Efface la valeur de seuil pour la catégorie par défaut.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Efface la valeur de seuil pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de Aspose.Imaging.ColorAdjustType qui spécifie la catégorie pour laquelle le seuil est effacé. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Définit la table de remappage des couleurs pour la catégorie de pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Un tableau d'objets com.aspose.psd.ColorMap. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Définit la clé de couleur pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | La valeur basse de la clé de couleur. |
| colorHigh | [Color](../../com.aspose.psd/color) | La valeur haute de la clé de couleur. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | La valeur basse de la clé de couleur. |
| colorHigh | [Color](../../com.aspose.psd/color) | La valeur haute de la clé de couleur. |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle la clé de couleur est définie. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Définit la matrice d'ajustement des couleurs et la matrice d'ajustement en niveaux de gris pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement des couleurs. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement du niveau de gris. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Définit la matrice d'ajustement des couleurs et la matrice d'ajustement en niveaux de gris pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement des couleurs. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement du niveau de gris. |
| drapeaux | int | Un élément de **Aspose.Imaging.ColorMatrixFlag** qui spécifie le type d'image et de couleur qui sera affecté par les matrices d'ajustement des couleurs et du niveau de gris. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Définit la matrice d'ajustement des couleurs et la matrice d'ajustement en niveaux de gris pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement des couleurs. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement du niveau de gris. |
| mode | int | Un élément de **Aspose.Imaging.ColorMatrixFlag** qui spécifie le type d'image et de couleur qui sera affecté par les matrices d'ajustement des couleurs et du niveau de gris. |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle les matrices d'ajustement des couleurs et du niveau de gris sont définies. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Définit la matrice d'ajustement des couleurs pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement des couleurs. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Définit la matrice d'ajustement des couleurs pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement des couleurs. |
| drapeaux | int | Un élément de **Aspose.Imaging.ColorMatrixFlag** qui spécifie le type d'image et de couleur qui sera affecté par la matrice d'ajustement des couleurs. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Définit la matrice d'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | La matrice d'ajustement des couleurs. |
| mode | int | Un élément de **Aspose.Imaging.ColorMatrixFlag** qui spécifie le type d'image et de couleur qui sera affecté par la matrice d'ajustement des couleurs. |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle la matrice d'ajustement des couleurs est définie. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Définit la valeur gamma pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | La valeur de correction gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Définit la valeur gamma pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | La valeur de correction gamma. |
| type | int | Un élément de l'énumération **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle la valeur gamma est définie. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Désactive l'ajustement des couleurs pour la catégorie par défaut.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Désactive l'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle la correction des couleurs est désactivée. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Définit le canal de sortie CMYK (cyan-magenta-jaune-noir) pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeaux | int | Un élément de **Aspose.Imaging.ColorChannelFlag** qui spécifie le canal de sortie. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Définit le canal de sortie CMYK (cyan-magenta-jaune-noir) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeaux | int | Un élément de **Aspose.Imaging.ColorChannelFlag** qui spécifie le canal de sortie. |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle le canal de sortie est défini. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Définit le fichier de profil couleur du canal de sortie pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Le chemin d'accès d'un fichier de profil couleur. Si le fichier de profil couleur se trouve dans le répertoire %SystemRoot%\\System32\\Spool\\Drivers\\Color, ce paramètre peut être le nom du fichier. Sinon, ce paramètre doit être le chemin d'accès complet. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Définit le fichier de profil couleur du canal de sortie pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Le chemin d'accès d'un fichier de profil couleur. Si le fichier de profil couleur se trouve dans le répertoire %SystemRoot%\\System32\\Spool\\Drivers\\Color, ce paramètre peut être le nom du fichier. Sinon, ce paramètre doit être le chemin d'accès complet. |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle le fichier de profil couleur du canal de sortie est défini. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Définit la table de remappage des couleurs pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Un tableau de paires de couleurs du type **com.aspose.psd.ColorMap**. Chaque paire de couleurs contient une couleur existante (la première valeur) et la couleur vers laquelle elle sera mappée (la deuxième valeur). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Définit la table de remappage des couleurs pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Un tableau de paires de couleurs du type **com.aspose.psd.ColorMap**. Chaque paire de couleurs contient une couleur existante (la première valeur) et la couleur vers laquelle elle sera mappée (la deuxième valeur). |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle la table de remappage des couleurs est définie. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Définit le seuil (plage de transparence) pour la catégorie par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Un nombre réel qui spécifie la valeur du seuil. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Définit le seuil (plage de transparence) pour une catégorie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Une valeur de seuil de 0.0 à 1.0 qui est utilisée comme point de rupture pour trier les couleurs qui seront mappées vers une valeur maximale ou minimale. |
| type | int | Un élément de **Aspose.Imaging.ColorAdjustType** qui spécifie la catégorie pour laquelle le seuil de couleur est défini. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Définit le mode d'enveloppe utilisé pour décider comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Un élément de **Aspose.Imaging.WrapMode** qui spécifie comment les copies répétées d'une image sont utilisées pour répéter une zone. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Un élément de **Aspose.Imaging.WrapMode** qui spécifie comment les copies répétées d'une image sont utilisées pour répéter une zone. |
| color | [Color](../../com.aspose.psd/color) | Un objet  com.aspose.psd.ImageAttributes  qui spécifie la couleur des pixels situés à l'extérieur d'une image rendue. Cette couleur est visible si le paramètre mode est défini sur  WrapMode.Clamp  et que le rectangle source passé à DrawImage est plus grand que l'image elle‑même. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Un élément de **Aspose.Imaging.WrapMode** qui spécifie comment les copies répétées d'une image sont utilisées pour répéter une zone. |
| color | [Color](../../com.aspose.psd/color) | Un objet couleur qui spécifie la couleur des pixels situés à l'extérieur d'une image rendue. Cette couleur est visible si le paramètre mode est défini sur  WrapMode.Clamp  et que le rectangle source passé à DrawImage est plus grand que l'image elle‑même. |
| clamp | booléen | Ce paramètre n'a aucun effet. Réglez‑le sur false. |

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

