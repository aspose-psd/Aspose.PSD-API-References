---
title: "GaussWienerFilterOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Opciones de filtro Gauss Wiener Deblur gauss"
type: docs
weight: 15
url: /es/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Opciones de filtro Gauss Wiener Deblur gauss
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Inicializa una nueva instancia de la clase  GaussWienerFilterOptions . |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Inicializa una nueva instancia de la clase  GaussWienerFilterOptions . |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Obtiene o establece la brightness. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Obtiene o establece un valor que indica si este [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) es en escala de grises. |
| [getRadius()](#getRadius--) | Obtiene o establece el radio. |
| [getSmooth()](#getSmooth--) | Obtiene o establece el suavizado. |
| [getSnr()](#getSnr--) | Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Obtiene un valor que indica si esta instancia está cargada parcialmente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Obtiene o establece la brightness. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Obtiene o establece un valor que indica si este [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) es en escala de grises. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Obtiene un valor que indica si esta instancia está cargada parcialmente. |
| [setRadius(int value)](#setRadius-int-) | Obtiene o establece el radio. |
| [setSmooth(double value)](#setSmooth-double-) | Obtiene o establece el suavizado. |
| [setSnr(double value)](#setSnr-double-) | Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Inicializa una nueva instancia de la clase  GaussWienerFilterOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | int | El radio. |
| suavizado | double | El suavizado. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Inicializa una nueva instancia de la clase  GaussWienerFilterOptions . Con la configuración predeterminada.

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
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Obtiene o establece el brillo. rango recomendado 1 - 1.5 valor predeterminado = 1.15

Valor: La brightness.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Obtiene o establece un valor que indica si este [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) está en escala de grises. Devuelve modo de escala de grises o modo RGB.

Valor:  true  si es escala de grises; de lo contrario,  false .

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


Obtiene o establece el radio.

Valor: El radio.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Obtiene o establece el suavizado.

Valor: El suavizado.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007

Valor: La SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


Obtiene un valor que indica si esta instancia está cargada parcialmente.

Valor:  true  si esta instancia está parcialmente cargada; de lo contrario,  false .

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




### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Obtiene o establece el brillo. rango recomendado 1 - 1.5 valor predeterminado = 1.15

Valor: La brightness.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Obtiene o establece un valor que indica si este [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) está en escala de grises. Devuelve modo de escala de grises o modo RGB.

Valor:  true  si es escala de grises; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Obtiene un valor que indica si esta instancia está cargada parcialmente.

Valor:  true  si esta instancia está parcialmente cargada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Obtiene o establece el radio.

Valor: El radio.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Obtiene o establece el suavizado.

Valor: El suavizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Obtiene o establece la relación señal-ruido (SNR) rango recomendado 0.002 - 0.009, valor predeterminado = 0.007

Valor: La SNR.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

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

