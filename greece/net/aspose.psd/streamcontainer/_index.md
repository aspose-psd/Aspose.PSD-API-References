---
title: "Κλάση StreamContainer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.StreamContainer. Αντιπροσωπεύει το κοντέινερ ροής που περιέχει τη ροή και παρέχει διαδικασίες επεξεργασίας ροής."
type: docs
weight: 6140
url: /el/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Αναπαριστά ένα δοχείο ρεύματος που περιέχει το ρεύμα και παρέχει ρουτίνες επεξεργασίας ρεύματος.

```csharp
public class StreamContainer : DisposableObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `StreamContainer`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει ανάγνωση. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει αναζήτηση. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το stream υποστηρίζει εγγραφή. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν αυτό το stream διαγράφεται κατά το κλείσιμο. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του stream σε bytes. Αυτή η τιμή είναι μικρότερη από το Length κατά τη θέση εκκίνησης του stream που περάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Λαμβάνει ή ορίζει την τρέχουσα θέση εντός του stream. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης του stream που περάστηκε στον κατασκευαστή StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Λαμβάνει το data stream. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Καθαρίζει όλες τις προσωρινές μνήμες για αυτή τη ροή και προκαλεί την εγγραφή τυχόν προσωρινών δεδομένων στη βασική συσκευή. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Διαβάζει byte για να γεμίσει την καθορισμένη προσωρινή μνήμη byte. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν βρίσκεται στο τέλος της ροής. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer [`ReadWriteBytesCount`](./readwritebytescount/) και την τιμή της ροής [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer [`ReadWriteBytesCount`](./readwritebytescount/) και την τιμή της ροής [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί την τιμή της ροής [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί την τιμή της ροής [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Ορίζει τη θέση μέσα στην τρέχουσα ροή. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Ορίζει τη θέση της ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση έναρξης της ροής που δόθηκε στον κατασκευαστή StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Μετατρέπει τα δεδομένα της ροής σε πίνακα Byte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Μετατρέπει τα δεδομένα της ροής σε πίνακα Byte. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο `StreamContainer`. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο `StreamContainer`. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Εκτελεί μια ρητή μετατροπή από το `StreamContainer` σε Stream. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Καθορίζει τον αριθμό των byte ανάγνωσης και εγγραφής κατά την σειριακή ανάγνωση. |

### Δείτε επίσης

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


