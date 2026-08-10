---
title: "Font.Font"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής Font. Αρχικοποιεί ένα νέο Font που χρησιμοποιεί το καθορισμένο υπάρχον Font και την απαρίθμηση FontStyle"
type: docs
weight: 10
url: /el/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Αρχικοποιεί ένα νέο [`Font`](../) που χρησιμοποιεί το καθορισμένο υπάρχον [`Font`](../) και την απαρίθμηση [`FontStyle`](../../fontstyle/).

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prototype | Font | Το υπάρχον [`Font`](../) από το οποίο θα δημιουργηθεί το νέο [`Font`](../). |
| newStyle | FontStyle | Το [`FontStyle`](../../fontstyle/) που θα εφαρμοστεί στο νέο [`Font`](../). Πολλαπλές τιμές της απαρίθμησης [`FontStyle`](../../fontstyle/) μπορούν να συνδυαστούν με τον τελεστή OR. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *prototype* είναι null. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Αρχικοποιεί ένα νέο [`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων ορίζεται σε Default, η μονάδα γραφικών σε Point, το στυλ γραμματοσειράς σε Regular.

```csharp
public Font(string fontName, float emSize)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μία αναπαράσταση συμβολοσειράς του ονόματος του [`Font`](../). |
| emSize | Single | Το em-size, σε points, της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αξιολογείται ως άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι null. |

### Δείτε επίσης

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Αρχικοποιεί ένα νέο [`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων ορίζεται σε Default, η μονάδα γραφικών σε Point, το στυλ γραμματοσειράς σε Regular.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μία αναπαράσταση συμβολοσειράς του ονόματος του [`Font`](../). |
| emSize | Single | Το em-size, σε points, της νέας γραμματοσειράς. |
| style | FontStyle | Το [`FontStyle`](../../fontstyle/) της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αξιολογείται ως άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι null. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Αρχικοποιεί ένα νέο [`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων ορίζεται σε Default, το στυλ ορίζεται σε Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μία αναπαράσταση συμβολοσειράς του ονόματος του [`Font`](../). |
| emSize | Single | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο *unit*. |
| unit | GraphicsUnit | Το [`GraphicsUnit`](../../graphicsunit/) της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αξιολογείται ως άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι null. |

### Δείτε επίσης

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Αρχικοποιεί ένα νέο [`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μία αναπαράσταση συμβολοσειράς του ονόματος του [`Font`](../). |
| emSize | Single | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο *unit*. |
| style | FontStyle | Το [`FontStyle`](../../fontstyle/) της νέας γραμματοσειράς. |
| unit | GraphicsUnit | Το [`GraphicsUnit`](../../graphicsunit/) της νέας γραμματοσειράς. |
| characterSet | CharacterSet | Ένα σύνολο χαρακτήρων προς χρήση για αυτή τη γραμματοσειρά. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αξιολογείται ως άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι null. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Αρχικοποιεί ένα νέο [`Font`](../) χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Μία αναπαράσταση συμβολοσειράς του ονόματος του [`Font`](../). |
| emSize | Single | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο *unit*. |
| style | FontStyle | Το [`FontStyle`](../../fontstyle/) της νέας γραμματοσειράς. |
| unit | GraphicsUnit | Το [`GraphicsUnit`](../../graphicsunit/) της νέας γραμματοσειράς. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* είναι μικρότερο ή ίσο με 0, αξιολογείται ως άπειρο ή δεν είναι έγκυρος αριθμός. |
| ArgumentNullException | *fontName* είναι null. |

### Δείτε επίσης

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


