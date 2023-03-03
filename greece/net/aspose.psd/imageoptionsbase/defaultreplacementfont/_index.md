---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD για Αναφορά API .NET
description: ImageOptionsBase ιδιοκτησία. Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα. Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily οικογένειες  col.Families stringN defaultFont PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /el/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης (γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ, εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα). Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] οικογένειες = col.Families; stringN defaultFont; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Αξία περιουσίας

Η προεπιλεγμένη γραμματοσειρά αντικατάστασης.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να χρησιμοποιήσετε την ιδιότητα DefaultReplacementFont για να αλλάξετε την προεπιλεγμένη γραμματοσειρά αντικατάστασης.

```csharp
[C#]

// Παρακαλώ, μην εγκαταστήσετε το Konstanting Font, γιατί αυτή η δοκιμή θα πρέπει να αντικαταστήσει τη γραμματοσειρά που δεν είναι εγκατεστημένη
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // Με αυτόν τον τρόπο μπορείτε να χρησιμοποιήσετε διαφορετικές γραμματοσειρές για διαφορετικές εξόδους 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../)
* χώρος ονομάτων [Aspose.PSD](../../imageoptionsbase/)
* συνέλευση [Aspose.PSD](../../../)


