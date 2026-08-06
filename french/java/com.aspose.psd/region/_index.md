---
title: "Region"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins."
type: docs
weight: 90
url: /fr/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Region()](#Region--) | Initialise un nouveau  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Initialise un nouveau  T:Aspose.Imaging.Region  à partir de la structure  T:Aspose.Imaging.RectangleF  spécifiée. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Initialise un nouveau  T:Aspose.Imaging.Region  à partir de la structure  T:Aspose.Imaging.Rectangle  spécifiée. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Initialise un nouveau  T:Aspose.Imaging.Region  avec le  T:Aspose.Imaging.GraphicsPath  spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Met à jour ce  com.aspose.psd.Region  pour contenir la partie du  com.aspose.psd.GraphicsPath  spécifié qui n'intersecte pas avec ce  com.aspose.psd.region. |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Met à jour ce  com.aspose.psd.Region  pour contenir la partie de la structure  com.aspose.psd.Rectangle  spécifiée qui n'intersecte pas avec ce  com.aspose.psd.region. |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Met à jour ce  com.aspose.psd.Region  pour contenir la partie de la structure  com.aspose.psd.RectangleF  spécifiée qui n'intersecte pas avec ce  com.aspose.psd.region. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Met à jour ce  com.aspose.psd.Region  pour contenir la partie du  com.aspose.psd.Region  spécifié qui n'intersecte pas avec ce  com.aspose.psd.region. |
| [deepClone()](#deepClone--) | Crée une copie profonde exacte de ce  com.aspose.psd.region. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n'intersecte pas avec le  com.aspose.psd.graphicsPath  spécifié. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n'intersecte pas avec la structure  com.aspose.psd.Rectangle  spécifiée. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n'intersecte pas avec la structure  com.aspose.psd.RectangleF  spécifiée. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n’intersecte pas avec le  com.aspose.psd.region  spécifié . |
| [getActions_internalized()](#getActions-internalized--) | Obtient les actions de la région. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec le  com.aspose.psd.graphicsPath  spécifié . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec la structure  com.aspose.psd.Rectangle  spécifiée. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec la structure  com.aspose.psd.RectangleF  spécifiée. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec le  com.aspose.psd.region  spécifié. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Teste si ce  com.aspose.psd.Region  a un intérieur vide sur la surface de dessin spécifiée. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Teste si le  com.aspose.psd.Region  spécifié est identique à ce  com.aspose.psd.Region  sur la surface de dessin spécifiée. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Teste si ce  com.aspose.psd.Region  a un intérieur infini sur la surface de dessin spécifiée. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Teste si la structure  com.aspose.psd.Point  spécifiée est contenue dans ce  com.aspose.psd.region . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Teste si la structure  com.aspose.psd.Point  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Teste si la structure  com.aspose.psd.PointF  spécifiée est contenue dans ce  com.aspose.psd.region . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Teste si la structure  com.aspose.psd.PointF  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Teste si une partie de la structure  com.aspose.psd.Rectangle  spécifiée est contenue dans ce  com.aspose.psd.region . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Teste si une partie de la structure  com.aspose.psd.Rectangle  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Teste si une partie de la structure  com.aspose.psd.RectangleF  spécifiée est contenue dans ce  com.aspose.psd.region . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Teste si une partie de la structure  com.aspose.psd.RectangleF  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Teste si le point spécifié est contenu dans ce  com.aspose.psd.region . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Teste si le point spécifié est contenu dans ce  com.aspose.psd.Region  lorsqu’il est dessiné avec le  com.aspose.psd.graphics  spécifié. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region  lorsqu’il est dessiné avec le  com.aspose.psd.graphics  spécifié. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Teste si le point spécifié est contenu dans cet objet  com.aspose.psd.Region  lorsqu’il est dessiné avec l’objet  com.aspose.psd.Graphics  spécifié. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region  lorsqu’il est dessiné avec le  com.aspose.psd.graphics  spécifié. |
| [makeEmpty()](#makeEmpty--) | Initialise ce  com.aspose.psd.Region  avec un intérieur vide. |
| [makeInfinite()](#makeInfinite--) | Initialise cet objet  com.aspose.psd.Region  avec un intérieur infini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Obtient ou définit la région lors du changement. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Transforme ce  com.aspose.psd.Region  par la  com.aspose.psd.matrix  spécifiée . |
| [translate(float dx, float dy)](#translate-float-float-) | Décale les coordonnées de ce  com.aspose.psd.Region  du montant spécifié . |
| [translate(int dx, int dy)](#translate-int-int-) | Décale les coordonnées de ce  com.aspose.psd.Region  du montant spécifié . |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et du  com.aspose.psd.graphicsPath  spécifié . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et de la structure  com.aspose.psd.Rectangle  spécifiée . |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et de la structure  com.aspose.psd.RectangleF  spécifiée . |
| [union(Region region)](#union-com.aspose.psd.Region-) | Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et du  com.aspose.psd.region  spécifié . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec le  com.aspose.psd.graphicsPath  spécifié . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec la structure  com.aspose.psd.Rectangle  spécifiée . |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec la structure  com.aspose.psd.RectangleF  spécifiée . |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec le  com.aspose.psd.region  spécifié . |
### Region() {#Region--}
```
public Region()
```


Initialise un nouveau  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Initialise un nouveau  T:Aspose.Imaging.Region  à partir de la structure  T:Aspose.Imaging.RectangleF  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Une structure  T:Aspose.Imaging.RectangleF  qui définit l'intérieur du nouveau  T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Initialise un nouveau  T:Aspose.Imaging.Region  à partir de la structure  T:Aspose.Imaging.Rectangle  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Une structure  T:Aspose.Imaging.Rectangle  qui définit l'intérieur du nouveau  T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialise un nouveau  T:Aspose.Imaging.Region  avec le  T:Aspose.Imaging.GraphicsPath  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un  T:Aspose.Imaging.GraphicsPath  qui définit le nouveau  T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Met à jour ce  com.aspose.psd.Region  pour contenir la partie du  com.aspose.psd.GraphicsPath  spécifié qui n'intersecte pas avec ce  com.aspose.psd.region.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le  com.aspose.psd.GraphicsPath  pour compléter ce  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Met à jour ce  com.aspose.psd.Region  pour contenir la partie de la structure  com.aspose.psd.Rectangle  spécifiée qui n'intersecte pas avec ce  com.aspose.psd.region.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La structure  com.aspose.psd.Rectangle  pour compléter ce  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Met à jour ce  com.aspose.psd.Region  pour contenir la partie de la structure  com.aspose.psd.RectangleF  spécifiée qui n'intersecte pas avec ce  com.aspose.psd.region.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La structure  com.aspose.psd.RectangleF  pour compléter ce  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Met à jour ce  com.aspose.psd.Region  pour contenir la partie du  com.aspose.psd.Region  spécifié qui n'intersecte pas avec ce  com.aspose.psd.region.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | L'objet  com.aspose.psd.Region  pour compléter cet objet  com.aspose.psd.Region . |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crée une copie profonde exacte de ce  com.aspose.psd.region.

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n'intersecte pas avec le  com.aspose.psd.graphicsPath  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le  com.aspose.psd.GraphicsPath  à exclure de ce  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n'intersecte pas avec la structure  com.aspose.psd.Rectangle  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La structure  com.aspose.psd.Rectangle  à exclure de ce  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n'intersecte pas avec la structure  com.aspose.psd.RectangleF  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La structure  com.aspose.psd.RectangleF  à exclure de ce  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Met à jour ce  com.aspose.psd.Region  pour ne contenir que la partie de son intérieur qui n’intersecte pas avec le  com.aspose.psd.region  spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Le  com.aspose.psd.Region  à exclure de ce  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Obtient les actions de la région.

**Returns:**
com.aspose.internal.RegionAction[] - Les actions de région .
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
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec le  com.aspose.psd.graphicsPath  spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le  com.aspose.psd.GraphicsPath  à intersecter avec ce  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec la structure  com.aspose.psd.Rectangle  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La structure  com.aspose.psd.Rectangle  à intersecter avec ce  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec la structure  com.aspose.psd.RectangleF  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La structure  com.aspose.psd.RectangleF  à intersecter avec ce  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Met à jour ce  com.aspose.psd.Region  à l’intersection de lui‑même avec le  com.aspose.psd.region  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Le  com.aspose.psd.Region  à intersecter avec ce  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Teste si ce  com.aspose.psd.Region  a un intérieur vide sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente une surface de dessin. |

**Returns:**
booléen - vrai si l'intérieur de ce  com.aspose.psd.Region  est vide lorsque la transformation associée à  g  est appliquée ; sinon, faux.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Teste si le  com.aspose.psd.Region  spécifié est identique à ce  com.aspose.psd.Region  sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Le  com.aspose.psd.Region  à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente une surface de dessin. |

**Returns:**
booléen - Vrai si l'intérieur de la région est identique à l'intérieur de cette région lorsque la transformation associée au paramètre  g  est appliquée ; sinon, faux.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Teste si ce  com.aspose.psd.Region  a un intérieur infini sur la surface de dessin spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente une surface de dessin. |

**Returns:**
booléen - vrai si l'intérieur de ce  com.aspose.psd.Region  est infini lorsque la transformation associée à  g  est appliquée ; sinon, faux.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Teste si la structure  com.aspose.psd.Point  spécifiée est contenue dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | La structure  com.aspose.psd.Point  à tester. |

**Returns:**
booléen - vrai lorsque  point  est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Teste si la structure  com.aspose.psd.Point  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | La structure  com.aspose.psd.Point  à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque  point  est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Teste si la structure  com.aspose.psd.PointF  spécifiée est contenue dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | La structure  com.aspose.psd.PointF  à tester. |

**Returns:**
booléen - vrai lorsque  point  est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Teste si la structure  com.aspose.psd.PointF  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | La structure  com.aspose.psd.PointF  à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque  point  est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Teste si une partie de la structure  com.aspose.psd.Rectangle  spécifiée est contenue dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La structure  com.aspose.psd.Rectangle  à tester. |

**Returns:**
booléen - Cette méthode renvoie vrai lorsque n'importe quelle partie de  rect  est contenue dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Teste si une partie de la structure  com.aspose.psd.Rectangle  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La structure  com.aspose.psd.Rectangle  à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie du  rect  est contenue dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Teste si une partie de la structure  com.aspose.psd.RectangleF  spécifiée est contenue dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La structure  com.aspose.psd.RectangleF  à tester. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie de  rect  est contenue dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Teste si une partie de la structure  com.aspose.psd.RectangleF  spécifiée est contenue dans ce  com.aspose.psd.Region  lorsqu’elle est dessinée avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La structure  com.aspose.psd.RectangleF  à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque  rect  est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Teste si le point spécifié est contenu dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
booléen - Vrai lorsque le point spécifié est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Teste si le point spécifié est contenu dans ce  com.aspose.psd.Region  lorsqu’il est dessiné avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - Vrai lorsque le point spécifié est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | float | La largeur du rectangle à tester. |
| hauteur | float | La hauteur du rectangle à tester. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet  com.aspose.psd.Region ; sinon, faux.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region  lorsqu’il est dessiné avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | float | La largeur du rectangle à tester. |
| hauteur | float | La hauteur du rectangle à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Teste si le point spécifié est contenu dans cet objet  com.aspose.psd.Region  lorsqu’il est dessiné avec l’objet  com.aspose.psd.Graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque le point spécifié est contenu dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.region .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | int | La largeur du rectangle à tester. |
| hauteur | int | La hauteur du rectangle à tester. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region ; sinon, faux.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Teste si une partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region  lorsqu’il est dessiné avec le  com.aspose.psd.graphics  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| largeur | int | La largeur du rectangle à tester. |
| hauteur | int | La hauteur du rectangle à tester. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  qui représente un contexte graphique. |

**Returns:**
booléen - vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans ce  com.aspose.psd.Region ; sinon, faux.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialise ce  com.aspose.psd.Region  avec un intérieur vide.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialise cet objet  com.aspose.psd.Region  avec un intérieur infini.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Obtient ou définit la région lors du changement.

Valeur : La région lors du changement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Transforme ce  com.aspose.psd.Region  par la  com.aspose.psd.matrix  spécifiée .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  com.aspose.psd.Matrix  par laquelle transformer cette  com.aspose.psd.region . |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Décale les coordonnées de ce  com.aspose.psd.Region  du montant spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La quantité pour décaler horizontalement cette  com.aspose.psd.Region . |
| dy | float | La quantité pour décaler verticalement cette  com.aspose.psd.Region . |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Décale les coordonnées de ce  com.aspose.psd.Region  du montant spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | int | La quantité pour décaler horizontalement cette  com.aspose.psd.Region . |
| dy | int | La quantité pour décaler verticalement cette  com.aspose.psd.Region . |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et du  com.aspose.psd.graphicsPath  spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le  com.aspose.psd.GraphicsPath  à unir avec cette  com.aspose.psd.region . |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et de la structure  com.aspose.psd.Rectangle  spécifiée .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La  com.aspose.psd.Rectangle  structure à unir avec cette  com.aspose.psd.region . |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et de la structure  com.aspose.psd.RectangleF  spécifiée .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  structure à unir avec cette  com.aspose.psd.region . |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Met à jour ce  com.aspose.psd.Region  à l'union de lui-même et du  com.aspose.psd.region  spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Le  com.aspose.psd.Region  à unir avec cette  com.aspose.psd.region . |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec le  com.aspose.psd.graphicsPath  spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Le  com.aspose.psd.GraphicsPath  à xor avec cette  com.aspose.psd.region . |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec la structure  com.aspose.psd.Rectangle  spécifiée .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La  com.aspose.psd.Rectangle  structure à xor avec cette  com.aspose.psd.region . |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec la structure  com.aspose.psd.RectangleF  spécifiée .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  structure à xor avec cette  com.aspose.psd.region . |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Met à jour ce  com.aspose.psd.Region  à l'union moins l'intersection de lui-même avec le  com.aspose.psd.region  spécifié .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Le  com.aspose.psd.Region  à xor avec cette  com.aspose.psd.region . |

