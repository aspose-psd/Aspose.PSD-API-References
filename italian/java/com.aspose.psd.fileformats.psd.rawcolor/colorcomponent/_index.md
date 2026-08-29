---
title: "ColorComponent"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il componente colore è un'astrazione su Channel Value e Channel Value."
type: docs
weight: 10
url: /it/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Il componente colore è un'astrazione su Channel Value e Channel Value. Qualsiasi colore è composto da un array di ColorComponent
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Inizializza una nuova istanza della classe [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Restituisce la profondità di bit del Color Component/Channel |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Restituisce la descrizione del Color Component |
| [getFullName()](#getFullName--) | Restituisce il nome completo del componente colore con nome e descrizione separata da spazi |
| [getName()](#getName--) | Restituisce il nome del componente colore. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Restituisce i nomi completi consentiti. |
| [getValue()](#getValue--) | Ottiene o imposta il valore. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Ottiene o imposta il valore. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Inizializza una nuova istanza della classe [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Si prega di verificare

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitDepth | byte | La profondità di bit. |
| fullName | java.lang.String | Il nome completo. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Restituisce la profondità di bit del Color Component/Channel

Valore: La profondità di bit.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Restituisce la descrizione del Color Component

Valore: La descrizione.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Restituisce il nome completo del componente colore con nome e descrizione separata da spazi

Valore: Il nome completo.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome del componente colore.

Valore: Il nome.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Restituisce i nomi completi consentiti.

Valore: I nomi completi consentiti.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Ottiene o imposta il valore. Si prega di notare che, se si tenta di impostare un valore superiore a quello che può essere memorizzato nella profondità di bit corrente, verrà generata un'eccezione.

Valore: Il valore.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Ottiene o imposta il valore. Si prega di notare che, se si tenta di impostare un valore superiore a quello che può essere memorizzato nella profondità di bit corrente, verrà generata un'eccezione.

Valore: Il valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

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

