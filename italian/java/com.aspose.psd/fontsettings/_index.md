---
title: "FontSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Impostazioni dei caratteri del renderer per formati vettoriali di imaging generali."
type: docs
weight: 47
url: /it/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Impostazioni dei caratteri del renderer per formati vettoriali di imaging generali.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Restituisce il nome del font Adobe in base al nome della famiglia del font. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Restituisce il nome del font predefinito. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Restituisce le cartelle dei font predefinite. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Restituisce l'array di sostituzioni dei font in base al nome del font |
| [getFontsFolders()](#getFontsFolders--) | Restituisce una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Imaging cerca i font TrueType. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Restituisce o imposta un valore che indica se [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Restituisce il font di sostituzione più adatto. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Determina se [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Rimuove il file della cache dei font. |
| [reset()](#reset--) | Ripristina la cartella dei font e il nome del font predefinito al valore predefinito del sistema. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Limita l'uso dei font tramite un elenco di font. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Imposta il nome del font predefinito. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Imposta l'elenco di sostituzione dei font. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Sovrascrivi l'elenco delle cartelle dei font per la cartella |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Sovrascrivi l'elenco delle cartelle dei font per le cartelle |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Restituisce o imposta un valore che indica se [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Aggiorna la cache dei font per i file PSD che contengono livelli di testo. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Restituisce il nome del font Adobe in base al nome della famiglia del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Il nome della famiglia del font. |

**Returns:**
java.lang.String - Il nome del font Adobe in base al nome della famiglia del font.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Restituisce il nome del font predefinito.

**Returns:**
java.lang.String - nome del font predefinito
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Restituisce le cartelle dei font predefinite.

**Returns:**
java.lang.String[] - Restituisce la cartella di sistema
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Restituisce l'array di sostituzioni dei font in base al nome del font

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del carattere. |

**Returns:**
java.lang.String[] - Array di nomi di sostituzioni per i caratteri forniti
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Restituisce una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Imaging cerca i font TrueType.

Il valore restituito è una copia dei dati utilizzati da Aspose.Imaging. Se modifichi le voci nell'array restituito, non avrà alcun effetto sul rendering del documento. Per specificare nuove posizioni dei caratteri usa il metodo  setFontsFolders .

**Returns:**
java.lang.String[] - Una copia delle attuali posizioni dei caratteri.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Restituisce o imposta un valore che indica se [get alternative font].

Valore:  true  se [get alternative font]; altrimenti,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Restituisce il carattere di sostituzione più adatto. Se tutte le sostituzioni non sono consentite, verrà restituito il primo carattere consentito e disponibile. Se non ci sono caratteri disponibili, verrà restituito il carattere passato come argomento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del carattere. |

**Returns:**
java.lang.String - Il nome del carattere sostituito
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


Determina se [is font allowed] [the specified font name].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del carattere. |

**Returns:**
boolean -  true  se [is font allowed] [il nome del carattere specificato]; altrimenti,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


Rimuove il file della cache dei font.

### reset() {#reset--}
```
public static void reset()
```


Ripristina la cartella dei font e il nome del font predefinito al valore predefinito del sistema.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Limita i caratteri usando un elenco di caratteri. Verifica i nomi reali dei caratteri prima della restrizione. Imposta l'elenco di caratteri consentiti a Null per rimuovere le restrizioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontList | java.lang.String[] | L'elenco dei caratteri. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Imposta il nome del font predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Il nome predefinito del carattere. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Imposta l'elenco di sostituzione dei caratteri. Se un carattere non è consentito, verrà cercata una sostituzione. Il primo carattere nell'elenco sarà usato per primo. Se anche questo è limitato, verrà selezionato il carattere successivo nell'elenco. Se il carattere non ha sostituzioni o tutte le sostituzioni non sono consentite, verrà usato il primo carattere consentito dall'elenco dei caratteri consentiti. Se non ci sono caratteri consentiti e disponibili, la libreria proverà a utilizzare il carattere predefinito di sistema anche se non è consentito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontToReplace | java.lang.String | Il carattere da sostituire. |
| fontNames | java.lang.String[] | I nomi dei caratteri di sostituzione in ordine di somiglianza. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Sovrascrivi l'elenco delle cartelle dei font per la cartella

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | java.lang.String | Cartella con caratteri TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Sovrascrivi l'elenco delle cartelle dei font per le cartelle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folders | java.lang.String[] | Array di cartelle |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Imposta le cartelle da cui vengono caricati i caratteri TrueType e cancella tutti i caratteri caricati. Non vengono eseguiti controlli sulle cartelle dei caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folders | java.lang.String[] | Le cartelle dei caratteri. |
| recursive | boolean | se impostato su  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Restituisce o imposta un valore che indica se [get alternative font].

Valore:  true  se [get alternative font]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Aggiorna la cache dei font per i file PSD che contengono livelli di testo. Questo metodo garantisce che i font dalla cartella fontsFolder usando il metodo FontSettings.setFontsFolder(fontsFolder) o dopo il reset dei font usando FontSettings.reset() saranno considerati durante l'elaborazione dei file PSD. Si prega di utilizzare questo metodo ogni volta che FontSettings.setFontsFolder(fontsFolder) o FontSettings.reset() vengono chiamati per le immagini PSD. Se non si chiama questo metodo non vi è alcuna garanzia che i font vengano aggiornati.

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

