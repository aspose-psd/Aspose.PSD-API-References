---
title: SplitStreamContainer.Read
second_title: Aspose.PSD για Αναφορά API .NET
description: SplitStreamContainer μέθοδος. Διαβάζει byte για να γεμίσει το καθορισμένο buffer bytes.
type: docs
weight: 110
url: /el/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

Διαβάζει byte για να γεμίσει το καθορισμένο buffer bytes.

```csharp
public override int Read(byte[] bytes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | Byte[] | Τα byte για συμπλήρωση. |

### Επιστρεφόμενη Αξία

Ο αριθμός των byte που διαβάζονται. Αυτή η τιμή μπορεί να είναι μικρότερη από τον αριθμό των byte στο buffer εάν δεν υπάρχουν αρκετά byte στη ροή.

### Δείτε επίσης

* class [SplitStreamContainer](../)
* χώρος ονομάτων [Aspose.PSD](../../splitstreamcontainer/)
* συνέλευση [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προωθεί τη θέση εντός της ροής κατά τον αριθμό των byte που διαβάζονται.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | Byte[] | Μια σειρά από byte. Όταν αυτή η μέθοδος επιστρέφει, το buffer περιέχει τον καθορισμένο πίνακα byte με τις τιμές μεταξύ τους*offset* και (*offset* +*count* - 1) αντικαθίσταται από τα byte που διαβάζονται από την τρέχουσα πηγή. |
| offset | Int32 | Η μετατόπιση του byte με βάση το μηδέν*buffer* όπου θα ξεκινήσει η αποθήκευση των δεδομένων που διαβάζονται από την τρέχουσα ροή. |
| count | Int32 | Ο μέγιστος αριθμός byte προς ανάγνωση από την τρέχουσα ροή. |

### Επιστρεφόμενη Αξία

Ο συνολικός αριθμός των byte που διαβάζονται στο buffer. Αυτός μπορεί να είναι μικρότερος από τον αριθμό των byte που ζητούνται εάν τόσα byte δεν είναι διαθέσιμα αυτήν τη στιγμή ή μηδέν (0) εάν έχει φτάσει το τέλος της ροής.

### Δείτε επίσης

* class [SplitStreamContainer](../)
* χώρος ονομάτων [Aspose.PSD](../../splitstreamcontainer/)
* συνέλευση [Aspose.PSD](../../../)


