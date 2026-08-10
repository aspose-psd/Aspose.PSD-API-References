---
title: "Κλάση PsdLoadOptions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions κλάση. Επιλογές φόρτωσης Psd."
type: docs
weight: 5250
url: /el/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Επιλογές φόρτωσης Psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Λαμβάνει ή ορίζει αν διατηρηθούν τα αρχικά pixel του επιπέδου κατά τη απόδοση εάν το επίπεδο δεν έχει τροποποιηθεί. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Λαμβάνει ή ορίζει αν αποθηκευτεί με την αποδοθείσα εικόνα, με ή χωρίς παραμόρφωση. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει το φόντο του [`Image`](../../aspose.psd/image/) [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία ανάκτησης δεδομένων. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σταθερό πλάτος του επιπέδου κειμένου PSD θα αγνοηθεί κατά την εκτέλεση της λειτουργίας UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [load effects resource] (από προεπιλογή ο πόρος δεν φορτώνεται). Όταν οριστεί, αυτή η επιλογή θα αποδώσει μόνο τα υποστηριζόμενα εφέ στην τελική συγχωνευμένη εικόνα. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use read only mode]. Αυτό είναι λειτουργία μόνο για ανάγνωση, υποστηριζόμενη για πλήρη συμβατότητα με το Adobe Photoshop. Όταν αυτή η επιλογή οριστεί, όλες οι αλλαγές που εφαρμόζονται στα επίπεδα δεν θα αποθηκευτούν στην τελική εικόνα. Όλα τα δεδομένα προέρχονται από την ενότητα ImageData, έτσι είναι ταυτόσημα με το Photoshop. Από προεπιλογή όλες οι φορτωμένες εικόνες δεν είναι πλήρως συμβατές με το Adobe Photoshop. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use disk for load effects resource] (από προεπιλογή χρησιμοποιείται δίσκος για τη φόρτωση πόρων εφέ, αλλά μπορεί να χρησιμοποιηθεί μνήμη εάν είναι επαρκής ορίζοντας αυτήν την τιμή σε false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει ότι η πρόοδος μετατροπής εγγράφου λειτουργεί σωστά και χωρίς εξαίρεση.

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
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


