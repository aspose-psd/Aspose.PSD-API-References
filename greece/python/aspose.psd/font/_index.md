---
title: "Κλάση Font"
type: docs
weight: 1340
url: /el/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων ορίζεται σε [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), η μονάδα γραφικών σε [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), το στυλ γραμματοσειράς σε [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων ορίζεται σε [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), η μονάδα γραφικών σε [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας συγκεκριμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων ορίζεται σε [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), το στυλ ορίζεται σε [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) που χρησιμοποιεί το καθορισμένο υπάρχον [Font](/psd/python-net/aspose.psd/font/) και την απαρίθμηση [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bold | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](/psd/python-net/aspose.psd/font/) είναι έντονο. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που χρησιμοποιεί αυτό το [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](/psd/python-net/aspose.psd/font/) είναι πλάγιο. |
| name | string | r | Λαμβάνει το όνομα γραμματοσειράς αυτού του [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Λαμβάνει το em-size αυτού του [Font](/psd/python-net/aspose.psd/font/) μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](/psd/python-net/aspose.psd/font/) καθορίζει μια οριζόντια γραμμή μέσω της γραμματοσειράς. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Λαμβάνει πληροφορίες στυλ για αυτό το [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το [Font](/psd/python-net/aspose.psd/font/) είναι υπογραμμισμένο. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Λαμβάνει τη μονάδα μέτρησης για αυτό το [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων ορίζεται σε [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), η μονάδα γραφικών σε [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), το στυλ γραμματοσειράς σε [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Μία αναπαράσταση συμβολοσειράς του ονόματος του [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων ορίζεται σε [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), η μονάδα γραφικών σε [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Μία αναπαράσταση συμβολοσειράς του ονόματος του [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Το [FontStyle](/psd/python-net/aspose.psd/fontstyle/) της νέας γραμματοσειράς. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Μία αναπαράσταση συμβολοσειράς του ονόματος του [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Το [FontStyle](/psd/python-net/aspose.psd/fontstyle/) της νέας γραμματοσειράς. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Το [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) της νέας γραμματοσειράς. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Μία αναπαράσταση συμβολοσειράς του ονόματος του [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Το [FontStyle](/psd/python-net/aspose.psd/fontstyle/) της νέας γραμματοσειράς. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Το [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) της νέας γραμματοσειράς. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Ένα σύνολο χαρακτήρων για χρήση με αυτή τη γραμματοσειρά. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας συγκεκριμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων ορίζεται σε [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), το στυλ ορίζεται σε [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Μία αναπαράσταση συμβολοσειράς του ονόματος του [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Το [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) της νέας γραμματοσειράς. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Αρχικοποιεί ένα νέο [Font](/psd/python-net/aspose.psd/font/) που χρησιμοποιεί το καθορισμένο υπάρχον [Font](/psd/python-net/aspose.psd/font/) και την απαρίθμηση [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Το υπάρχον [Font](/psd/python-net/aspose.psd/font/) από το οποίο θα δημιουργηθεί το νέο [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Το [FontStyle](/psd/python-net/aspose.psd/fontstyle/) που θα εφαρμοστεί στη νέα [Font](/psd/python-net/aspose.psd/font/). Πολλαπλές τιμές της απαρίθμησης [FontStyle](/psd/python-net/aspose.psd/fontstyle/) μπορούν να συνδυαστούν με τον τελεστή OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Το [Font](/psd/python-net/aspose.psd/font/) που δημιουργεί αυτή η μέθοδος. |


