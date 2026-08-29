---
title: "Blend"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce un modello di fusione."
type: docs
weight: 11
url: /it/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definisce un modello di blend. Questa classe non può essere ereditata.

L'uso tipico della classe blend consiste nel definire un modello di blend per il pennello. Pertanto le proprietà di blend devono essere inizializzate con attenzione. Gli array nulli non sono consentiti. Il pennello genererà l'eccezione appropriata se gli array dei fattori di blend o delle posizioni sono vuoti o se la loro lunghezza non è la stessa. Se ci sono due o più elementi nell'array delle posizioni, il primo elemento deve essere 0 e l'ultimo deve essere 1.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Blend()](#Blend--) | Inizializza una nuova istanza della classe  Blend  . |
| [Blend(int count)](#Blend-int-) | Inizializza una nuova istanza della classe  Blend  con il numero specificato di fattori e posizioni. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è una classe  com.aspose.psd.Blend  e se è equivalente a questa classe  com.aspose.psd.Blend . |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Restituisce l'array dei fattori di blend per il gradiente. |
| [getPositions()](#getPositions--) | Restituisce l'array delle posizioni di blend per il gradiente. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Imposta l'array dei fattori di blend per il gradiente. |
| [setPositions(float[] value)](#setPositions-float---) | Imposta l'array delle posizioni di blend per il gradiente. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Inizializza una nuova istanza della classe  Blend . Il numero di elementi negli array dei fattori e dei blend sarà pari a 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Inizializza una nuova istanza della classe  Blend  con il numero specificato di fattori e posizioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| count | int | Il numero di elementi negli array dei fattori e delle posizioni. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è una classe  com.aspose.psd.Blend  e se è equivalente a questa classe  com.aspose.psd.Blend .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - True se  obj  è una classe  com.aspose.psd.Blend  equivalente a questa classe  com.aspose.psd.Blend ; altrimenti, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Restituisce l'array dei fattori di blend per il gradiente.

**Returns:**
float[] - L'array dei fattori di blend che specificano le percentuali del colore iniziale e del colore finale da utilizzare nella posizione corrispondente.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Restituisce l'array delle posizioni di blend per il gradiente.

**Returns:**
float[] - L'array delle posizioni di blend che specificano le percentuali della distanza lungo la linea del gradiente.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Imposta l'array dei fattori di blend per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | L'array dei fattori di blend che specificano le percentuali del colore iniziale e del colore finale da utilizzare nella posizione corrispondente. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Imposta l'array delle posizioni di blend per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | L'array delle posizioni di blend che specificano le percentuali della distanza lungo la linea del gradiente. |

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

