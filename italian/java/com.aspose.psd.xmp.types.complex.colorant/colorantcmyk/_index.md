---
title: "ColorantCmyk"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il colorante CMYK."
type: docs
weight: 13
url: /it/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Rappresenta il colorante CMYK.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Inizializza una nuova istanza della classe  ColorantCmyk . |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Inizializza una nuova istanza della classe  ColorantCmyk . |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Valore massimo del colore nel colorante CMYK. |
| [ColorValueMin](#ColorValueMin) | Valore minimo del colore nel colorante CMYK. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Aggiunge la chiave specificata. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Ottiene o imposta il valore del componente nero. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Ottiene o imposta il tipo di colore. |
| [getCyan()](#getCyan--) | Ottiene o imposta il valore del componente ciano. |
| [getMagenta()](#getMagenta--) | Ottiene o imposta il valore del componente magenta. |
| [getMode()](#getMode--) | Ottiene  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | Ottiene l'URI dello spazio dei nomi predefinito. |
| [getPrefix()](#getPrefix--) | Ottiene il prefisso. |
| [getSwatchName()](#getSwatchName--) | Ottiene o imposta il nome del campione. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore stringa contenuto in formato XMP. |
| [getYellow()](#getYellow--) | Ottiene o imposta il valore del componente giallo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Ottiene o imposta il valore del componente nero. |
| [setColorType(int value)](#setColorType-int-) | Ottiene o imposta il tipo di colore. |
| [setCyan(float value)](#setCyan-float-) | Ottiene o imposta il valore del componente ciano. |
| [setMagenta(float value)](#setMagenta-float-) | Ottiene o imposta il valore del componente magenta. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Ottiene o imposta il nome del campione. |
| [setYellow(float value)](#setYellow-float-) | Ottiene o imposta il valore del componente giallo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Inizializza una nuova istanza della classe  ColorantCmyk .

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Inizializza una nuova istanza della classe  ColorantCmyk .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nero | float | Il valore del componente nero. |
| ciano | float | Il valore del componente colore ciano. |
| magenta | float | Il valore del componente magenta. |
| giallo | float | Il valore del componente giallo. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Valore massimo del colore nel colorante CMYK.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Valore minimo del colore nel colorante CMYK.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Aggiunge la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.Object | Il valore a cui aggiungere. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Ottiene o imposta il valore del componente nero.

Valore: Il valore del componente nero.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Ottiene o imposta il tipo di colore.

Valore: Il tipo di colore.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Ottiene o imposta il valore del componente ciano.

Valore: Il valore del componente ciano.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Ottiene o imposta il valore del componente magenta.

Valore: Il valore del componente magenta.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Ottiene  ColorMode .

Valore: La modalità colore.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ottiene l'URI dello spazio dei nomi predefinito.

**Returns:**
java.lang.String - L'URI di spazio dei nomi predefinito.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ottiene il prefisso.

**Returns:**
java.lang.String - Il prefisso.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Ottiene o imposta il nome del campione.

Valore: Il nome del campione.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore stringa contenuto in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore stringa contenuto in formato XMP.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Ottiene o imposta il valore del componente giallo.

Valore: Il valore del componente giallo.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Ottiene o imposta il valore del componente nero.

Valore: Il valore del componente nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ottiene o imposta il tipo di colore.

Valore: Il tipo di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Ottiene o imposta il valore del componente ciano.

Valore: Il valore del componente ciano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Ottiene o imposta il valore del componente magenta.

Valore: Il valore del componente magenta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Ottiene o imposta il nome del campione.

Valore: Il nome del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Ottiene o imposta il valore del componente giallo.

Valore: Il valore del componente giallo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

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

