---
title: "AutoMaskingArgs"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente les arguments spécifiés pour les méthodes de masquage automatisées"
type: docs
weight: 11
url: /fr/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Représente les arguments spécifiés pour les méthodes de masquage automatisées
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Obtient le nombre maximal d'itérations. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Obtient le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan). |
| [getObjectsPoints()](#getObjectsPoints--) | Obtient les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Obtient les rectangles des objets qui appartiennent aux objets séparés (facultatif). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Obtient les points qui n'appartiennent plus à aucun objet (facultatif). |
| [getPrecision()](#getPrecision--) | Obtient la précision de la méthode de segmentation (facultatif). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Définit le nombre maximal d'itérations. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Définit le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Définit les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Définit les rectangles des objets qui appartiennent aux objets séparés (facultatif). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Définit les points qui n'appartiennent plus à aucun objet (facultatif). |
| [setPrecision(double value)](#setPrecision-double-) | Définit la précision de la méthode de segmentation (facultatif). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Obtient le nombre maximal d'itérations.

Valeur: Le nombre maximal maximal d'itérations.

**Returns:**
int - le nombre maximal d'itérations.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Obtient le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan).

Valeur: Le nombre d'objets.

**Returns:**
int - le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Obtient les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale. Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur: Les points des objets.

**Returns:**
com.aspose.psd.Point[][] - les points qui appartiennent aux objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent aux objets NumberOfObjects de l'image initiale.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Obtient les rectangles des objets qui appartiennent aux objets séparés (facultatif). Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur: Les rectangles des objets.

**Returns:**
com.aspose.psd.Rectangle[] - les rectangles des objets qui appartiennent à des objets séparés (facultatif).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Obtient les points qui n'appartiennent plus à aucun objet (facultatif). Ce paramètre n'est utilisé que dans le cas d'une re-segmentation.

Valeur : les points orphelins.

**Returns:**
com.aspose.psd.Point[] - les points qui n'appartiennent plus à aucun objet (facultatif).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Obtient la précision de la méthode de segmentation (facultatif).

Valeur : la précision de la méthode de segmentation (facultatif).

**Returns:**
double - la précision de la méthode de segmentation (facultatif).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Définit le nombre maximal d'itérations.

Valeur: Le nombre maximal maximal d'itérations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre maximal d'itérations. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Définit le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière-plan).

Valeur: Le nombre d'objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre d'objets pour séparer l'image initiale (facultatif), la valeur par défaut est 2 (objet et arrière‑plan). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Définit les points qui appartiennent à des objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent à NumberOfObjects objets de l'image initiale. Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur: Les points des objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | les points qui appartiennent à des objets séparés (facultatif) coordonnées NumberOfObjects qui appartiennent à NumberOfObjects objets de l'image initiale. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Définit les rectangles des objets qui appartiennent à des objets séparés (facultatif). Ce paramètre est utilisé pour augmenter la précision de la méthode de segmentation.

Valeur: Les rectangles des objets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | les rectangles des objets qui appartiennent à des objets séparés (facultatif). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Définit les points qui n'appartiennent plus à aucun objet (facultatif). Ce paramètre n'est utilisé que dans le cas d'une re‑segmentation.

Valeur : les points orphelins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | les points qui n'appartiennent plus à aucun objet (facultatif). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Définit la précision de la méthode de segmentation (facultatif).

Valeur : la précision de la méthode de segmentation (facultatif).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | la précision de la méthode de segmentation (facultatif). |

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

