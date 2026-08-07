---
title: "GraphicsPath"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una serie di linee e curve collegate."
type: docs
weight: 50
url: /it/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Rappresenta una serie di linee e curve connesse. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Inizializza una nuova istanza della classe  GraphicsPath . |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Inizializza una nuova istanza della classe  GraphicsPath . |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Inizializza una nuova istanza della classe  GraphicsPath . |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Inizializza una nuova istanza della classe  GraphicsPath . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Aggiunge una nuova figura. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Aggiunge nuove figure. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Aggiunge alla fine il  com.aspose.psd.GraphicsPath  specificato a questo percorso. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Aggiunge alla fine il  com.aspose.psd.GraphicsPath  specificato a questo percorso. |
| [deepClone()](#deepClone--) | Esegue una clonazione profonda di questo percorso grafico. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Converte ogni curva in questo percorso in una sequenza di segmenti di linea connessi. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Applica la trasformazione specificata e poi converte ogni curva in questo  com.aspose.psd.GraphicsPath  in una sequenza di segmenti di linea connessi. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Converte ogni curva in questo  com.aspose.psd.GraphicsPath  in una sequenza di segmenti di linea connessi. |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dell'oggetto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Ottiene i limiti dell'oggetto. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Ottiene le figure del percorso. |
| [getFillMode()](#getFillMode--) | Ottiene un'enumerazione  com.aspose.psd.FillMode  che determina come vengono riempiti gli interni delle forme in questo  com.aspose.psd.GraphicsPath . |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath  nella regione di ritaglio visibile del  com.aspose.psd.graphics  specificato. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath , utilizzando il  com.aspose.psd.graphics  specificato. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Rimuove una figura. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Rimuove figure. |
| [reset()](#reset--) | Svuota il percorso grafico e imposta il  com.aspose.psd.FillMode  su  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Inverte l'ordine di figure, forme e punti in ogni forma di questo  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | Imposta una enumerazione  com.aspose.psd.FillMode  che determina come vengono riempiti gli interni delle forme in questo  com.aspose.psd.GraphicsPath . |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applica la trasformazione specificata alla forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Aggiunge un contorno aggiuntivo al percorso. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Aggiunge un contorno aggiuntivo al  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Sostituisce questo  com.aspose.psd.GraphicsPath  con curve che racchiudono l'area che viene riempita quando questo percorso è disegnato con la penna specificata. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Inizializza una nuova istanza della classe  GraphicsPath .

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Inizializza una nuova istanza della classe  GraphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Le figure da cui inizializzare. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Inizializza una nuova istanza della classe  GraphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Le figure da cui inizializzare. |
| fillMode | int | La modalità di riempimento. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Inizializza una nuova istanza della classe  GraphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillMode | int | La modalità di riempimento. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Aggiunge una nuova figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | La figura da aggiungere. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Aggiunge nuove figure.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Le figure da aggiungere. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Aggiunge alla fine il  com.aspose.psd.GraphicsPath  specificato a questo percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  com.aspose.psd.GraphicsPath  da aggiungere. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Aggiunge alla fine il  com.aspose.psd.GraphicsPath  specificato a questo percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  com.aspose.psd.GraphicsPath  da aggiungere. |
| connect | boolean | Un valore Booleano che specifica se la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore true specifica che la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore false specifica che la prima figura nel percorso aggiunto è separata dall'ultima figura in questo percorso. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Esegue una clonazione profonda di questo percorso grafico.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Converte ogni curva in questo percorso in una sequenza di segmenti di linea connessi.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Applica la trasformazione specificata e poi converte ogni curva in questo  com.aspose.psd.GraphicsPath  in una sequenza di segmenti di linea connessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  con cui trasformare questo  com.aspose.psd.GraphicsPath  prima di appiattirlo. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Converte ogni curva in questo  com.aspose.psd.GraphicsPath  in una sequenza di segmenti di linea connessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  con cui trasformare questo  com.aspose.psd.GraphicsPath  prima di appiattirlo. |
| flatness | float | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita. Un valore di 0.25 è quello predefinito. Ridurre il valore di flatness aumenterà il numero di segmenti lineari nell'approssimazione. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene o imposta i limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.psd/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

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


Ottiene le figure del percorso.

**Returns:**
com.aspose.psd.Figure[] - Le figure del percorso.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Ottiene un'enumerazione  com.aspose.psd.FillMode  che determina come vengono riempiti gli interni delle forme in questo  com.aspose.psd.GraphicsPath .

**Returns:**
int - La modalità di riempimento. Una enumerazione  com.aspose.psd.FillMode  che specifica come vengono riempiti gli interni delle forme in questo  com.aspose.psd.GraphicsPath .
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


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo  com.aspose.psd.GraphicsPath  quando disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo  com.aspose.psd.GraphicsPath  come disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo  com.aspose.psd.GraphicsPath  quando disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  come disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo  com.aspose.psd.GraphicsPath  quando disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  come disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la penna specificata  com.aspose.psd.pen .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo  com.aspose.psd.GraphicsPath  quando disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto (sotto) il contorno di questo  com.aspose.psd.GraphicsPath  quando è disegnato con la  com.aspose.psd.Pen  specificata e utilizzando la  com.aspose.psd.graphics  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.psd/pen) | Il  com.aspose.psd.Pen  da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo  com.aspose.psd.GraphicsPath  come disegnato con il  com.aspose.psd.Pen  specificato; altrimenti, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  che rappresenta il punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  che rappresenta il punto da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  che rappresenta il punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  che rappresenta il punto da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath  nella regione di ritaglio visibile del  com.aspose.psd.graphics  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath , utilizzando il  com.aspose.psd.graphics  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Il  com.aspose.psd.Graphics  per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo  com.aspose.psd.GraphicsPath ; altrimenti, false.
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


Rimuove una figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | La figura da rimuovere. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Rimuove figure.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Le figure da rimuovere. |

### reset() {#reset--}
```
public void reset()
```


Svuota il percorso grafico e imposta il  com.aspose.psd.FillMode  su  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Inverte l'ordine di figure, forme e punti in ogni forma di questo  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Imposta una enumerazione  com.aspose.psd.FillMode  che determina come vengono riempiti gli interni delle forme in questo  com.aspose.psd.GraphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di riempimento. |

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


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La trasformazione da applicare. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di strutture  com.aspose.psd.PointF  che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da  srcRect . L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  che rappresenta il rettangolo trasformato nel parallelogramma definito da  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di strutture  com.aspose.psd.PointF  che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da  srcRect . L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  che rappresenta il rettangolo trasformato nel parallelogramma definito da  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  che specifica una trasformazione geometrica da applicare al percorso. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di strutture  com.aspose.psd.PointF  che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da  srcRect . L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  che rappresenta il rettangolo trasformato nel parallelogramma definito da  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  che specifica una trasformazione geometrica da applicare al percorso. |
| warpMode | int | Una enumerazione  com.aspose.psd.WarpMode  che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Un array di strutture  com.aspose.psd.PointF  che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da  srcRect . L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Un  com.aspose.psd.RectangleF  che rappresenta il rettangolo trasformato nel parallelogramma definito da  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  che specifica una trasformazione geometrica da applicare al percorso. |
| warpMode | int | Una enumerazione  com.aspose.psd.WarpMode  che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |
| flatness | float | Un valore da 0 a 1 che specifica quanto è piatto il percorso risultante. Per ulteriori informazioni, vedere i metodi  com.aspose.psd.GraphicsPath.flatten . |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Aggiunge un contorno aggiuntivo al percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Una  com.aspose.psd.Pen  che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Aggiunge un contorno aggiuntivo al  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Una  com.aspose.psd.Pen  che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  che specifica una trasformazione da applicare al percorso prima dell'allargamento. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Sostituisce questo  com.aspose.psd.GraphicsPath  con curve che racchiudono l'area che viene riempita quando questo percorso è disegnato con la penna specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Una  com.aspose.psd.Pen  che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Una  com.aspose.psd.Matrix  che specifica una trasformazione da applicare al percorso prima dell'allargamento. |
| flatness | float | Un valore che specifica la piattezza per le curve. |

