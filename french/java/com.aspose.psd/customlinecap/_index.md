---
title: "CustomLineCap"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Encapsule une extrémité de ligne personnalisée définie par l'utilisateur."
type: docs
weight: 34
url: /fr/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Encapsule une extrémité de ligne personnalisée définie par l'utilisateur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Initialise une nouvelle instance de la classe  CustomLineCap  avec le contour et le remplissage spécifiés. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Initialise une nouvelle instance de la classe  CustomLineCap  à partir de l'énumération  LineCap  existante spécifiée avec le contour et le remplissage spécifiés. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Initialise une nouvelle instance de la classe  CustomLineCap  à partir de l'énumération  LineCap  existante spécifiée avec le contour, le remplissage et le retrait spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Obtient l'énumération  LineCap  sur laquelle ce  CustomLineCap  est basé. |
| [getBaseInset()](#getBaseInset--) | Obtient la distance entre le cap et la ligne. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Obtient l'objet qui définit le remplissage du capuchon personnalisé. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Obtient les caps utilisés pour démarrer et terminer les lignes qui composent ce capuchon personnalisé. |
| [getStrokeJoin()](#getStrokeJoin--) | Obtient l'énumération  LineJoin  qui détermine comment les lignes qui composent cet objet  CustomLineCap  sont jointes. |
| [getStrokePath()](#getStrokePath--) | Obtient l'objet qui définit le contour du capuchon personnalisé. |
| [getWidthScale()](#getWidthScale--) | Obtient la quantité par laquelle mettre à l'échelle cet objet de classe  CustomLineCap  par rapport à la largeur de l'objet  System.Drawing.Pen  . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Définit l'énumération  LineCap  sur laquelle ce  CustomLineCap  est basé. |
| [setBaseInset(float value)](#setBaseInset-float-) | Définit la distance entre le cap et la ligne. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Définit l'objet qui définit le remplissage du capuchon personnalisé. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Définit les caps utilisés pour démarrer et terminer les lignes qui composent ce capuchon personnalisé. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Définit l'énumération  LineJoin  qui détermine comment les lignes qui composent cet objet  CustomLineCap  sont jointes. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Définit l'objet qui définit le contour du capuchon personnalisé. |
| [setWidthScale(float value)](#setWidthScale-float-) | Définit la quantité par laquelle mettre à l'échelle cet objet de classe  CustomLineCap  par rapport à la largeur de l'objet  System.Drawing.Pen  . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialise une nouvelle instance de la classe  CustomLineCap  avec le contour et le remplissage spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objet  GraphicsPath  qui définit le remplissage du capuchon personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objet  GraphicsPath  qui définit le contour du capuchon personnalisé. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialise une nouvelle instance de la classe  CustomLineCap  à partir de l'énumération  LineCap  existante spécifiée avec le contour et le remplissage spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objet  GraphicsPath  qui définit le remplissage du capuchon personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objet  GraphicsPath  qui définit le contour du capuchon personnalisé. |
| baseCap | int | Le cap de ligne à partir duquel créer le capuchon personnalisé. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialise une nouvelle instance de la classe  CustomLineCap  à partir de l'énumération  LineCap  existante spécifiée avec le contour, le remplissage et le retrait spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objet  GraphicsPath  qui définit le remplissage du capuchon personnalisé. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objet  GraphicsPath  qui définit le contour du capuchon personnalisé. |
| baseCap | int | Le cap de ligne à partir duquel créer le capuchon personnalisé. |
| baseInset | float | La distance entre le cap et la ligne. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Obtient l'énumération  LineCap  sur laquelle ce  CustomLineCap  est basé.

**Returns:**
int - L'énumération  LineCap  sur laquelle ce  CustomLineCap  est basé.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Obtient la distance entre le cap et la ligne.

**Returns:**
float - La distance entre le début du cap et la fin de la ligne.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Obtient l'objet qui définit le remplissage du capuchon personnalisé.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Obtient les caps utilisés pour démarrer et terminer les lignes qui composent ce capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int[] | L'énumération  LineCap  utilisée au début d'une ligne dans ce cap. |
| endCap | int[] | L'énumération  LineCap  utilisée à la fin d'une ligne dans ce cap. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Obtient l'énumération  LineJoin  qui détermine comment les lignes qui composent cet objet  CustomLineCap  sont jointes.

**Returns:**
int - L'énumération  LineJoin  que cet objet  CustomLineCap  utilise pour joindre les lignes.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Obtient l'objet qui définit le contour du capuchon personnalisé.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtient la quantité par laquelle mettre à l'échelle cet objet de classe  CustomLineCap  par rapport à la largeur de l'objet  System.Drawing.Pen  .

**Returns:**
float - La quantité par laquelle le cap est mis à l'échelle.
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Définit l'énumération  LineCap  sur laquelle ce  CustomLineCap  est basé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'énumération  LineCap  sur laquelle ce  CustomLineCap  est basé. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Définit la distance entre le cap et la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La distance entre le début du cap et la fin de la ligne. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Définit l'objet qui définit le remplissage du capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | L'objet qui définit le remplissage du cap personnalisé. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Définit les caps utilisés pour démarrer et terminer les lignes qui composent ce capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int | L'énumération  LineCap  utilisée au début d'une ligne dans ce cap. |
| endCap | int | L'énumération  LineCap  utilisée à la fin d'une ligne dans ce cap. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Définit l'énumération  LineJoin  qui détermine comment les lignes qui composent cet objet  CustomLineCap  sont jointes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'énumération  LineJoin  que cet objet  CustomLineCap  utilise pour joindre les lignes. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Définit l'objet qui définit le contour du capuchon personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | L'objet qui définit le contour du cap personnalisé. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Définit la quantité par laquelle mettre à l'échelle cet objet de classe  CustomLineCap  par rapport à la largeur de l'objet  System.Drawing.Pen  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La quantité par laquelle le cap est mis à l'échelle. |

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

