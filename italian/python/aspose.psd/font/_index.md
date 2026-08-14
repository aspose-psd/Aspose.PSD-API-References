---
title: "Classe Font"
type: docs
weight: 1340
url: /it/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione specificata. Il set di caratteri è impostato a [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unità grafica a [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), lo stile del font a [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione e uno stile specificati. Il set di caratteri è impostato a [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unità grafica a [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione, uno stile e un'unità specificati. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione, uno stile, un'unità e un set di caratteri specificati. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione e un'unità specificate. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), lo stile è impostato su [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) che utilizza il [Font](/psd/python-net/aspose.psd/font/) esistente specificato e l'enumerazione [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | Restituisce un valore che indica se questo [Font](/psd/python-net/aspose.psd/font/) è in grassetto. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Restituisce un valore byte che specifica il set di caratteri utilizzato da questo [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | Restituisce un valore che indica se questo [Font](/psd/python-net/aspose.psd/font/) è in corsivo. |
| name | string | r | Restituisce il nome del tipo di carattere di questo [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Restituisce la dimensione em di questo [Font](/psd/python-net/aspose.psd/font/) misurata nelle unità specificate dalla proprietà [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Restituisce un valore che indica se questo [Font](/psd/python-net/aspose.psd/font/) specifica una linea orizzontale attraverso il carattere. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Restituisce le informazioni di stile per questo [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Restituisce un valore che indica se questo [Font](/psd/python-net/aspose.psd/font/) è sottolineato. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Restituisce l'unità di misura per questo [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una copia profonda esatta di questo [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione specificata. Il set di caratteri è impostato a [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unità grafica a [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), lo stile del font a [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La dimensione em, in punti, del nuovo font. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione e uno stile specificati. Il set di caratteri è impostato a [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), l'unità grafica a [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La dimensione em, in punti, del nuovo font. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Il [FontStyle](/psd/python-net/aspose.psd/fontstyle/) del nuovo font. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione, uno stile e un'unità specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La dimensione em del nuovo font nelle unità specificate dal parametro <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Il [FontStyle](/psd/python-net/aspose.psd/fontstyle/) del nuovo font. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Il [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) del nuovo font. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione, uno stile, un'unità e un set di caratteri specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La dimensione em del nuovo font nelle unità specificate dal parametro <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Il [FontStyle](/psd/python-net/aspose.psd/fontstyle/) del nuovo font. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Il [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) del nuovo font. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Un set di caratteri da utilizzare per questo font. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) usando una dimensione e un'unità specificate. Il set di caratteri è impostato su [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), lo stile è impostato su [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Una rappresentazione stringa del nome del [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | La dimensione em del nuovo font nelle unità specificate dal parametro <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Il [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) del nuovo font. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Inizializza un nuovo [Font](/psd/python-net/aspose.psd/font/) che utilizza il [Font](/psd/python-net/aspose.psd/font/) esistente specificato e l'enumerazione [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Il [Font](/psd/python-net/aspose.psd/font/) esistente da cui creare il nuovo [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Il [FontStyle](/psd/python-net/aspose.psd/fontstyle/) da applicare al nuovo [Font](/psd/python-net/aspose.psd/font/). È possibile combinare più valori dell'enumerazione [FontStyle](/psd/python-net/aspose.psd/fontstyle/) con l'operatore OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una copia profonda esatta di questo [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Il [Font](/psd/python-net/aspose.psd/font/) che questo metodo crea. |


