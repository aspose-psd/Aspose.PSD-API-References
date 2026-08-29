---
title: "Font"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce un formato particolare per il testo includendo la dimensione del tipo di carattere e gli attributi di stile."
type: docs
weight: 46
url: /it/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Inizializza un nuovo  com.aspose.psd.Font  che utilizza il  com.aspose.psd.Font  esistente specificato e l'enumerazione  com.aspose.psd.FontStyle . |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione specificata. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione e uno stile specificati. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione, uno stile, un'unità e un set di caratteri specificati. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione, uno stile e un'unità specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda esatta di questo  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica se l'oggetto specificato è un  com.aspose.psd.Font  e ha gli stessi valori delle proprietà di questo  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Ottiene un valore che indica se questo  Font  è in grassetto. |
| [getCharacterSet()](#getCharacterSet--) | Ottiene un valore byte che specifica il set di caratteri utilizzato da questo  Font . |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Ottiene un valore che indica se questo  Font  è in corsivo. |
| [getName()](#getName--) | Ottiene il nome del tipo di carattere di questo  Font . |
| [getSize()](#getSize--) | Ottiene la dimensione em di questo  Font  misurata nelle unità specificate dalla proprietà  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Ottiene un valore che indica se questo  Font  specifica una linea orizzontale attraverso il carattere. |
| [getStyle()](#getStyle--) | Ottiene le informazioni di stile per questo  Font . |
| [getUnderline()](#getUnderline--) | Ottiene un valore che indica se questo  Font  è sottolineato. |
| [getUnit()](#getUnit--) | Ottiene l'unità di misura per questo  Font . |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questo  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione e un'unità specificate. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Inizializza un nuovo  com.aspose.psd.Font  che utilizza il  com.aspose.psd.Font  esistente specificato e l'enumerazione  com.aspose.psd.FontStyle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Il  com.aspose.psd.Font  esistente da cui creare il nuovo  com.aspose.psd.Font . |
| newStyle | int | Il  com.aspose.psd.FontStyle  da applicare al nuovo  com.aspose.psd.Font . È possibile combinare più valori dell'enumerazione  com.aspose.psd.FontStyle  con l'operatore OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione specificata. Il set di caratteri è impostato su  F:Aspose.Imaging.CharacterSet.Default , l'unità grafica su  F:Aspose.Imaging.GraphicsUnit.Point , lo stile del carattere su  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del  com.aspose.psd.Font . |
| emSize | float | La dimensione em, in punti, del nuovo carattere. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione e uno stile specificati. Il set di caratteri è impostato su  F:Aspose.Imaging.CharacterSet.Default , l'unità grafica su  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del  com.aspose.psd.Font . |
| emSize | float | La dimensione em, in punti, del nuovo carattere. |
| style | int | Lo  com.aspose.psd.FontStyle  del nuovo carattere. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione, uno stile, un'unità e un set di caratteri specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del  com.aspose.psd.Font . |
| emSize | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro  unit . |
| style | int | Lo  com.aspose.psd.FontStyle  del nuovo carattere. |
| unit | int | L'  com.aspose.psd.GraphicsUnit  del nuovo carattere. |
| characterSet | int | Un set di caratteri da utilizzare per questo carattere. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione, uno stile e un'unità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del  com.aspose.psd.Font . |
| emSize | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro  unit . |
| style | int | Lo  com.aspose.psd.FontStyle  del nuovo carattere. |
| unit | int | L'  com.aspose.psd.GraphicsUnit  del nuovo carattere. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crea una copia profonda esatta di questo  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica se l'oggetto specificato è un  com.aspose.psd.Font  e ha gli stessi valori delle proprietà di questo  com.aspose.psd.Font .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - True se il parametro  obj  è un  com.aspose.psd.Font  e ha gli stessi valori delle proprietà di questo  com.aspose.psd.Font ; altrimenti, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Ottiene un valore che indica se questo  Font  è in grassetto.

**Returns:**
boolean - True se questo  Font  è in grassetto; altrimenti, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Ottiene un valore byte che specifica il set di caratteri utilizzato da questo  Font .

**Returns:**
int - Un set di caratteri che questo  Font  utilizza.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Ottiene un valore che indica se questo  Font  è in corsivo.

**Returns:**
boolean - True se questo  Font  è in corsivo; altrimenti, false.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome del tipo di carattere di questo  Font .

**Returns:**
java.lang.String - Una rappresentazione stringa del nome del tipo di carattere di questo  Font .
### getSize() {#getSize--}
```
public float getSize()
```


Ottiene la dimensione em di questo  Font  misurata nelle unità specificate dalla proprietà  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - La dimensione em di questo  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Ottiene un valore che indica se questo  Font  specifica una linea orizzontale attraverso il carattere.

**Returns:**
boolean - True se questo  Font  ha una linea orizzontale attraverso di esso; altrimenti, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Ottiene le informazioni di stile per questo  Font .

**Returns:**
int - Un'enumerazione  FontStyle  che contiene informazioni di stile per questo  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Ottiene un valore che indica se questo  Font  è sottolineato.

**Returns:**
boolean - True se questo  Font  è sottolineato; altrimenti, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Ottiene l'unità di misura per questo  Font .

**Returns:**
int - Un  GraphicsUnit  che rappresenta l'unità di misura per questo  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash per questo  com.aspose.psd.Font .

**Returns:**
int - Il codice hash per questo  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Inizializza un nuovo  com.aspose.psd.Font  usando una dimensione e un'unità specificate. Il set di caratteri è impostato su  F:Aspose.Imaging.CharacterSet.Default , lo stile è impostato su  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del  com.aspose.psd.Font . |
| emSize | float | La dimensione em del nuovo carattere nelle unità specificate dal parametro  unit . |
| unit | int | L'  com.aspose.psd.GraphicsUnit  del nuovo carattere. |

**Returns:**
[Font](../../com.aspose.psd/font)
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


Restituisce una rappresentazione stringa leggibile dall'uomo di questo  com.aspose.psd.Font .

**Returns:**
java.lang.String - Una stringa che rappresenta questo  com.aspose.psd.Font .
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

