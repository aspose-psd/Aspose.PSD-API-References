---
title: "MultiPageOptions"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe de base pour les formats prenant en charge plusieurs pages"
type: docs
weight: 17
url: /fr/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Classe de base pour les formats prenant en charge plusieurs pages
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe  MultiPageOptions . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Obtient ou définit la zone d'exportation. |
| [getMergeLayers()](#getMergeLayers--) | Obtient une valeur indiquant si [merege layers]. |
| [getMode()](#getMode--) | Obtient ou définit le mode. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Obtient les options de rasterisation de la page. |
| [getPageTitles()](#getPageTitles--) | Obtient ou définit les titres de page. |
| [getPages()](#getPages--) | Obtient ou définit les pages. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Obtient l'intervalle de temps. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Initialise les pages à partir du tableau de plages |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Obtient ou définit la zone d'exportation. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Définit une valeur indiquant si [merege layers]. |
| [setMode(int value)](#setMode-int-) | Obtient ou définit le mode. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Définit les options de rasterisation de la page. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Obtient ou définit les titres de page. |
| [setPages(int[] value)](#setPages-int---) | Obtient ou définit les pages. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Définit l'intervalle de temps. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pages | int[] | Les pages. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pages | int[] | Le tableau de pages. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | La zone d'exportation. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Les titres de page. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Les titres de page. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | La zone d'exportation. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Le  IntRange . |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Le  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | La zone d'exportation. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Le  IntRange . |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Le  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | La zone d'exportation. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | int | L'index de page. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initialise une nouvelle instance de la classe  MultiPageOptions .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | int | L'index de page. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | La zone d'exportation. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient ou définit la zone d'exportation.

Valeur: La zone d'exportation.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Obtient une valeur indiquant si [merege layers].

Valeur:  true  si [merege layers]; sinon,  false .

**Returns:**
booléen - une valeur indiquant si [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Obtient ou définit le mode.

Valeur: Le mode.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour Psd)

Valeur: Les noms des calques de sortie.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Obtient les options de rasterisation de la page.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - les options de rasterisation de la page.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Obtient ou définit les titres de page.

Valeur: Les titres de page.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Obtient ou définit les pages.

Valeur: Les pages.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Obtient l'intervalle de temps.

Valeur: L'intervalle de temps.

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


Initialise les pages à partir du tableau de plages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Les plages. |

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


Obtient ou définit la zone d'exportation.

Valeur: La zone d'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Définit une valeur indiquant si [merege layers].

Valeur:  true  si [merege layers]; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | une valeur indiquant si [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Obtient ou définit le mode.

Valeur: Le mode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Obtient ou définit les noms des calques de sortie (Fonctionne si le format d'exportation prend en charge le nommage des calques, par exemple pour Psd)

Valeur: Les noms des calques de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Définit les options de rasterisation de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | les options de rastérisation de la page. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Obtient ou définit les titres de page.

Valeur: Les titres de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Obtient ou définit les pages.

Valeur: Les pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Définit l'intervalle de temps.

Valeur: L'intervalle de temps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | l'intervalle de temps. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

