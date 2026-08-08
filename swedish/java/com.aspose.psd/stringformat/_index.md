---
title: "StringFormat"
second_title: "Aspose.PSD för Java API-referens"
description: "Inkapslar information om textlayout såsom justering, orientering och tabbstopp, samt displaymanipulationer som insättning av ellips och nationell siffrasubstitution samt OpenType-funktioner."
type: docs
weight: 106
url: /sv/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Inkapslar information om textlayout (såsom justering, orientering och tabbstopp) displaymanipulationer (såsom insättning av ellips och nationell siffrasubstitution) och OpenType-funktioner. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initierar ett nytt  com.aspose.psd.StringFormat  -objekt. |
| [StringFormat(int options)](#StringFormat-int-) | Initierar ett nytt  com.aspose.psd.StringFormat  -objekt med den angivna  com.aspose.psd.StringFormatFlags  -enumerationen och språk. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Initierar ett nytt  com.aspose.psd.StringFormat  -objekt från det angivna befintliga  com.aspose.psd.StringFormat  -objektet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Skapar en djup klon av detta  com.aspose.psd.StringFormat  -objekt. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Hämtar information om textjustering på den vertikala planet. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Hämtar språket som används när lokala siffror ersätts med västerländska siffror. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Hämtar metoden som ska användas för siffrasubstitution. |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| [getFormatFlags()](#getFormatFlags--) | Hämtar en  com.aspose.psd.StringFormatFlags  -enumeration som innehåller formateringsinformation. |
| [getGenericDefault()](#getGenericDefault--) | Hämtar ett generiskt standard  com.aspose.psd.StringFormat  -objekt. |
| [getGenericTypographic()](#getGenericTypographic--) | Hämtar ett generiskt typografiskt  com.aspose.psd.StringFormat  -objekt. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Hämtar  com.aspose.psd.HotkeyPrefix  -objektet för detta  com.aspose.psd.StringFormat  -objekt. |
| [getLineAlignment()](#getLineAlignment--) | Hämtar radjusteringen på det horisontella planet. |
| [getTabStops()](#getTabStops--) | Hämtar en array med avstånd mellan tabbstopp i de enheter som anges av egenskapen  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | Hämtar  com.aspose.psd.StringTrimming  -enumerationen för detta  com.aspose.psd.StringFormat  -objekt. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Ställer in information om textjustering på det vertikala planet. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Ställer in språket som används när lokala siffror ersätts med västerländska siffror. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Ställer in metoden som ska användas för siffrasubstitution. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Ställer in en  com.aspose.psd.StringFormatFlags  uppräkning som innehåller formateringsinformation. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Ställer in  com.aspose.psd.HotkeyPrefix  objektet för detta  com.aspose.psd.StringFormat  objekt. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Ställer in radjusteringen på den horisontella planet. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Ställer in tabbstopp för detta  com.aspose.psd.StringFormat  objekt. |
| [setTrimming(int value)](#setTrimming-int-) | Ställer in  com.aspose.psd.StringTrimming  uppräkning för detta  com.aspose.psd.StringFormat  objekt. |
| [toString()](#toString--) | Konverterar detta  com.aspose.psd.StringFormat  objekt till en människoläsbar sträng. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initierar ett nytt  com.aspose.psd.StringFormat  -objekt.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initierar ett nytt  com.aspose.psd.StringFormat  -objekt med den angivna  com.aspose.psd.StringFormatFlags  -enumerationen och språk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alternativ | int | Den  com.aspose.psd.StringFormatFlags  uppräkningen för det nya  com.aspose.psd.StringFormat  objektet. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initierar ett nytt  com.aspose.psd.StringFormat  -objekt från det angivna befintliga  com.aspose.psd.StringFormat  -objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Det  com.aspose.psd.StringFormat  objektet som ska användas för att initiera det nya  com.aspose.psd.StringFormat  objektet. |

### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Skapar en djup klon av detta  com.aspose.psd.StringFormat  -objekt.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Hämtar information om textjustering på den vertikala planet.

**Returns:**
int – En  com.aspose.psd.StringAlignment  uppräkning som specificerar information om textjustering.
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


Hämtar språket som används när lokala siffror ersätts med västerländska siffror.

**Returns:**
int – En National Language Support (NLS) språkidentifierare som identifierar språket som kommer att användas när lokala siffror ersätts med västerländska siffror. Du kan skicka  P:System.Globalization.CultureInfo.LCID  egenskapen för ett  System.Globalization.CultureInfo  objekt som NLS-språkidentifierare. Till exempel, anta att du skapar ett  System.Globalization.CultureInfo  objekt genom att skicka strängen \"ar-EG\" till en  System.Globalization.CultureInfo  konstruktor. Om du skickar  P:System.Globalization.CultureInfo.LCID  egenskapen för det där  System.Globalization.CultureInfo  objektet tillsammans med  com.aspose.psd.StringDigitSubstitute.Traditional  till  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  metoden, så kommer arabiskt-indiska siffror att ersättas med västerländska siffror vid visningstid.

Sättaren introduceras för den föråldrade metoden setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Hämtar metoden som ska användas för siffrasubstitution.

**Returns:**
int – Ett  com.aspose.psd.StringDigitSubstitute  uppräkningsvärde som specificerar hur man ersätter tecken i en sträng som inte kan visas eftersom de inte stöds av det aktuella teckensnittet.

Sättaren introduceras för den föråldrade metoden SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet.

**Returns:**
float – Det första tabbsteg.

Egenskapen introduceras för den borttagna metoden GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Hämtar en  com.aspose.psd.StringFormatFlags  -enumeration som innehåller formateringsinformation.

**Returns:**
int – En  com.aspose.psd.StringFormatFlags  uppräkning som innehåller formateringsinformation.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Hämtar ett generiskt standard  com.aspose.psd.StringFormat  -objekt.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Hämtar ett generiskt typografiskt  com.aspose.psd.StringFormat  -objekt.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Hämtar  com.aspose.psd.HotkeyPrefix  -objektet för detta  com.aspose.psd.StringFormat  -objekt.

**Returns:**
int –  com.aspose.psd.HotkeyPrefix  objektet för detta  com.aspose.psd.StringFormat  objekt, standardvärdet är  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Hämtar radjusteringen på det horisontella planet.

**Returns:**
int – En  com.aspose.psd.StringAlignment  uppräkning som representerar radjusteringen.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Hämtar en array med avstånd mellan tabbstopp i de enheter som anges av egenskapen  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] – Tabbstoppen.

Egenskapen introduceras för den borttagna metoden GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Hämtar  com.aspose.psd.StringTrimming  -enumerationen för detta  com.aspose.psd.StringFormat  -objekt.

**Returns:**
int – En  com.aspose.psd.StringTrimming  uppräkning som anger hur text som ritas med detta  com.aspose.psd.StringFormat  objekt beskärs när den överskrider kanterna på layoutrektangeln.
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


Ställer in information om textjustering på det vertikala planet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En  com.aspose.psd.StringAlignment  uppräkning som specificerar information om textjustering. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Ställer in språket som används när lokala siffror ersätts med västerländska siffror.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Ett National Language Support (NLS) språkidentifierare som identifierar språket som kommer att användas när lokala siffror ersätts med västerländska siffror. Du kan skicka  P:System.Globalization.CultureInfo.LCID  egenskapen för ett  System.Globalization.CultureInfo  objekt som NLS språkidentifierare. Till exempel, anta att du skapar ett  System.Globalization.CultureInfo  objekt genom att skicka strängen "ar-EG" till en  System.Globalization.CultureInfo  konstruktor. Om du skickar  P:System.Globalization.CultureInfo.LCID  egenskapen för det  System.Globalization.CultureInfo  objektet tillsammans med  com.aspose.psd.StringDigitSubstitute.Traditional  till  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  metoden, kommer arabiskt-indiska siffror att ersättas med västerländska siffror vid visningstid. |

Sättaren introduceras för den föråldrade metoden SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Ställer in metoden som ska användas för siffrasubstitution.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Ett  com.aspose.psd.StringDigitSubstitute  uppräkningsvärde som specificerar hur man ersätter tecken i en sträng som inte kan visas eftersom de inte stöds av det aktuella teckensnittet. |

Sättaren introduceras för den föråldrade metoden SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Ställer in en  com.aspose.psd.StringFormatFlags  uppräkning som innehåller formateringsinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En  com.aspose.psd.StringFormatFlags  uppräkning som innehåller formateringsinformation. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Ställer in  com.aspose.psd.HotkeyPrefix  objektet för detta  com.aspose.psd.StringFormat  objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Objektet  com.aspose.psd.HotkeyPrefix  för detta  com.aspose.psd.StringFormat  objekt, standardvärdet är  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Ställer in radjusteringen på den horisontella planet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En  com.aspose.psd.StringAlignment  uppräkning som representerar radjusteringen. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Ställer in tabbstopp för detta  com.aspose.psd.StringFormat  objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstTabOffset | float | Antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| tabStops | float[] | En array av avstånd mellan tabbstopp i de enheter som anges av egenskapen  com.aspose.psd.Graphics.PageUnit . |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Ställer in  com.aspose.psd.StringTrimming  uppräkning för detta  com.aspose.psd.StringFormat  objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En  com.aspose.psd.StringTrimming  uppräkning som indikerar hur text som ritas med detta  com.aspose.psd.StringFormat  objekt beskärs när den överskrider kanterna på layoutrektangeln. |

### toString() {#toString--}
```
public String toString()
```


Konverterar detta  com.aspose.psd.StringFormat  objekt till en människoläsbar sträng.

**Returns:**
java.lang.String - En strängrepresentation av detta  com.aspose.psd.StringFormat  objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

