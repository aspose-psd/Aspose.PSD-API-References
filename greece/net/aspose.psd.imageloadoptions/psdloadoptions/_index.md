---
title: Class PsdLoadOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions τάξη. Επιλογές φόρτωσης Psd
type: docs
weight: 4770
url: /el/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Επιλογές φόρτωσης Psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Λαμβάνει ή ορίζει εάν θα αποθηκεύεται με την αποδοθείσα εικόνα, με ή χωρίς μετασχηματισμό στημόνι. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει το[`Image`](../../aspose.psd/image/) Ιστορικό[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία ανάκτησης δεδομένων. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [αγνοήστε το κανάλι άλφα]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σταθερό πλάτος του επιπέδου κειμένου PSD θα αγνοηθεί κατά την εκτέλεση της λειτουργίας UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [φόρτωση πόρου εφέ] (από προεπιλογή ο πόρος δεν έχει φορτωθεί). Όταν οριστεί αυτή η επιλογή, μόνο τα υποστηριζόμενα εφέ θα αποδίδονται στην τελική συγχωνευμένη εικόνα. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων προόδου. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [χρήση λειτουργίας μόνο για ανάγνωση]. Αυτή είναι η λειτουργία μόνο για ανάγνωση, που υποστηρίζεται για πανομοιότυπη συμβατότητα με το Adobe Photoshop. Όταν οριστεί αυτή η επιλογή, όλες οι αλλαγές που εφαρμόζονται για τα επίπεδα δεν θα αποθηκευτούν στην τελική εικόνα. Όλα τα δεδομένα χρησιμοποιούνται από την ενότητα ImageData, επομένως είναι πανομοιότυπα με το Photoshop. Από προεπιλογή, όλες οι εικόνες που έχουν φορτωθεί δεν είναι πανομοιότυπες με τις συμβατές με το Adobe Photoshop. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [χρήση δίσκου για πόρο εφέ φόρτωσης] (από προεπιλογή χρησιμοποιείται δίσκος για φόρτωση πόρου εφέ, αλλά μπορεί να χρησιμοποιηθεί μνήμη εάν είναι αρκετή ορίζοντας αυτήν την τιμή σε false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει ότι η πρόοδος μετατροπής του εγγράφου λειτουργεί σωστά και χωρίς εξαίρεση.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### Δείτε επίσης

* class [LoadOptions](../../aspose.psd/loadoptions/)
* χώρος ονομάτων [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* συνέλευση [Aspose.PSD](../../)


