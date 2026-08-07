---
title: "VectorPathData"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe per lavorare con un percorso vettoriale."
type: docs
weight: 18
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

La classe per lavorare con un percorso vettoriale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Inizializza una nuova istanza della classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
| [VectorPathData()](#VectorPathData--) | Inizializza una nuova istanza della classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | La dimensione delle informazioni generali come versione e flag. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Ottiene come array di byte. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Ottiene la lunghezza dei dati del percorso vettoriale nella risorsa in byte. |
| [getPaths()](#getPaths--) | Ottiene o imposta i record del percorso. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| [isInverted()](#isInverted--) | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| [isNotLinked()](#isNotLinked--) | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| [setInverted(boolean value)](#setInverted-boolean-) | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Ottiene o imposta i record del percorso. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Inizializza una nuova istanza della classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati della risorsa. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Inizializza una nuova istanza della classe [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


La dimensione delle informazioni generali come versione e flag.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Ottiene come array di byte.

**Returns:**
byte[] - La risorsa come array di byte.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Ottiene la lunghezza dei dati del percorso vettoriale nella risorsa in byte.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Ottiene o imposta i record del percorso.

Valore: i percorsi.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene o imposta la versione.

Valore: La versione.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Ottiene o imposta un valore che indica se questa istanza è disabilitata.

Valore:  true  se questa istanza è disabilitata; altrimenti,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Ottiene o imposta un valore che indica se questa istanza è invertita.

Valore:  true  se questa istanza è invertita; altrimenti,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Ottiene o imposta un valore che indica se questa istanza non è collegata.

Valore:  true  se questa istanza non è collegata; altrimenti,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è disabilitata.

Valore:  true  se questa istanza è disabilitata; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è invertita.

Valore:  true  se questa istanza è invertita; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza non è collegata.

Valore:  true  se questa istanza non è collegata; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Ottiene o imposta i record del percorso.

Valore: i percorsi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Ottiene o imposta la versione.

Valore: La versione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

