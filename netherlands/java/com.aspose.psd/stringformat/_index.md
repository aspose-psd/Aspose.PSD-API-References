---
title: "StringFormat"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Omsluit tekstindelingsinformatie zoals uitlijning, oriëntatie en tabstops, weergavemanipulaties zoals het invoegen van een ellipsis en nationale cijfervervanging en OpenType-functies."
type: docs
weight: 106
url: /nl/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Omsluit tekstindelingsinformatie (zoals uitlijning, oriëntatie en tabstops) weergavemanipulaties (zoals het invoegen van een ellipsis en nationale cijfervervanging) en OpenType-functies. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialiseert een nieuw  com.aspose.psd.StringFormat  object. |
| [StringFormat(int options)](#StringFormat-int-) | Initialiseert een nieuw  com.aspose.psd.StringFormat  object met de opgegeven  com.aspose.psd.StringFormatFlags  enumeratie en taal. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Initialiseert een nieuw  com.aspose.psd.StringFormat  object vanuit het opgegeven bestaande  com.aspose.psd.StringFormat  object. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Maakt een diepe kloon van dit  com.aspose.psd.StringFormat  object. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Haalt tekstuitlijningsinformatie op het verticale vlak op. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Haalt de taal op die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Haalt de methode op die moet worden gebruikt voor cijfervervanging. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Haalt het aantal spaties op tussen het begin van een tekstregel en de eerste tabstop. |
| [getFormatFlags()](#getFormatFlags--) | Haalt een  com.aspose.psd.StringFormatFlags  enumeratie op die opmaakinformatie bevat. |
| [getGenericDefault()](#getGenericDefault--) | Haalt een generiek standaard  com.aspose.psd.StringFormat  object op. |
| [getGenericTypographic()](#getGenericTypographic--) | Haalt een generiek typografisch  com.aspose.psd.StringFormat  object op. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Haalt het  com.aspose.psd.HotkeyPrefix  object op voor dit  com.aspose.psd.StringFormat  object. |
| [getLineAlignment()](#getLineAlignment--) | Haalt de lijnuitlijning op het horizontale vlak op. |
| [getTabStops()](#getTabStops--) | Haalt een array van afstanden tussen tabstops op in de eenheden gespecificeerd door de  P:Aspose.Imaging.getGraphics().PageUnit  eigenschap. |
| [getTrimming()](#getTrimming--) | Haalt de  com.aspose.psd.StringTrimming  enumeratie op voor dit  com.aspose.psd.StringFormat  object. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Stelt tekstuitlijningsinformatie in op het verticale vlak. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Stelt de taal in die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Stelt de methode in die wordt gebruikt voor cijfervervanging. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Stelt een  com.aspose.psd.StringFormatFlags  enumeratie in die opmaakinformatie bevat. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Stelt het  com.aspose.psd.HotkeyPrefix  object in voor dit  com.aspose.psd.StringFormat  object. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Stelt de regeluitlijning in op het horizontale vlak. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Stelt tabstops in voor dit  com.aspose.psd.StringFormat  object. |
| [setTrimming(int value)](#setTrimming-int-) | Stelt de  com.aspose.psd.StringTrimming  enumeratie in voor dit  com.aspose.psd.StringFormat  object. |
| [toString()](#toString--) | Converteert dit  com.aspose.psd.StringFormat  object naar een menselijk leesbare tekenreeks. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialiseert een nieuw  com.aspose.psd.StringFormat  object.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialiseert een nieuw  com.aspose.psd.StringFormat  object met de opgegeven  com.aspose.psd.StringFormatFlags  enumeratie en taal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | int | De  com.aspose.psd.StringFormatFlags  enumeratie voor het nieuwe  com.aspose.psd.StringFormat  object. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialiseert een nieuw  com.aspose.psd.StringFormat  object vanuit het opgegeven bestaande  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Het  com.aspose.psd.StringFormat  object waaruit het nieuwe  com.aspose.psd.StringFormat  object moet worden geïnitialiseerd. |

### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Maakt een diepe kloon van dit  com.aspose.psd.StringFormat  object.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Haalt tekstuitlijningsinformatie op het verticale vlak op.

**Returns:**
int - Een  com.aspose.psd.StringAlignment  enumeratie die tekstuitlijningsinformatie specificeert.
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


Haalt de taal op die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers.

**Returns:**
int - Een National Language Support (NLS) taalidentificatie die de taal identificeert die zal worden gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. U kunt de  P:System.Globalization.CultureInfo.LCID  eigenschap van een  System.Globalization.CultureInfo  object doorgeven als de NLS-taalidentificatie. Bijvoorbeeld, stel dat u een  System.Globalization.CultureInfo  object maakt door de tekenreeks "ar-EG" door te geven aan een  System.Globalization.CultureInfo  constructor. Als u de  P:System.Globalization.CultureInfo.LCID  eigenschap van dat  System.Globalization.CultureInfo  object samen met  com.aspose.psd.StringDigitSubstitute.Traditional  doorgeeft aan de  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  methode, dan worden Arabisch-Indic cijfers vervangen door westerse cijfers tijdens het weergeven.

De setter is geïntroduceerd voor de verouderde methode setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Haalt de methode op die moet worden gebruikt voor cijfervervanging.

**Returns:**
int - Een  com.aspose.psd.StringDigitSubstitute  enumeratiewaarde die specificeert hoe tekens in een tekenreeks moeten worden vervangen die niet kunnen worden weergegeven omdat ze niet worden ondersteund door het huidige lettertype.

De setter is geïntroduceerd voor de verouderde methode SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Haalt het aantal spaties op tussen het begin van een tekstregel en de eerste tabstop.

**Returns:**
float - De eerste tab-offset.

De eigenschap is geïntroduceerd voor de verwijderde methode GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Haalt een  com.aspose.psd.StringFormatFlags  enumeratie op die opmaakinformatie bevat.

**Returns:**
int - Een  com.aspose.psd.StringFormatFlags  enumeratie die opmaakinformatie bevat.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Haalt een generiek standaard  com.aspose.psd.StringFormat  object op.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Haalt een generiek typografisch  com.aspose.psd.StringFormat  object op.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Haalt het  com.aspose.psd.HotkeyPrefix  object op voor dit  com.aspose.psd.StringFormat  object.

**Returns:**
int - Het  com.aspose.psd.HotkeyPrefix  object voor dit  com.aspose.psd.StringFormat  object, de standaard is  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Haalt de lijnuitlijning op het horizontale vlak op.

**Returns:**
int - Een  com.aspose.psd.StringAlignment  enumeratie die de regeluitlijning weergeeft.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Haalt een array van afstanden tussen tabstops op in de eenheden gespecificeerd door de  P:Aspose.Imaging.getGraphics().PageUnit  eigenschap.

**Returns:**
float[] - De tabstops.

De eigenschap is geïntroduceerd voor de verwijderde methode GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Haalt de  com.aspose.psd.StringTrimming  enumeratie op voor dit  com.aspose.psd.StringFormat  object.

**Returns:**
int - Een  com.aspose.psd.StringTrimming  enumeratie die aangeeft hoe tekst die met dit  com.aspose.psd.StringFormat  object wordt getekend, wordt bijgesneden wanneer deze de randen van de lay-outrechthoek overschrijdt.
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


Stelt tekstuitlijningsinformatie in op het verticale vlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  com.aspose.psd.StringAlignment  enumeratie die tekstuitlijningsinformatie specificeert. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Stelt de taal in die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Een National Language Support (NLS) taalidentificatie die de taal identificeert die zal worden gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. U kunt de  P:System.Globalization.CultureInfo.LCID  eigenschap van een  System.Globalization.CultureInfo  object doorgeven als de NLS-taalidentificatie. Bijvoorbeeld, stel dat u een  System.Globalization.CultureInfo  object maakt door de tekenreeks "ar-EG" door te geven aan een  System.Globalization.CultureInfo  constructor. Als u de  P:System.Globalization.CultureInfo.LCID  eigenschap van dat  System.Globalization.CultureInfo  object samen met  com.aspose.psd.StringDigitSubstitute.Traditional  doorgeeft aan de  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  methode, dan worden Arabisch-Indic cijfers vervangen door westerse cijfers tijdens het weergeven. |

The setter is geïntroduceerd voor de verouderde methode SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Stelt de methode in die wordt gebruikt voor cijfervervanging.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Een  com.aspose.psd.StringDigitSubstitute  enumeratiewaarde die aangeeft hoe tekens in een tekenreeks moeten worden vervangen die niet kunnen worden weergegeven omdat ze niet worden ondersteund door het huidige lettertype. |

The setter is geïntroduceerd voor de verouderde methode SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Stelt een  com.aspose.psd.StringFormatFlags  enumeratie in die opmaakinformatie bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  com.aspose.psd.StringFormatFlags  enumeratie die opmaakinformatie bevat. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Stelt het  com.aspose.psd.HotkeyPrefix  object in voor dit  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Het  com.aspose.psd.HotkeyPrefix  object voor dit  com.aspose.psd.StringFormat  object, de standaard is  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Stelt de regeluitlijning in op het horizontale vlak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  com.aspose.psd.StringAlignment  enumeratie die de regeluitlijning weergeeft. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Stelt tabstops in voor dit  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstTabOffset | float | Het aantal spaties tussen het begin van een regel tekst en de eerste tabstop. |
| tabStops | float[] | Een array van afstanden tussen tabstops in de eenheden die zijn opgegeven door de  com.aspose.psd.Graphics.PageUnit  eigenschap. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Stelt de  com.aspose.psd.StringTrimming  enumeratie in voor dit  com.aspose.psd.StringFormat  object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  com.aspose.psd.StringTrimming  enumeratie die aangeeft hoe tekst die met dit  com.aspose.psd.StringFormat  object is getekend wordt bijgesneden wanneer deze de randen van de lay-outrechthoek overschrijdt. |

### toString() {#toString--}
```
public String toString()
```


Converteert dit  com.aspose.psd.StringFormat  object naar een menselijk leesbare tekenreeks.

**Returns:**
java.lang.String - Een tekenreeksrepresentatie van dit  com.aspose.psd.StringFormat  object.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

