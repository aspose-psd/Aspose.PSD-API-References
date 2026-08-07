---
title: "LoadOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta le opzioni di caricamento."
type: docs
weight: 68
url: /it/java/com.aspose.psd/loadoptions/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Rappresenta le opzioni di caricamento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Le origini dei font personalizzati |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Ottiene il colore di sfondo dell'Image. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Ottiene la modalità di recupero dati. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Ottiene un valore che indica se [ignore after load]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Ottiene un valore che indica se la conversione del profilo ICC deve essere applicata. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Questo fa parte del modello di licenza venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Imposta il colore di sfondo dell'Image. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Imposta la modalità di recupero dati. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Imposta un valore che indica se [ignore after load]. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Ottiene o imposta il MGR della memoria. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Imposta un valore che indica se la conversione del profilo ICC deve essere applicata. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Questo fa parte del modello di licenza venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Le origini dei font personalizzati

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int - il suggerimento della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Ottiene il colore di sfondo dell'Image.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Tipicamente il colore di sfondo viene impostato ogni volta che il valore del pixel non può essere recuperato a causa di corruzione dei dati.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Ottiene la modalità di recupero dati.

**Returns:**
int - La modalità di recupero dati.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Ottiene un valore che indica se [ignore after load].

**Returns:**
boolean -  true  se [ignore after load]; altrimenti,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Ottiene un valore che indica se la conversione del profilo ICC deve essere applicata.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Questo fa parte del modello di licenza venture. Questo valore sarà impostato da VentureLicenser se il venture ci fornisce un oggetto LoadOptions.

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il suggerimento della dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Imposta il colore di sfondo dell'Image.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Il colore di sfondo. |

Tipicamente il colore di sfondo viene impostato ogni volta che il valore del pixel non può essere recuperato a causa di corruzione dei dati. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Imposta la modalità di recupero dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di recupero dati. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Imposta un valore che indica se [ignore after load].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se [ignore after load]; altrimenti, false. |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Ottiene o imposta il MGR della memoria.

Valore: Il memory MGR.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Il gestore dell'evento di avanzamento. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Imposta un valore che indica se la conversione del profilo ICC deve essere applicata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Questo fa parte del modello di licenza venture. Questo valore sarà impostato da VentureLicenser se il venture ci fornisce un oggetto LoadOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

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

