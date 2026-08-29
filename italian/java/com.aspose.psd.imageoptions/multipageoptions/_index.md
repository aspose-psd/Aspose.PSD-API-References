---
title: "MultiPageOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe base per i formati che supportano più pagine"
type: docs
weight: 17
url: /it/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Classe base per i formati che supportano più pagine
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe  MultiPageOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Ottiene o imposta l'area di esportazione. |
| [getMergeLayers()](#getMergeLayers--) | Ottiene un valore che indica se [merege layers]. |
| [getMode()](#getMode--) | Ottiene o imposta la modalità. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Ottiene o imposta i nomi dei livelli di output (Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Ottiene le opzioni di rasterizzazione della pagina. |
| [getPageTitles()](#getPageTitles--) | Ottiene o imposta i titoli delle pagine. |
| [getPages()](#getPages--) | Ottiene o imposta le pagine. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Ottiene l'intervallo di tempo. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Inizializza le pagine dall'array di intervalli |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Ottiene o imposta l'area di esportazione. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Imposta un valore che indica se [merege layers]. |
| [setMode(int value)](#setMode-int-) | Ottiene o imposta la modalità. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Ottiene o imposta i nomi dei livelli di output (Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Imposta le opzioni di rasterizzazione della pagina. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Ottiene o imposta i titoli delle pagine. |
| [setPages(int[] value)](#setPages-int---) | Ottiene o imposta le pagine. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Imposta l'intervallo di tempo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Inizializza una nuova istanza della classe  MultiPageOptions.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagine | int[] | Le pagine. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagine | int[] | L'array di pagine. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | L'area di esportazione. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageTitles | java.lang.String[] | I titoli delle pagine. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageTitles | java.lang.String[] | I titoli delle pagine. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | L'area di esportazione. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | L'IntRange. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | L'IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | L'area di esportazione. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | L'IntRange. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | L'IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | L'area di esportazione. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | int | L'indice della pagina. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Inizializza una nuova istanza della classe  MultiPageOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | int | L'indice della pagina. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | L'area di esportazione. |

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
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Ottiene o imposta l'area di esportazione.

Valore: L'area di esportazione.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Ottiene un valore che indica se [merege layers].

Valore:  true  se [merege layers]; altrimenti,  false .

**Returns:**
boolean - un valore che indica se [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Ottiene o imposta la modalità.

Valore: La modalità.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Ottiene o imposta i nomi dei livelli di output (Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd)

Valore: I nomi dei livelli di output.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Ottiene le opzioni di rasterizzazione della pagina.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - le opzioni di rasterizzazione della pagina.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Ottiene o imposta i titoli delle pagine.

Valore: I titoli della pagina.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Ottiene o imposta le pagine.

Valore: Le pagine.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Ottiene l'intervallo di tempo.

Valore: L'intervallo di tempo.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Inizializza le pagine dall'array di intervalli

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Gli intervalli. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Ottiene o imposta l'area di esportazione.

Valore: L'area di esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Imposta un valore che indica se [merege layers].

Valore:  true  se [merege layers]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Ottiene o imposta la modalità.

Valore: La modalità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Ottiene o imposta i nomi dei livelli di output (Funziona se il formato di esportazione supporta la denominazione dei livelli, ad esempio per Psd)

Valore: I nomi dei livelli di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Imposta le opzioni di rasterizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | le opzioni di rasterizzazione della pagina. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Ottiene o imposta i titoli delle pagine.

Valore: I titoli della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Ottiene o imposta le pagine.

Valore: Le pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Imposta l'intervallo di tempo.

Valore: L'intervallo di tempo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | l'intervallo di tempo. |

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

