---
title: "Font Classe"
type: docs
weight: 1340
url: /fr/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille spécifiée. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), le style de police sur [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille, un style et une unité spécifiés. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), le style est défini sur [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) qui utilise le [Font](/psd/python-net/aspose.psd/font/) existant spécifié et l'énumération [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | Obtient une valeur indiquant si ce [Font](/psd/python-net/aspose.psd/font/) est gras. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Obtient une valeur byte qui spécifie le jeu de caractères utilisé par ce [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | Obtient une valeur indiquant si ce [Font](/psd/python-net/aspose.psd/font/) est italique. |
| name | string | r | Obtient le nom de la police de ce [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Obtient la taille en em de ce [Font](/psd/python-net/aspose.psd/font/) mesurée dans les unités spécifiées par la propriété [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Obtient une valeur indiquant si ce [Font](/psd/python-net/aspose.psd/font/) spécifie une ligne horizontale traversant la police. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Obtient les informations de style pour ce [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Obtient une valeur indiquant si ce [Font](/psd/python-net/aspose.psd/font/) est souligné. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Obtient l'unité de mesure de ce [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crée une copie profonde exacte de ce [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille spécifiée. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), le style de police sur [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La taille en em, en points, de la nouvelle police. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unité graphique sur [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La taille en em, en points, de la nouvelle police. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Le [FontStyle](/psd/python-net/aspose.psd/fontstyle/) de la nouvelle police. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille, un style et une unité spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Le [FontStyle](/psd/python-net/aspose.psd/fontstyle/) de la nouvelle police. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) de la nouvelle police. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille, un style, une unité et un jeu de caractères spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Le [FontStyle](/psd/python-net/aspose.psd/fontstyle/) de la nouvelle police. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) de la nouvelle police. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Un jeu de caractères à utiliser pour cette police. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), le style est défini sur [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_name | string | Une représentation sous forme de chaîne du nom du [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La taille en em de la nouvelle police dans les unités spécifiées par le paramètre <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) de la nouvelle police. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initialise un nouveau [Font](/psd/python-net/aspose.psd/font/) qui utilise le [Font](/psd/python-net/aspose.psd/font/) existant spécifié et l'énumération [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Le [Font](/psd/python-net/aspose.psd/font/) existant à partir duquel créer le nouveau [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Le [FontStyle](/psd/python-net/aspose.psd/fontstyle/) à appliquer au nouveau [Font](/psd/python-net/aspose.psd/font/). Plusieurs valeurs de l'énumération [FontStyle](/psd/python-net/aspose.psd/fontstyle/) peuvent être combinées avec l'opérateur OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crée une copie profonde exacte de ce [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Type | Description |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Le [Font](/psd/python-net/aspose.psd/font/) que cette méthode crée. |


