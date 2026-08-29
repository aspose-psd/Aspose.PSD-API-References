---
title: "StreamContainer.Read"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος StreamContainer. Διαβάζει bytes για να γεμίσει το καθορισμένο buffer bytes"
type: docs
weight: 110
url: /el/net/aspose.psd/streamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Διαβάζει byte για να γεμίσει την καθορισμένη προσωρινή μνήμη byte.

```csharp
public virtual int Read(byte[] bytes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | Byte[] | Τα bytes προς γέμισμα. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν. Αυτή η τιμή μπορεί να είναι μικρότερη από τον αριθμό των bytes στο buffer εάν δεν υπάρχουν αρκετά bytes στη ροή.

### Δείτε επίσης

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | Byte[] | Ένας πίνακας bytes. Όταν αυτή η μέθοδος επιστρέψει, το buffer περιέχει τον καθορισμένο πίνακα byte με τις τιμές μεταξύ *offset* και (*offset* + *count* - 1) που αντικαταστάθηκαν από τα bytes που διαβάστηκαν από την τρέχουσα πηγή. |
| offset | Int32 | Η μηδενική βάση offset byte στο *buffer* στην οποία θα ξεκινήσει η αποθήκευση των δεδομένων που διαβάστηκαν από την τρέχουσα ροή. |
| πλήθος | Int32 | Ο μέγιστος αριθμός των bytes που θα διαβαστούν από την τρέχουσα ροή. |

### Τιμή Επιστροφής

Ο συνολικός αριθμός των bytes που διαβάστηκαν στο buffer. Αυτό μπορεί να είναι μικρότερο από τον αριθμό των bytes που ζητήθηκαν εάν αυτά τα bytes δεν είναι διαθέσιμα αυτή τη στιγμή, ή μηδέν (0) εάν έχει φτάσει το τέλος της ροής.

### Δείτε επίσης

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


