---
title: Class FileStreamContainer
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileStreamContainer τάξη. Βοηθός για επεξεργασία ροής αρχείων.
type: docs
weight: 4250
url: /el/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Βοηθός για επεξεργασία ροής αρχείων.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει ανάγνωση. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει αναζήτηση. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει εγγραφή. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Λαμβάνει τη διαδρομή του αρχείου. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή δημιουργήθηκε ρητά. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η ροή διατίθεται στο κλείσιμο. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η ροή είναι προσωρινή. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος ροής σε byte. Αυτή η τιμή είναι μικρότερη από τοLengthαπό τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα θέση εντός της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Λαμβάνει τη ροή δεδομένων. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Δημιουργεί μια νέα ροή αρχείων. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Ανοίγει μια υπάρχουσα ροή αρχείων. Εάν η ροή αρχείου δεν υπάρχει, δημιουργείται η κατάλληλη εξαίρεση. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Διαγράφει όλα τα buffer για αυτήν τη ροή και προκαλεί την εγγραφή τυχόν αποθηκευμένων δεδομένων στην υποκείμενη συσκευή. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Διαβάζει byte για να γεμίσει το καθορισμένο buffer bytes. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προωθεί τη θέση εντός της ροής κατά τον αριθμό των byte που διαβάζονται. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Διαβάζει ένα byte από τη ροή και προωθεί τη θέση εντός της ροής κατά ένα byte ή επιστρέφει -1 εάν στο τέλος της ροής. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί προεπιλεγμένο μέγεθος buffer[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και ρέμα[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί προεπιλεγμένο μέγεθος buffer[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και ρέμα[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί ροή[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί ροή[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Ορίζει τη θέση εντός της τρέχουσας ροής. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Ορίζει τη θέση ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Μετατρέπει τα δεδομένα ροής σεByte συστοιχία. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Μετατρέπει τα δεδομένα ροής σεByte συστοιχία. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προωθεί την τρέχουσα θέση σε αυτήν τη ροή με τον αριθμό των byte που γράφτηκαν. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προωθεί τη θέση μέσα στη ροή κατά ένα byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Αντιγράφει τα δεδομένα που περιέχονται σε άλλο[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Αντιγράφει τα δεδομένα που περιέχονται σε άλλο[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Εκτελεί ρητή μετατροπή από`FileStreamContainer` προς τηνStream . (2 operators) |

### Δείτε επίσης

* class [StreamContainer](../streamcontainer/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


