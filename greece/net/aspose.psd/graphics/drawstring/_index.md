---
title: Graphics.DrawString
second_title: Aspose.PSD για Αναφορά API .NET
description: Graphics μέθοδος. Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένηBrush καιFont αντικείμενα.
type: docs
weight: 320
url: /el/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../../brush/) και[`Font`](../../font/) αντικείμενα.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Κορδόνι για να σχεδιάσετε. |
| font | Font | [`Font`](../../font/) που καθορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | Single | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | Single | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *brush* είναι μηδενικό. -ή- *s* είναι μηδενικό. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../../brush/) και[`Font`](../../font/) αντικείμενα.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Κορδόνι για να σχεδιάσετε. |
| font | Font | [`Font`](../../font/) που καθορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | PointF | [`PointF`](../../pointf/) δομή που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *brush* είναι μηδενικό. -ή- *s* είναι μηδενικό. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση της κλάσης Font και SolidBrush για τη σχεδίαση συμβολοσειρών στην επιφάνεια εικόνας. Το παράδειγμα δημιουργεί μια νέα εικόνα και σχεδιάζει σχήματα χρησιμοποιώντας το Figure και το GraphicsPath

```csharp
[C#]

//Δημιουργεί μια παρουσία εικόνας
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργεί και προετοιμάζει μια παρουσία της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίζει την επιφάνεια γραφικών
    graphics.Clear(Color.Wheat);

    //Δημιουργεί μια παρουσία γραμματοσειράς
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Δημιουργήστε μια παρουσία του SolidBrush με κόκκινο χρώμα
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Σχεδιάστε μια συμβολοσειρά
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // δημιουργία επιλογών εξαγωγής.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // αποθήκευση όλων των αλλαγών
    image.Save("C:\\temp\\output.gif", options);
}
```

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../../brush/) και[`Font`](../../font/) αντικείμενα που χρησιμοποιούν τα χαρακτηριστικά μορφοποίησης του καθορισμένου[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Κορδόνι για να σχεδιάσετε. |
| font | Font | [`Font`](../../font/) που καθορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | Single | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | Single | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| format | StringFormat | [`StringFormat`](../../stringformat/) που καθορίζει χαρακτηριστικά μορφοποίησης, όπως διάστιχο και στοίχιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *brush* είναι μηδενικό. -ή- *s* είναι μηδενικό. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../../brush/) και[`Font`](../../font/) αντικείμενα που χρησιμοποιούν τα χαρακτηριστικά μορφοποίησης του καθορισμένου[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Κορδόνι για να σχεδιάσετε. |
| font | Font | [`Font`](../../font/) που καθορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | PointF | [`PointF`](../../pointf/) δομή που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |
| format | StringFormat | [`StringFormat`](../../stringformat/) που καθορίζει χαρακτηριστικά μορφοποίησης, όπως διάστιχο και στοίχιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *brush* είναι μηδενικό. -ή- *s* είναι μηδενικό. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με το καθορισμένο[`Brush`](../../brush/) και[`Font`](../../font/) αντικείμενα.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Κορδόνι για να σχεδιάσετε. |
| font | Font | [`Font`](../../font/) που καθορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *brush* είναι μηδενικό. -ή- *s* είναι μηδενικό. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με το καθορισμένο[`Brush`](../../brush/) και[`Font`](../../font/) αντικείμενα που χρησιμοποιούν τα χαρακτηριστικά μορφοποίησης του καθορισμένου[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | String | Κορδόνι για να σχεδιάσετε. |
| font | Font | [`Font`](../../font/) που καθορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | Brush | [`Brush`](../../brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |
| format | StringFormat | [`StringFormat`](../../stringformat/) που καθορίζει χαρακτηριστικά μορφοποίησης, όπως διάστιχο και στοίχιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *brush* είναι μηδενικό. -ή- *s* είναι μηδενικό. -ή- *brush* είναι μηδενικό. |

### Δείτε επίσης

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)


