---
title: "Κλάση Font"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Font. Ορίζει μια συγκεκριμένη μορφή κειμένου που περιλαμβάνει το μέγεθος και τα χαρακτηριστικά του τύπου γραμματοσειράς. Αυτή η κλάση δεν μπορεί να κληρονομηθεί."
type: docs
weight: 4750
url: /el/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Ορίζει μια συγκεκριμένη μορφή κειμένου, συμπεριλαμβανομένων της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class Font
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Αρχικοποιεί ένα νέο `Font` που χρησιμοποιεί το καθορισμένο υπάρχον `Font` και την απαρίθμηση [`FontStyle`](../fontstyle/). |
| [Font](font/#constructor_1)(string, float) | Αρχικοποιεί ένα νέο `Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων ορίζεται σε Default, η μονάδα γραφικών σε Point, το στυλ γραμματοσειράς σε Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Αρχικοποιεί ένα νέο `Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων ορίζεται σε Default, η μονάδα γραφικών σε Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Αρχικοποιεί ένα νέο `Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων ορίζεται σε Default, το στυλ ορίζεται σε Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Αρχικοποιεί ένα νέο `Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα. Το σύνολο χαρακτήρων ορίζεται σε Default, το στυλ ορίζεται σε Regular. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Αρχικοποιεί ένα νέο `Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `Font` είναι έντονο. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που χρησιμοποιεί αυτό το `Font`. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `Font` είναι πλάγιο. |
| [Name](../../aspose.psd/font/name/) { get; } | Λαμβάνει το όνομα προσώπου αυτού του `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | Λαμβάνει το em-size αυτού του `Font` μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `Font` καθορίζει μια οριζόντια γραμμή μέσω της γραμματοσειράς. |
| [Style](../../aspose.psd/font/style/) { get; } | Λαμβάνει πληροφορίες στυλ για αυτό το `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το `Font` είναι υπογραμμισμένο. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Λαμβάνει τη μονάδα μέτρησης για αυτό το `Font`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα `Font` και έχει τις ίδιες τιμές ιδιοτήτων με αυτό το `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού για αυτό το `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `Font`. |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


