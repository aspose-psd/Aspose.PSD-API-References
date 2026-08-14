---
title: "ColorComponent Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Δημιουργεί μια νέα παρουσία της [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) κλάσης.<br/>            Παρακαλώ ελέγξτε |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bit_depth | byte | r | Αποκτά το βάθος bit του Color Component/Channel |
| description | string | r | Αποκτά την περιγραφή του Color Component |
| full_name | string | r | Αποκτά το πλήρες όνομα του συστατικού χρώματος με όνομα και περιγραφή χωρισμένη με κενά |
| name | string | r | Λαμβάνει το όνομα του στοιχείου χρώματος. |
| permitted_full_names [static] | string | r | Λαμβάνει τα επιτρεπόμενα πλήρη ονόματα. |
| value | ulong | r/w | Λαμβάνει ή ορίζει την τιμή. <br/>            Σημειώστε ότι, εάν προσπαθήσετε να ορίσετε τιμή που είναι μεγαλύτερη από <br/>            αυτή που μπορεί να αποθηκευτεί στο τρέχον βάθος bit, θα προκύψει εξαίρεση |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Δημιουργεί μια νέα παρουσία της [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) κλάσης.<br/>            Παρακαλώ ελέγξτε

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bit_depth | byte | Το βάθος bit. |
| full_name | string | Το πλήρες όνομα. |

