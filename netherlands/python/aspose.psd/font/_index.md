---
title: "Font Klasse"
type: docs
weight: 1340
url: /nl/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte. De tekenset wordt ingesteld op [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), de grafische eenheid op [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), en de lettertype‑stijl op [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte en stijl. De tekenset wordt ingesteld op [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), de grafische eenheid op [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte, stijl en eenheid. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte, stijl, eenheid en tekenset. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte en eenheid. De tekenset wordt ingesteld op [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), de stijl wordt ingesteld op [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) die de opgegeven bestaande [Font](/psd/python-net/aspose.psd/font/) en [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeratie gebruikt. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bold | bool | r | Haalt een waarde op die aangeeft of deze [Font](/psd/python-net/aspose.psd/font/) vet is. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Haalt een byte‑waarde op die de tekenset specificeert die deze [Font](/psd/python-net/aspose.psd/font/) gebruikt. |
| italic | bool | r | Haalt een waarde op die aangeeft of deze [Font](/psd/python-net/aspose.psd/font/) cursief is. |
| name | string | r | Haalt de gezichtsnaam op van deze [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Haalt de em-grootte op van deze [Font](/psd/python-net/aspose.psd/font/) gemeten in de eenheden die zijn gespecificeerd door de eigenschap [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Haalt een waarde op die aangeeft of deze [Font](/psd/python-net/aspose.psd/font/) een horizontale doorstreping in het lettertype specificeert. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Haalt stijl‑informatie op voor deze [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Haalt een waarde op die aangeeft of deze [Font](/psd/python-net/aspose.psd/font/) onderstreept is. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Haalt de meeteenheid op voor deze [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Maakt een exacte diepe kopie van deze [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte. De tekenset wordt ingesteld op [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), de grafische eenheid op [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), en de lettertype‑stijl op [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Een tekenreeksrepresentatie van de naam van de [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | De em-grootte, in punten, van het nieuwe lettertype. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte en stijl. De tekenset wordt ingesteld op [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), de grafische eenheid op [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Een tekenreeksrepresentatie van de naam van de [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | De em-grootte, in punten, van het nieuwe lettertype. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | De [FontStyle](/psd/python-net/aspose.psd/fontstyle/) van het nieuwe lettertype. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte, stijl en eenheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Een tekenreeksrepresentatie van de naam van de [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn gespecificeerd door de parameter <paramref name=\"unit\" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | De [FontStyle](/psd/python-net/aspose.psd/fontstyle/) van het nieuwe lettertype. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) van het nieuwe lettertype. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte, stijl, eenheid en tekenset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Een tekenreeksrepresentatie van de naam van de [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn gespecificeerd door de parameter <paramref name=\"unit\" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | De [FontStyle](/psd/python-net/aspose.psd/fontstyle/) van het nieuwe lettertype. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) van het nieuwe lettertype. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Een tekenset om te gebruiken voor dit lettertype. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) met een opgegeven grootte en eenheid. De tekenset wordt ingesteld op [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), de stijl wordt ingesteld op [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Een tekenreeksrepresentatie van de naam van de [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | De em-grootte van het nieuwe lettertype in de eenheden die zijn gespecificeerd door de parameter <paramref name=\"unit\" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) van het nieuwe lettertype. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initialiseert een nieuwe [Font](/psd/python-net/aspose.psd/font/) die de opgegeven bestaande [Font](/psd/python-net/aspose.psd/font/) en [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeratie gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | De bestaande [Font](/psd/python-net/aspose.psd/font/) waaruit de nieuwe [Font](/psd/python-net/aspose.psd/font/) moet worden gemaakt. |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | De [FontStyle](/psd/python-net/aspose.psd/fontstyle/) die op de nieuwe [Font](/psd/python-net/aspose.psd/font/) moet worden toegepast. Meerdere waarden van de [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeratie kunnen worden gecombineerd met de OR‑operator. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Maakt een exacte diepe kopie van deze [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | De [Font](/psd/python-net/aspose.psd/font/) die deze methode maakt. |


