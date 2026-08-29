---
title: "CustomLineCap"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Incapsula un'estremità di linea personalizzata definita dall'utente."
type: docs
weight: 34
url: /it/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Incapsula un'estremità di linea personalizzata definita dall'utente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Inizializza una nuova istanza della classe  CustomLineCap  con il contorno e il riempimento specificati. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Inizializza una nuova istanza della classe  CustomLineCap  dall'enumerazione  LineCap  esistente specificata, con il contorno e il riempimento specificati. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Inizializza una nuova istanza della classe  CustomLineCap  dall'enumerazione  LineCap  esistente specificata, con il contorno, il riempimento e l'inserimento specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Ottiene l'enumerazione  LineCap  su cui si basa questo  CustomLineCap . |
| [getBaseInset()](#getBaseInset--) | Ottiene la distanza tra il cap e la linea. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Ottiene l'oggetto che definisce il riempimento per il cap personalizzato. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Ottiene i cap usati per avviare e terminare le linee che compongono questo cap personalizzato. |
| [getStrokeJoin()](#getStrokeJoin--) | Ottiene l'enumerazione  LineJoin  che determina come le linee che compongono questo oggetto  CustomLineCap  vengono unite. |
| [getStrokePath()](#getStrokePath--) | Ottiene l'oggetto che definisce il contorno del cap personalizzato. |
| [getWidthScale()](#getWidthScale--) | Ottiene la quantità con cui scalare questo oggetto  CustomLineCap  rispetto alla larghezza dell'oggetto  System.Drawing.Pen . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Imposta l'enumerazione  LineCap  su cui si basa questo  CustomLineCap . |
| [setBaseInset(float value)](#setBaseInset-float-) | Imposta la distanza tra il cap e la linea. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Imposta l'oggetto che definisce il riempimento per il cap personalizzato. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Imposta i cap usati per avviare e terminare le linee che compongono questo cap personalizzato. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Imposta l'enumerazione  LineJoin  che determina come le linee che compongono questo oggetto  CustomLineCap  vengono unite. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Imposta l'oggetto che definisce il contorno del cap personalizzato. |
| [setWidthScale(float value)](#setWidthScale-float-) | Imposta la quantità con cui scalare questo oggetto  CustomLineCap  rispetto alla larghezza dell'oggetto  System.Drawing.Pen . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Inizializza una nuova istanza della classe  CustomLineCap  con il contorno e il riempimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un oggetto  GraphicsPath  che definisce il riempimento per il cap personalizzato. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un oggetto  GraphicsPath  che definisce il contorno del cap personalizzato. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Inizializza una nuova istanza della classe  CustomLineCap  dall'enumerazione  LineCap  esistente specificata, con il contorno e il riempimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un oggetto  GraphicsPath  che definisce il riempimento per il cap personalizzato. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un oggetto  GraphicsPath  che definisce il contorno del cap personalizzato. |
| baseCap | int | Il cappuccio di linea da cui creare il cappuccio personalizzato. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Inizializza una nuova istanza della classe  CustomLineCap  dall'enumerazione  LineCap  esistente specificata, con il contorno, il riempimento e l'inserimento specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un oggetto  GraphicsPath  che definisce il riempimento per il cap personalizzato. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un oggetto  GraphicsPath  che definisce il contorno del cap personalizzato. |
| baseCap | int | Il cappuccio di linea da cui creare il cappuccio personalizzato. |
| baseInset | float | La distanza tra il cappuccio e la linea. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Ottiene l'enumerazione  LineCap  su cui si basa questo  CustomLineCap .

**Returns:**
int - L'enumerazione  LineCap  su cui si basa questo  CustomLineCap .
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Ottiene la distanza tra il cap e la linea.

**Returns:**
float - La distanza tra l'inizio del cappuccio e la fine della linea.
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


Ottiene l'oggetto che definisce il riempimento per il cap personalizzato.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Ottiene i cap usati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int[] | L'enumerazione  LineCap  usata all'inizio di una linea all'interno di questo cappuccio. |
| endCap | int[] | L'enumerazione  LineCap  usata alla fine di una linea all'interno di questo cappuccio. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Ottiene l'enumerazione  LineJoin  che determina come le linee che compongono questo oggetto  CustomLineCap  vengono unite.

**Returns:**
int - L'enumerazione  LineJoin  che questo oggetto  CustomLineCap  usa per unire le linee.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Ottiene l'oggetto che definisce il contorno del cap personalizzato.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Ottiene la quantità con cui scalare questo oggetto  CustomLineCap  rispetto alla larghezza dell'oggetto  System.Drawing.Pen .

**Returns:**
float - La quantità di cui scalare il cappuccio.
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


Imposta l'enumerazione  LineCap  su cui si basa questo  CustomLineCap .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'enumerazione  LineCap  su cui si basa questo  CustomLineCap . |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Imposta la distanza tra il cap e la linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La distanza tra l'inizio del cappuccio e la fine della linea. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Imposta l'oggetto che definisce il riempimento per il cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | L'oggetto che definisce il riempimento per il cappuccio personalizzato. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Imposta i cap usati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int | L'enumerazione  LineCap  usata all'inizio di una linea all'interno di questo cappuccio. |
| endCap | int | L'enumerazione  LineCap  usata alla fine di una linea all'interno di questo cappuccio. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Imposta l'enumerazione  LineJoin  che determina come le linee che compongono questo oggetto  CustomLineCap  vengono unite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'enumerazione  LineJoin  che questo oggetto  CustomLineCap  usa per unire le linee. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Imposta l'oggetto che definisce il contorno del cap personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | L'oggetto che definisce il contorno del cappuccio personalizzato. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Imposta la quantità con cui scalare questo oggetto  CustomLineCap  rispetto alla larghezza dell'oggetto  System.Drawing.Pen .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La quantità di cui scalare il cappuccio. |

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

