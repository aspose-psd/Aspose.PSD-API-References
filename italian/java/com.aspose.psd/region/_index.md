---
title: "Region"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Descrive l'interno di una forma grafica composta da rettangoli e percorsi."
type: docs
weight: 90
url: /it/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Region()](#Region--) | Inizializza un nuovo  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Inizializza un nuovo  T:Aspose.Imaging.Region  dalla struttura  T:Aspose.Imaging.RectangleF  specificata. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Inizializza un nuovo  T:Aspose.Imaging.Region  dalla struttura  T:Aspose.Imaging.Rectangle  specificata. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Inizializza un nuovo  T:Aspose.Imaging.Region  con il  T:Aspose.Imaging.GraphicsPath  specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Aggiorna questo  com.aspose.psd.Region  per contenere la porzione del  com.aspose.psd.GraphicsPath  specificato che non interseca questo  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Aggiorna questo  com.aspose.psd.Region  per contenere la porzione della struttura  com.aspose.psd.Rectangle  specificata che non interseca questo  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Aggiorna questo com.aspose.psd.Region per contenere la porzione della struttura com.aspose.psd.RectangleF specificata che non interseca questo com.aspose.psd.region. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Aggiorna questo com.aspose.psd.Region per contenere la porzione del com.aspose.psd.Region specificato che non interseca questo com.aspose.psd.region. |
| [deepClone()](#deepClone--) | Crea una copia profonda esatta di questo com.aspose.psd.region. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca il com.aspose.psd.graphicsPath specificato. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca la struttura com.aspose.psd.Rectangle specificata. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca la struttura com.aspose.psd.RectangleF specificata. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca il com.aspose.psd.region specificato. |
| [getActions_internalized()](#getActions-internalized--) | Ottiene le azioni della regione. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Aggiorna questo com.aspose.psd.Region all'intersezione di sé con il com.aspose.psd.graphicsPath specificato. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Aggiorna questo com.aspose.psd.Region all'intersezione di sé con la struttura com.aspose.psd.Rectangle specificata. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Aggiorna questo com.aspose.psd.Region all'intersezione di sé con la struttura com.aspose.psd.RectangleF specificata. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Aggiorna questo com.aspose.psd.Region all'intersezione di sé con il com.aspose.psd.region specificato. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Verifica se questo com.aspose.psd.Region ha un interno vuoto sulla superficie di disegno specificata. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Verifica se il com.aspose.psd.Region specificato è identico a questo com.aspose.psd.Region sulla superficie di disegno specificata. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Verifica se questo com.aspose.psd.Region ha un interno infinito sulla superficie di disegno specificata. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Verifica se la struttura com.aspose.psd.Point specificata è contenuta in questo com.aspose.psd.region. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Verifica se la struttura com.aspose.psd.Point specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Verifica se la struttura com.aspose.psd.PointF specificata è contenuta in questo com.aspose.psd.region. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Verifica se la struttura com.aspose.psd.PointF specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Verifica se qualche porzione della struttura com.aspose.psd.Rectangle specificata è contenuta in questo com.aspose.psd.region. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Verifica se qualche porzione della struttura com.aspose.psd.Rectangle specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Verifica se qualche porzione della struttura com.aspose.psd.RectangleF specificata è contenuta in questo com.aspose.psd.region. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Verifica se qualche porzione della struttura com.aspose.psd.RectangleF specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Verifica se il punto specificato è contenuto in questo com.aspose.psd.region. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Verifica se il punto specificato è contenuto in questo com.aspose.psd.Region quando viene disegnato usando il com.aspose.psd.graphics specificato. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.Region  quando viene disegnata usando la specificata  com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Verifica se il punto specificato è contenuto in questo  com.aspose.psd.Region  oggetto quando viene disegnato usando il specificato  com.aspose.psd.Graphics  oggetto. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.Region  quando viene disegnata usando la specificata  com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Inizializza questo  com.aspose.psd.Region  con un interno vuoto. |
| [makeInfinite()](#makeInfinite--) | Inizializza questo  com.aspose.psd.Region  oggetto con un interno infinito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Ottiene o imposta la regione al cambiamento. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Trasforma questo  com.aspose.psd.Region  con la specificata  com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Sposta le coordinate di questo  com.aspose.psd.Region  dell'importo specificato. |
| [translate(int dx, int dy)](#translate-int-int-) | Sposta le coordinate di questo  com.aspose.psd.Region  dell'importo specificato. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e del specificato  com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e della specificata struttura  com.aspose.psd.Rectangle . |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e della specificata struttura  com.aspose.psd.RectangleF . |
| [union(Region region)](#union-com.aspose.psd.Region-) | Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e del specificato  com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con il specificato  com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con la specificata struttura  com.aspose.psd.Rectangle . |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con la specificata struttura  com.aspose.psd.RectangleF . |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con il specificato  com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Inizializza un nuovo  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Inizializza un nuovo  T:Aspose.Imaging.Region  dalla struttura  T:Aspose.Imaging.RectangleF  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una struttura  T:Aspose.Imaging.RectangleF  che definisce l'interno del nuovo  T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Inizializza un nuovo  T:Aspose.Imaging.Region  dalla struttura  T:Aspose.Imaging.Rectangle  specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una struttura  T:Aspose.Imaging.Rectangle  che definisce l'interno del nuovo  T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Inizializza un nuovo  T:Aspose.Imaging.Region  con il  T:Aspose.Imaging.GraphicsPath  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un  T:Aspose.Imaging.GraphicsPath  che definisce il nuovo  T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Aggiorna questo  com.aspose.psd.Region  per contenere la porzione del  com.aspose.psd.GraphicsPath  specificato che non interseca questo  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  com.aspose.psd.GraphicsPath  per completare questo  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Aggiorna questo  com.aspose.psd.Region  per contenere la porzione della struttura  com.aspose.psd.Rectangle  specificata che non interseca questo  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura  com.aspose.psd.Rectangle  per completare questo  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Aggiorna questo com.aspose.psd.Region per contenere la porzione della struttura com.aspose.psd.RectangleF specificata che non interseca questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  per completare questo  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Aggiorna questo com.aspose.psd.Region per contenere la porzione del com.aspose.psd.Region specificato che non interseca questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | L'oggetto  com.aspose.psd.Region  per completare questo  com.aspose.psd.Region  oggetto. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Crea una copia profonda esatta di questo com.aspose.psd.region.

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca il com.aspose.psd.graphicsPath specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  com.aspose.psd.GraphicsPath  da escludere da questo  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca la struttura com.aspose.psd.Rectangle specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura  com.aspose.psd.Rectangle  da escludere da questo  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca la struttura com.aspose.psd.RectangleF specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura com.aspose.psd.RectangleF da escludere da questo com.aspose.psd.region. |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Aggiorna questo com.aspose.psd.Region per contenere solo la porzione del suo interno che non interseca il com.aspose.psd.region specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Il com.aspose.psd.Region da escludere da questo com.aspose.psd.region. |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Ottiene le azioni della regione.

**Returns:**
com.aspose.internal.RegionAction[] - Le azioni della regione.
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


Aggiorna questo com.aspose.psd.Region all'intersezione di sé con il com.aspose.psd.graphicsPath specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il com.aspose.psd.GraphicsPath da intersecare con questo com.aspose.psd.region. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Aggiorna questo com.aspose.psd.Region all'intersezione di sé con la struttura com.aspose.psd.Rectangle specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle da intersecare con questo com.aspose.psd.region. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Aggiorna questo com.aspose.psd.Region all'intersezione di sé con la struttura com.aspose.psd.RectangleF specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura com.aspose.psd.RectangleF da intersecare con questo com.aspose.psd.region. |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Aggiorna questo com.aspose.psd.Region all'intersezione di sé con il com.aspose.psd.region specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Il com.aspose.psd.Region da intersecare con questo com.aspose.psd.region. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Verifica se questo com.aspose.psd.Region ha un interno vuoto sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno di questo com.aspose.psd.Region è vuoto quando viene applicata la trasformazione associata a g; altrimenti, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Verifica se il com.aspose.psd.Region specificato è identico a questo com.aspose.psd.Region sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Il com.aspose.psd.Region da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta una superficie di disegno. |

**Returns:**
boolean - True se l'interno della regione è identico all'interno di questa regione quando viene applicata la trasformazione associata al parametro g; altrimenti, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Verifica se questo com.aspose.psd.Region ha un interno infinito sulla superficie di disegno specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta una superficie di disegno. |

**Returns:**
boolean - true se l'interno di questo com.aspose.psd.Region è infinito quando viene applicata la trasformazione associata a g; altrimenti, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Verifica se la struttura com.aspose.psd.Point specificata è contenuta in questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | La struttura com.aspose.psd.Point da testare. |

**Returns:**
boolean - true quando point è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Verifica se la struttura com.aspose.psd.Point specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | La struttura com.aspose.psd.Point da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando point è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Verifica se la struttura com.aspose.psd.PointF specificata è contenuta in questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | La struttura com.aspose.psd.PointF da testare. |

**Returns:**
boolean - true quando point è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Verifica se la struttura com.aspose.psd.PointF specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | La struttura com.aspose.psd.PointF da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando point è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Verifica se qualche porzione della struttura com.aspose.psd.Rectangle specificata è contenuta in questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle da testare. |

**Returns:**
boolean - Questo metodo restituisce true quando qualsiasi parte di rect è contenuta in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Verifica se qualche porzione della struttura com.aspose.psd.Rectangle specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura com.aspose.psd.Rectangle da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rect è contenuta in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Verifica se qualche porzione della struttura com.aspose.psd.RectangleF specificata è contenuta in questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura com.aspose.psd.RectangleF da testare. |

**Returns:**
boolean - true quando qualsiasi parte di rect è contenuta in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Verifica se qualche porzione della struttura com.aspose.psd.RectangleF specificata è contenuta in questo com.aspose.psd.Region quando viene disegnata usando il com.aspose.psd.graphics specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura com.aspose.psd.RectangleF da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando rect è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Verifica se il punto specificato è contenuto in questo com.aspose.psd.region.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - True quando il punto specificato è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Verifica se il punto specificato è contenuto in questo com.aspose.psd.Region quando viene disegnato usando il com.aspose.psd.graphics specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - True quando il punto specificato è contenuto in questo com.aspose.psd.Region; altrimenti, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| larghezza | float | La larghezza del rettangolo da testare. |
| altezza | float | L'altezza del rettangolo da testare. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo oggetto com.aspose.psd.Region; altrimenti, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.Region  quando viene disegnata usando la specificata  com.aspose.psd.graphics .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| larghezza | float | La larghezza del rettangolo da testare. |
| altezza | float | L'altezza del rettangolo da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo com.aspose.psd.Region; altrimenti, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Verifica se il punto specificato è contenuto in questo  com.aspose.psd.Region  oggetto quando viene disegnato usando il specificato  com.aspose.psd.Graphics  oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando il punto specificato è contenuto all'interno di questo com.aspose.psd.Region; altrimenti, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| larghezza | int | La larghezza del rettangolo da testare. |
| altezza | int | L'altezza del rettangolo da testare. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo com.aspose.psd.Region; altrimenti, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Verifica se una qualsiasi parte del rettangolo specificato è contenuta in questo  com.aspose.psd.Region  quando viene disegnata usando la specificata  com.aspose.psd.graphics .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| larghezza | int | La larghezza del rettangolo da testare. |
| altezza | int | L'altezza del rettangolo da testare. |
| g | [Graphics](../../com.aspose.psd/graphics) | Un com.aspose.psd.Graphics che rappresenta un contesto grafico. |

**Returns:**
boolean - true quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo com.aspose.psd.Region; altrimenti, false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Inizializza questo  com.aspose.psd.Region  con un interno vuoto.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Inizializza questo  com.aspose.psd.Region  oggetto con un interno infinito.

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


Ottiene o imposta la regione al cambiamento.

Valore: La regione al cambiamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.ChangeActionList |  |

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


Trasforma questo  com.aspose.psd.Region  con la specificata  com.aspose.psd.matrix .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  com.aspose.psd.Matrix  con cui trasformare questo  com.aspose.psd.region . |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Sposta le coordinate di questo  com.aspose.psd.Region  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | La quantità per traslare orizzontalmente questo  com.aspose.psd.Region . |
| dy | float | La quantità per traslare verticalmente questo  com.aspose.psd.Region . |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Sposta le coordinate di questo  com.aspose.psd.Region  dell'importo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | int | La quantità per traslare orizzontalmente questo  com.aspose.psd.Region . |
| dy | int | La quantità per traslare verticalmente questo  com.aspose.psd.Region . |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e del specificato  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  com.aspose.psd.GraphicsPath  da unire a questo  com.aspose.psd.region . |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e della specificata struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura  com.aspose.psd.Rectangle  da unire a questo  com.aspose.psd.region . |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e della specificata struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  da unire a questo  com.aspose.psd.region . |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Aggiorna questo  com.aspose.psd.Region  all'unione di sé stesso e del specificato  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Il  com.aspose.psd.Region  da unire a questo  com.aspose.psd.region . |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con il specificato  com.aspose.psd.graphicsPath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Il  com.aspose.psd.GraphicsPath  da xor con questo  com.aspose.psd.region . |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con la specificata struttura  com.aspose.psd.Rectangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La struttura  com.aspose.psd.Rectangle  da xor con questo  com.aspose.psd.region . |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con la specificata struttura  com.aspose.psd.RectangleF .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | La struttura  com.aspose.psd.RectangleF  da xor con questo  com.aspose.psd.region . |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Aggiorna questo  com.aspose.psd.Region  all'unione meno l'intersezione di sé stesso con il specificato  com.aspose.psd.region .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Il  com.aspose.psd.Region  da xor con questo  com.aspose.psd.region . |

