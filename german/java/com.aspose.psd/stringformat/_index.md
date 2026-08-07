---
title: "StringFormat"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Kapselt Textlayout-Informationen wie Ausrichtung, Orientierung und Tabstopps sowie Anzeige-Manipulationen wie das Einfügen von Auslassungszeichen, nationale Ziffernersetzung und OpenType‑Funktionen."
type: docs
weight: 106
url: /de/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Kapselt Textlayout-Informationen (wie Ausrichtung, Orientierung und Tabstopps), Anzeige-Manipulationen (wie das Einfügen von Auslassungszeichen und nationale Ziffernersetzung) und OpenType‑Funktionen. Diese Klasse kann nicht vererbt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialisiert ein neues  com.aspose.psd.StringFormat  Objekt. |
| [StringFormat(int options)](#StringFormat-int-) | Initialisiert ein neues  com.aspose.psd.StringFormat  Objekt mit der angegebenen  com.aspose.psd.StringFormatFlags  Aufzählung und Sprache. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Initialisiert ein neues  com.aspose.psd.StringFormat  Objekt aus dem angegebenen vorhandenen  com.aspose.psd.StringFormat  Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Erstellt einen tiefen Klon dieses  com.aspose.psd.StringFormat  Objekts. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Ruft Textausrichtungsinformationen in der Vertikalebene ab. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Ruft die Sprache ab, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Ruft die Methode ab, die für die Ziffernersetzung verwendet werden soll. |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Ruft die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp ab. |
| [getFormatFlags()](#getFormatFlags--) | Ruft eine  com.aspose.psd.StringFormatFlags  Aufzählung ab, die Formatierungsinformationen enthält. |
| [getGenericDefault()](#getGenericDefault--) | Ruft ein generisches Standard-  com.aspose.psd.StringFormat  Objekt ab. |
| [getGenericTypographic()](#getGenericTypographic--) | Ruft ein generisches typografisches  com.aspose.psd.StringFormat  Objekt ab. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ruft das  com.aspose.psd.HotkeyPrefix  Objekt für dieses  com.aspose.psd.StringFormat  Objekt ab. |
| [getLineAlignment()](#getLineAlignment--) | Ruft die Zeilenausrichtung in der Horizontalebene ab. |
| [getTabStops()](#getTabStops--) | Ruft ein Array von Abständen zwischen Tabstopps in den Einheiten ab, die durch die Eigenschaft  P:Aspose.Imaging.getGraphics().PageUnit  angegeben sind. |
| [getTrimming()](#getTrimming--) | Ruft die  com.aspose.psd.StringTrimming  Aufzählung für dieses  com.aspose.psd.StringFormat  Objekt ab. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Setzt Textausrichtungsinformationen in der Vertikalebene. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Setzt die Sprache, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Setzt die Methode, die für die Ziffernersetzung verwendet werden soll. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Setzt eine  com.aspose.psd.StringFormatFlags  Aufzählung, die Formatierungsinformationen enthält. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Setzt das  com.aspose.psd.HotkeyPrefix  Objekt für dieses  com.aspose.psd.StringFormat  Objekt ab. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Legt die Zeilenausrichtung auf der horizontalen Ebene fest. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Legt Tabstopps für dieses  com.aspose.psd.StringFormat  Objekt fest. |
| [setTrimming(int value)](#setTrimming-int-) | Legt die  com.aspose.psd.StringTrimming  Aufzählung für dieses  com.aspose.psd.StringFormat  Objekt fest. |
| [toString()](#toString--) | Konvertiert dieses  com.aspose.psd.StringFormat  Objekt in einen menschenlesbaren String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialisiert ein neues  com.aspose.psd.StringFormat  Objekt.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialisiert ein neues  com.aspose.psd.StringFormat  Objekt mit der angegebenen  com.aspose.psd.StringFormatFlags  Aufzählung und Sprache.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Optionen | int | Die  com.aspose.psd.StringFormatFlags  Aufzählung für das neue  com.aspose.psd.StringFormat  Objekt. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialisiert ein neues  com.aspose.psd.StringFormat  Objekt aus dem angegebenen vorhandenen  com.aspose.psd.StringFormat  Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Das  com.aspose.psd.StringFormat  Objekt, aus dem das neue  com.aspose.psd.StringFormat  Objekt initialisiert wird. |

### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Erstellt einen tiefen Klon dieses  com.aspose.psd.StringFormat  Objekts.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ruft Textausrichtungsinformationen in der Vertikalebene ab.

**Returns:**
int - Eine  com.aspose.psd.StringAlignment  Aufzählung, die Informationen zur Textausrichtung angibt.
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


Ruft die Sprache ab, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden.

**Returns:**
int - Ein National Language Support (NLS) Sprachbezeichner, der die Sprache identifiziert, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. Sie können die  P:System.Globalization.CultureInfo.LCID  Eigenschaft eines  System.Globalization.CultureInfo  Objekts als NLS-Sprachbezeichner übergeben. Zum Beispiel, nehmen Sie an, Sie erstellen ein  System.Globalization.CultureInfo  Objekt, indem Sie den String \"ar-EG\" an einen  System.Globalization.CultureInfo  Konstruktor übergeben. Wenn Sie die  P:System.Globalization.CultureInfo.LCID  Eigenschaft dieses  System.Globalization.CultureInfo  Objekts zusammen mit  com.aspose.psd.StringDigitSubstitute.Traditional  an die  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  Methode übergeben, werden arabisch-indische Ziffern zur Anzeigezeit durch westliche Ziffern ersetzt.

Der Setter wurde für die veraltete Methode setDigitSubstitution eingeführt.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Ruft die Methode ab, die für die Ziffernersetzung verwendet werden soll.

**Returns:**
int - Ein  com.aspose.psd.StringDigitSubstitute  Aufzählungswert, der angibt, wie Zeichen in einem String ersetzt werden, die nicht angezeigt werden können, weil sie von der aktuellen Schriftart nicht unterstützt werden.

Der Setter wurde für die veraltete Methode SetDigitSubstitution eingeführt.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Ruft die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp ab.

**Returns:**
float - Der erste Tab-Offset.

Die Eigenschaft wurde für die entfernte Methode GetTabStops eingeführt.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Ruft eine  com.aspose.psd.StringFormatFlags  Aufzählung ab, die Formatierungsinformationen enthält.

**Returns:**
int - Eine  com.aspose.psd.StringFormatFlags  Aufzählung, die Formatierungsinformationen enthält.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Ruft ein generisches Standard-  com.aspose.psd.StringFormat  Objekt ab.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Ruft ein generisches typografisches  com.aspose.psd.StringFormat  Objekt ab.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ruft das  com.aspose.psd.HotkeyPrefix  Objekt für dieses  com.aspose.psd.StringFormat  Objekt ab.

**Returns:**
int - Das  com.aspose.psd.HotkeyPrefix  Objekt für dieses  com.aspose.psd.StringFormat  Objekt, standardmäßig ist  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Ruft die Zeilenausrichtung in der Horizontalebene ab.

**Returns:**
int - Eine  com.aspose.psd.StringAlignment  Aufzählung, die die Zeilenausrichtung darstellt.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ruft ein Array von Abständen zwischen Tabstopps in den Einheiten ab, die durch die Eigenschaft  P:Aspose.Imaging.getGraphics().PageUnit  angegeben sind.

**Returns:**
float[] - Die Tabstopps.

Die Eigenschaft wurde für die entfernte Methode GetTabStops eingeführt.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ruft die  com.aspose.psd.StringTrimming  Aufzählung für dieses  com.aspose.psd.StringFormat  Objekt ab.

**Returns:**
int - Eine  com.aspose.psd.StringTrimming  Aufzählung, die angibt, wie Text, der mit diesem  com.aspose.psd.StringFormat  Objekt gezeichnet wird, beschnitten wird, wenn er die Ränder des Layout-Rechtecks überschreitet.
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


Setzt Textausrichtungsinformationen in der Vertikalebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine  com.aspose.psd.StringAlignment  Aufzählung, die Informationen zur Textausrichtung angibt. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Setzt die Sprache, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Ein National Language Support (NLS)-Sprachbezeichner, der die Sprache identifiziert, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. Sie können die Eigenschaft P:System.Globalization.CultureInfo.LCID eines System.Globalization.CultureInfo-Objekts als NLS-Sprachbezeichner übergeben. Zum Beispiel, wenn Sie ein System.Globalization.CultureInfo-Objekt erstellen, indem Sie den String "ar-EG" an einen System.Globalization.CultureInfo-Konstruktor übergeben. Wenn Sie die Eigenschaft P:System.Globalization.CultureInfo.LCID dieses System.Globalization.CultureInfo-Objekts zusammen mit com.aspose.psd.StringDigitSubstitute.Traditional an die Methode com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) übergeben, werden arabisch-indische Ziffern zur Anzeigezeit durch westliche Ziffern ersetzt. |

Der Setter wurde für die veraltete Methode SetDigitSubstitution eingeführt. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Setzt die Methode, die für die Ziffernersetzung verwendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Ein com.aspose.psd.StringDigitSubstitute-Enumerationswert, der angibt, wie Zeichen in einem String ersetzt werden, die nicht angezeigt werden können, weil sie von der aktuellen Schriftart nicht unterstützt werden. |

Der Setter wurde für die veraltete Methode SetDigitSubstitution eingeführt. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Setzt eine  com.aspose.psd.StringFormatFlags  Aufzählung, die Formatierungsinformationen enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine com.aspose.psd.StringFormatFlags-Enumeration, die Formatierungsinformationen enthält. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Setzt das  com.aspose.psd.HotkeyPrefix  Objekt für dieses  com.aspose.psd.StringFormat  Objekt ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das com.aspose.psd.HotkeyPrefix-Objekt für dieses com.aspose.psd.StringFormat-Objekt, standardmäßig ist F:Aspose.Imaging.HotkeyPrefix.None. |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Legt die Zeilenausrichtung auf der horizontalen Ebene fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine com.aspose.psd.StringAlignment-Enumeration, die die Zeilenausrichtung darstellt. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Legt Tabstopps für dieses  com.aspose.psd.StringFormat  Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstTabOffset | float | Die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |
| tabStops | float[] | Ein Array von Abständen zwischen Tabstopps in den durch die Eigenschaft com.aspose.psd.Graphics.PageUnit angegebenen Einheiten. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Legt die  com.aspose.psd.StringTrimming  Aufzählung für dieses  com.aspose.psd.StringFormat  Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine com.aspose.psd.StringTrimming-Enumeration, die angibt, wie mit diesem com.aspose.psd.StringFormat-Objekt gezeichneter Text beschnitten wird, wenn er die Ränder des Layoutrechtecks überschreitet. |

### toString() {#toString--}
```
public String toString()
```


Konvertiert dieses  com.aspose.psd.StringFormat  Objekt in einen menschenlesbaren String.

**Returns:**
java.lang.String – Eine String‑Darstellung dieses com.aspose.psd.StringFormat-Objekts.
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

