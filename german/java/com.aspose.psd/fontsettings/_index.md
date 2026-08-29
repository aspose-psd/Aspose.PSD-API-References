---
title: "FontSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Allgemeine Schriftarteinstellungen des Renderers für Bildvektorformate."
type: docs
weight: 47
url: /de/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Allgemeine Schriftarteinstellungen des Renderers für Bildvektorformate.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Ruft den Adobe-Schriftartnamen anhand des Schriftfamiliennamens ab. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Ruft den Standard-Schriftartnamen ab. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Ruft die Standard-Schriftordner ab. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Ruft das Schriftart-Ersetzungsarray anhand des Schriftartnamens ab |
| [getFontsFolders()](#getFontsFolders--) | Ruft eine Kopie des Arrays ab, das die Liste der Ordner enthält, in denen Aspose.Imaging nach TrueType-Schriften sucht. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Liest oder setzt einen Wert, der angibt, ob [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Ruft die am besten geeignete Ersatzschriftart ab. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Bestimmt, ob [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Entfernt die Schrift-Cache-Datei. |
| [reset()](#reset--) | Setzt den Schriftordner und den Standard-Schriftartnamen auf die Systemvorgabe zurück. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Beschränkt die Schriftverwendung auf eine Liste von Schriften. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Setzt den Standard-Schriftartnamen. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Setzt die Schriftart-Ersetzungsliste. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Überschreibe die Schriftordnerliste für  folder |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Überschreibe die Schriftordnerliste für  folders |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Setzt die Ordner, aus denen TrueType-Schriften geladen werden, und löscht alle geladenen Schriften. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Liest oder setzt einen Wert, der angibt, ob [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Aktualisiert den Schrift-Cache für PSD-Dateien, die Textebenen enthalten. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Ruft den Adobe-Schriftartnamen anhand des Schriftfamiliennamens ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Der Schriftfamilienname. |

**Returns:**
java.lang.String - Der Adobe-Schriftname nach Schriftfamiliennamen.
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


Ruft den Standard-Schriftartnamen ab.

**Returns:**
java.lang.String - Standard-Schriftname
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Ruft die Standard-Schriftordner ab.

**Returns:**
java.lang.String[] - Gibt Systemordner zurück
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Ruft das Schriftart-Ersetzungsarray anhand des Schriftartnamens ab

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name der Schrift. |

**Returns:**
java.lang.String[] - Array von Namen der Ersatzschriften für bereitgestellte Schriften
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Ruft eine Kopie des Arrays ab, das die Liste der Ordner enthält, in denen Aspose.Imaging nach TrueType-Schriften sucht.

Der zurückgegebene Wert ist eine Kopie der Daten, die Aspose.Imaging verwendet. Wenn Sie die Einträge im zurückgegebenen Array ändern, hat dies keine Auswirkung auf die Dokumentendarstellung. Um neue Schriftortungen anzugeben, verwenden Sie die  setFontsFolders  Methode.

**Returns:**
java.lang.String[] - Eine Kopie der aktuellen Schriftorte.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Liest oder setzt einen Wert, der angibt, ob [get alternative font].

Wert:  true  wenn [get alternative font]; andernfalls,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Ermittelt die am besten geeignete Ersatzschrift. Wenn alle Ersatzschriften nicht erlaubt sind, wird die erste erlaubte und verfügbare Schrift zurückgegeben. Wenn keine verfügbaren Schriften vorhanden sind, wird die Schrift aus dem Argument zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name der Schrift. |

**Returns:**
java.lang.String - Der Name der ersetzten Schrift
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


Bestimmt, ob [is font allowed] [the specified font name].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Name der Schrift. |

**Returns:**
boolean -  true  wenn [is font allowed] [der angegebene Schriftname]; andernfalls,  false .
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


Entfernt die Schrift-Cache-Datei.

### reset() {#reset--}
```
public static void reset()
```


Setzt den Schriftordner und den Standard-Schriftartnamen auf die Systemvorgabe zurück.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Beschränkt Schriften anhand einer Schriftliste. Bitte prüfen Sie die tatsächlichen Schriftnamen vor der Einschränkung. Setzen Sie die erlaubte Schriftliste auf Null, um Einschränkungen zu entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontList | java.lang.String[] | Die Schriftliste. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Setzt den Standard-Schriftartnamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Der Standardname der Schrift. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Legt die Ersatzschriftliste fest. Wenn eine Schrift nicht erlaubt ist, wird ein Ersatz gefunden. Die erste Schrift in der Liste wird zuerst verwendet. Wenn diese ebenfalls eingeschränkt ist, wird die nächste Schrift aus der Liste ausgewählt. Wenn die Schrift keine Ersatzschriften hat oder alle Ersatzschriften nicht erlaubt sind, wird die erste erlaubte Schrift aus der erlaubten Schriftliste verwendet. Wenn keine erlaubten und verfügbaren Schriften vorhanden sind, versucht die Bibliothek, die systemweite Standardschrift zu verwenden, selbst wenn sie nicht erlaubt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontToReplace | java.lang.String | Die zu ersetzende Schrift. |
| fontNames | java.lang.String[] | Die Ersatzschriftnamen in Reihenfolge der Ähnlichkeit. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Überschreibe die Schriftordnerliste für  folder

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | java.lang.String | Ordner mit TrueType-Schriften. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Überschreibe die Schriftordnerliste für  folders

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folders | java.lang.String[] | Array von Ordnern |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten. Es werden keine Prüfungen der Schriftarten‑Ordner durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folders | java.lang.String[] | Die Schriftarten‑Ordner. |
| rekursiv | boolean | wenn auf  true  [rekursiv] gesetzt. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [get alternative font].

Wert:  true  wenn [get alternative font]; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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


Aktualisiert den Schriftarten‑Cache für PSD‑Dateien, die Textebenen enthalten. Diese Methode garantiert, dass Schriftarten aus dem Ordner fontsFolder, die mit der Methode FontSettings.setFontsFolder(fontsFolder) festgelegt wurden, oder nach dem Zurücksetzen der Schriftarten mit FontSettings.reset() berücksichtigt werden, wenn PSD‑Dateien verarbeitet werden. Bitte verwenden Sie diese Methode jedes Mal, wenn FontSettings.setFontsFolder(fontsFolder) oder FontSettings.reset() für PSD‑Bilder aufgerufen wird. Ohne Aufruf dieser Methode gibt es keine Garantie, dass die Schriftarten aktualisiert werden.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

