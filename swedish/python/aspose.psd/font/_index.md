---
title: "Typsnittsklass"
type: docs
weight: 1340
url: /sv/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), teckensnittsstilen till [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek och stil. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek, stil och enhet. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek, stil, enhet och teckenuppsättning. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek och enhet. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), stilen sätts till [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) som använder det angivna befintliga [Font](/psd/python-net/aspose.psd/font/) och [FontStyle](/psd/python-net/aspose.psd/fontstyle/)‑enumerationen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bold | bool | r | Hämtar ett värde som indikerar om detta [Font](/psd/python-net/aspose.psd/font/) är fet. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Hämtar ett byte‑värde som specificerar teckenuppsättningen som detta [Font](/psd/python-net/aspose.psd/font/) använder. |
| italic | bool | r | Hämtar ett värde som indikerar om detta [Font](/psd/python-net/aspose.psd/font/) är kursiv. |
| name | string | r | Hämtar teckensnittets namn för detta [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Hämtar em‑storleken för detta [Font](/psd/python-net/aspose.psd/font/) mätt i de enheter som anges av egenskapen [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Hämtar ett värde som indikerar om detta [Font](/psd/python-net/aspose.psd/font/) specificerar en horisontell linje genom teckensnittet. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Hämtar stilinformation för detta [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Hämtar ett värde som indikerar om detta [Font](/psd/python-net/aspose.psd/font/) är understruket. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Hämtar måttenheten för detta [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Skapar en exakt djup kopia av detta [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), teckensnittsstilen till [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Em-storleken, i punkter, för det nya teckensnittet. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek och stil. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), grafik‑enheten till [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Em-storleken, i punkter, för det nya teckensnittet. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) för det nya teckensnittet. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek, stil och enhet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) för det nya teckensnittet. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) för det nya teckensnittet. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek, stil, enhet och teckenuppsättning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) för det nya teckensnittet. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) för det nya teckensnittet. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | En teckenuppsättning att använda för detta teckensnitt. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) med en angiven storlek och enhet. Teckenuppsättningen sätts till [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), stilen sätts till [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | En strängrepresentation av namnet på [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Em-storleken för det nya teckensnittet i de enheter som anges av parametern <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) för det nya teckensnittet. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initierar ett nytt [Font](/psd/python-net/aspose.psd/font/) som använder det angivna befintliga [Font](/psd/python-net/aspose.psd/font/) och [FontStyle](/psd/python-net/aspose.psd/fontstyle/)‑enumerationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Det befintliga [Font](/psd/python-net/aspose.psd/font/) som den nya [Font](/psd/python-net/aspose.psd/font/) ska skapas från. |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) att tillämpa på det nya [Font](/psd/python-net/aspose.psd/font/). Flera värden i [FontStyle](/psd/python-net/aspose.psd/fontstyle/)‑enumerationen kan kombineras med OR‑operatorn. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Skapar en exakt djup kopia av detta [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som den här metoden skapar. |


