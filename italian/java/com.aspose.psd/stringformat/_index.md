---
title: "StringFormat"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Incapsula le informazioni di layout del testo (come allineamento, orientamento e tabulazioni) manipolazioni di visualizzazione (come inserimento di ellissi e sostituzione di cifre nazionali) e funzionalità OpenType."
type: docs
weight: 106
url: /it/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Incapsula le informazioni di layout del testo (come allineamento, orientamento e tabulazioni) manipolazioni di visualizzazione (come inserimento di ellissi e sostituzione di cifre nazionali) e funzionalità OpenType. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StringFormat()](#StringFormat--) | Inizializza un nuovo  com.aspose.psd.StringFormat  oggetto. |
| [StringFormat(int options)](#StringFormat-int-) | Inizializza un nuovo  com.aspose.psd.StringFormat  oggetto con l'enumerazione  com.aspose.psd.StringFormatFlags  specificata e la lingua. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Inizializza un nuovo  com.aspose.psd.StringFormat  oggetto dal  com.aspose.psd.StringFormat  oggetto esistente specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una copia profonda di questo  com.aspose.psd.StringFormat  oggetto. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Ottiene le informazioni di allineamento del testo sul piano verticale. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Ottiene la lingua utilizzata quando le cifre locali sono sostituite con cifre occidentali. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Ottiene il metodo da utilizzare per la sostituzione delle cifre. |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Ottiene il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| [getFormatFlags()](#getFormatFlags--) | Ottiene un'enumerazione  com.aspose.psd.StringFormatFlags  che contiene informazioni di formattazione. |
| [getGenericDefault()](#getGenericDefault--) | Ottiene un oggetto generico predefinito  com.aspose.psd.StringFormat . |
| [getGenericTypographic()](#getGenericTypographic--) | Ottiene un oggetto tipografico generico  com.aspose.psd.StringFormat . |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ottiene l'oggetto  com.aspose.psd.HotkeyPrefix  per questo oggetto  com.aspose.psd.StringFormat . |
| [getLineAlignment()](#getLineAlignment--) | Ottiene l'allineamento della linea sul piano orizzontale. |
| [getTabStops()](#getTabStops--) | Ottiene un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | Ottiene l'enumerazione  com.aspose.psd.StringTrimming  per questo oggetto  com.aspose.psd.StringFormat . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Imposta le informazioni di allineamento del testo sul piano verticale. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Imposta la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Imposta il metodo da utilizzare per la sostituzione delle cifre. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Imposta una  com.aspose.psd.StringFormatFlags  enumerazione che contiene informazioni di formattazione. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Imposta l'oggetto  com.aspose.psd.HotkeyPrefix  per questo oggetto  com.aspose.psd.StringFormat . |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Imposta l'allineamento della linea sul piano orizzontale. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Imposta le tabulazioni per questo oggetto  com.aspose.psd.StringFormat . |
| [setTrimming(int value)](#setTrimming-int-) | Imposta la  com.aspose.psd.StringTrimming  enumerazione per questo oggetto  com.aspose.psd.StringFormat . |
| [toString()](#toString--) | Converte questo oggetto  com.aspose.psd.StringFormat  in una stringa leggibile. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Inizializza un nuovo  com.aspose.psd.StringFormat  oggetto.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Inizializza un nuovo  com.aspose.psd.StringFormat  oggetto con l'enumerazione  com.aspose.psd.StringFormatFlags  specificata e la lingua.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| opzioni | int | La  com.aspose.psd.StringFormatFlags  enumerazione per il nuovo oggetto  com.aspose.psd.StringFormat . |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Inizializza un nuovo  com.aspose.psd.StringFormat  oggetto dal  com.aspose.psd.StringFormat  oggetto esistente specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | L'oggetto  com.aspose.psd.StringFormat  da cui inizializzare il nuovo oggetto  com.aspose.psd.StringFormat . |

### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crea una copia profonda di questo  com.aspose.psd.StringFormat  oggetto.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ottiene le informazioni di allineamento del testo sul piano verticale.

**Returns:**
int - Una  com.aspose.psd.StringAlignment  enumerazione che specifica le informazioni di allineamento del testo.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Ottiene la lingua utilizzata quando le cifre locali sono sostituite con cifre occidentali.

**Returns:**
int - Un identificatore di lingua del National Language Support (NLS) che identifica la lingua da utilizzare quando le cifre locali vengono sostituite con cifre occidentali. È possibile passare la proprietà  P:System.Globalization.CultureInfo.LCID  di un oggetto  System.Globalization.CultureInfo  come identificatore di lingua NLS. Ad esempio, supponiamo di creare un oggetto  System.Globalization.CultureInfo  passando la stringa "ar-EG" al costruttore di  System.Globalization.CultureInfo . Se si passa la proprietà  P:System.Globalization.CultureInfo.LCID  di tale oggetto  System.Globalization.CultureInfo  insieme a  com.aspose.psd.StringDigitSubstitute.Traditional  al metodo  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) , le cifre arabo-indiane saranno sostituite alle cifre occidentali al momento della visualizzazione.

Il setter è introdotto per il metodo obsoleto setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Ottiene il metodo da utilizzare per la sostituzione delle cifre.

**Returns:**
int - Un valore della enumerazione  com.aspose.psd.StringDigitSubstitute  che specifica come sostituire i caratteri in una stringa che non può essere visualizzata perché non supportata dal font corrente.

Il setter è introdotto per il metodo obsoleto SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Ottiene il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione.

**Returns:**
float - Il primo offset della tabulazione.

La proprietà è introdotta per il metodo rimosso GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Ottiene un'enumerazione  com.aspose.psd.StringFormatFlags  che contiene informazioni di formattazione.

**Returns:**
int - Una  com.aspose.psd.StringFormatFlags  enumerazione che contiene informazioni di formattazione.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Ottiene un oggetto generico predefinito  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Ottiene un oggetto tipografico generico  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ottiene l'oggetto  com.aspose.psd.HotkeyPrefix  per questo oggetto  com.aspose.psd.StringFormat .

**Returns:**
int - L'oggetto  com.aspose.psd.HotkeyPrefix  per questo oggetto  com.aspose.psd.StringFormat , il valore predefinito è  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Ottiene l'allineamento della linea sul piano orizzontale.

**Returns:**
int - Una  com.aspose.psd.StringAlignment  enumerazione che rappresenta l'allineamento della linea.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ottiene un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] - Le tabulazioni.

La proprietà è introdotta per il metodo rimosso GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ottiene l'enumerazione  com.aspose.psd.StringTrimming  per questo oggetto  com.aspose.psd.StringFormat .

**Returns:**
int - Una  com.aspose.psd.StringTrimming  enumerazione che indica come il testo disegnato con questo oggetto  com.aspose.psd.StringFormat  viene troncato quando supera i bordi del rettangolo di layout.
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Imposta le informazioni di allineamento del testo sul piano verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Una  com.aspose.psd.StringAlignment  enumerazione che specifica le informazioni di allineamento del testo. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Imposta la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Un identificatore di lingua del National Language Support (NLS) che identifica la lingua da utilizzare quando le cifre locali vengono sostituite con cifre occidentali. È possibile passare la proprietà  P:System.Globalization.CultureInfo.LCID  di un oggetto  System.Globalization.CultureInfo  come identificatore di lingua NLS. Ad esempio, supponiamo di creare un oggetto  System.Globalization.CultureInfo  passando la stringa "ar-EG" al costruttore di  System.Globalization.CultureInfo . Se si passa la proprietà  P:System.Globalization.CultureInfo.LCID  di tale oggetto  System.Globalization.CultureInfo  insieme a  com.aspose.psd.StringDigitSubstitute.Traditional  al metodo  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) , le cifre arabo-indiane saranno sostituite alle cifre occidentali al momento della visualizzazione. |

Il setter è introdotto per il metodo obsoleto SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Imposta il metodo da utilizzare per la sostituzione delle cifre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Un valore di enumerazione  com.aspose.psd.StringDigitSubstitute  che specifica come sostituire i caratteri in una stringa che non può essere visualizzata perché non sono supportati dal font corrente. |

Il setter è introdotto per il metodo obsoleto SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Imposta una  com.aspose.psd.StringFormatFlags  enumerazione che contiene informazioni di formattazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione  com.aspose.psd.StringFormatFlags  che contiene informazioni di formattazione. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Imposta l'oggetto  com.aspose.psd.HotkeyPrefix  per questo oggetto  com.aspose.psd.StringFormat .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'oggetto  com.aspose.psd.HotkeyPrefix  per questo oggetto  com.aspose.psd.StringFormat , il valore predefinito è  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Imposta l'allineamento della linea sul piano orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione  com.aspose.psd.StringAlignment  che rappresenta l'allineamento della linea. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Imposta le tabulazioni per questo oggetto  com.aspose.psd.StringFormat .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstTabOffset | float | Il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore. |
| tabStops | float[] | Un array di distanze tra i tabulatori nelle unità specificate dalla proprietà  com.aspose.psd.Graphics.PageUnit . |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Imposta la  com.aspose.psd.StringTrimming  enumerazione per questo oggetto  com.aspose.psd.StringFormat .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione  com.aspose.psd.StringTrimming  che indica come il testo disegnato con questo oggetto  com.aspose.psd.StringFormat  viene troncato quando supera i bordi del rettangolo di layout. |

### toString() {#toString--}
```
public String toString()
```


Converte questo oggetto  com.aspose.psd.StringFormat  in una stringa leggibile.

**Returns:**
java.lang.String - Una rappresentazione stringa di questo oggetto  com.aspose.psd.StringFormat .
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

