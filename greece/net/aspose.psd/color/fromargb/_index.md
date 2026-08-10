---
title: "Color.FromArgb"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Color. Δημιουργεί μια δομή Color από μια τιμή ARGB 32bit"
type: docs
weight: 1430
url: /el/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Δημιουργεί μια δομή [`Color`](../) από μια τιμή ARGB 32-bit.

```csharp
public static Color FromArgb(int argb)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb | Int32 | Μια τιμή που καθορίζει την τιμή ARGB 32-bit. |

### Τιμή Επιστροφής

Η δομή [`Color`](../) που δημιουργεί αυτή η μέθοδος.

### Δείτε επίσης

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Δημιουργεί μια δομή [`Color`](../) από τις τέσσερις τιμές των συστατικών ARGB (alpha, red, green, και blue). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας 32-bit τιμής για κάθε συστατικό, η τιμή κάθε συστατικού περιορίζεται στα 8 bits.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | Int32 | Το συστατικό alpha. Οι έγκυρες τιμές είναι από 0 έως 255. |
| κόκκινο | Int32 | Το συστατικό red. Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | Int32 | Το συστατικό green. Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | Int32 | Το συστατικό blue. Οι έγκυρες τιμές είναι από 0 έως 255. |

### Τιμή Επιστροφής

Το [`Color`](../) που δημιουργεί αυτή η μέθοδος.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green*, ή *blue* είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Δείτε επίσης

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Δημιουργεί μια δομή [`Color`](../) από τη συγκεκριμένη δομή [`Color`](../), αλλά με τη νέα καθορισμένη τιμή άλφα. Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για την τιμή άλφα, η τιμή περιορίζεται στα 8 bits.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | Int32 | Η τιμή άλφα για το νέο [`Color`](../). Οι έγκυρες τιμές είναι 0 έως 255. |
| baseColor | Color | Το [`Color`](../) από το οποίο θα δημιουργηθεί το νέο [`Color`](../). |

### Τιμή Επιστροφής

Το [`Color`](../) που δημιουργεί αυτή η μέθοδος.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Δείτε επίσης

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Δημιουργεί μια δομή [`Color`](../) από τις καθορισμένες τιμές χρώματος 8-bit (κόκκινο, πράσινο και μπλε). Η τιμή άλφα είναι έμμεσα 255 (πλήρως αδιαφανής). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα χρώματος, η τιμή κάθε συνιστώσας περιορίζεται στα 8 bits.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| red | Int32 | Η τιμή της κόκκινης συνιστώσας για το νέο [`Color`](../). Οι έγκυρες τιμές είναι 0 έως 255. |
| green | Int32 | Η τιμή της πράσινης συνιστώσας για το νέο [`Color`](../). Οι έγκυρες τιμές είναι 0 έως 255. |
| blue | Int32 | Η τιμή της μπλε συνιστώσας για το νέο [`Color`](../). Οι έγκυρες τιμές είναι 0 έως 255. |

### Τιμή Επιστροφής

Το [`Color`](../) που δημιουργεί αυτή η μέθοδος.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green* ή *blue* είναι μικρότερο από 0 ή μεγαλύτερο από 255. |

### Δείτε επίσης

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


