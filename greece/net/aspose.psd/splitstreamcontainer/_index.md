---
title: "Κλάση SplitStreamContainer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.SplitStreamContainer κλάση. Αντιπροσωπεύει το split stream container που περιέχει το stream και παρέχει ρουτίνες επεξεργασίας stream"
type: docs
weight: 6130
url: /el/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Αναπαριστά ένα δοχείο διαχωρισμένου ρεύματος που περιέχει το ρεύμα και παρέχει ρουτίνες επεξεργασίας ρεύματος.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SplitStreamContainer`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει ανάγνωση. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει αναζήτηση. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει εγγραφή. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό το stream διαγράφεται κατά το κλείσιμο. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του stream σε bytes. Αυτή η τιμή είναι μικρότερη από το Length κατά τη θέση εκκίνησης του stream που περάστηκε στον κατασκευαστή StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα θέση εντός του stream. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης του stream που περάστηκε στον κατασκευαστή StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Λαμβάνει το data stream. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Καθαρίζει όλες τις προσωρινές μνήμες για αυτή τη ροή και προκαλεί την εγγραφή τυχόν προσωρινών δεδομένων στη βασική συσκευή. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Εισάγει το δοχείο ροής στη συγκεκριμένη θέση. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Διαβάζει byte για να γεμίσει την καθορισμένη προσωρινή μνήμη byte. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν βρίσκεται στο τέλος της ροής. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί το προεπιλεγμένο μέγεθος προσωρινής μνήμης [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί το προεπιλεγμένο μέγεθος προσωρινής μνήμης [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) και την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί την τιμή της ροής [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί την τιμή της ροής [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Ορίζει τη θέση μέσα στην τρέχουσα ροή. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Ορίζει τη θέση της ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση έναρξης της ροής που δόθηκε στον κατασκευαστή StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Μετατρέπει τα δεδομένα της ροής σε πίνακα Byte. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Μετατρέπει τα δεδομένα της ροής σε πίνακα Byte. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [`StreamContainer`](../streamcontainer/). |

### Δείτε επίσης

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


