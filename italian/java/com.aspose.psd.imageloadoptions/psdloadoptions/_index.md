---
title: "PsdLoadOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Opzioni di caricamento Psd"
type: docs
weight: 12
url: /it/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Opzioni di caricamento Psd
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Inizializza una nuova istanza della classe [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Le origini dei font personalizzati |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Ottiene o imposta se preservare i pixel originali del livello durante il rendering se il livello non è stato modificato. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Ottiene o imposta se salvare con l'immagine renderizzata, con o senza una trasformazione warp. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Ottiene il colore di sfondo dell'Image. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Ottiene la modalità di recupero dati. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Ottiene un valore che indica se [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Ottiene o imposta un valore che indica se [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Ottiene o imposta un valore che indica se la larghezza fissa del livello di testo PSD verrà ignorata durante l'esecuzione dell'operazione UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Ottiene o imposta un valore che indica se [load effects resource] (per impostazione predefinita la risorsa non è caricata). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Ottiene o imposta un valore che indica se [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Ottiene o imposta la modalità di sola lettura utilizzata durante il caricamento di un'immagine PSD. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Ottiene o imposta un valore che indica se [use disk for load effects resource] (per impostazione predefinita viene usato il disco per caricare le risorse degli effetti, ma può essere usata la memoria se è sufficiente impostando questo valore su false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Ottiene un valore che indica se la conversione del profilo ICC deve essere applicata. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Questo fa parte del modello di licenza venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Ottiene o imposta se preservare i pixel originali del livello durante il rendering se il livello non è stato modificato. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Ottiene o imposta se salvare con l'immagine renderizzata, con o senza una trasformazione warp. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Imposta il colore di sfondo dell'Image. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Imposta la modalità di recupero dati. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Imposta un valore che indica se [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Ottiene o imposta un valore che indica se [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Ottiene o imposta un valore che indica se la larghezza fissa del livello di testo PSD verrà ignorata durante l'esecuzione dell'operazione UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Ottiene o imposta un valore che indica se [load effects resource] (per impostazione predefinita la risorsa non è caricata). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Ottiene o imposta il MGR della memoria. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Ottiene o imposta un valore che indica se [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Ottiene o imposta la modalità di sola lettura utilizzata durante il caricamento di un'immagine PSD. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Ottiene o imposta un valore che indica se [use disk for load effects resource] (per impostazione predefinita viene usato il disco per caricare le risorse degli effetti, ma può essere usata la memoria se è sufficiente impostando questo valore su false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Imposta un valore che indica se la conversione del profilo ICC deve essere applicata. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Questo fa parte del modello di licenza venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Inizializza una nuova istanza della classe [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Ottiene o imposta se preservare i pixel originali del livello durante il rendering se il livello non è stato modificato.

Valore: true per mantenere i pixel originali dei livelli non modificati; altrimenti, false.

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Ottiene o imposta se salvare con l'immagine renderizzata, con o senza una trasformazione warp.

Valore: true per renderizzare l'immagine con trasformazione warp; false altrimenti.

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
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Ottiene o imposta un valore che indica se [ignore alpha channel].

Valore: true se [ignore alpha channel]; altrimenti, false.

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Ottiene o imposta un valore che indica se la larghezza fissa del livello di testo PSD verrà ignorata durante l'esecuzione dell'operazione UpdateText.

Valore: true se [ignore text layer width]; altrimenti, false.

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Ottiene o imposta un valore che indica se [load effects resource] (per impostazione predefinita la risorsa non è caricata). Quando impostata, questa opzione renderà solo gli effetti supportati nell'immagine finale unita.

Valore: true se [load effects resource]; altrimenti, false.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Ottiene o imposta un valore che indica se [use read only mode]. Questa è la modalità di sola lettura, supportata per una compatibilità identica con Adobe Photoshop. Quando questa opzione è impostata, tutte le modifiche applicate ai livelli non verranno salvate nell'immagine finale. Tutti i dati sono presi dalla sezione ImageData, quindi è identica a Photoshop. Per impostazione predefinita tutte le immagini caricate non sono compatibili in modo identico con Adobe Photoshop.

Valore: true se [use photoshop compatibility mode]; altrimenti, false.

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Ottiene o imposta la modalità di sola lettura utilizzata durante il caricamento di un'immagine PSD.

Valore: Uno dei valori di ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Ottiene o imposta un valore che indica se [use disk for load effects resource] (per impostazione predefinita viene usato il disco per caricare le risorse degli effetti, ma può essere usata la memoria se è sufficiente impostando questo valore su false).

Valore: true se [use disk for load effects resource]; altrimenti, false.

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Ottiene o imposta se preservare i pixel originali del livello durante il rendering se il livello non è stato modificato.

Valore: true per mantenere i pixel originali dei livelli non modificati; altrimenti, false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Ottiene o imposta se salvare con l'immagine renderizzata, con o senza una trasformazione warp.

Valore: true per renderizzare l'immagine con trasformazione warp; false altrimenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Ottiene o imposta un valore che indica se [ignore alpha channel].

Valore: true se [ignore alpha channel]; altrimenti, false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Ottiene o imposta un valore che indica se la larghezza fissa del livello di testo PSD verrà ignorata durante l'esecuzione dell'operazione UpdateText.

Valore: true se [ignore text layer width]; altrimenti, false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Ottiene o imposta un valore che indica se [load effects resource] (per impostazione predefinita la risorsa non è caricata). Quando impostata, questa opzione renderà solo gli effetti supportati nell'immagine finale unita.

Valore: true se [load effects resource]; altrimenti, false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Ottiene o imposta un valore che indica se [use read only mode]. Questa è la modalità di sola lettura, supportata per una compatibilità identica con Adobe Photoshop. Quando questa opzione è impostata, tutte le modifiche applicate ai livelli non verranno salvate nell'immagine finale. Tutti i dati sono presi dalla sezione ImageData, quindi è identica a Photoshop. Per impostazione predefinita tutte le immagini caricate non sono compatibili in modo identico con Adobe Photoshop.

Valore: true se [use photoshop compatibility mode]; altrimenti, false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Ottiene o imposta la modalità di sola lettura utilizzata durante il caricamento di un'immagine PSD.

Valore: Uno dei valori di ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Ottiene o imposta un valore che indica se [use disk for load effects resource] (per impostazione predefinita viene usato il disco per caricare le risorse degli effetti, ma può essere usata la memoria se è sufficiente impostando questo valore su false).

Valore: true se [use disk for load effects resource]; altrimenti, false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

