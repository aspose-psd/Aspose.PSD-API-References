---
title: Class Font
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Font τάξη. Καθορίζει μια συγκεκριμένη μορφή για το κείμενο συμπεριλαμβανομένων των χαρακτηριστικών όψης γραμματοσειράς μεγέθους και στυλ. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 4280
url: /el/net/aspose.psd/font/
---
## Font class

Καθορίζει μια συγκεκριμένη μορφή για το κείμενο, συμπεριλαμβανομένων των χαρακτηριστικών όψης γραμματοσειράς, μεγέθους και στυλ. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class Font
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Αρχικοποιεί ένα νέο`Font` που χρησιμοποιεί το καθορισμένο υπάρχον`Font` και[`FontStyle`](../fontstyle/) απαρίθμηση. |
| [Font](font/#constructor_1)(string, float) | Αρχικοποιεί ένα νέο`Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων έχει οριστεί σεDefault , η μονάδα γραφικών σεPoint , το στυλ γραμματοσειράς σεRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Αρχικοποιεί ένα νέο`Font` χρησιμοποιώντας ένα συγκεκριμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων έχει οριστεί σεDefault , η μονάδα γραφικών σεPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Αρχικοποιεί ένα νέο`Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων έχει οριστεί σεDefault το στυλ έχει οριστεί σεRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Αρχικοποιεί ένα νέο`Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Αρχικοποιεί ένα νέο`Font` χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό`Font` είναι τολμηρή. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που αυτό`Font` χρήσεις. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό`Font`είναι πλάγιο. |
| [Name](../../aspose.psd/font/name/) { get; } | Λαμβάνει το όνομα προσώπου αυτού`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Παίρνει το em-size αυτού`Font` μετράται στις μονάδες που καθορίζονται από το[`Unit`](./unit/) ιδιοκτησία. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό`Font` καθορίζει μια οριζόντια γραμμή μέσω της γραμματοσειράς. |
| [Style](../../aspose.psd/font/style/) { get; } | Λαμβάνει πληροφορίες στυλ για αυτό`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό`Font` είναι υπογραμμισμένο. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Παίρνει τη μονάδα μέτρησης για αυτό`Font` . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Δημιουργεί ένα ακριβές σε βάθος αντίγραφο αυτού`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Υποδεικνύει εάν το καθορισμένο αντικείμενο είναι α`Font` και έχει τις ίδιες αξίες ιδιοκτησίας με αυτό`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού για αυτό`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Επιστρέφει μια αναπαράσταση συμβολοσειράς αναγνώσιμη από τον άνθρωπο`Font` . |

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

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


