---
title: "Graphics.DrawString"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Graphics. Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα Brush και Font αντικείμενα."
type: docs
weight: 330
url: /el/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα `Brush` και `Font` αντικείμενα.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Συμβολοσειρά για σχεδίαση. |
| font | Font | `Font` που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | `Brush` που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | Single | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | Single | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *s* είναι null. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα `Brush` και `Font` αντικείμενα.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Συμβολοσειρά για σχεδίαση. |
| font | Font | `Font` που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | `Brush` που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | PointF | `PointF` δομή που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *s* είναι null. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση των κλάσεων Font και SolidBrush για τη σχεδίαση κειμένων στην επιφάνεια της Image. Το παράδειγμα δημιουργεί μια νέα Image και σχεδιάζει σχήματα χρησιμοποιώντας τις Figures και το GraphicsPath.

```csharp
[C#]

//Δημιουργεί ένα στιγμιότυπο της Image.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργεί και αρχικοποιεί ένα στιγμιότυπο της κλάσης Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίζει την επιφάνεια Graphics.
    graphics.Clear(Color.Wheat);

    //Δημιουργεί ένα στιγμιότυπο της Font.
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Δημιουργεί ένα στιγμιότυπο της SolidBrush με κόκκινο χρώμα.
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Σχεδιάζει μια συμβολοσειρά.
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // Δημιουργεί επιλογές εξαγωγής.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // αποθηκεύστε όλες τις αλλαγές
    image.Save("C:\\temp\\output.gif", options);
}
```

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα `Brush` και `Font` αντικείμενα χρησιμοποιώντας τα χαρακτηριστικά μορφοποίησης του καθορισμένου `StringFormat`.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Συμβολοσειρά για σχεδίαση. |
| font | Font | `Font` που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | `Brush` που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | Single | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | Single | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| format | StringFormat | `StringFormat` που καθορίζει χαρακτηριστικά μορφοποίησης, όπως το διάστημα γραμμών και η στοίχιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *s* είναι null. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα `Brush` και `Font` αντικείμενα χρησιμοποιώντας τα χαρακτηριστικά μορφοποίησης του καθορισμένου `StringFormat`.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Συμβολοσειρά για σχεδίαση. |
| font | Font | `Font` που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | `Brush` που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | PointF | `PointF` δομή που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |
| format | StringFormat | `StringFormat` που καθορίζει χαρακτηριστικά μορφοποίησης, όπως το διάστημα γραμμών και η στοίχιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *s* είναι null. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα `Brush` και `Font` αντικείμενα.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Συμβολοσειρά για σχεδίαση. |
| font | Font | `Font` που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | `Brush` που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | RectangleF | `RectangleF` δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *s* είναι null. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Σχεδίαζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα `Brush` και `Font` αντικείμενα χρησιμοποιώντας τα χαρακτηριστικά μορφοποίησης του καθορισμένου `StringFormat`.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Συμβολοσειρά για σχεδίαση. |
| font | Font | `Font` που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | `Brush` που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | RectangleF | `RectangleF` δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |
| format | StringFormat | `StringFormat` που καθορίζει χαρακτηριστικά μορφοποίησης, όπως το διάστημα γραμμών και η στοίχιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *brush* είναι null. -ή- *s* είναι null. -ή- *brush* είναι null. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


