---
title: "StringFormat"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Encapsula información de diseño de texto como alineación, orientación y tabulaciones, manipulaciones de visualización como inserción de elipsis y sustitución de dígitos nacionales y características OpenType."
type: docs
weight: 106
url: /es/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Encapsula información de diseño de texto (como alineación, orientación y tabulaciones) manipulaciones de visualización (como inserción de elipsis y sustitución de dígitos nacionales) y características OpenType. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [StringFormat()](#StringFormat--) | Inicializa un nuevo  com.aspose.psd.StringFormat  object. |
| [StringFormat(int options)](#StringFormat-int-) | Inicializa un nuevo objeto  com.aspose.psd.StringFormat  con la enumeración  com.aspose.psd.StringFormatFlags  especificada y el idioma. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Inicializa un nuevo objeto  com.aspose.psd.StringFormat  a partir del objeto  com.aspose.psd.StringFormat  existente especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una clonación profunda de este objeto  com.aspose.psd.StringFormat . |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Obtiene información de alineación de texto en el plano vertical. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Obtiene el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Obtiene el método que se utilizará para la sustitución de dígitos. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Obtiene el número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| [getFormatFlags()](#getFormatFlags--) | Obtiene una enumeración  com.aspose.psd.StringFormatFlags  que contiene información de formato. |
| [getGenericDefault()](#getGenericDefault--) | Obtiene un objeto genérico predeterminado  com.aspose.psd.StringFormat . |
| [getGenericTypographic()](#getGenericTypographic--) | Obtiene un objeto tipográfico genérico  com.aspose.psd.StringFormat . |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Obtiene el objeto  com.aspose.psd.HotkeyPrefix  para este objeto  com.aspose.psd.StringFormat . |
| [getLineAlignment()](#getLineAlignment--) | Obtiene la alineación de línea en el plano horizontal. |
| [getTabStops()](#getTabStops--) | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | Obtiene la enumeración  com.aspose.psd.StringTrimming  para este objeto  com.aspose.psd.StringFormat . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Establece información de alineación de texto en el plano vertical. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Establece el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Establece el método que se utilizará para la sustitución de dígitos. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Establece una  com.aspose.psd.StringFormatFlags  enumeración que contiene información de formato. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Establece el objeto  com.aspose.psd.HotkeyPrefix  para este objeto  com.aspose.psd.StringFormat . |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Establece la alineación de línea en el plano horizontal. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Establece los tabuladores para este objeto  com.aspose.psd.StringFormat . |
| [setTrimming(int value)](#setTrimming-int-) | Establece la enumeración  com.aspose.psd.StringTrimming  para este objeto  com.aspose.psd.StringFormat . |
| [toString()](#toString--) | Convierte este objeto  com.aspose.psd.StringFormat  a una cadena legible por humanos. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Inicializa un nuevo  com.aspose.psd.StringFormat  object.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Inicializa un nuevo objeto  com.aspose.psd.StringFormat  con la enumeración  com.aspose.psd.StringFormatFlags  especificada y el idioma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | int | La enumeración  com.aspose.psd.StringFormatFlags  para el nuevo objeto  com.aspose.psd.StringFormat . |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Inicializa un nuevo objeto  com.aspose.psd.StringFormat  a partir del objeto  com.aspose.psd.StringFormat  existente especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | El objeto  com.aspose.psd.StringFormat  del cual inicializar el nuevo objeto  com.aspose.psd.StringFormat . |

### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crea una clonación profunda de este objeto  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtiene información de alineación de texto en el plano vertical.

**Returns:**
int - Una enumeración  com.aspose.psd.StringAlignment  que especifica información de alineación de texto.
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


Obtiene el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales.

**Returns:**
int - Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se utilizará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad  P:System.Globalization.CultureInfo.LCID  de un objeto  System.Globalization.CultureInfo  como el identificador de idioma NLS. Por ejemplo, suponga que crea un objeto  System.Globalization.CultureInfo  pasando la cadena "ar-EG" a un constructor de  System.Globalization.CultureInfo . Si pasa la propiedad  P:System.Globalization.CultureInfo.LCID  de ese objeto  System.Globalization.CultureInfo  junto con  com.aspose.psd.StringDigitSubstitute.Traditional  al método  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) , entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización.

El setter se introduce para el método obsoleto setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Obtiene el método que se utilizará para la sustitución de dígitos.

**Returns:**
int - Un valor de enumeración  com.aspose.psd.StringDigitSubstitute  que especifica cómo sustituir caracteres en una cadena que no se pueden mostrar porque no son compatibles con la fuente actual.

El setter se introduce para el método obsoleto SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Obtiene el número de espacios entre el comienzo de una línea de texto y la primera tabulación.

**Returns:**
float - El primer desplazamiento de tabulación.

La propiedad se introduce para el método eliminado GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Obtiene una enumeración  com.aspose.psd.StringFormatFlags  que contiene información de formato.

**Returns:**
int - Una enumeración  com.aspose.psd.StringFormatFlags  que contiene información de formato.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Obtiene un objeto genérico predeterminado  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Obtiene un objeto tipográfico genérico  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Obtiene el objeto  com.aspose.psd.HotkeyPrefix  para este objeto  com.aspose.psd.StringFormat .

**Returns:**
int - El objeto  com.aspose.psd.HotkeyPrefix  para este objeto  com.aspose.psd.StringFormat , el valor predeterminado es  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Obtiene la alineación de línea en el plano horizontal.

**Returns:**
int - Una enumeración  com.aspose.psd.StringAlignment  que representa la alineación de línea.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] - Los tabuladores.

La propiedad se introduce para el método eliminado GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Obtiene la enumeración  com.aspose.psd.StringTrimming  para este objeto  com.aspose.psd.StringFormat .

**Returns:**
int - Una enumeración  com.aspose.psd.StringTrimming  que indica cómo se recorta el texto dibujado con este objeto  com.aspose.psd.StringFormat  cuando supera los bordes del rectángulo de diseño.
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


Establece información de alineación de texto en el plano vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración  com.aspose.psd.StringAlignment  que especifica información de alineación de texto. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Establece el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | Un identificador de idioma de Soporte de Idioma Nacional (NLS) que identifica el idioma que se utilizará cuando los dígitos locales se sustituyan por dígitos occidentales. Puede pasar la propiedad  P:System.Globalization.CultureInfo.LCID  de un objeto  System.Globalization.CultureInfo  como el identificador de idioma NLS. Por ejemplo, suponga que crea un objeto  System.Globalization.CultureInfo  pasando la cadena "ar-EG" a un constructor de  System.Globalization.CultureInfo . Si pasa la propiedad  P:System.Globalization.CultureInfo.LCID  de ese objeto  System.Globalization.CultureInfo  junto con  com.aspose.psd.StringDigitSubstitute.Traditional  al método  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) , entonces los dígitos árabe-indios se sustituirán por dígitos occidentales en tiempo de visualización. |

Se introduce el setter para el método obsoleto SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Establece el método que se utilizará para la sustitución de dígitos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | Un valor de enumeración  com.aspose.psd.StringDigitSubstitute  que especifica cómo sustituir caracteres en una cadena que no se pueden mostrar porque no son compatibles con la fuente actual. |

Se introduce el setter para el método obsoleto SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Establece una  com.aspose.psd.StringFormatFlags  enumeración que contiene información de formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración  com.aspose.psd.StringFormatFlags  que contiene información de formato. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Establece el objeto  com.aspose.psd.HotkeyPrefix  para este objeto  com.aspose.psd.StringFormat .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El objeto  com.aspose.psd.HotkeyPrefix  para este objeto  com.aspose.psd.StringFormat , el valor predeterminado es  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Establece la alineación de línea en el plano horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración  com.aspose.psd.StringAlignment  que representa la alineación de línea. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Establece los tabuladores para este objeto  com.aspose.psd.StringFormat .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstTabOffset | float | El número de espacios entre el comienzo de una línea de texto y la primera tabulación. |
| tabStops | float[] | Una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad  com.aspose.psd.Graphics.PageUnit . |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Establece la enumeración  com.aspose.psd.StringTrimming  para este objeto  com.aspose.psd.StringFormat .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Una enumeración  com.aspose.psd.StringTrimming  que indica cómo se recorta el texto dibujado con este objeto  com.aspose.psd.StringFormat  cuando supera los bordes del rectángulo de diseño. |

### toString() {#toString--}
```
public String toString()
```


Convierte este objeto  com.aspose.psd.StringFormat  a una cadena legible por humanos.

**Returns:**
java.lang.String - Una representación en cadena de este objeto  com.aspose.psd.StringFormat .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

