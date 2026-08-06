---
title: "PdfCoreOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Les options communes pour la conversion en PDF"
type: docs
weight: 10
url: /fr/java/com.aspose.psd.fileformats.pdf/pdfcoreoptions/
---

**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Les options communes pour la conversion en PDF
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Spécifie à quel niveau dans le plan du document afficher les objets de signet. |
| [getClass()](#getClass--) |  |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Spécifie combien de niveaux du plan du document doivent être affichés développés lorsque le fichier PDF est visualisé. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Spécifie combien de niveaux d'éléments du plan doivent être inclus dans le plan du document. |
| [getJpegQuality()](#getJpegQuality--) | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). |
| [getPdfCompliance()](#getPdfCompliance--) | Obtient la conformité PDF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Spécifie à quel niveau dans le plan du document afficher les objets de signet. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Spécifie combien de niveaux du plan du document doivent être affichés développés lorsque le fichier PDF est visualisé. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Spécifie combien de niveaux d'éléments du plan doivent être inclus dans le plan du document. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Définit la conformité PDF. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
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
### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Spécifie à quel niveau dans le plan du document afficher les objets de signet. 0 - non affiché. 1 au premier niveau, etc. La valeur par défaut est 0.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Spécifie combien de niveaux du plan du document doivent être affichés développés lorsque le fichier PDF est visualisé. 0 - le plan du document n'est pas développé. 1 - les éléments du premier niveau sont développés, etc. La valeur par défaut est 0.

**Returns:**
int
### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Spécifie combien de niveaux d'éléments du plan doivent être inclus dans le plan du document. 0 - aucun plan, 1 - un niveau de plan, etc. La valeur par défaut est 0.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). La valeur par défaut est 95.

**Returns:**
int
### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Obtient la conformité PDF.

**Returns:**
int - la conformité PDF.
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




### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Spécifie à quel niveau dans le plan du document afficher les objets de signet. 0 - non affiché. 1 au premier niveau, etc. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Spécifie combien de niveaux du plan du document doivent être affichés développés lorsque le fichier PDF est visualisé. 0 - le plan du document n'est pas développé. 1 - les éléments du premier niveau sont développés, etc. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Spécifie combien de niveaux d'éléments du plan doivent être inclus dans le plan du document. 0 - aucun plan, 1 - un niveau de plan, etc. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). La valeur par défaut est 95.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Définit la conformité PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la conformité PDF. |

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

