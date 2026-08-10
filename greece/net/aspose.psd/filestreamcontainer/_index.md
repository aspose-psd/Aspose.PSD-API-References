---
title: "Κλάση FileStreamContainer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileStreamContainer κλάση. Βοηθός για την επεξεργασία ροής αρχείου"
type: docs
weight: 4720
url: /el/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Βοηθός για επεξεργασία ροής αρχείου.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει ανάγνωση. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει αναζήτηση. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει εγγραφή. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Λαμβάνει τη διαδρομή του αρχείου. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή δημιουργήθηκε ρητά. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό το stream διαγράφεται κατά το κλείσιμο. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η ροή είναι προσωρινή. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του stream σε bytes. Αυτή η τιμή είναι μικρότερη από το Length κατά τη θέση εκκίνησης του stream που περάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα θέση εντός του stream. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης του stream που περάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Λαμβάνει το data stream. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Δημιουργεί μια νέα ροή αρχείου. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Ανοίγει μια υπάρχουσα ροή αρχείου. Εάν η ροή αρχείου δεν υπάρχει, η κατάλληλη εξαίρεση ρίχνεται. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Καθαρίζει όλες τις προσωρινές μνήμες για αυτή τη ροή και προκαλεί την εγγραφή τυχόν προσωρινών δεδομένων στη βασική συσκευή. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Διαβάζει byte για να γεμίσει την καθορισμένη προσωρινή μνήμη byte. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν βρίσκεται στο τέλος της ροής. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί το προεπιλεγμένο μέγεθος προσωρινής μνήμης [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί το προεπιλεγμένο μέγεθος προσωρινής μνήμης [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Ορίζει τη θέση μέσα στην τρέχουσα ροή. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Ορίζει τη θέση της ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση έναρξης της ροής που δόθηκε στον κατασκευαστή StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Μετατρέπει τα δεδομένα της ροής σε πίνακα Byte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Μετατρέπει τα δεδομένα της ροής σε πίνακα Byte. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Εκτελεί μια ρητή μετατροπή από `FileStreamContainer` σε Stream. (2 τελεστές) |

### Δείτε επίσης

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


