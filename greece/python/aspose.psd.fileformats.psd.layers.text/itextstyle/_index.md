---
title: "ITextStyle Κλάση"
type: docs
weight: 40
url: /el/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Λαμβάνει ή ορίζει το auto kerning. |
| auto_leading | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν είναι ενεργό το [automatic leading]. |
| baseline_shift | double | r/w | Η μετατόπιση της γραμμής βάσης. |
| contextual_alternates | bool | r/w | Τα contextual alternates που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους. |
| discretionary_ligatures | bool | r/w | Τα discretionary ligatures που χρησιμοποιούνται για τη σύνδεση των γραμμάτων, ειδικά σε γραμματοσειρές με στυλ γραφής. |
| faux_bold | bool | r/w | Λαμβάνει ή ορίζει αν το faux bold είναι ενεργοποιημένο. |
| faux_italic | bool | r/w | Λαμβάνει ή ορίζει αν το faux bold είναι ενεργοποιημένο. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το χρώμα του γεμίσματος. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | Η γραμμή βάσης της γραμματοσειράς. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Τα κεφαλαία της γραμματοσειράς. |
| font_index | int | r | Λαμβάνει τον δείκτη της γραμματοσειράς. |
| font_name | string | r/w | Λαμβάνει ή ορίζει το όνομα γραμματοσειράς. |
| font_size | double | r/w | Λαμβάνει ή ορίζει το μέγεθος της γραμματοσειράς. |
| fractions | bool | r/w | Τα σύμβολα κλασμάτων μπορούν να αντικατασταθούν με ειδικό γλύφο. |
| hindi_numbers | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν είναι ενεργά τα [hindi numbers]. |
| horizontal_scale | double | r/w | Η οριζόντια κλίμακα. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Λαμβάνει ή ορίζει την τυπική κατακόρυφη Ρωμαϊκή στοίχιση.<br/>            Αυτό βασίζεται στην τιμή του πόρου BaselineDirection και εφαρμόζεται μόνο όταν ο προσανατολισμός κειμένου είναι [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Λαμβάνει ή ορίζει το kerning. |
| language_index | int | r | Λαμβάνει το language index. |
| leading | double | r/w | Λαμβάνει ή ορίζει το leading. |
| no_break | bool | r/w | Λαμβάνει ή ορίζει την τιμή no break value. |
| standard_ligatures | bool | r/w | Οι τυπικές contextual ligatures που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους. |
| strikethrough | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το χρώμα του stroke. |
| tracking | int | r/w | Λαμβάνει ή ορίζει το tracking. |
| underline | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [underline]. |
| vertical_scale | double | r/w | Η vertical scale. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [apply(style)](#apply_style_1) | Εφαρμόζει το καθορισμένο στυλ. |
| [is_equal(style)](#is_equal_style_2) | Καθορίζει εάν το καθορισμένο στυλ είναι ίσο. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Εφαρμόζει το καθορισμένο στυλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Το στυλ. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Καθορίζει εάν το καθορισμένο στυλ είναι ίσο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Το στυλ. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν το καθορισμένο στυλ είναι ίσο· διαφορετικά, <c>false</c>. |


