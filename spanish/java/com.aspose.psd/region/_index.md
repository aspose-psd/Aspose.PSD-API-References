---
title: "Region"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Describe el interior de una forma gráfica compuesta por rectángulos y rutas."
type: docs
weight: 90
url: /es/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Describe el interior de una forma gráfica compuesta de rectángulos y rutas. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Region()](#Region--) | Inicializa un nuevo  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Inicializa un nuevo  T:Aspose.Imaging.Region  a partir de la estructura  T:Aspose.Imaging.RectangleF  especificada. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Inicializa un nuevo  T:Aspose.Imaging.Region  a partir de la estructura  T:Aspose.Imaging.Rectangle  especificada. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Inicializa un nuevo  T:Aspose.Imaging.Region  con el  T:Aspose.Imaging.GraphicsPath  especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Actualiza este  com.aspose.psd.Region  para contener la porción del  com.aspose.psd.GraphicsPath  especificado que no intersecta con este  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Actualiza este  com.aspose.psd.Region  para contener la porción de la estructura  com.aspose.psd.Rectangle  especificada que no intersecta con este  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Actualiza este  com.aspose.psd.Region  para que contenga la porción de la estructura  com.aspose.psd.RectangleF  especificada que no intersecta con este  com.aspose.psd.region . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Actualiza este  com.aspose.psd.Region  para que contenga la porción del  com.aspose.psd.Region  especificado que no intersecta con este  com.aspose.psd.region . |
| [deepClone()](#deepClone--) | Crea una copia profunda exacta de este  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con el  com.aspose.psd.graphicsPath  especificado . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con la estructura  com.aspose.psd.Rectangle  especificada. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con la estructura  com.aspose.psd.RectangleF  especificada. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con el  com.aspose.psd.region  especificado. |
| [getActions_internalized()](#getActions-internalized--) | Obtiene las acciones de la región. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con el  com.aspose.psd.graphicsPath  especificado. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con la estructura  com.aspose.psd.Rectangle  especificada. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con la estructura  com.aspose.psd.RectangleF  especificada. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con el  com.aspose.psd.region  especificado. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Comprueba si este  com.aspose.psd.Region  tiene un interior vacío en la superficie de dibujo especificada. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Comprueba si el  com.aspose.psd.Region  especificado es idéntico a este  com.aspose.psd.Region  en la superficie de dibujo especificada. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Comprueba si este  com.aspose.psd.Region  tiene un interior infinito en la superficie de dibujo especificada. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Comprueba si la estructura  com.aspose.psd.Point  especificada está contenida dentro de este  com.aspose.psd.region . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Comprueba si la estructura  com.aspose.psd.Point  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Comprueba si la estructura  com.aspose.psd.PointF  especificada está contenida dentro de este  com.aspose.psd.region . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Comprueba si la estructura  com.aspose.psd.PointF  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Comprueba si alguna porción de la estructura  com.aspose.psd.Rectangle  especificada está contenida dentro de este  com.aspose.psd.region . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Comprueba si alguna porción de la estructura  com.aspose.psd.Rectangle  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Comprueba si alguna porción de la estructura  com.aspose.psd.RectangleF  especificada está contenida dentro de este  com.aspose.psd.region . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Comprueba si alguna porción de la estructura  com.aspose.psd.RectangleF  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Comprueba si el punto especificado está contenido dentro de este  com.aspose.psd.region . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Comprueba si el punto especificado está contenido dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Comprueba si el punto especificado está contenido dentro de este  com.aspose.psd.Region  objeto cuando se dibuja usando el objeto  com.aspose.psd.Graphics  especificado. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado. |
| [makeEmpty()](#makeEmpty--) | Inicializa este  com.aspose.psd.Region  con un interior vacío. |
| [makeInfinite()](#makeInfinite--) | Inicializa este objeto  com.aspose.psd.Region  con un interior infinito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Obtiene o establece la región al cambiar. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Transforma este  com.aspose.psd.Region  mediante la  com.aspose.psd.matrix  especificada. |
| [translate(float dx, float dy)](#translate-float-float-) | Desplaza las coordenadas de este  com.aspose.psd.Region  en la cantidad especificada. |
| [translate(int dx, int dy)](#translate-int-int-) | Desplaza las coordenadas de este  com.aspose.psd.Region  en la cantidad especificada. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y el  com.aspose.psd.graphicsPath  especificado. |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y la estructura  com.aspose.psd.Rectangle  especificada. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y la estructura  com.aspose.psd.RectangleF  especificada. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y el  com.aspose.psd.region  especificado. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con el  com.aspose.psd.graphicsPath  especificado. |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con la estructura  com.aspose.psd.Rectangle  especificada. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con la estructura  com.aspose.psd.RectangleF  especificada. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con el  com.aspose.psd.region  especificado. |
### Region() {#Region--}
```
public Region()
```


Inicializa un nuevo  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Inicializa un nuevo  T:Aspose.Imaging.Region  a partir de la estructura  T:Aspose.Imaging.RectangleF  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una estructura  T:Aspose.Imaging.RectangleF  que define el interior del nuevo  T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Inicializa un nuevo  T:Aspose.Imaging.Region  a partir de la estructura  T:Aspose.Imaging.Rectangle  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una estructura  T:Aspose.Imaging.Rectangle  que define el interior del nuevo  T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Inicializa un nuevo  T:Aspose.Imaging.Region  con el  T:Aspose.Imaging.GraphicsPath  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Una  T:Aspose.Imaging.GraphicsPath  que define el nuevo  T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Actualiza este  com.aspose.psd.Region  para contener la porción del  com.aspose.psd.GraphicsPath  especificado que no intersecta con este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | El  com.aspose.psd.GraphicsPath  para complementar este  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Actualiza este  com.aspose.psd.Region  para contener la porción de la estructura  com.aspose.psd.Rectangle  especificada que no intersecta con este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La estructura  com.aspose.psd.Rectangle  para complementar este  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Actualiza este  com.aspose.psd.Region  para que contenga la porción de la estructura  com.aspose.psd.RectangleF  especificada que no intersecta con este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura  com.aspose.psd.RectangleF  para complementar este  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Actualiza este  com.aspose.psd.Region  para que contenga la porción del  com.aspose.psd.Region  especificado que no intersecta con este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | El objeto  com.aspose.psd.Region  para complementar este objeto  com.aspose.psd.Region . |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crea una copia profunda exacta de este  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con el  com.aspose.psd.graphicsPath  especificado .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | El  com.aspose.psd.GraphicsPath  para excluir de este  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con la estructura  com.aspose.psd.Rectangle  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La estructura  com.aspose.psd.Rectangle  para excluir de este  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con la estructura  com.aspose.psd.RectangleF  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  estructura para excluir de este  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Actualiza este  com.aspose.psd.Region  para que contenga solo la porción de su interior que no intersecta con el  com.aspose.psd.region  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | La  com.aspose.psd.Region  para excluir de este  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Obtiene las acciones de la región.

**Returns:**
com.aspose.internal.RegionAction[] - Las acciones de la región.
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


Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con el  com.aspose.psd.graphicsPath  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | La  com.aspose.psd.GraphicsPath  para intersectar con este  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con la estructura  com.aspose.psd.Rectangle  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La  com.aspose.psd.Rectangle  estructura para intersectar con este  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con la estructura  com.aspose.psd.RectangleF  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  estructura para intersectar con este  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Actualiza este  com.aspose.psd.Region  a la intersección de sí mismo con el  com.aspose.psd.region  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | La  com.aspose.psd.Region  para intersectar con este  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Comprueba si este  com.aspose.psd.Region  tiene un interior vacío en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de este  com.aspose.psd.Region  está vacío cuando se aplica la transformación asociada con  g ; de lo contrario, falso.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Comprueba si el  com.aspose.psd.Region  especificado es idéntico a este  com.aspose.psd.Region  en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | La  com.aspose.psd.Region  para probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa una superficie de dibujo. |

**Returns:**
boolean - Verdadero si el interior de la región es idéntico al interior de esta región cuando se aplica la transformación asociada con el parámetro  g ; de lo contrario, falso.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Comprueba si este  com.aspose.psd.Region  tiene un interior infinito en la superficie de dibujo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa una superficie de dibujo. |

**Returns:**
boolean - verdadero si el interior de este  com.aspose.psd.Region  es infinito cuando se aplica la transformación asociada con  g ; de lo contrario, falso.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Comprueba si la estructura  com.aspose.psd.Point  especificada está contenida dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | La  com.aspose.psd.Point  estructura para probar. |

**Returns:**
boolean - verdadero cuando  point  está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Comprueba si la estructura  com.aspose.psd.Point  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | La  com.aspose.psd.Point  estructura para probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando  point  está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Comprueba si la estructura  com.aspose.psd.PointF  especificada está contenida dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | La  com.aspose.psd.PointF  estructura para probar. |

**Returns:**
boolean - verdadero cuando  point  está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Comprueba si la estructura  com.aspose.psd.PointF  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | La  com.aspose.psd.PointF  estructura para probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando  point  está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Comprueba si alguna porción de la estructura  com.aspose.psd.Rectangle  especificada está contenida dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La  com.aspose.psd.Rectangle  estructura para probar. |

**Returns:**
boolean - Este método devuelve verdadero cuando cualquier porción de  rect  está contenida dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Comprueba si alguna porción de la estructura  com.aspose.psd.Rectangle  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La  com.aspose.psd.Rectangle  estructura para probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier porción del  rect  está contenida dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Comprueba si alguna porción de la estructura  com.aspose.psd.RectangleF  especificada está contenida dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  estructura para probar. |

**Returns:**
boolean - verdadero cuando cualquier porción de  rect  está contenida dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Comprueba si alguna porción de la estructura  com.aspose.psd.RectangleF  especificada está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La  com.aspose.psd.RectangleF  estructura para probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando  rect  está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Comprueba si el punto especificado está contenido dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Verdadero cuando el punto especificado está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Comprueba si el punto especificado está contenido dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - Verdadero cuando el punto especificado está contenido dentro de este  com.aspose.psd.Region ; de lo contrario, falso.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo para probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo para probar. |
| ancho | float | El ancho del rectángulo a probar. |
| alto | float | La altura del rectángulo a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto com.aspose.psd.Region; de lo contrario, falso.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo para probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo para probar. |
| ancho | float | El ancho del rectángulo a probar. |
| alto | float | La altura del rectángulo a probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este com.aspose.psd.Region; de lo contrario, falso.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Comprueba si el punto especificado está contenido dentro de este  com.aspose.psd.Region  objeto cuando se dibuja usando el objeto  com.aspose.psd.Graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando el punto especificado está contenido dentro de este com.aspose.psd.Region; de lo contrario, falso.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.region .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo para probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo para probar. |
| ancho | int | El ancho del rectángulo a probar. |
| alto | int | La altura del rectángulo a probar. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este com.aspose.psd.Region; de lo contrario, falso.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Comprueba si alguna parte del rectángulo especificado está contenida dentro de este  com.aspose.psd.Region  cuando se dibuja usando el  com.aspose.psd.graphics  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo para probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo para probar. |
| ancho | int | El ancho del rectángulo a probar. |
| alto | int | La altura del rectángulo a probar. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un  com.aspose.psd.Graphics  que representa un contexto gráfico. |

**Returns:**
boolean - verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este com.aspose.psd.Region; de lo contrario, falso.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Inicializa este  com.aspose.psd.Region  con un interior vacío.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Inicializa este objeto  com.aspose.psd.Region  con un interior infinito.

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


Obtiene o establece la región al cambiar.

Valor: La región al cambiar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.ChangeActionList |  |

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


Transforma este  com.aspose.psd.Region  mediante la  com.aspose.psd.matrix  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La com.aspose.psd.Matrix por la cual transformar esta com.aspose.psd.region. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Desplaza las coordenadas de este  com.aspose.psd.Region  en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | La cantidad para desplazar horizontalmente este com.aspose.psd.Region. |
| dy | float | La cantidad para desplazar verticalmente este com.aspose.psd.Region. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Desplaza las coordenadas de este  com.aspose.psd.Region  en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | int | La cantidad para desplazar horizontalmente este com.aspose.psd.Region. |
| dy | int | La cantidad para desplazar verticalmente este com.aspose.psd.Region. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y el  com.aspose.psd.graphicsPath  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | El com.aspose.psd.GraphicsPath para unir con esta com.aspose.psd.region. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y la estructura  com.aspose.psd.Rectangle  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle para unir con esta com.aspose.psd.region. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y la estructura  com.aspose.psd.RectangleF  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura com.aspose.psd.RectangleF para unir con esta com.aspose.psd.region. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Actualiza este  com.aspose.psd.Region  a la unión de sí mismo y el  com.aspose.psd.region  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | El com.aspose.psd.Region para unir con esta com.aspose.psd.region. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con el  com.aspose.psd.graphicsPath  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | El com.aspose.psd.GraphicsPath para xor con esta com.aspose.psd.region. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con la estructura  com.aspose.psd.Rectangle  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle para xor con esta com.aspose.psd.region. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con la estructura  com.aspose.psd.RectangleF  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura com.aspose.psd.RectangleF para xor con esta com.aspose.psd.region. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Actualiza este  com.aspose.psd.Region  a la unión menos la intersección de sí mismo con el  com.aspose.psd.region  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | El com.aspose.psd.Region para xor con esta com.aspose.psd.region. |

