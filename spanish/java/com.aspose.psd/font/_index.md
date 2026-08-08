---
title: "Fuente"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define un formato particular para el texto que incluye atributos de tipo de fuente, tamaño y estilo."
type: docs
weight: 46
url: /es/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Define un formato particular para el texto, que incluye tipo de fuente, tamaño y atributos de estilo. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Inicializa un nuevo  com.aspose.psd.Font  que usa la  com.aspose.psd.Font  existente especificada y la enumeración  com.aspose.psd.FontStyle . |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño especificado. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño y estilo especificados. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño, estilo, unidad y conjunto de caracteres especificados. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño, estilo y unidad especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda exacta de este  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica si el objeto especificado es un  com.aspose.psd.Font  y tiene los mismos valores de propiedad que este  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Obtiene un valor que indica si este  Font  está en negrita. |
| [getCharacterSet()](#getCharacterSet--) | Obtiene un valor de byte que especifica el conjunto de caracteres que usa este  Font . |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Obtiene un valor que indica si este  Font  está en cursiva. |
| [getName()](#getName--) | Obtiene el nombre de la familia de este  Font . |
| [getSize()](#getSize--) | Obtiene el tamaño em de este  Font  medido en las unidades especificadas por la propiedad  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Obtiene un valor que indica si este  Font  especifica una línea horizontal a través de la fuente. |
| [getStyle()](#getStyle--) | Obtiene la información de estilo para este  Font . |
| [getUnderline()](#getUnderline--) | Obtiene un valor que indica si este  Font  está subrayado. |
| [getUnit()](#getUnit--) | Obtiene la unidad de medida de este  Font . |
| [hashCode()](#hashCode--) | Obtiene el código hash de este  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño y unidad especificados. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Inicializa un nuevo  com.aspose.psd.Font  que usa la  com.aspose.psd.Font  existente especificada y la enumeración  com.aspose.psd.FontStyle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | El  com.aspose.psd.Font  existente del cual crear el nuevo  com.aspose.psd.Font . |
| newStyle | int | El  com.aspose.psd.FontStyle  a aplicar al nuevo  com.aspose.psd.Font . Se pueden combinar múltiples valores de la enumeración  com.aspose.psd.FontStyle  con el operador OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño especificado. El conjunto de caracteres se establece en  F:Aspose.Imaging.CharacterSet.Default , la unidad gráfica en  F:Aspose.Imaging.GraphicsUnit.Point , el estilo de fuente en  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación en cadena del nombre del  com.aspose.psd.Font . |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño y estilo especificados. El conjunto de caracteres se establece en  F:Aspose.Imaging.CharacterSet.Default , la unidad gráfica en  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación en cadena del nombre del  com.aspose.psd.Font . |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |
| style | int | El  com.aspose.psd.FontStyle  de la nueva fuente. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño, estilo, unidad y conjunto de caracteres especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación en cadena del nombre del  com.aspose.psd.Font . |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro  unit . |
| style | int | El  com.aspose.psd.FontStyle  de la nueva fuente. |
| unit | int | El  com.aspose.psd.GraphicsUnit  de la nueva fuente. |
| characterSet | int | Un conjunto de caracteres para usar con esta fuente. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño, estilo y unidad especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación en cadena del nombre del  com.aspose.psd.Font . |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro  unit . |
| style | int | El  com.aspose.psd.FontStyle  de la nueva fuente. |
| unit | int | El  com.aspose.psd.GraphicsUnit  de la nueva fuente. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crea una copia profunda exacta de este  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica si el objeto especificado es un  com.aspose.psd.Font  y tiene los mismos valores de propiedad que este  com.aspose.psd.Font .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - Verdadero si el parámetro  obj  es un  com.aspose.psd.Font  y tiene los mismos valores de propiedad que este  com.aspose.psd.Font ; de lo contrario, falso.
### getBold() {#getBold--}
```
public boolean getBold()
```


Obtiene un valor que indica si este  Font  está en negrita.

**Returns:**
boolean - Verdadero si este  Font  está en negrita; de lo contrario, falso.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Obtiene un valor de byte que especifica el conjunto de caracteres que usa este  Font .

**Returns:**
int - Un conjunto de caracteres que usa este  Font .
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


Obtiene un valor que indica si este  Font  está en cursiva.

**Returns:**
boolean - Verdadero si este  Font  está en cursiva; de lo contrario, falso.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre de la familia de este  Font .

**Returns:**
java.lang.String - Una representación en cadena del nombre de familia de este  Font .
### getSize() {#getSize--}
```
public float getSize()
```


Obtiene el tamaño em de este  Font  medido en las unidades especificadas por la propiedad  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - El tamaño em de este  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Obtiene un valor que indica si este  Font  especifica una línea horizontal a través de la fuente.

**Returns:**
boolean - Verdadero si este  Font  tiene una línea horizontal a través de él; de lo contrario, falso.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtiene la información de estilo para este  Font .

**Returns:**
int - Una enumeración  FontStyle  que contiene información de estilo para este  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Obtiene un valor que indica si este  Font  está subrayado.

**Returns:**
boolean - Verdadero si este  Font  está subrayado; de lo contrario, falso.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Obtiene la unidad de medida de este  Font .

**Returns:**
int - Un  GraphicsUnit  que representa la unidad de medida para este  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de este  com.aspose.psd.Font .

**Returns:**
int - El código hash de este  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Inicializa un nuevo  com.aspose.psd.Font  usando un tamaño y unidad especificados. El conjunto de caracteres se establece en  F:Aspose.Imaging.CharacterSet.Default , el estilo se establece en  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación en cadena del nombre del  com.aspose.psd.Font . |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro  unit . |
| unit | int | El  com.aspose.psd.GraphicsUnit  de la nueva fuente. |

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


Devuelve una representación de cadena legible por humanos de este  com.aspose.psd.Font .

**Returns:**
java.lang.String - Una cadena que representa este  com.aspose.psd.Font .
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

