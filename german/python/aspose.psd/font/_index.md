---
title: "Font Klasse"
type: docs
weight: 1340
url: /de/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) und der Schriftsstil auf [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe, einem Stil und einer Einheit. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe, einem Stil, einer Einheit und einem Zeichensatz. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) gesetzt, der Stil wird auf [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) gesetzt. |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/), das das angegebene vorhandene [Font](/psd/python-net/aspose.psd/font/) und die [FontStyle](/psd/python-net/aspose.psd/fontstyle/) Aufzählung verwendet. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bold | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Font](/psd/python-net/aspose.psd/font/) fett ist. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den dieses [Font](/psd/python-net/aspose.psd/font/) verwendet. |
| italic | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Font](/psd/python-net/aspose.psd/font/) kursiv ist. |
| name | string | r | Gibt den Schriftartnamen dieses [Font](/psd/python-net/aspose.psd/font/) zurück. |
| size | float | r | Gibt die Em-Größe dieses [Font](/psd/python-net/aspose.psd/font/) zurück, gemessen in den durch die Eigenschaft [Font.unit](/psd/python-net/aspose.psd/font/) angegebenen Einheiten. |
| strikeout | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Font](/psd/python-net/aspose.psd/font/) eine horizontale Durchstreichung hat. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Gibt Stilinformationen für dieses [Font](/psd/python-net/aspose.psd/font/) zurück. |
| underline | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Font](/psd/python-net/aspose.psd/font/) unterstrichen ist. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Gibt die Maßeinheit für dieses [Font](/psd/python-net/aspose.psd/font/) zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Erstellt eine exakte tiefe Kopie dieses [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) und der Schriftsstil auf [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des [Font](/psd/python-net/aspose.psd/font/) Namens. |
| em_size | float | Die Em-Größe, in Punkten, des neuen Schriftsatzes. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) gesetzt, die Grafikeinheit auf [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des [Font](/psd/python-net/aspose.psd/font/) Namens. |
| em_size | float | Die Em-Größe, in Punkten, des neuen Schriftsatzes. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Der [FontStyle](/psd/python-net/aspose.psd/fontstyle/) des neuen Schriftsatzes. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe, einem Stil und einer Einheit.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des [Font](/psd/python-net/aspose.psd/font/) Namens. |
| em_size | float | Die Em-Größe des neuen Schriftsatzes in den durch den Parameter <paramref name=\"unit\" /> angegebenen Einheiten. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Der [FontStyle](/psd/python-net/aspose.psd/fontstyle/) des neuen Schriftsatzes. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) des neuen Schriftsatzes. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe, einem Stil, einer Einheit und einem Zeichensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des [Font](/psd/python-net/aspose.psd/font/) Namens. |
| em_size | float | Die Em-Größe des neuen Schriftsatzes in den durch den Parameter <paramref name=\"unit\" /> angegebenen Einheiten. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Der [FontStyle](/psd/python-net/aspose.psd/fontstyle/) des neuen Schriftsatzes. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) des neuen Schriftsatzes. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Ein Zeichensatz, der für diesen Schriftsatz verwendet werden soll. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) gesetzt, der Stil wird auf [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) gesetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Eine Zeichenkettenrepräsentation des [Font](/psd/python-net/aspose.psd/font/) Namens. |
| em_size | float | Die Em-Größe des neuen Schriftsatzes in den durch den Parameter <paramref name=\"unit\" /> angegebenen Einheiten. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) des neuen Schriftsatzes. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initialisiert ein neues [Font](/psd/python-net/aspose.psd/font/), das das angegebene vorhandene [Font](/psd/python-net/aspose.psd/font/) und die [FontStyle](/psd/python-net/aspose.psd/fontstyle/) Aufzählung verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Das vorhandene [Font](/psd/python-net/aspose.psd/font/) aus dem der neue [Font](/psd/python-net/aspose.psd/font/) erstellt werden soll. |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Der [FontStyle](/psd/python-net/aspose.psd/fontstyle/) zum Anwenden auf das neue [Font](/psd/python-net/aspose.psd/font/). Mehrere Werte der [FontStyle](/psd/python-net/aspose.psd/fontstyle/) Aufzählung können mit dem ODER-Operator kombiniert werden. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Erstellt eine exakte tiefe Kopie dieses [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Der [Font](/psd/python-net/aspose.psd/font/), den diese Methode erstellt. |


