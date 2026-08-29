---
title: "LayerHashCalculator"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Calcolatore di hash per i livelli PSD."
type: docs
weight: 20
url: /it/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Calcolatore di hash per i livelli PSD. Può essere usato per trovare livelli uguali o diversi in diversi file PSD.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Inizializza una nuova istanza della classe [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Ottiene l'hash di fusione. |
| [getChannelsHash()](#getChannelsHash--) | Ottiene l'hash dei canali. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Ottiene l'hash del contenuto. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


Inizializza una nuova istanza della classe [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Il livello. |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Ottiene l'hash di fusione.

**Returns:**
int - Hash univoco per le opzioni di fusione del livello
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Ottiene l'hash dei canali.

**Returns:**
int - Hash di tutti i canali del livello
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


Ottiene l'hash del contenuto.

**Returns:**
int - L'hash dei parametri significativi dei livelli. Questo hash è diverso per tutti i tipi di livello
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

