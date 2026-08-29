---
title: "GraphicsPath"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa una serie de líneas y curvas conectadas."
type: docs
weight: 50
url: /es/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Representa una serie de líneas y curvas conectadas. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Inicializa una nueva instancia de la clase  GraphicsPath  . |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Inicializa una nueva instancia de la clase  GraphicsPath  . |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Inicializa una nueva instancia de la clase  GraphicsPath  . |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Inicializa una nueva instancia de la clase  GraphicsPath  . |
## Métodos

| Método | Descripción |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Agrega una nueva figura. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Agrega nuevas figuras. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Añade el  com.aspose.psd.GraphicsPath  especificado a esta ruta. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Añade el  com.aspose.psd.GraphicsPath  especificado a esta ruta. |
| [deepClone()](#deepClone--) | Realiza una clonación profunda de esta ruta gráfica. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Convierte cada curva en esta ruta en una secuencia de segmentos de línea conectados. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Aplica la transformación especificada y luego convierte cada curva en este  com.aspose.psd.GraphicsPath  en una secuencia de segmentos de línea conectados. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Convierte cada curva en este  com.aspose.psd.GraphicsPath  en una secuencia de segmentos de línea conectados. |
| [getBounds()](#getBounds--) | Obtiene o establece los límites del objeto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtiene los límites del objeto. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Obtiene las figuras de la ruta. |
| [getFillMode()](#getFillMode--) | Obtiene una enumeración  com.aspose.psd.FillMode  que determina cómo se rellenan los interiores de las formas en este  com.aspose.psd.GraphicsPath . |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath  en la región de recorte visible del  com.aspose.psd.graphics  especificado. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Indica si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath , usando el  com.aspose.psd.graphics  especificado. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Elimina una figura. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Elimina figuras. |
| [reset()](#reset--) | Vacía la ruta gráfica y establece el  com.aspose.psd.FillMode  a  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Invierte el orden de figuras, formas y puntos en cada forma de este  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | Establece una enumeración  com.aspose.psd.FillMode  que determina cómo se rellenan los interiores de las formas en este  com.aspose.psd.GraphicsPath . |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Aplica la transformación especificada a la forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Añade un contorno adicional a la ruta. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Añade un contorno adicional al  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Reemplaza este  com.aspose.psd.GraphicsPath  con curvas que encierran el área que se rellena cuando esta ruta se dibuja con la pluma especificada. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Inicializa una nueva instancia de la clase  GraphicsPath  .

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Inicializa una nueva instancia de la clase  GraphicsPath  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Las figuras desde las que inicializar. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Inicializa una nueva instancia de la clase  GraphicsPath  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Las figuras desde las que inicializar. |
| fillMode | int | El modo de relleno. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Inicializa una nueva instancia de la clase  GraphicsPath  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillMode | int | El modo de relleno. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Agrega una nueva figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | La figura a añadir. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Agrega nuevas figuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Las figuras a añadir. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Añade el  com.aspose.psd.GraphicsPath  especificado a esta ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | El  com.aspose.psd.GraphicsPath  a añadir. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Añade el  com.aspose.psd.GraphicsPath  especificado a esta ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | El  com.aspose.psd.GraphicsPath  a añadir. |
| connect | boolean | Un valor Booleano que especifica si la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor true indica que la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor false indica que la primera figura en la ruta añadida es independiente de la última figura en esta ruta. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Realiza una clonación profunda de esta ruta gráfica.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Convierte cada curva en esta ruta en una secuencia de segmentos de línea conectados.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Aplica la transformación especificada y luego convierte cada curva en este  com.aspose.psd.GraphicsPath  en una secuencia de segmentos de línea conectados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  mediante la cual transformar este  com.aspose.psd.GraphicsPath  antes de aplanarlo. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Convierte cada curva en este  com.aspose.psd.GraphicsPath  en una secuencia de segmentos de línea conectados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  mediante la cual transformar este  com.aspose.psd.GraphicsPath  antes de aplanarlo. |
| flatness | float | Especifica el error máximo permitido entre la curva y su aproximación aplanada. Un valor de 0.25 es el predeterminado. Reducir el valor de flatness aumentará el número de segmentos de línea en la aproximación. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene o establece los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matriz a aplicar antes de que se calculen los límites. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](../../com.aspose.psd/pen) | El bolígrafo a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Obtiene las figuras de la ruta.

**Returns:**
com.aspose.psd.Figure[] - Las figuras de la ruta.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Obtiene una enumeración  com.aspose.psd.FillMode  que determina cómo se rellenan los interiores de las formas en este  com.aspose.psd.GraphicsPath .

**Returns:**
int - El modo de relleno. Una enumeración  com.aspose.psd.FillMode  que especifica cómo se rellenan los interiores de las formas en este  com.aspose.psd.GraphicsPath .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este  com.aspose.psd.GraphicsPath  tal como se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este  com.aspose.psd.GraphicsPath  tal como se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este  com.aspose.psd.GraphicsPath  tal como se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.pen  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (debajo) del contorno de este  com.aspose.psd.GraphicsPath  cuando se dibuja con el  com.aspose.psd.Pen  especificado y usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.psd/pen) | El  com.aspose.psd.Pen  a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este  com.aspose.psd.GraphicsPath  tal como se dibuja con el  com.aspose.psd.Pen  especificado; de lo contrario, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  que representa el punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  que representa el punto a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  que representa el punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  que representa el punto a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de esto; de lo contrario, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath  en la región de recorte visible del  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath , usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | El  com.aspose.psd.Graphics  para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este  com.aspose.psd.GraphicsPath ; de lo contrario, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Elimina una figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | La figura a eliminar. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Elimina figuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Las figuras a eliminar. |

### reset() {#reset--}
```
public void reset()
```


Vacía la ruta gráfica y establece el  com.aspose.psd.FillMode  a  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Invierte el orden de figuras, formas y puntos en cada forma de este  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Establece una enumeración  com.aspose.psd.FillMode  que determina cómo se rellenan los interiores de las formas en este  com.aspose.psd.GraphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de relleno. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Aplica la transformación especificada a la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La transformación a aplicar. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de estructuras  com.aspose.psd.PointF  que definen un paralelogramo al que se transforma el rectángulo definido por  srcRect . La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  que representa el rectángulo que se transforma al paralelogramo definido por  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de estructuras  com.aspose.psd.PointF  que definen un paralelogramo al que se transforma el rectángulo definido por  srcRect . La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  que representa el rectángulo que se transforma al paralelogramo definido por  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  que especifica una transformación geométrica para aplicar a la ruta. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de estructuras  com.aspose.psd.PointF  que define un paralelogramo al que se transforma el rectángulo definido por  srcRect . La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  que representa el rectángulo que se transforma al paralelogramo definido por  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  que especifica una transformación geométrica para aplicar a la ruta. |
| warpMode | int | Una enumeración  com.aspose.psd.WarpMode  que especifica si esta operación de deformación usa modo perspectiva o bilineal. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de estructuras  com.aspose.psd.PointF  que definen un paralelogramo al que se transforma el rectángulo definido por  srcRect . La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los primeros tres puntos. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  que representa el rectángulo que se transforma al paralelogramo definido por  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  que especifica una transformación geométrica para aplicar a la ruta. |
| warpMode | int | Una enumeración  com.aspose.psd.WarpMode  que especifica si esta operación de deformación usa modo perspectiva o bilineal. |
| flatness | float | Un valor de 0 a 1 que especifica cuán plana es la ruta resultante. Para más información, consulte los métodos  com.aspose.psd.GraphicsPath.flatten . |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Añade un contorno adicional a la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  com.aspose.psd.Pen  que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Añade un contorno adicional al  com.aspose.psd.graphicsPath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  com.aspose.psd.Pen  que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  que especifica una transformación para aplicar a la ruta antes de ensancharla. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Reemplaza este  com.aspose.psd.GraphicsPath  con curvas que encierran el área que se rellena cuando esta ruta se dibuja con la pluma especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Un  com.aspose.psd.Pen  que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  que especifica una transformación para aplicar a la ruta antes de ensancharla. |
| flatness | float | Un valor que especifica la planitud para curvas. |

