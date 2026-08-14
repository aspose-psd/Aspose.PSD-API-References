---
title: "Κλάση StringFormat"
type: docs
weight: 4260
url: /el/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Αρχικοποιεί ένα νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Αρχικοποιεί ένα νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/) από το καθορισμένο υπάρχον αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(options)](#StringFormat_options_3) | Αρχικοποιεί ένα νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/) με την καθορισμένη απαρίθμηση [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) και γλώσσα. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Λαμβάνει ή ορίζει πληροφορίες στοίχισης κειμένου στον κάθετο άξονα. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Λαμβάνει ή ορίζει το προσαρμοσμένο αναγνωριστικό χαρακτήρα. |
| digit_substitution_language | int | r/w | Λαμβάνει ή ορίζει τη γλώσσα που χρησιμοποιείται όταν οι τοπικοί αριθμοί αντικαθίστανται από δυτικούς αριθμούς. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Λαμβάνει ή ορίζει τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| first_tab_offset | float | r | Λαμβάνει τον αριθμό των κενών μεταξύ της αρχής μιας γραμμής κειμένου και του πρώτου σημείου εσοχής. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Λαμβάνει ή ορίζει μια απαρίθμηση [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) που περιέχει πληροφορίες μορφοποίησης. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Λαμβάνει ένα γενικό προεπιλεγμένο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Λαμβάνει ένα γενικό τυπογραφικό αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Λαμβάνει ή ορίζει το αντικείμενο [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) για αυτό το αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Λαμβάνει ή ορίζει τη στοίχιση γραμμής στον οριζόντιο άξονα. |
| tab_stops | float | r | Λαμβάνει έναν πίνακα αποστάσεων μεταξύ σημείων εσοχής στις μονάδες που καθορίζονται από την ιδιότητα [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Λαμβάνει ή ορίζει την απαρίθμηση [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) για αυτό το αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Δημιουργεί ένα πλήρες αντίγραφο αυτού του αντικειμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Ορίζει σημεία εσοχής για αυτό το αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Αρχικοποιεί ένα νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Αρχικοποιεί ένα νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/) από το καθορισμένο υπάρχον αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Το αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/) από το οποίο θα αρχικοποιηθεί το νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Αρχικοποιεί ένα νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/) με την καθορισμένη απαρίθμηση [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) και γλώσσα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | Η απαρίθμηση [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) για το νέο αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Δημιουργεί ένα πλήρες αντίγραφο αυτού του αντικειμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | Το πλήρες αντίγραφο του τρέχοντος [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Ορίζει σημεία εσοχής για αυτό το αντικείμενο [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| first_tab_offset | float | Ο αριθμός των κενών μεταξύ της αρχής μιας γραμμής κειμένου και του πρώτου σημείου εσοχής. |
| tab_stops | float | Ένας πίνακας αποστάσεων μεταξύ σημείων εσοχής στις μονάδες που καθορίζονται από την ιδιότητα [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

