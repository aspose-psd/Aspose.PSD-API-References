---
title: "MultiPageOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase base para formatos que admiten múltiples páginas."
type: docs
weight: 17
url: /es/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Clase base para formatos que admiten múltiples páginas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Inicializa una nueva instancia de la clase  MultiPageOptions . |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Obtiene o establece el área de exportación. |
| [getMergeLayers()](#getMergeLayers--) | Obtiene un valor que indica si [merege layers]. |
| [getMode()](#getMode--) | Obtiene o establece el modo. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Obtiene o establece los nombres de las capas de salida(Funciona si el formato de exportación admite nombrado de capas, por ejemplo para Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Obtiene las opciones de rasterizado de la página. |
| [getPageTitles()](#getPageTitles--) | Obtiene o establece los títulos de la página. |
| [getPages()](#getPages--) | Obtiene o establece las páginas. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Obtiene el intervalo de tiempo. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Inicializa las páginas a partir del arreglo de rangos |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Obtiene o establece el área de exportación. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Establece un valor que indica si [merege layers]. |
| [setMode(int value)](#setMode-int-) | Obtiene o establece el modo. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Obtiene o establece los nombres de las capas de salida(Funciona si el formato de exportación admite nombrado de capas, por ejemplo para Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Establece las opciones de rasterizado de la página. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Obtiene o establece los títulos de la página. |
| [setPages(int[] value)](#setPages-int---) | Obtiene o establece las páginas. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Establece el intervalo de tiempo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| páginas | int[] | Las páginas. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| páginas | int[] | El arreglo de páginas. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | El área de exportación. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Los títulos de la página. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Los títulos de la página. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | El área de exportación. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | El  IntRange . |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | El  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | El área de exportación. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | El  IntRange . |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | El  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | El área de exportación. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int | El índice de la página. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase  MultiPageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int | El índice de la página. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | El área de exportación. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene o establece el área de exportación.

Valor: El área de exportación.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Obtiene un valor que indica si [merege layers].

Valor:  true  si [merege layers]; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Obtiene o establece el modo.

Valor: El modo.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Obtiene o establece los nombres de las capas de salida(Funciona si el formato de exportación admite nombrado de capas, por ejemplo para Psd)

Valor: Los nombres de las capas de salida.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Obtiene las opciones de rasterizado de la página.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - las opciones de rasterización de la página.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Obtiene o establece los títulos de la página.

Valor: Los títulos de la página.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Obtiene o establece las páginas.

Valor: Las páginas.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Obtiene el intervalo de tiempo.

Valor: El intervalo de tiempo.

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


Inicializa las páginas a partir del arreglo de rangos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Los rangos. |

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


Obtiene o establece el área de exportación.

Valor: El área de exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Establece un valor que indica si [merege layers].

Valor:  true  si [merege layers]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Obtiene o establece el modo.

Valor: El modo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Obtiene o establece los nombres de las capas de salida(Funciona si el formato de exportación admite nombrado de capas, por ejemplo para Psd)

Valor: Los nombres de las capas de salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Establece las opciones de rasterizado de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | las opciones de rasterización de la página. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Obtiene o establece los títulos de la página.

Valor: Los títulos de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Obtiene o establece las páginas.

Valor: Las páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Establece el intervalo de tiempo.

Valor: El intervalo de tiempo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | el intervalo de tiempo. |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

