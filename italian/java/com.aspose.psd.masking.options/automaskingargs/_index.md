---
title: "AutoMaskingArgs"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta gli argomenti specificati per i metodi di mascheramento automatico"
type: docs
weight: 11
url: /it/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Rappresenta gli argomenti specificati per i metodi di mascheramento automatico
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Restituisce il numero massimo di iterazioni. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Restituisce il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo). |
| [getObjectsPoints()](#getObjectsPoints--) | Restituisce i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Restituisce i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Restituisce i punti che non appartengono più a nessun oggetto (opzionale). |
| [getPrecision()](#getPrecision--) | Restituisce la precisione del metodo di segmentazione (opzionale). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Imposta il numero massimo di iterazioni. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Imposta il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Imposta i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Imposta i rettangoli degli oggetti che appartengono agli oggetti separati (opzionale). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Imposta i punti che non appartengono più a nessun oggetto (opzionale). |
| [setPrecision(double value)](#setPrecision-double-) | Imposta la precisione del metodo di segmentazione (opzionale). |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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


Restituisce il numero massimo di iterazioni.

Valore: Il massimo numero di iterazioni.

**Returns:**
int - il numero massimo di iterazioni.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Restituisce il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo).

Valore: Il numero di oggetti.

**Returns:**
int - il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Restituisce i punti che appartengono agli oggetti separati (opzionale) coordinate NumberOfObjects che appartengono a NumberOfObjects oggetti dell'immagine iniziale. Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I punti degli oggetti.

**Returns:**
com.aspose.psd.Point[][] - i punti che appartengono a oggetti separati (opzionale) NumberOfObjects coordinate che appartengono a NumberOfObjects oggetti dell'immagine iniziale.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Restituisce i rettangoli degli oggetti che appartengono a oggetti separati (opzionale). Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I rettangoli degli oggetti.

**Returns:**
com.aspose.psd.Rectangle[] - i rettangoli degli oggetti che appartengono a oggetti separati (opzionale).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Restituisce i punti che non appartengono più a nessun oggetto (opzionale). Questo parametro è usato solo in caso di ri-segmentazione.

Valore: I punti orfani.

**Returns:**
com.aspose.psd.Point[] - i punti che non appartengono più a nessun oggetto (opzionale).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Restituisce la precisione del metodo di segmentazione (opzionale).

Valore: La precisione del metodo di segmentazione (opzionale).

**Returns:**
double - la precisione del metodo di segmentazione (opzionale).
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


Imposta il numero massimo di iterazioni.

Valore: Il massimo numero di iterazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il numero massimo di iterazioni. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Imposta il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo).

Valore: Il numero di oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il numero di oggetti in cui separare l'immagine iniziale (opzionale), il valore predefinito è 2 (oggetto e sfondo). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Imposta i punti che appartengono a oggetti separati (opzionale) NumberOfObjects coordinate che appartengono a NumberOfObjects oggetti dell'immagine iniziale. Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I punti degli oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | i punti che appartengono a oggetti separati (opzionale) NumberOfObjects coordinate che appartengono a NumberOfObjects oggetti dell'immagine iniziale. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Imposta i rettangoli degli oggetti che appartengono a oggetti separati (opzionale). Questo parametro è usato per aumentare la precisione del metodo di segmentazione.

Valore: I rettangoli degli oggetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | i rettangoli degli oggetti che appartengono a oggetti separati (opzionale). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Imposta i punti che non appartengono più a nessun oggetto (opzionale). Questo parametro è usato solo in caso di ri-segmentazione.

Valore: I punti orfani.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | i punti che non appartengono più a nessun oggetto (opzionale). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Imposta la precisione del metodo di segmentazione (opzionale).

Valore: La precisione del metodo di segmentazione (opzionale).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | la precisione del metodo di segmentazione (opzionale). |

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

