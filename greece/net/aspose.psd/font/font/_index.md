---
title: Font.Font
second_title: Aspose.PSD για Αναφορά API .NET
description: Font κατασκευαστής. Αρχικοποιεί ένα νέοFont που χρησιμοποιεί το καθορισμένο υπάρχονFont καιFontStyle απαρίθμηση.
type: docs
weight: 10
url: /el/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Αρχικοποιεί ένα νέο[`Font`](../) που χρησιμοποιεί το καθορισμένο υπάρχον[`Font`](../) και[`FontStyle`](../../fontstyle/) απαρίθμηση.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prototype | Font | Τα υπαρχοντα[`Font`](../) από το οποίο να δημιουργηθεί το νέο[`Font`](../). |
| newStyle | FontStyle | ο[`FontStyle`](../../fontstyle/) για να κάνετε αίτηση στο νέο[`Font`](../) . Πολλαπλές τιμές του[`FontStyle`](../../fontstyle/) Η απαρίθμηση μπορεί να συνδυαστεί με τον τελεστή OR. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *prototype* είναι μηδενικό. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* χώρος ονομάτων [Aspose.PSD](../../font/)
* συνέλευση [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Αρχικοποιεί ένα νέο[`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων έχει οριστεί σεDefault , η μονάδα γραφικών σεPoint , το στυλ γραμματοσειράς σεRegular .

```csharp
public Font(string fontName, float emSize)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μια συμβολοσειρά αναπαράσταση του[`Font`](../) όνομα. |
| emSize | Single | Το em-size, σε σημεία, της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αποτιμάται στο άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι μηδενικό. |

### Δείτε επίσης

* class [Font](../)
* χώρος ονομάτων [Aspose.PSD](../../font/)
* συνέλευση [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Αρχικοποιεί ένα νέο[`Font`](../) χρησιμοποιώντας ένα συγκεκριμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων έχει οριστεί σεDefault , η μονάδα γραφικών σεPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μια συμβολοσειρά αναπαράσταση του[`Font`](../) όνομα. |
| emSize | Single | Το em-size, σε σημεία, της νέας γραμματοσειράς. |
| style | FontStyle | ο[`FontStyle`](../../fontstyle/) της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αποτιμάται στο άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι μηδενικό. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* χώρος ονομάτων [Aspose.PSD](../../font/)
* συνέλευση [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Αρχικοποιεί ένα νέο[`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων έχει οριστεί σεDefault το στυλ έχει οριστεί σεRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μια συμβολοσειρά αναπαράσταση του[`Font`](../) όνομα. |
| emSize | Single | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από το*unit* παράμετρος. |
| unit | GraphicsUnit | ο[`GraphicsUnit`](../../graphicsunit/) της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αποτιμάται στο άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι μηδενικό. |

### Δείτε επίσης

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* χώρος ονομάτων [Aspose.PSD](../../font/)
* συνέλευση [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Αρχικοποιεί ένα νέο[`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μια συμβολοσειρά αναπαράσταση του[`Font`](../) όνομα. |
| emSize | Single | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από το*unit* παράμετρος. |
| style | FontStyle | ο[`FontStyle`](../../fontstyle/) της νέας γραμματοσειράς. |
| unit | GraphicsUnit | ο[`GraphicsUnit`](../../graphicsunit/) της νέας γραμματοσειράς. |
| characterSet | CharacterSet | Ένα σύνολο χαρακτήρων που θα χρησιμοποιηθεί για αυτήν τη γραμματοσειρά. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αποτιμάται στο άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι μηδενικό. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* χώρος ονομάτων [Aspose.PSD](../../font/)
* συνέλευση [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Αρχικοποιεί ένα νέο[`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μια συμβολοσειρά αναπαράσταση του[`Font`](../) όνομα. |
| emSize | Single | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από το*unit* παράμετρος. |
| style | FontStyle | ο[`FontStyle`](../../fontstyle/) της νέας γραμματοσειράς. |
| unit | GraphicsUnit | ο[`GraphicsUnit`](../../graphicsunit/) της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αποτιμάται στο άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι μηδενικό. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* χώρος ονομάτων [Aspose.PSD](../../font/)
* συνέλευση [Aspose.PSD](../../../)


