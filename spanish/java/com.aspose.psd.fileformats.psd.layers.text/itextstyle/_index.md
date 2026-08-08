---
title: "ITextStyle"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Interfaz para trabajar con estilo de texto"
type: docs
weight: 14
url: /es/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Interfaz para trabajar con estilo de texto
## Métodos

| Método | Descripción |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Aplica el estilo especificado. |
| [getAutoKerning()](#getAutoKerning--) | Obtiene o establece el kerning automático. |
| [getAutoLeading()](#getAutoLeading--) | Obtiene o establece un valor que indica si [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | El desplazamiento de la línea base. |
| [getContextualAlternates()](#getContextualAlternates--) | Los alternantes contextuales usados para conectar letras entre sí. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Las ligaduras discrecionales usadas para conectar letras, especialmente en fuentes cursivas. |
| [getFauxBold()](#getFauxBold--) | Obtiene o establece si el faux bold está habilitado. |
| [getFauxItalic()](#getFauxItalic--) | Obtiene o establece si el faux bold está habilitado. |
| [getFillColor()](#getFillColor--) | Obtiene o establece el color del relleno. |
| [getFontBaseline()](#getFontBaseline--) | La línea base de la fuente. |
| [getFontCaps()](#getFontCaps--) | Las mayúsculas de la fuente. |
| [getFontIndex()](#getFontIndex--) | Obtiene el índice de la fuente. |
| [getFontName()](#getFontName--) | Obtiene o establece el nombre de la fuente. |
| [getFontSize()](#getFontSize--) | Obtiene o establece el tamaño de la fuente. |
| [getFractions()](#getFractions--) | Los símbolos de fracciones pueden ser reemplazados por un glifo especial. |
| [getHindiNumbers()](#getHindiNumbers--) | Obtiene o establece un valor que indica si [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | La escala horizontal. |
| [getKerning()](#getKerning--) | Obtiene o establece el kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | Obtiene el índice de idioma. |
| [getLeading()](#getLeading--) | Obtiene o establece el interlineado. |
| [getStandardLigatures()](#getStandardLigatures--) | Las ligaduras contextuales estándar usadas para conectar letras entre sí. |
| [getStrikethrough()](#getStrikethrough--) | Obtiene o establece un valor que indica si [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Obtiene o establece el color del trazo. |
| [getTracking()](#getTracking--) | Obtiene o establece el tracking. |
| [getUnderline()](#getUnderline--) | Obtiene o establece un valor que indica si [underline]. |
| [getVerticalScale()](#getVerticalScale--) | La escala vertical. |
| [get_noBreak()](#get-noBreak--) | Obtiene ot establece el valor de no romper. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Determina si el estilo especificado es igual. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Obtiene o establece la alineación vertical romana estándar. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Obtiene o establece el kerning automático. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Obtiene o establece un valor que indica si [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | El desplazamiento de la línea base. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Los alternantes contextuales usados para conectar letras entre sí. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Las ligaduras discrecionales usadas para conectar letras, especialmente en fuentes cursivas. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Obtiene o establece si el faux bold está habilitado. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Obtiene o establece si el faux bold está habilitado. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Obtiene o establece el color del relleno. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | La línea base de la fuente. |
| [setFontCaps(int value)](#setFontCaps-int-) | Las mayúsculas de la fuente. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Obtiene o establece el nombre de la fuente. |
| [setFontSize(double value)](#setFontSize-double-) | Obtiene o establece el tamaño de la fuente. |
| [setFractions(boolean value)](#setFractions-boolean-) | Los símbolos de fracciones pueden ser reemplazados por un glifo especial. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Obtiene o establece un valor que indica si [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | La escala horizontal. |
| [setKerning(int value)](#setKerning-int-) | Obtiene o establece el kerning. |
| [setLeading(double value)](#setLeading-double-) | Obtiene o establece el interlineado. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Las ligaduras contextuales estándar usadas para conectar letras entre sí. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Obtiene o establece un valor que indica si [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Obtiene o establece el color del trazo. |
| [setTracking(int value)](#setTracking-int-) | Obtiene o establece el tracking. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Obtiene o establece un valor que indica si [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | La escala vertical. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Obtiene o establece la alineación vertical romana estándar. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Obtiene ot establece el valor de no romper. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Aplica el estilo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | El estilo. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Obtiene o establece el kerning automático.

Valor: El kerning automático entre dos caracteres.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Obtiene o establece un valor que indica si [automatic leading].

Valor:  true  si [automatic leading]; de lo contrario,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


El desplazamiento de la línea base.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Los alternantes contextuales usados para conectar letras entre sí.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Las ligaduras discrecionales usadas para conectar letras, especialmente en fuentes cursivas.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Obtiene o establece si el faux bold está habilitado.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Obtiene o establece si el faux bold está habilitado.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Obtiene o establece el color del relleno.

Valor: El color del relleno.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


La línea base de la fuente.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Las mayúsculas de la fuente.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Obtiene el índice de la fuente.

Valor: La fuente.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Obtiene o establece el nombre de la fuente.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Obtiene o establece el tamaño de la fuente.

Valor: El tamaño de la fuente.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Los símbolos de fracciones pueden ser reemplazados por un glifo especial.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Obtiene o establece un valor que indica si [hindi numbers].

Valor:  true  si [hindi numbers]; de lo contrario,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


La escala horizontal.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Obtiene o establece el kerning.

Valor: El kerning entre dos caracteres.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Obtiene el índice de idioma.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Obtiene o establece el interlineado.

Valor: El interlineado.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Las ligaduras contextuales estándar usadas para conectar letras entre sí.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Obtiene o establece un valor que indica si [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Obtiene o establece el color del trazo.

Valor: El color del trazo.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Obtiene o establece el tracking.

Valor: El tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Obtiene o establece un valor que indica si [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


La escala vertical.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Obtiene ot establece el valor de no romper.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Determina si el estilo especificado es igual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | El estilo. |

**Returns:**
boolean -  true  si el estilo especificado es igual; de lo contrario,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Obtiene o establece la alineación vertical romana estándar. Este valor basado en el recurso BaselineDirection se aplica solo cuando la orientación del texto es [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Obtiene o establece el kerning automático.

Valor: El kerning automático entre dos caracteres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Obtiene o establece un valor que indica si [automatic leading].

Valor:  true  si [automatic leading]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


El desplazamiento de la línea base.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Los alternantes contextuales usados para conectar letras entre sí.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Las ligaduras discrecionales usadas para conectar letras, especialmente en fuentes cursivas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Obtiene o establece si el faux bold está habilitado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Obtiene o establece si el faux bold está habilitado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Obtiene o establece el color del relleno.

Valor: El color del relleno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


La línea base de la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Las mayúsculas de la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Obtiene o establece el nombre de la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Obtiene o establece el tamaño de la fuente.

Valor: El tamaño de la fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Los símbolos de fracciones pueden ser reemplazados por un glifo especial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Obtiene o establece un valor que indica si [hindi numbers].

Valor:  true  si [hindi numbers]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


La escala horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Obtiene o establece el kerning.

Valor: El kerning entre dos caracteres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Obtiene o establece el interlineado.

Valor: El interlineado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Las ligaduras contextuales estándar usadas para conectar letras entre sí.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Obtiene o establece un valor que indica si [strikethrough].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Obtiene o establece el color del trazo.

Valor: El color del trazo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Obtiene o establece el tracking.

Valor: El tracking.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Obtiene o establece un valor que indica si [underline].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


La escala vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Obtiene o establece la alineación vertical romana estándar. Este valor basado en el recurso BaselineDirection se aplica solo cuando la orientación del texto es [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Obtiene ot establece el valor de no romper.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

