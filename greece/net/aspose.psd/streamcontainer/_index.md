---
title: Class StreamContainer
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.StreamContainer τάξη. Αντιπροσωπεύει το κοντέινερ ροής που περιέχει τη ροή και παρέχει ρουτίνες επεξεργασίας ροής.
type: docs
weight: 5640
url: /el/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Αντιπροσωπεύει το κοντέινερ ροής που περιέχει τη ροή και παρέχει ρουτίνες επεξεργασίας ροής.

```csharp
public class StreamContainer : DisposableObject
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Αρχικοποιεί μια νέα παρουσία του`StreamContainer` τάξη. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Αρχικοποιεί μια νέα παρουσία του`StreamContainer` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει ανάγνωση. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει αναζήτηση. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει εγγραφή. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η ροή διατίθεται στο κλείσιμο. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος ροής σε byte. Αυτή η τιμή είναι μικρότερη από τοLengthαπό τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα θέση εντός της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Λαμβάνει τη ροή δεδομένων. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Διαγράφει όλα τα buffer για αυτήν τη ροή και προκαλεί την εγγραφή τυχόν αποθηκευμένων δεδομένων στην υποκείμενη συσκευή. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Διαβάζει byte για να γεμίσει το καθορισμένο buffer bytes. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προωθεί τη θέση εντός της ροής κατά τον αριθμό των byte που διαβάζονται. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Διαβάζει ένα byte από τη ροή και προωθεί τη θέση εντός της ροής κατά ένα byte ή επιστρέφει -1 εάν στο τέλος της ροής. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί προεπιλεγμένο μέγεθος buffer[`ReadWriteBytesCount`](./readwritebytescount/) και ρέμα[`Length`](./length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί προεπιλεγμένο μέγεθος buffer[`ReadWriteBytesCount`](./readwritebytescount/) και ρέμα[`Length`](./length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί ροή[`Length`](./length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. Χρησιμοποιεί ροή[`Length`](./length/) τιμή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στην καθορισμένη ροή. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Ορίζει τη θέση εντός της τρέχουσας ροής. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Ορίζει τη θέση ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης ροής που μεταβιβάστηκε στον κατασκευαστή StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Μετατρέπει τα δεδομένα ροής σεByte συστοιχία. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Μετατρέπει τα δεδομένα ροής σεByte συστοιχία. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προωθεί την τρέχουσα θέση σε αυτήν τη ροή με τον αριθμό των byte που γράφτηκαν. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προωθεί τη θέση μέσα στη ροή κατά ένα byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Αντιγράφει τα δεδομένα που περιέχονται σε άλλο`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Αντιγράφει τα δεδομένα που περιέχονται σε άλλο`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Εκτελεί ρητή μετατροπή από`StreamContainer` προς τηνStream . |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Καθορίζει τον αριθμό των byte ανάγνωσης και εγγραφής κατά τη διαδοχική ανάγνωση. |

### Δείτε επίσης

* class [DisposableObject](../disposableobject/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


