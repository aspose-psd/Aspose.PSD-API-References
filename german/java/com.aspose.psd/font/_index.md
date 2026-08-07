---
title: "Schriftart"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil-Attribute."
type: docs
weight: 46
url: /de/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil-Attribute. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Initialisiert ein neues  com.aspose.psd.Font , das die angegebene vorhandene  com.aspose.psd.Font  und die  com.aspose.psd.FontStyle  Aufzählung verwendet. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe und einem Stil. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe, Stil, Einheit und Zeichensatz. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe, Stil und Einheit. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine exakte tiefe Kopie dieses  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob das angegebene Objekt ein  com.aspose.psd.Font  ist und dieselben Eigenschaftswerte wie dieses  com.aspose.psd.Font  hat. |
| [getBold()](#getBold--) | Gibt einen Wert zurück, der angibt, ob dieses  Font  fett ist. |
| [getCharacterSet()](#getCharacterSet--) | Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den dieses  Font  verwendet. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Gibt einen Wert zurück, der angibt, ob dieses  Font  kursiv ist. |
| [getName()](#getName--) | Gibt den Namen der Schriftart dieses  Font  zurück. |
| [getSize()](#getSize--) | Gibt die Em-Größe dieses  Font  zurück, gemessen in den Einheiten, die durch die Eigenschaft  P:Aspose.Imaging.Font.Unit  angegeben sind. |
| [getStrikeout()](#getStrikeout--) | Gibt einen Wert zurück, der angibt, ob dieses  Font  eine horizontale Linie durch die Schriftart definiert. |
| [getStyle()](#getStyle--) | Gibt Stilinformationen für dieses  Font  zurück. |
| [getUnderline()](#getUnderline--) | Gibt einen Wert zurück, der angibt, ob dieses  Font  unterstrichen ist. |
| [getUnit()](#getUnit--) | Gibt die Maßeinheit für dieses  Font  zurück. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für dieses  com.aspose.psd.Font  zurück. |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe und Einheit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses com.aspose.psd.Font zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initialisiert ein neues  com.aspose.psd.Font , das die angegebene vorhandene  com.aspose.psd.Font  und die  com.aspose.psd.FontStyle  Aufzählung verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Der vorhandene com.aspose.psd.Font, aus dem der neue com.aspose.psd.Font erstellt werden soll. |
| newStyle | int | Der com.aspose.psd.FontStyle, der auf den neuen com.aspose.psd.Font angewendet werden soll. Mehrere Werte der com.aspose.psd.FontStyle‑Aufzählung können mit dem ODER‑Operator kombiniert werden. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initialisiert ein neues com.aspose.psd.Font mit einer angegebenen Größe. Der Zeichensatz wird auf F:Aspose.Imaging.CharacterSet.Default gesetzt, die Grafikeinheit auf F:Aspose.Imaging.GraphicsUnit.Point und der Schriftstil auf F:Aspose.Imaging.FontStyle.Regular.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des com.aspose.psd.Font. |
| emSize | float | Die Em-Größe des neuen Schriftsatzes in Punkten. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initialisiert ein neues com.aspose.psd.Font mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf F:Aspose.Imaging.CharacterSet.Default gesetzt, die Grafikeinheit auf F:Aspose.Imaging.GraphicsUnit.Point.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des com.aspose.psd.Font. |
| emSize | float | Die Em-Größe des neuen Schriftsatzes in Punkten. |
| style | int | Der com.aspose.psd.FontStyle des neuen Schriftsatzes. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe, Stil, Einheit und Zeichensatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des com.aspose.psd.Font. |
| emSize | float | Die Em-Größe des neuen Schriftsatzes in den durch den Parameter unit angegebenen Einheiten. |
| style | int | Der com.aspose.psd.FontStyle des neuen Schriftsatzes. |
| unit | int | Die com.aspose.psd.GraphicsUnit des neuen Schriftsatzes. |
| characterSet | int | Ein Zeichensatz, der für diesen Schriftsatz verwendet werden soll. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initialisiert ein neues  com.aspose.psd.Font  mit einer angegebenen Größe, Stil und Einheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des com.aspose.psd.Font. |
| emSize | float | Die Em-Größe des neuen Schriftsatzes in den durch den Parameter unit angegebenen Einheiten. |
| style | int | Der com.aspose.psd.FontStyle des neuen Schriftsatzes. |
| unit | int | Die com.aspose.psd.GraphicsUnit des neuen Schriftsatzes. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Erstellt eine exakte tiefe Kopie dieses  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob das angegebene Objekt ein  com.aspose.psd.Font  ist und dieselben Eigenschaftswerte wie dieses  com.aspose.psd.Font  hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolesch – Wahr, wenn der Parameter obj ein com.aspose.psd.Font ist und dieselben Eigenschaftswerte wie dieses com.aspose.psd.Font hat; andernfalls falsch.
### getBold() {#getBold--}
```
public boolean getBold()
```


Gibt einen Wert zurück, der angibt, ob dieses  Font  fett ist.

**Returns:**
boolesch – Wahr, wenn dieses Font fett ist; andernfalls falsch.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den dieses  Font  verwendet.

**Returns:**
int – Ein Zeichensatz, den dieses Font verwendet.
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


Gibt einen Wert zurück, der angibt, ob dieses  Font  kursiv ist.

**Returns:**
boolesch – Wahr, wenn dieses Font kursiv ist; andernfalls falsch.
### getName() {#getName--}
```
public String getName()
```


Gibt den Namen der Schriftart dieses  Font  zurück.

**Returns:**
java.lang.String – Eine Zeichenkettenrepräsentation des Schriftartnamens dieses Font.
### getSize() {#getSize--}
```
public float getSize()
```


Gibt die Em-Größe dieses  Font  zurück, gemessen in den Einheiten, die durch die Eigenschaft  P:Aspose.Imaging.Font.Unit  angegeben sind.

**Returns:**
float – Die Em-Größe dieses Font.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Gibt einen Wert zurück, der angibt, ob dieses  Font  eine horizontale Linie durch die Schriftart definiert.

**Returns:**
boolesch – Wahr, wenn dieses Font einen horizontalen Strich durch sich hat; andernfalls falsch.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gibt Stilinformationen für dieses  Font  zurück.

**Returns:**
int – Eine FontStyle‑Aufzählung, die Stilinformationen für dieses Font enthält.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Gibt einen Wert zurück, der angibt, ob dieses  Font  unterstrichen ist.

**Returns:**
boolesch – Wahr, wenn dieses Font unterstrichen ist; andernfalls falsch.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Gibt die Maßeinheit für dieses  Font  zurück.

**Returns:**
int - Eine GraphicsUnit, die die Maßeinheit für diese Font darstellt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für dieses  com.aspose.psd.Font  zurück.

**Returns:**
int - Der Hashcode für dieses com.aspose.psd.Font.
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initialisiert ein neues com.aspose.psd.Font mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf F:Aspose.Imaging.CharacterSet.Default gesetzt, der Stil wird auf F:Aspose.Imaging.FontStyle.Regular gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Eine Zeichenkettenrepräsentation des Namens des com.aspose.psd.Font. |
| emSize | float | Die Em-Größe des neuen Schriftsatzes in den durch den Parameter unit angegebenen Einheiten. |
| unit | int | Die com.aspose.psd.GraphicsUnit des neuen Schriftsatzes. |

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


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses com.aspose.psd.Font zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses com.aspose.psd.Font darstellt.
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

