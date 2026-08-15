---
title: "Clase Font"
type: docs
weight: 1340
url: /es/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño especificado. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), el estilo de fuente en [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño, estilo y unidad especificados. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño, estilo, unidad y conjunto de caracteres especificados. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), el estilo se establece en [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) que utiliza el [Font](/psd/python-net/aspose.psd/font/) existente especificado y la enumeración [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bold | bool | r | Obtiene un valor que indica si este [Font](/psd/python-net/aspose.psd/font/) está en negrita. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Obtiene un valor de byte que especifica el conjunto de caracteres que utiliza este [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | Obtiene un valor que indica si este [Font](/psd/python-net/aspose.psd/font/) está en cursiva. |
| name | string | r | Obtiene el nombre de la familia tipográfica de este [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Obtiene el tamaño em de este [Font](/psd/python-net/aspose.psd/font/) medido en las unidades especificadas por la propiedad [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Obtiene un valor que indica si este [Font](/psd/python-net/aspose.psd/font/) especifica una línea horizontal a través de la fuente. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Obtiene información de estilo para este [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Obtiene un valor que indica si este [Font](/psd/python-net/aspose.psd/font/) está subrayado. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Obtiene la unidad de medida de este [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una copia profunda exacta de este [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño especificado. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), el estilo de fuente en [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | El tamaño em, en puntos, de la nueva fuente. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), la unidad gráfica en [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | El tamaño em, en puntos, de la nueva fuente. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | El [FontStyle](/psd/python-net/aspose.psd/fontstyle/) de la nueva fuente. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño, estilo y unidad especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro <paramref name=\"unit\" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | El [FontStyle](/psd/python-net/aspose.psd/fontstyle/) de la nueva fuente. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | El [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) de la nueva fuente. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño, estilo, unidad y conjunto de caracteres especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro <paramref name=\"unit\" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | El [FontStyle](/psd/python-net/aspose.psd/fontstyle/) de la nueva fuente. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | El [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) de la nueva fuente. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Un conjunto de caracteres para usar con esta fuente. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), el estilo se establece en [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Una representación en cadena del nombre del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro <paramref name=\"unit\" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | El [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) de la nueva fuente. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Inicializa un nuevo [Font](/psd/python-net/aspose.psd/font/) que utiliza el [Font](/psd/python-net/aspose.psd/font/) existente especificado y la enumeración [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | El [Font](/psd/python-net/aspose.psd/font/) existente del cual crear el nuevo [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | El [FontStyle](/psd/python-net/aspose.psd/fontstyle/) a aplicar al nuevo [Font](/psd/python-net/aspose.psd/font/). Se pueden combinar múltiples valores de la enumeración [FontStyle](/psd/python-net/aspose.psd/fontstyle/) con el operador OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una copia profunda exacta de este [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | El [Font](/psd/python-net/aspose.psd/font/) que crea este método. |


