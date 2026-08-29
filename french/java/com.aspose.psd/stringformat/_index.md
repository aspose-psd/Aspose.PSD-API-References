---
title: "StringFormat"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Encapsule les informations de mise en page du texte telles que l'alignement, l'orientation et les tabulations, les manipulations d'affichage telles que l'insertion d'ellipses et la substitution de chiffres nationaux ainsi que les fonctionnalités OpenType."
type: docs
weight: 106
url: /fr/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Encapsule les informations de mise en page du texte (telles que l'alignement, l'orientation et les tabulations) les manipulations d'affichage (telles que l'insertion d'ellipses et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialise un nouveau  com.aspose.psd.StringFormat  objet. |
| [StringFormat(int options)](#StringFormat-int-) | Initialise un nouveau  com.aspose.psd.StringFormat  objet avec l'énumération  com.aspose.psd.StringFormatFlags  spécifiée et la langue. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Initialise un nouveau  com.aspose.psd.StringFormat  objet à partir du  com.aspose.psd.StringFormat  objet existant spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [deepClone()](#deepClone--) | Crée une copie profonde de ce  com.aspose.psd.StringFormat  objet. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Obtient les informations d'alignement du texte sur le plan vertical. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Obtient la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Obtient la méthode à utiliser pour la substitution de chiffres. |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Obtient le nombre d'espaces entre le début d'une ligne de texte et la première tabulation. |
| [getFormatFlags()](#getFormatFlags--) | Obtient une énumération  com.aspose.psd.StringFormatFlags  qui contient les informations de formatage. |
| [getGenericDefault()](#getGenericDefault--) | Obtient un objet générique par défaut  com.aspose.psd.StringFormat. |
| [getGenericTypographic()](#getGenericTypographic--) | Obtient un objet typographique générique  com.aspose.psd.StringFormat. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtient l'objet  com.aspose.psd.HotkeyPrefix  pour cet objet  com.aspose.psd.StringFormat. |
| [getLineAlignment()](#getLineAlignment--) | Obtient l'alignement de ligne sur le plan horizontal. |
| [getTabStops()](#getTabStops--) | Obtient un tableau de distances entre les tabulations dans les unités spécifiées par la propriété  P:Aspose.Imaging.getGraphics().PageUnit. |
| [getTrimming()](#getTrimming--) | Obtient l'énumération  com.aspose.psd.StringTrimming  pour cet objet  com.aspose.psd.StringFormat. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Définit les informations d'alignement du texte sur le plan vertical. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Définit la méthode à utiliser pour la substitution de chiffres. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Définit une énumération  com.aspose.psd.StringFormatFlags  qui contient les informations de formatage. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Définit l'objet  com.aspose.psd.HotkeyPrefix  pour cet objet  com.aspose.psd.StringFormat. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Définit l'alignement de ligne sur le plan horizontal. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Définit les tabulations pour cet objet  com.aspose.psd.StringFormat. |
| [setTrimming(int value)](#setTrimming-int-) | Définit l'énumération  com.aspose.psd.StringTrimming  pour cet objet  com.aspose.psd.StringFormat . |
| [toString()](#toString--) | Convertit cet objet  com.aspose.psd.StringFormat  en une chaîne lisible par l'homme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialise un nouveau  com.aspose.psd.StringFormat  objet.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialise un nouveau  com.aspose.psd.StringFormat  objet avec l'énumération  com.aspose.psd.StringFormatFlags  spécifiée et la langue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | int | L'énumération  com.aspose.psd.StringFormatFlags  pour le nouvel objet  com.aspose.psd.StringFormat . |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialise un nouveau  com.aspose.psd.StringFormat  objet à partir du  com.aspose.psd.StringFormat  objet existant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | L'objet  com.aspose.psd.StringFormat  à partir duquel initialiser le nouvel objet  com.aspose.psd.StringFormat . |

### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crée une copie profonde de ce  com.aspose.psd.StringFormat  objet.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtient les informations d'alignement du texte sur le plan vertical.

**Returns:**
int - Une énumération  com.aspose.psd.StringAlignment  qui spécifie les informations d'alignement du texte.
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


Obtient la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

**Returns:**
int - Un identifiant de langue National Language Support (NLS) qui identifie la langue à utiliser lorsque les chiffres locaux sont substitués aux chiffres occidentaux. Vous pouvez transmettre la propriété  P:System.Globalization.CultureInfo.LCID  d'un objet  System.Globalization.CultureInfo  comme identifiant de langue NLS. Par exemple, supposons que vous créiez un objet  System.Globalization.CultureInfo  en passant la chaîne "ar-EG" à un constructeur  System.Globalization.CultureInfo . Si vous transmettez la propriété  P:System.Globalization.CultureInfo.LCID  de cet objet  System.Globalization.CultureInfo  ainsi que  com.aspose.psd.StringDigitSubstitute.Traditional  à la méthode  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) , alors les chiffres arabes-indien seront substitués aux chiffres occidentaux lors de l'affichage.

Le mutateur est introduit pour la méthode obsolète setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Obtient la méthode à utiliser pour la substitution de chiffres.

**Returns:**
int - Une valeur d'énumération  com.aspose.psd.StringDigitSubstitute  qui spécifie comment substituer les caractères d'une chaîne qui ne peuvent pas être affichés parce qu'ils ne sont pas pris en charge par la police actuelle.

Le mutateur est introduit pour la méthode obsolète SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Obtient le nombre d'espaces entre le début d'une ligne de texte et la première tabulation.

**Returns:**
float - Le premier décalage de tabulation.

La propriété est introduite pour la méthode supprimée GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Obtient une énumération  com.aspose.psd.StringFormatFlags  qui contient les informations de formatage.

**Returns:**
int - Une énumération  com.aspose.psd.StringFormatFlags  qui contient des informations de mise en forme.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Obtient un objet générique par défaut  com.aspose.psd.StringFormat.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Obtient un objet typographique générique  com.aspose.psd.StringFormat.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtient l'objet  com.aspose.psd.HotkeyPrefix  pour cet objet  com.aspose.psd.StringFormat.

**Returns:**
int - L'objet  com.aspose.psd.HotkeyPrefix  pour cet objet  com.aspose.psd.StringFormat , la valeur par défaut étant  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Obtient l'alignement de ligne sur le plan horizontal.

**Returns:**
int - Une énumération  com.aspose.psd.StringAlignment  qui représente l'alignement de ligne.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtient un tableau de distances entre les tabulations dans les unités spécifiées par la propriété  P:Aspose.Imaging.getGraphics().PageUnit.

**Returns:**
float[] - Les arrêts de tabulation.

La propriété est introduite pour la méthode supprimée GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtient l'énumération  com.aspose.psd.StringTrimming  pour cet objet  com.aspose.psd.StringFormat.

**Returns:**
int - Une énumération  com.aspose.psd.StringTrimming  qui indique comment le texte dessiné avec cet objet  com.aspose.psd.StringFormat  est tronqué lorsqu'il dépasse les bords du rectangle de mise en page.
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


Définit les informations d'alignement du texte sur le plan vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération  com.aspose.psd.StringAlignment  qui spécifie les informations d'alignement du texte. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Un identifiant de langue National Language Support (NLS) qui identifie la langue à utiliser lorsque les chiffres locaux sont substitués aux chiffres occidentaux. Vous pouvez transmettre la propriété  P:System.Globalization.CultureInfo.LCID  d'un objet  System.Globalization.CultureInfo  comme identifiant de langue NLS. Par exemple, supposons que vous créiez un objet  System.Globalization.CultureInfo  en passant la chaîne "ar-EG" à un constructeur  System.Globalization.CultureInfo . Si vous transmettez la propriété  P:System.Globalization.CultureInfo.LCID  de cet objet  System.Globalization.CultureInfo  ainsi que  com.aspose.psd.StringDigitSubstitute.Traditional  à la méthode  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) , alors les chiffres arabes-indien seront substitués aux chiffres occidentaux lors de l'affichage. |

Le mutateur est introduit pour la méthode obsolète SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Définit la méthode à utiliser pour la substitution de chiffres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Une valeur d'énumération  com.aspose.psd.StringDigitSubstitute  qui spécifie comment substituer les caractères d'une chaîne qui ne peuvent pas être affichés parce qu'ils ne sont pas pris en charge par la police actuelle. |

Le mutateur est introduit pour la méthode obsolète SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Définit une énumération  com.aspose.psd.StringFormatFlags  qui contient les informations de formatage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération  com.aspose.psd.StringFormatFlags  qui contient des informations de mise en forme. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Définit l'objet  com.aspose.psd.HotkeyPrefix  pour cet objet  com.aspose.psd.StringFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'objet  com.aspose.psd.HotkeyPrefix  pour cet objet  com.aspose.psd.StringFormat , la valeur par défaut étant  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Définit l'alignement de ligne sur le plan horizontal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération  com.aspose.psd.StringAlignment  qui représente l'alignement de ligne. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Définit les tabulations pour cet objet  com.aspose.psd.StringFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstTabOffset | float | Le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| tabStops | float[] | Un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété com.aspose.psd.Graphics.PageUnit. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Définit l'énumération  com.aspose.psd.StringTrimming  pour cet objet  com.aspose.psd.StringFormat .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Une énumération com.aspose.psd.StringTrimming qui indique comment le texte dessiné avec cet objet com.aspose.psd.StringFormat est tronqué lorsqu'il dépasse les bords du rectangle de mise en page. |

### toString() {#toString--}
```
public String toString()
```


Convertit cet objet  com.aspose.psd.StringFormat  en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une représentation sous forme de chaîne de cet objet com.aspose.psd.StringFormat.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

