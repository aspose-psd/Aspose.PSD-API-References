---
title: Class SplitStreamContainer
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.SplitStreamContainer τάξη. Αντιπροσωπεύει το κοντέινερ διαχωρισμού ροής που περιέχει τη ροή και παρέχει ρουτίνες επεξεργασίας ροής.
type: docs
weight: 5630
url: /el/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Αντιπροσωπεύει το κοντέινερ διαχωρισμού ροής που περιέχει τη ροή και παρέχει ρουτίνες επεξεργασίας ροής.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Αρχικοποιεί μια νέα παρουσία του`SplitStreamContainer` τάξη. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Αρχικοποιεί μια νέα παρουσία του`SplitStreamContainer` τάξη. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Αρχικοποιεί μια νέα παρουσία του`SplitStreamContainer` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει ανάγνωση. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει αναζήτηση. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει εγγραφή. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η ροή διατίθεται στο κλείσιμο. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος ροής σε byte. Αυτή η τιμή είναι μικρότερη από τοLengthαπό τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα θέση εντός της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Λαμβάνει τη ροή δεδομένων. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Διαγράφει όλα τα buffer για αυτήν τη ροή και προκαλεί την εγγραφή τυχόν αποθηκευμένων δεδομένων στην υποκείμενη συσκευή. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Εισάγει το κοντέινερ ροής στην καθορισμένη θέση. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Διαβάζει byte για να γεμίσει το καθορισμένο buffer bytes. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προωθεί τη θέση εντός της ροής κατά τον αριθμό των byte που διαβάζονται. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Διαβάζει ένα byte από τη ροή και προωθεί τη θέση εντός της ροής κατά ένα byte ή επιστρέφει -1 εάν στο τέλος της ροής. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί προεπιλεγμένο μέγεθος buffer[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και ρέμα[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί προεπιλεγμένο μέγεθος buffer[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και ρέμα[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί ροή[`Length`](../streamcontainer/length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί ροή[`Length`](../streamcontainer/length/) τιμή. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Ορίζει τη θέση εντός της τρέχουσας ροής. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Ορίζει τη θέση ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Μετατρέπει τα δεδομένα ροής σεByte συστοιχία. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Μετατρέπει τα δεδομένα ροής σεByte συστοιχία. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προωθεί την τρέχουσα θέση σε αυτήν τη ροή με τον αριθμό των byte που γράφτηκαν. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προωθεί τη θέση μέσα στη ροή κατά ένα byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Αντιγράφει τα δεδομένα που περιέχονται σε άλλο[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Αντιγράφει τα δεδομένα που περιέχονται σε άλλο[`StreamContainer`](../streamcontainer/) . |

### Δείτε επίσης

* class [StreamContainer](../streamcontainer/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


