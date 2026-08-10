---
title: "Κλάση RawColor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor κλάση. Η κλάση Raw Color βοηθά στην αποθήκευση χρωμάτων με οποιονδήποτε αριθμό καναλιών, οποιαδήποτε λειτουργία χρώματος και οποιοδήποτε βάθος bit. Παρακαλούμε σημειώστε ότι ορισμένες εσωτερικές κλάσεις μπορεί να έχουν προβλήματα με τη μετατροπή του RawColor στη φυσική του μορφή, οπότε εάν το API παρέχει χρώμα CMYK, είναι πιο αξιόπιστο να χρησιμοποιήσετε τη μορφή που παρέχεται. Επίσης, μπορεί να υπάρξουν περιπτώσεις όπου το Raw Color μπορεί να μετατραπεί."
type: docs
weight: 1650
url: /el/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Η Raw Color Class βοηθά στην αποθήκευση χρωμάτων με οποιονδήποτε αριθμό καναλιών, οποιαδήποτε λειτουργία χρώματος και οποιοδήποτε βάθος bit. Παρακαλώ σημειώστε ότι ορισμένες εσωτερικές κλάσεις μπορεί να έχουν προβλήματα με τη μετατροπή του RawColor στη φυσική του μορφή, έτσι εάν το API παρέχει για εσάς χρώμα CMYK, είναι πιο αξιόπιστο να χρησιμοποιήσετε τη δοθείσα μορφή. Επίσης, μπορεί να υπάρξουν κάποιες περιπτώσεις όπου το Raw Color μπορεί να μετατραπεί

```csharp
public sealed class RawColor
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Αρχικοποιεί μια νέα παρουσία της κλάσης `RawColor` από μορφή δεδομένων εικονοστοιχείων χρησιμοποιώντας προκαθορισμένες λειτουργίες χρώματος |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Λειτουργία για το χρώμα που ακολουθεί |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Αποκτά τα συστατικά του χρώματος. Κάθε συστατικό είναι ξεχωριστό κανάλι, και εάν χρησιμοποιείτε μη δημοφιλές σχήμα χρώματος, είναι καλύτερο να εργάζεστε με κάθε κανάλι ξεχωριστά. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Αποκτά το χρώμα ως int σε περίπτωση που είναι δυνατόν να το λάβει. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Αποκτά το χρώμα ως long σε περίπτωση που είναι δυνατόν να το λάβει. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Αποκτά το βάθος bit του Raw Color. Για παράδειγμα, για χρώμα ARGB με 8 bit ανά κανάλι/συστατικό το βάθος είναι 32. Το βάθος bit πλήρους χρώματος ARGB με 16 bit ανά κανάλι/συστατικό είναι 64. Το βάθος bit συσσωρεύεται από το άθροισμα των βάθων bit των καναλιών. Είναι δυνατόν εάν διαφορετικά κανάλια έχουν διαφορετικά βάθη bit. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Αποκτά το όνομα της λειτουργίας χρώματος. Το όνομα της λειτουργίας χρώματος συσσωρεύεται από τα ονόματα των καναλιών/συστατικών |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Λαμβάνει τον κωδικό κατακερματισμού του τρέχοντος αντικειμένου. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Ορίζει δεδομένα σε όλα τα κανάλια από το επιχείρημα int εάν είναι δυνατόν |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Ορίζει δεδομένα σε όλα τα κανάλια από το επιχείρημα int εάν είναι δυνατόν |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Υλοποιεί τον τελεστή ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Υλοποιεί τον τελεστή !=. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της κλάσης RawColor αντί της παλαιάς δομής Color.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


